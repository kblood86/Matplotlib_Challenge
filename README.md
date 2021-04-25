# Matplotlib_Challenge

Two data sets were merged to create the intial data frame. One set included the mouse ID and it's tumor size based on the timepoint. The other data set included the Mouse ID, the drug regimen it was on, it's weight, age, and gender.


After the data was merged any mouse with duplicate time points was removed.


A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was created using two different methods.


Two bar plots were created using different methods (PyPlot and Pandas) were total number of measurements taken for each treatment regimen throughout the course of the study.


NOTE: These plots should look identical.



Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.


NOTE: These plots should look identical.



Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.


Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.


Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.


Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.