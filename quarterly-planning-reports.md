## Problem statement
Each quarter the Information and Analysis Group of the planning department does a wonderful job producing data tracking development in San Francisco. Currently they produce the analysis and then load that into the portal. They also [embed the map/table on their site](http://sf-planning.org/pipeline-report) and link to the dataset. The IAG does a lot of analysis work, both ad hoc and regular reporting. As a small team, producing the data is time-consuming enough that outputting a report with context is icing on the cake, but they want individuals to also have robust understanding of the data in the reports. The exploration tools on the open data portal are limited.

## Challenge
Build a simple web based report that visualizes the pipeline data in context using maps and charts. Make that report keyed off of the open data APIs so that it can be updated with the most recent data easily. Bonus points for allowing cross filtering and other more interactive features. Note: we'll be working on consolidating these reports into a single dataset, for now [prototype against the latest one](https://data.sfgov.org/Housing-and-Buildings/San-Francisco-Development-Pipeline-2016-Quarter-1/dtz9-jkjt).

## Inspiration
* You can see [past PDF reports for examples](http://sf-planning.org/pipeline-report) (at the bottom) of how IAG reported the data via reports in the past..this will give you a sense of the visuals that people may find most useful to provide context
* The data dictionary for the dataset is inside the reports. [Here's the last one that was produced](http://sf-planning.org/sites/default/files/FileCenter/Documents/9338-pipelinereport_q3_2014.pdf). Dictionary on Page 19
* There are lots of charting libraries that are easy to plug open data APIs into ([C3](http://c3js.org), [highcharts](http://www.highcharts.com/), [amcharts](https://www.amcharts.com/), and so on) also for cross filtering, check out [crossfilter.js](http://square.github.io/crossfilter/)
