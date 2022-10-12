# (Ford GoBike System Data)
## by (Manuel Tekena)


## Dataset


> The dataset I selected is the 2017-fordgobike-tripdata.csv. This datasetoriginaly had 183412 rows with 16 columns such as locations, time, and user attributes. I however made some adjustments i thought were necessary for the exploration. My wrangling included changing the datatype of the start and end time columns to datetime, changing the name of the birth year column to age and then changing the birth years to their actual ages, changing the durations columns to trip hours and converting the time from seconds to hours. During my analysis I further created a subset from the data set of the most active stations, I used this subset to carry out most of my analysis.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

1. So the bulk of my analysis for this project was going to based on the top 5 busiest stations. In order to carry this out I had to locate the top 5 busiest stations and create a subdataset for them alone. 
 I also looked at the genger category and found out that there are more male users than female users as was ecpected.
 I also did some analysis on User type and found out that subscribers are more than customers by a lot( further investigation would have to be carried out as to why the difference is so large

2. So I considered the relationship betwen age column and trip hours but there were missing values which were messing the the plot so i had to drop those values. Most of the ages fall between 30 to 40. Males seem to have a lot more trips than the females

3. The distribution of the age of male and female users are positive-skewed. For the first plot for the female distribution the bin sizes were too narrow and so it appeared that the distribution was bi-modal but after adjusting the bin size it gave a more accurate representation
4. From my exlorations I deduced that there are more subcribers than customers probably as a result of the good servies offered by GoBike systems that would make customers want to become members. I also discovered that most of these subscribers are males and a majority of those males are in their 30's and 40's while a majority of women are in their 30's 



## Key Insights for Presentation

> For my presentation I will be focusing on my analysis that concerns USer Type and User Gender in regards to how much of the trips in the 5 top stations revolve around them. I will also be looking at the distribution of ages for males and females in the top 5 stations