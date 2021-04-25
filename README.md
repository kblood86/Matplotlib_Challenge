# Matplotlib_Challenge

Two data sets were merged to create the intial data frame. One set included the mouse ID and it's tumor size based on the timepoint. The other data set included the Mouse ID, the drug regimen it was on, it's weight, age, and gender.


After the data was merged any mouse with duplicate time points was removed.


A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was created using two different methods.


Two bar charts were created using different methods (PyPlot and Pandas). These showed the total number of measurements taken for each treatment regimen throughout the course of the study.


Two pie charts were created using different methods (PyPlot and Pandas). These showed the distribution of female and male mice in the study.


The final tumor volume of each mouse was calculated across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The quartiles and IQR were then determined. Any potential outliers were quantitatively determined across all four treatment regimens.


A box and whisker plot of the final tumor volume for all four treatment regimens was created. The singular potential outlier in the plot was identified. 


Mouse S185 was selected due to its treatment with the Capomulin regimen. A line plot show casing the tumor volume over time was created for this mouse. 


A scatter plot of tumor volume versus mouse weight was also created for the Capomulin treatment regimen.


The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment was determined . Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.