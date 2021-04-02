## Context

This analysis is part of **Microsoft Course for Data Scientist**. In this notebook the aim is to find the reason for delays in departures or arrival of a flight by answering questions.

I couldn't find the dataset link, but information I have is that this is a real-world dataset containing flights data of US domestic flights in 2013 from the US Department of Transportation.

## The Dataset

This dataset has 246484 rows and 20 columns: numeric and non-numeric. All the information contained therein concerns the reality of an airport. Before start to answer the questions, I had to clean the data from outliers and null-values. 


## The Challenge

There were proposed 7 questions to help understand the dataset:

 - *What are the average (mean) departure and arrival delays?*
 - *How do the carriers compare in terms of arrival delay performance?*
 - *Are some days of the week more prone to arrival days than others?*
 - *Which departure airport has the highest average departure delay?*
 - *Do **late** departures tend to result in longer arrival delays than on-time departures?*
 - *Which route (from origin airport to destination airport) has the most **late** arrivals?*
 - *Which route has the highest average arrival delay?*

All of them have been answered, sometimes as a chart, sometimes as a pandas output. I had the answers provided by Microsoft Course, but I only used it to verify. As a matter of fact when I eliminated  outliers I used the 85th percentile and the 10th percentile, whereas Microsoft used 90th percentile and 1st percentile. THerefore the answers had to be different. 

## Libraries

 - [Pandas](https://pandas.pydata.org/): One of the most famous python libraries, to make it simple pandas is like an Excel but for python.
 - [Searborn](https://seaborn.pydata.org/index.html): A great statistic and visualization library, it works similarly as matplotlib, but, in my opinion, works better for statistical visualization.
 - warnings: This library doesn't show the warning messages. It's good to have a clean code visualization.
 - [Matplotlib](https://matplotlib.org/): Although I have chosen seaborn as visualization library, pyplot(which is part of matplotlib) works good to personalize the chart, and therefore it's also used in the code.

## Conclusion

This project is focused on showing my EDA skills, I also have others similar projects that you can see by clicking [here](https://github.com/LucasbFontes/Exploratory-Data-Analysis), if you want to see the flights EDA that I explained in this readme, just click here
