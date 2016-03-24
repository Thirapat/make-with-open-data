## Problem statement
Each quarter the Information and Analysis Group of the planning department does a wonderful job producing data tracking development in San Francisco. Currently they produce the analysis and then load that into the portal. They also embed the map/table on their site and link to the dataset. The IAG does a lot of analysis work, both ad hoc and regular reporting. As a small team, producing the data is time-consuming enough that outputting a report with context is icing on the cake, but they want individuals to also have robust understanding of the data in the reports. The exploration tools on the open data portal are limited.

## Challenge
Build a simple web based report that visualizes the pipeline data in context using maps and charts. Make that report keyed off of the open data APIs so that it can be updated with the most recent data easily. Bonus points for allowing cross filtering and other more interactive features.

## Inspiration
* You can see [past PDF reports for examples](http://www.sf-planning.org/?page=1691) (at the bottom) of how IAG reported the data via reports in the past..this will give you a sense of the visuals that people may find most useful to provide context
* There are lots of charting libraries that are easy to plug open data APIs into ([C3](http://c3js.org), [highcharts](http://www.highcharts.com/), [amcharts](https://www.amcharts.com/), and so on) also for cross filtering, check out [crossfilter.js](http://square.github.io/crossfilter/)