# owf-lib-viz-plotly
Open Water Foundation visualization library based on Plot.ly

## Getting Started

A standard development folder structure is recommended. The website development files can be set up as follows (Windows is assumed, but Linux would be similar):

```
> C:
> cd \Users\user
> mkdir Plotly-JS
> cd Plotly-JS
> mkdir git-repos
> cd git-repos
> git clone https://github.com/OpenWaterFoundation/owf-lib-viz-plotly-js
``` 
The repository contains multiple folders that include time series examples using different sets of data.
## Additional Documentation

See also:
* [Plotly.js Documentation](https://plot.ly/javascript/)
* [Plotly Python Documentation](https://plot.ly/python/)
* [Plotly Matlab Documentation](https://plot.ly/matlab/)
* [Plotly R Documentation](https://plot.ly/r/)

## Data Format RCC-ACIS Precipitation Time Series
|Date   |StationID 1   |StationID 2   |StationID 3   |StationID X   |
|:-:|---|---|---|---|
|1/01/2000   |0.0   |1.0   |0.0   |precipitation amount   |
|1/02/2000   |0.5   |1.73   |0.2   |precipitation amount   |
|1/03/2000   |0.26   |0.84   |0.64   |precipitation amount   |

** **Note** the data below each station is the amount of precipitation that occured that day. 

## What is a Timeseries Graph

Timeseries, also known as Line Graphs, are used to display quantitative value over a continuous interval or time span. It is most frequently used to show trends and relationships (when grouped with other lines). Line Graphs also help to give a "big picture" over an interval, to see how it has developed over that period.

Line Graphs are drawn by first plotting data points on a Cartesian coordinate grid, then connecting a line between these points. Typically, the y-axis has a quantitative value, while the x-axis has either a category or sequenced scale. Negative values can be displayed below the x-axis.

For more information refer to the links below:

* [Timeseries Graph](http://www.datavizcatalogue.com/methods/line_graph.html)
* [Timeseries Documenation](https://developers.google.com/chart/interactive/docs/gallery/linechart)