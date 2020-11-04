# Python Matplotlib - Pharmaceutical Data Analysis


## Background

For this assignment I am working for Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I have been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. We have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Instructions

Your tasks are to do the following:

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

## Observations

After reviewing the data following observations can be made:
1. Two drug regimens had the highest number of data points: "Capomulin" and "Ramicane". It maybe because the drugs were effective on tumors and helped with mouse survival over the study time.
2. For an effective results all outside variable were accounted for including mouse sex which has an equal number of male and female mouse in the study.
3. After plotting "Tumor Volume" size against "Timepoint" for a mouse (b128) on "Capomulin" drug regimen it can be observed that the Capomulin Drug helped in reduction of tumor volume in the mouse over time.
4. It can also be observed that there is a positive correlation between "Mouse Weight" and "Tumor Volume" which is further clarified after running a regression line analysis which gave us the a line slope of .95 and intercept of 21.55. It can be inferred that the tumor volume is impacting the mouse weight. As the tumor volume grows so does the mouse weight.
