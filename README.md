# Ment-r
A way to visualize mentor skillsets using a D3 cluster dendrogram and a csv file.

## Overview
These files use a cluster dendrogram layout from the D3 library.  There are two versions of the visualization.

### JSON Cluster Dendrogram
The [mentorship example](http://openglobe.github.io/Ment-r/ment-r.html) uses a JSON file to construct the nodes and links.  The graph will grow, add and expand depending on the data found in the csv file.  the JSON file [is here](https://github.com/OpenGlobe/Ment-r/blob/gh-pages/data/18fmentors.json).

### CSV Cluster Dendrogram
The [consulting example](http://openglobe.github.io/Ment-r/18fconsulting2.html) uses a CSV file to construct the nodes and links.  The graph will grow, add and expand depending on the data found in the csv file.  The CSV file follows the schema found in the data/graph.csv file.  The CSV file is [here](https://github.com/OpenGlobe/Ment-r/blob/gh-pages/18fconsulting2.csv).  This version does not yet include functional node labels.

### More Information
More information can be found [here](http://d3js.org/) and [here] (http://bl.ocks.org/mbostock/2949981).

