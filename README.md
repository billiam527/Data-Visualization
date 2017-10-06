# Data-Visualization-Iris

1) Become very familiar with what exactly this dataset includes so that you can answer questions about data collection, the type of data, and the possible analytic choices.

The Iris data is a dataset containing three different species of the flower Setosa, Versicolor, and Virginica.  Each species contains 50 measurements.  These measurements are the sepal width, sepal length, petal width, and petal length.  Each of these are measured in centimeters.  There is also an "Id" column that represents a count from 1-150 of each of the flower's measurements.  From a preliminary look at the data, the sepal length will be the largest followed by the sepal width, the petal length, and the petal width in that order.  Finally, at first glance, it appears Virginica will be the largest species, Versicolor next and Setosa last.

2) Select one of the kernels that include visualizations, and you are interested in reproducing/learning. 

I chose to recreate the following kernel: https://www.kaggle.com/benhamner/python-data-visualizations.

3) Copy the kernel in your python code. This does not mean that you can simply copy and paste.  It will require you to understand the code of someone else’s and EXPLAIN everything that is included in the code in your own words.  So, you will include a write-up for every line of code in your GitHub submission (not necessary to include in the Kaggle submission).

4) Once the code is understood and clear, you can start tweaking something – this part is something you will do with whatever you are comfortable doing (i.e., color, axes, 3D, the shape, horizontal/vertical, titles, legends, etc.) For the first part of the project, I will not ask you to do more than 2 (two) of these tweakings, but please feel free to do more. 

I made a number of tweaks to the original submission.
1) I added a regression line into the first jointplot.
2) I added a hexogonal visualization into a seperate instance of the jointplot
3) I added in a extra piece of data to the box plot.  The original called for just the petal length but I wanted to use graphs that showed both sepal and petal lengths and widths so I included those into the axes.
4) In the FacetGrid visualization, I used the original but then I also used the fill feature for a second graph.
5) For the final pairplot graph, I changed the markers of the scatterplots to +'s and I changed the colors to the scheme: husl.
6) For the final three plots I played with various color schemes again and went with Greens, gist_rainbow, and winter respectively.

5) Finally, all the work will need to post on Github (including a detailed readme file an explanation for every line of code), and Kaggle. Please make sure that your Github readme files include a table, italics, headings, bold, or whatever you want – but it needs to use Github markdowns and looks visually presentable. 
