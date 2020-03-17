# rivm_corona_map_plot
Single script repository that holds a notebook that scrapes the RIVM website for corona virus incidence data.

The notebook does the following:

* Downloads a public map of Dutch municipalities (Gemeentes)
* Scrapes the RIVM website for data on the daily cases of Covid-19 (note, this data is updated once per day)
* Does limited cleaning
* Stores raw data to your disk as a csv
* Merges the public data with the corona data
* Plots a pretty graph to show where the cases are
* Stores the pretty graph

Example:
![](https://github.com/jeffluppes/rivm_corona_map_plot/blob/master/corona_cases_netherlands17-Mar-2020.png)
