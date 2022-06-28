# Choosing appropriate chart types for your data visualization project

Compiled By: Dr. Nimrita Koul, Bangalore , India

Sources : Various webpages listed in References below and linked in place in the text. 

Date: 28 June 2022



## [What is data visualization?](https://homes.cs.washington.edu/~jheer/files/zoo/)

Enormous amounts of data available to us today holds valuable information about almost all aspects of human behaviour and life. It has information about governance, health and medical history, finances, business, shopping and leisure activity.    We need ways to explore and communicate the data so that the human visual system can understand the information conveyed by it. [To put the information to good use, we need ways to meaningfully explore, relate, and communicate the data.](https://homes.cs.washington.edu/~jheer/files/zoo/)[1]

Data visualization is the [presentation of data in a pictorial or graphical format](https://guides.lib.berkeley.edu/data-visualization/about) [2]. 
A good picture can convey the results of data analysis with more clarity than a written description. 


Visualizations help us identify patterns in data and discover actionable insights from it. They leverage the visual abilities of human eyes and brain in detecting patterns and violation of patterns in visual representations. It is easier and quicker for us to spot trends, gaps and outliers in visuals. [3] 

[Noah Illinsky, Center for Advanced Visualization, IBM,](http://complexdiagrams.com/4pillars) [3,4] has laid out following [4 properties of a successful visualization](https://www.dropbox.com/s/c80bodax3yx4au1/iliinsky%20visualization%201%20-%20pillars.pdf?dl=0):

1. It has a clear purpose (Ask yourself "**why** is this visualization required?")
2. Includes only the relevant content ("**what** are you vizualizing in this figure?")
3. Uses appropriate structure ("**how** are you visualizing it?")
4. Has useful formatting ("Does your figure have **required formatting** to make it more readable?")


### [Benefits of visualization]((https://guides.lib.berkeley.edu/data-visualization/about))

- Visualizations enable us to [identify not so obvious patterns in data](https://guides.lib.berkeley.edu/data-visualization/about) in data. [Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet) consists of four datasets that have nearly identical statistical properties but when visualized in scatter plots, they reveal four distinct patterns.


<img src = "https://upload.wikimedia.org/wikipedia/commons/e/ec/Anscombe%27s_quartet_3.svg" style="width: 600px;"/>
<center><i> Source: https://upload.wikimedia.org/wikipedia/commons/e/ec/Anscombe%27s_quartet_3.svg</i></center>


- They help us compare two or more variables. 
- They help us discover hidden information and insights from data. 
- They enable us to comprehend massive amounts of data in small space. 


### [Types of associations in data](https://multimedia.journalism.berkeley.edu/tutorials/visualizing-data-a-guide-to-chart-types/) [6]:

1. Relationship - A relationship that shows a relative pattern in the values of way two or more variables.  E.g., height and weight of a person, salary and years of experience of professionals. 

2. Comparison - A comparison shows the differences between two or more variables, their interactions. E.g., the Amazon user rating of a digital camera of various brands over last one year. 

3. Composition - A composition shows the constituent information about a variable. E.g., the professions of the customers of a department store, browesers used by customers to visit your webpage. 

4. Distribution - A distribution shows information about two or more variables in order to identify any interactions between them. E.g., rainfall in centimeters in every month of 2021. 


### [Choosing appropriate Chart Types](https://guides.lib.berkeley.edu/data-visualization/type) [7]

Choice of possible visual representations/chart types for a dataset is huge. 

Various computer scientists, psychologists, and statisticians have studied effectiveness of different chart types in facilitating comprehension of different types of data. E.g., [positional chart types like scatter plots or bar charts are most effective in representing numerical data as compared to chart types that use visual cues like angle, 1D length, 2D area, 3D volumne or color saturation](https://homes.cs.washington.edu/~jheer/files/zoo/)[1]. 

Bar charts, grouped bar charts, and histograms are good examples of visualizations that allow for [easy comparisons](https://homes.cs.washington.edu/~jheer/files/zoo/)[1]. A well-crafted visualization will enable you to quickly compare one variable (or a set of variables) against another.


#### [Think about your variables to select right type of visualization](https://guides.lib.berkeley.edu/data-visualization/type) [7]

You should take into account data types of your variable (categorical or numeric), volume of data and the question you wish to answer through the visualization. Take into account the audience of your visualization. Optimize your data narrative through design. According to [Cleveland and McGill (1985)](https://www.science.org/doi/10.1126/science.229.4716.828) [8], the visual characteristics of data visualization in the order of least difficult to most difficult are: 

1. position along a common scale
2. position along a non-aligned scale
3. length
4. angle and slope
5. area
6. volume, density, and color saturation
7. color hue 

This means that a visualization consisting of differently sized and colored bubbles is more difficult for the human eye to discern than a bar chart (position along a common scale).

[Image below](https://multimedia.journalism.berkeley.edu/wp-content/uploads/Screen-Shot-2016-08-11-at-1.34.23-PM.png) [6] shows a criteria for choosing chart type for your data.

<img src = "https://multimedia.journalism.berkeley.edu/wp-content/uploads/Screen-Shot-2016-08-11-at-1.34.23-PM.png" style="width: 1000px;"/>
<center><i> Source: https://multimedia.journalism.berkeley.edu/tutorials/visualizing-data-a-guide-to-chart-types/</i></center>
 

#### [Suitable Plot Types for different types of associations in data](https://www.dropbox.com/s/c80bodax3yx4au1/iliinsky%20visualization%201%20-%20pillars.pdf?dl=0) [3] 
[9](https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/)

1. To visualize Relationships among data points 
- scatter plot
- matrix chart
- network diagram

2. To visualize correlations - 
- scatter plot
- bubble plot 
- strip plot
- count plot
- marginal histogram
- heat map
- pair plot

3. To visualize deviation
- diverging bar plot
- area chart

4. To visualize ranking
- Ordered bar chart
- line plot

5. To visualize distribution 
- histogram
- density plot
- box plot
- violin plot
- catplot

6. To visualize composition
- pie chart
- tree map

7. To visualize change in data
- line plot
- stacked area chart
- time series plot

8. To visualize grouping in data
- dendrogram
- cluster plot

  
#### [About prominent chart types](https://multimedia.journalism.berkeley.edu/tutorials/visualizing-data-a-guide-to-chart-types/)

- Line Charts - Line charts should be used to visualize changes in one or more numeric variables over time, or over stages of progress. 
- Area Charts - Area charts also show changes in numerical variables over time, however they have a shaded area under the lines that displays values of variables for easy comparison of their magnitudes. 
- Scatter charts - Display relative values of two numerical variables on two different axes in the plot. 
- Bubble charts - Like scatter plot, bubble plot also shows values of two variables on two axes, however they can represent a third variable also by the size of the bubbles. 
- Bar charts - Bar plots can be used to compare two or more discrete or categorical variables. Horizontal bar charts focus more on categories which are compared, and vertical bar charts focus on values of data.
- Stacked Bar - These allow to view multiple categories in each bar in the graph. 
- Pie charts - These enable to display components of a whole. However, piecharts can be confusing because the relative size of the pie and the slice of the pie can be hard to discern. Therefore, piecharts have been replaced by bar charts often.  

### [Matplotlib](https://matplotlib.org/)

Matplotlib is a python library that provides comprehensive functions for creating static, animated, and interactive visualizations. It enables you to create and customize publication quality plots. You can customize the visual style and layout of your plots as well as zoom, pan or update them. You can save and export your plots to many file formats. 


The python plotting libraries [Matplotlib](https://matplotlib.org/stable/plot_types/index.html) and [Seaborn](https://seaborn.pydata.org/examples/index.html) provide multiple chart types for effective visualization of data. 
Matplotlib supports 2D plotting extensively and simple 3D plotting using [mplot3d](https://matplotlib.org/stable/api/toolkits/mplot3d.html?highlight=mplot3d) toolkit. 

##### [Prominent 2D Chart Types in Matplotlib](https://matplotlib.org/stable/plot_types/index.html)

- line plot
- scatter plot
- bar plot
- contour plot
- histogram
- box plot
- violin plot
- pie chart
- fill-between plot
- error bar
- stem plot
- event plot

##### [Prominent 3D Chart Types in Matplotlib](https://matplotlib.org/2.0.2/mpl_toolkits/mplot3d/tutorial.html)

- scatter plot
- wireframe plot
- surface plot
- contour plot


#### [Seaborn Plotting Library](https://seaborn.pydata.org/)

Seaborn is a python data visualization library based on matplotlib. It is a high level interface for drawing attractive and informative statistical graphics.


##### [Prominent Seaborn Chart Types](https://seaborn.pydata.org/examples/index.html)
- scatter plot
- lineplot
- catplot
- relplot
- distplot
- jointplot
- JointGrid
- FacetGrid
- heatmap
- kdeplot
- swarm plot

References-

[1]. https://homes.cs.washington.edu/~jheer/files/zoo/

[2]. https://guides.lib.berkeley.edu/data-visualization/about

[3]. https://www.dropbox.com/s/c80bodax3yx4au1/iliinsky%20visualization%201%20-%20pillars.pdf?dl=0

[4]. http://complexdiagrams.com/4pillars

[5]. https://guides.lib.berkeley.edu/data-visualization/about

[6]. https://multimedia.journalism.berkeley.edu/tutorials/visualizing-data-a-guide-to-chart-types/

[7]. https://guides.lib.berkeley.edu/data-visualization/type

[8]. Cleveland, William S., and Robert McGill. 1985, "Graphical perception and graphical methods for analyzing scientific data." Science 299 (4716):828-833.

[9]. https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/



```python

```
