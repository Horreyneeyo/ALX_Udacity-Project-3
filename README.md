# Ford GoBike System Data
## by Omoniyi Akinpelumi


## Dataset Exploration Steps

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
The goal of this data analysis is to explore and present insights on the bike-sharing trips taken within this said location. I was able to perform this analysis by investigating relationships of important dataset features.
Although, the dataset was observed to have low data quality issues. Hence data cleaning and wrangling actions were undertaken before the conducting proper exploratory data analysis.
The first step taken was to remove all null data and duplicates. The next action was to conduct some preliminary data statistical check that identify outliers to be removed. This was also done during data exploration.
Furthermore, I performed some feature engineering exercise in generating new information from two or more of the dataset features which can provide more insights on the behaviour of the bike trips - This was the generation of average speed feature and categorical variables for start_period, end_period and start_day
I was also re-engineering data values of distance and duration features from metres to kilometres and secs to minutes. 
 

## Summary of Findings

- The original bike trip dataset had 183412 observations and 16 features. This was modified to 174952 observations and 18 features using feature engineering, dropping of null data and irrelevant features.

- Outputs of feature engineered data output revealed that there are more 'young adults' age-group biker trips than any other age-groups. The next set of age-groups trips counts in decreasing order are the 'older adults', 'elderly' and then 'youth' age_grade groups 

- The average speed of the elderly and the Youth age group is slower compared to the rest of the age groups. The violing plots shows that all the age groups have a normal statistical distribution.

- The longest bike time duration for bike trips occurs in the afternoon for both start and end periods. While morning bike trip start and end period has the lowest bike time duration. While the longest distances covered by the bikers occur in the morning period, this is followed by evening and aftenoon and Night periods.

- Those who chose a 'No' bike share option have higher peak average speed and cover longer distances and then shorter trop duration than those who chose 'Yes' bike share option. Although, this subject to further data exploration using mean values instead of count values due to the imbalance in data. 

- More of the male gender tend to engage in longer distance bike trips than other genders while there is no distinct gender type which engage in longer duration bike trips. 

- More subscribers engage in longer distance bike trips than customers while there is no distinct user type which engage in longer duration bike trips


## Key Insights

-  An overview of the modified dataset shows that 91% of the bikers are subscribers, 9% are customers. 75% of bikers are male, 23% females, 2% identify as others. 10% of the bikers prefer the biker sharing option while 90% do not.

- 75% of bikers covered a distance of 2.2km for a period of about 13 minutes (less than an hour). Although, there were few bike trips with long duration of a max of about 1400 minutes. This could be that bikers took rest breaks before completing the trip 

- Generally, thursday is the most popular day for bike trips with the 'Young adult' age group more active in bike trips. Also, weekends have very low number of bike trips compared to other weekdays. 

- Also, generally, the longest bike time duration for bike trips occurs in the afternoon, while the long distances covered usually occur in the morning period. The evening periods also witness high bike trip durations and long bike distance covered

- On weekends, there are more bike trips in the afternoon period than any time period, while on weekdays, the morning period have the most bike trip start engagments. The elderly age groups are less reluntant to engage in weekend bike trip start. 

- Overall, there is not much difference between the start hour and end hour of bike trips but that there are bi-modal distributions for the start and end bike trips with the two peak bike trip demands at the morning and evening periods on an average day of the week

- Changes were made to all exploration plots by adding titles, labels and legends which makes the visulaization plots more readable and appealing 
