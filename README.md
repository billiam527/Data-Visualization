# Data-Visualization-Iris
####### By: William Fisher

Analyzing data from iris flowers using various techniques.

### Libraries

⋅⋅* Pnadas
⋅⋅* Seaborn
⋅⋅* MatPlotLib
⋅⋅* Numpy
⋅⋅* PyGal

### Files

Iris.csv - Iris data in csv format. Data includes 150 entries for three different iris species.

Iris_Data_Visualization.ipynb - Data visualization notebook created with Jupyter Notebook.

DATA_620_Iris_Visualization.ipynb - Supplementry notebook containing PyGal charts.  PyGal is not supported by Kaggle so these were not included in the Kaggle submission.

### Kaggle Submission

The Kaggle submission can be found here: https://www.kaggle.com/billfish/iris-data-visualization.

Kaggle submission based off original content found here: https://www.kaggle.com/benhamner/python-data-visualizations.

Adjustments made to original submission.
1) I added a regression line into the first jointplot.
2) I added a hexogonal visualization into a seperate instance of the jointplot
3) I added an extra piece of data to the box plot.  The original called for just the petal length but I wanted to use graphs that showed both sepal and petal lengths and widths so I included those into the axes.
4) In the FacetGrid visualization, I used the original but then I also used the fill feature for a second graph.
5) For the final pairplot graph, I changed the markers of the scatterplots to +'s and I changed the colors to the scheme: husl.
6) For the final three plots I played with various color schemes again and went with Greens, gist_rainbow, and winter respectively.

### Iris Dataset

Data can be found here: https://www.kaggle.com/uciml/iris.

The Iris data is a dataset containing three different species of the flower Setosa, Versicolor, and Virginica.  Each species contains 50 measurements.  These measurements are the sepal width, sepal length, petal width, and petal length.  Each of these are measured in centimeters.  There is also an "Id" column that represents a count from 1-150 of each of the flower's measurements.  From a preliminary look at the data, the sepal length will be the largest followed by the sepal width, the petal length, and the petal width in that order.  Finally, at first glance, it appears Virginica will be the largest species, Versicolor next and Setosa last.
