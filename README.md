# **Pharma-Data-Visualization-MatPlotLib**

### Task

* Use artificial data of a scientific study on drug effectiveness on reducing tumor sizes in mice.
* Specifically, compare the regimen Capomulin against other treatments.
* The following results have been calculated:

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM (standard error of the mean) of the tumor volume for each drug regimen.
    
![SummaryTable](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/SummaryStats.png)

* A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen.
   
![BarPlot](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/BarChart.png)

* A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

![PieChart](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/PieChart.png)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
* Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

![QuartilesETC](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/QuartilesETC.png)

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens

![BoxWhisker](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/BoxandWhisker.png)

* Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

![LinePlot](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/LineGraph.png)

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

![Scatter](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/VolumeVsWeight.png)

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 
* Plot the linear regression model on top of the previous scatter plot.

![LinearReg](https://github.com/michaellegg16/matplotlib-challenge/blob/master/Screenshots/LinearRegression.png)


### Instructions

1. To run this code, open the .ipynb file in juyter notebook (make sure that you have the necessary modules installed).
1. Ensure that the data is downloaded into the proper path to be imported.
1. Run all of the kernals in jupyter notebook to see the results be calculated. 


### Conclusion

Based on my analysis it can be determined that the drug regimens Capomulin and Ramicane appear to have the smallest average tumor size at the final time point. Additionally, tumor volume seems to effectively and consistenly go down over time when treated with teh fictional drug Capomulin. While this all sounds promising, I believe the most influential factor when determining tumor size is simply mouse weight. A 0.84 correlation coefficient was calculated from the linear regression of average mouse weight on Capomulin vs average tumor volume demostrating how strongly related mouse weight and tumor volume are. Tumor volume did become reduced to small volumes over time on the Caplmulin regimen, but it is impossible to make any true conclusions from this study since it is all fictional and for demonstrative purposes only. 
