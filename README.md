# Pymaceuticals


As a senior data analyst at Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, you've been given access to the complete data from their most recent animal study. This animal study is the company's recent efforts at screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Note; Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

The results will contain the following;

       * A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
   ![](Graphs%20and%20Charts/Screen%20Shot%202020-11-30%20at%2022.20.05.png)
       * A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
  ![](Graphs%20and%20Charts/PyPlotBar.png)
  
       * A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
      
   ![](Graphs%20and%20Charts/PyPlotPie.png)
   
       * Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
       * Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
       * Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
       * Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
   ![](Graphs%20and%20Charts/Time%20Series%20of%20Tumor%20Volume.png)
   
       * Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
   ![](Graphs%20and%20Charts/Weight%20vs%20Average%20Tumor%20Volume.png)
   
       * Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
   ![](Graphs%20and%20Charts/Linear%20Regression.png)
