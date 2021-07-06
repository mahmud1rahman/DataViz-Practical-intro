# DataViz_Practice_through_code_exapmles

This project include the Work through the code examples from the book 
[Data Visualization
A practical introduction](https://socviz.co/index.html#preface) by Kieran Healy.

My Main takeways so far :

1.Cleveland dotplots are generally preferred to bar or column charts

2.There are so many great packages to take advantages of when creating plots with ggplot2.

- RColorBrewer
- ggthemes
- cowplot (contains a well-developed theme suitable for figures)
- hrbrthemes
- cowplot
- ggridges



Below can work as guideline for anyone :

''When producing a graphic like this in ggplot, or when looking at good plots made by others, it should gradually become your habit to see not just the content of the plot but also the implicit or explicit structure that it has. First, you will be able to see the mappings that form the basis of the plot, picking out which variables are mapped to x and y, and which to to color, fill, shape, label, and so on. What geoms were used to produce them? Second, how have the scales been adjusted? Are the axes transformed? Are the fill and color legends combined? And third, especially as you practice making plots of your own, you will find yourself picking out the **layered** structure of the plot. What is the base layer? What has been drawn on top of it, and in what order? Which upper layers are formed from subsets of the data? Which are new datasets? Are there annotations? The ability to evaluate plots in this way, to apply the grammar of graphics in practice, is useful both for looking at plots and for thinking about how to make them.''