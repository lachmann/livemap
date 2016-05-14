# LiveMap

We want a simple map made from D3.js where at specific intervals (eg: every 3 seconds), a new point appears on the map with a tooltip that fades out. If the user then clicks a point, a popup will appear with some data.

### Sample demo

See here: http://rcmap.hatnote.com/#en

Github repo and code is here: https://github.com/hatnote/rcmap

This is a world map showing live wikipedia updates. It has most of the functionality we require, and its code can be used as a starting point.

**Our map will be much simpler**

### Our map specifics

##### Modifications
1. We do NOT want a world map, but rather specific American States. Specifically, the US states are: MA, CT, RI, NY, PA, NJ, MD, DE, VA. It will look like this (without the legend and lines): ![image](https://cloud.githubusercontent.com/assets/569722/15265131/1f30cd3a-1943-11e6-9e0f-a03b79a900fa.png)  
2. The points data will not be via websockets, they will be hard-coded and just appear at the specified interval time.

##### Additions

1. We will need to add function where when a user clicks a point, a popup appears
