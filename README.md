# Major Question: What is the relationship between weather and homelessness in 20 of the largest populated metropolitan cities?

Hypothesis: IF the weather is warmer than average in a major U.S. metropolitan county THEN it will have a higher homelessness rate.

Initially, we collected 20 out of the top 50 largest populated metropolitan cities, and drew data on the total homeless population based on the county that they preside in from the years 2014 to 2015. This data came from a series of csvfile.

We decided upon using 2014 data specifically to represent our data as the small change in homelessness from 2014 to 2015 we assessed to be negligible. 

## Is our sample weather data heterogenous enough to use?
Using a boxplot, and configuring the median temperature for each county, we found that our temperatures were spread out enough to assess the possibility of correlation with homelessness rate. 

## What is the population and homelessness per capita? 
Using an estimated population projection from the 2010 census, we represented the population for 2014 using a bar graph. We also used a bar graph to represent 2014 total homelessness in each county.

## Is there a difference in homelessness per county across counties?
To do this, we calculated homelessness per capita using total homeless individuals over total population of selected respective county. Then, we used a pie graph to represent these values, providing a preliminary idea on whether our hypothesis may or may not be true. 

## Is there correlation between weather and homelessness rate?
Using both data with and without outliers (outliers were found using boxplot analysis), we created scatterplots to compare the difference in temperatures and total homeless per capita to see if there was significant correlation between these two factors. We found that there was little to no correlation for either plot, indicating that our hypothesis was false.

## Table of Contents:


Folders:
    -County_Weather: Contains weather CSVs
        -CSV for each county's weather data
        -Weather_Summary CSVs: Contain summary statistics of all county weather (mean, median, min, max, etc.)
        -All_Temps CSVs: Contain every hourly temperature measurement for every county
    -Data_Cleaning: Contains data cleaning notebooks
        -All_Temp_Measurements notebooks: for loop notebook gathering and cleaning every hourly temperature measurement for each county
        -Final_Data_Cleaning: for loop notebook gathering and cleaning summary weather measurements for each county 
        -Master DataFrame: Contains weather summary data as well as population data and homeless population data. Calculates rate of homelessness in each county
    -Figures: Contains all figure outputs
    -Jupyter_Notebooks: Contains notebooks used for graphs and figures

          