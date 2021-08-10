# Matplotlib Exploration

The Data Science & Analytics Certification Course covered the Matplotlib library and explored its capabilities together with other powerful libraries such as numpy, scipy, amd scickit-learn in order to give a statisical analysis both qualitativley as well as quantitatively. 

Below a background on the assignment dataset is given as well as a set of deliverables.

The concepts covered in this portion of the certification were well understood and can easily be applied to other real world datasets.

## Background

"What good is data without a good plot to tell the story?

So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

![Laboratory](Images/Laboratory.jpg)

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results."


## Data Clean Up

* Before beginning the analysis, the data was checked for any mouse ID with duplicate time points and any data associated with that mouse ID was removed.

* The cleaned data was saved to a new dataframe and used for the remaining steps.


## Statistical Analysis and Qualitative Figures (Deliverables)

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was created for later reference.

* A bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` was generated that showed the total number of measurements taken for each treatment regimen throughout the course of the study.

* A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` was generated that showed the distribution of female or male mice in the study.

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin was calculated. 
Also, the quartiles and IQR were calculated in order to determine if there were any potential outliers across all four treatment regimens.

* Using Matplotlib, a box and whisker plot was generated for the final tumor volumes for all four treatment regimens and any potential outliers were highlighted in the plot by changing their color and style.

* A mouse that was treated with Capomulin was selected and a line plot of "tumor volume vs. time" was generated for that mouse.

* A scatter plot of "mouse weight versus average tumor volume" was generated for the Capomulin treatment regimen.

* The correlation coefficient was calculated and a linear regression model between mouse weight and average tumor volume for the Capomulin treatment was produced. The linear regression model was plotted on top of the previous scatter plot.
