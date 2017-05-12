# Summary

The graph compares reasons of plane delay by carrier name from 2003
to 2017. The time component also highlights when carriers were active.

<br>

# Design

The dataset has a lot of information; the highlight to me was how carriers 
improved their 'on time' flights throughout the years.

Initially all I wanted was a bar graph. The graph would showcase delay reason vs
carrier name and could be interacted with on hover to view values.

After filtering the data (at least I though I had) I noticed including an 
animation over the years would be an absolutely great idea. I got some help
reorganizing my code to properly work with this idea.

#### 1) index1.html

Initially designed to showcase I wrangled my data properly and was not intended 
as a final product. I really enjoy dimple's automatic choice of colors and 
general layout. From this chart I decided to switch where I was to put years and
lengend data. 

Although this chart is a total for all carriers, not all carriers existed from
2003 to 2017; a better representaion for comparing carriers by year is to 
animate the chart.

#### 2) index2.html

Animation more easily revealed when carriers were active. It was a lot of fun
visually seeing which carriers were present for each year and how delay 
percentages would generally increase or decease for each carrier. 

Problems:

* Not being able to select years 
* Not being able to pause 
* Not being able to easily compare values across carriers within the same year


#### 3) index3.html

Introducing the option to select years (thus pausing the chart) solved much of
the earlier issues! Readers are more apt to interact with the dataset when they
access to pause or change the animation. 

The main problem in this graph is some values are so small changes can't be 
viewed (such as 'security').


#### 4) index_final.html

Because the 'On Time' Information was taking up most of the graph it was removed
to help better understand delay reasons for each Carrier. The number of carriers
in each data set is mapped on the selection for each year. 

The only value so small it's _still_ difficult to view is 'Security'. I do not 
see this as a problem because (with 'On Time' no longer part of the graph and
a similar color to 'Security') the contrast with the smaller variables is more
readily apparent.

A piece of feedback I recieved is being able to rearrange bars horizontally to
more easily rank carriers. Although this is a great feature I feel having more
moving parts would be very difficult for readers to understand.

Because the 'On Time' Information was taking up most of the graph it was removed
to help better understand delay reasons for each Carrier. The number of carriers
in each data set is mapped on the selection for each year. 

The only value so small it's _still_ difficult to view is 'Security'. I do not 
see this as a problem because (with 'On Time' no longer part of the graph and
a similar color to 'Security') the contrast with the smaller variables is more
readily apparent.

<br>

# Feedback

"Taking out 'On Time' values and viewing just Carrier delays is a lot more 
<<<<<<< HEAD
intersting" - Amazing Person in Life

"Wow! There's even a chart displaying the number of carriers; I like how the 
entire page is being used to display data!" - Renown Research Analyst

"Looks like I chose the correct carrier for our trip!" - Occacional Flyer
=======
intersting" - Amazing Person in My Life
>>>>>>> master

<br>

# Resources

http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control

http://dimplejs.org/examples_viewer.html?id=bars_vertical_stacked_100pct

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart

https://discussions.udacity.com/t/dand-project-trying-to-make-a-bar-chart/245558/2

http://www.d3noob.org/2013/01/adding-title-to-your-d3js-graph.html