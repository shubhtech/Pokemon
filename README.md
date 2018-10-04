# Exploration and Visualization of Data with Python and libraries like matplotlib and seaborn

### About this Jupyter Notebook
To run this notebook you need to install necessary packages, listed down. If you have not done so, you will need to install them first, as these are not in the Anaconda distribution as of now. From a command prompt on your computer type the following command. If no error occurs, you will have installed them.

```pip install seaborn```
```pip install pandas```
```pip install matplotlib```

### How to get started?
Fork the repository to run the jupyter notebook on your own computer.

### About the dataset
The datasets used for exploration is [Pokemon Dataset](https://github.com/Praneet460/DataVisualizationPyDelhi/blob/master/pokemon.csv) 

You can download the dataset from [Kaggle](https://www.kaggle.com/rounakbanik/pokemon/home)

### Basic chart types
There are enumerable chart types that are used for data exploration. Some of them are explained below
* <b>Scatter plot</b> : Scatter plots show the relationship between two variables in the form of dots on the plot. In simple terms, the value along a horizontal axis are plotted against a vertical axis.
* <b>Line plot</b> : Line plots are similar to point plots. In line plots the discrete points are conneced by lines.
* <b>Bar plot</b> : Bar plots are used to display the counts of unique values of a categorical variable. The height of the bar represents the count for each unique category of the variable.
* <b>Histogram</b> : Histograms are related to bar plots. Histograms are used for numeric variables. Whereas, a bar plot shows the counts of unique categories, a histogram shows the number of data with values within a bin. The bin divide the values of the variable into equal segments. The vertical axis of the histogram shows the count of data values within each bin.
* <b>Box plot</b> : Box plots, also known as box and wisker plots, were introduced by John Tukey in 1970. Box plots are another way to visualize the distribution of data values. In this respect, box plots are comparable to histograms, but are quite different in presentation. On a box plot the median value is shown with a dark bar. The inner two quartiles of data values are contained within the 'box'. The 'wiskers' enclose the majority of the data(up to +/-2.5 * interquartile range). Outliers are shown by symbols beyond the wiskers. Several box plots can be stacked along an axis for comparison. The data are divided using a 'group by' operation, and the box plots for each group are atacked next to each other. In this way, the box plot allows you to display two dimensions of your dataset.
* <b>Kernel Density Estimation Plots(KDE)</b> : Kernel density plots are similar in concept to a histogram. A kernel density plot displays the values of a smoothed density curve of the data values. In other words, the kernel density plot is a smoothed version of a histogram.
* <b>Violin plot</b> : A violin plot combines attributes of boxplots and a kernel density estimation plot. Like a box plot, the violin plots can be stacked, with a 'group by' operation. Additionally, the violin plot provides a kernel density estimate for each group. As with the box plot, violin plots allow you to display two dimensions of your dataset.
