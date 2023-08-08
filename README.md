# Project Description

Hello there :wave:
I hope this project finds you well!

In this project, I will discover patterns to understand passenger preferences and the impact of external factors on the rides of a ride-sharing company in Chicago.

**Objective**
To understand passenger preferences and the impact of external factors on the rides. You will study the database, analyze data from competitors, and test hypotheses about the influence of weather on trip frequency.

**Hypotheses**
1. The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays.

# Steps

1. Data Overview
2. Data Preprocessing
3. Exploratory Data Analysis
4. Hypotheses Testing

## 1. Data Overview

**Data Description** 

Company Dataset

-   `company_name` - taxi company name
-   `trips_amount` - number of trips for each taxi company on November 15-16, 2017.

Drop-off Dataset

The dataset includes the following columns:
- `dropoff_location_name` - name of the Chicago area where trips end
- `average_trips` - average number of trips ending in each area in November 2017.

trips dataset
- `start_ts` - date and time of pickup
- `weather_conditions` - weather conditions at the start of the trip
- `duration_seconds` - duration of the trip in seconds


## 2. Pre-Processing Data

The following are data preprocessing steps I did in this project:
1. Rounding average_trips
2. Fixing Data Types
3. Define Lower Bound and Upper Bound
4. Cleansing Outliers Data


## 3. Exploratory Data Analysis:

1. Identifying the top 10 drop-off locations based on average trips. Present the data in a graph.
	
**Findings**

- Based on the data subset above, Loop is the top drop-off location with the highest average number of trips, which is 10728 trips.
- There is a noticeable difference with Sheffield & DePaul, which is the 10th drop-off location with 1260 trips.
- This indicates that Loop is the most preferred drop-off area, possibly having a high concentration of destinations or stores that passengers frequently travel to.

2. Identifying the top 10 company names based on the number of trips. Present the data in a graph.

**Findings**

- Based on the subset of data above, Flash Cab is the most trusted company by customers, with a total of 19558 trips.
- About 30% below that, Blue Ribbon ranks 10th with a total of 5953 trips.
- This indicates that Flash Cab has the highest number of trips among taxi companies, which might be due to having a large fleet and covering a wide range of areas.


# Hypotheses Testing

#### Hypothesis 1: The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays

**Verdict**
The average travel duration from Loop to O'Hare International Airport CHANGES on rainy Saturdays or when weather conditions are "Bad."
This means that when weather conditions are "Bad," the travel duration is different.

**Insight**
Since the travel duration changes when weather conditions are "Bad," this can be anticipated by providing extended travel duration estimates.


# General Conclusion

1. Loop is the drop-off point with the highest average number of trips, totaling 10,728 trips. This indicates that Loop is the most favored drop-off location, possibly because it's a destination for many passengers.
2. Flash Cab is the most trusted company among customers, with a total of 19,558 trips. This shows that Flash Cab has the highest number of trips, likely due to a large fleet of vehicles covering many areas.

3. The hypothesis is accepted, meaning that the average travel duration from Loop to O'Hare International Airport CHANGES on rainy Saturdays or when weather conditions are "Bad."
