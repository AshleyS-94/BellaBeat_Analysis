# Marketing Analysis

## Table on Contents

1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Tools](#tools)
4. [Data Cleaning & Preparations](#data-cleaning-&-preparations)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Data Analysis](#data-analysis)
7. [Results & Findings](#results-&-findings)
8. [Recommendations](#recommendations)
9. [Limitations](#limitations)
10. [References](References)

### Project Overview

This project aims to optimize BellaBeat's marketing strategy by analyzing consumer behavior through smart device data. We identify trends, make data-driven recommendations, and deepen our understanding of the target audience.

### Data Sources

FitBit Fitness Tracker Data - The primary data source for analysis using the "dailyActivity_merged.csv", "heartrate_seconds_merged.csv", and "minuteSleep_merged.csv" files. [Download here](https://www.kaggle.com/datasets/arashnic/fitbit)

### Tools

- Excel
- BigQuery

### Data Cleaning & Preparation

I carried out these data preprocessing procedures to prepare the dataset for analysis:
- Data loading and inspection
- Remove duplicates
- Handling missing values
- Data formatting

### Exploratory Data Analysis

Explore the marketing analysis to answer key questions such as:
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

### Data Analysis

Coding/features worked with

```sql
SELECT DISTINCT Id, ActivityDate, Calories 
FROM `my-data-project122722.Fitbit_data_tracker.daily_activity` 
WHERE Calories > 2400;
```

### Results & Findings

Thirty users actively participated in the study. Although over half slept seven or more hours nightly, 48% had an obese BMI. The CDC recommends 150-300 minutes of weekly moderate exercise, which our participants did not meet on average.


### Recommendations

To optimize user engagement, we suggest:
1. Promoting the Leaf product as a valuable tool for staying active through timely reminders.
2. Adding soft melody sounds or an alarm clock to encourage more users to utilize the sleep monitoring features.

### Limitations

- Limited demographic information: The age and demographics of the study participants were not fully documented.
- Small sample size: The study involved a relatively small group of participants.
- Thirty-day data collection period: Data was gathered over a one-month period.

### References

FitBiT Fitness Tracker data. (2020, December 16). Kaggle. (https://www.kaggle.com/datasets/arashnic/fitbit)

Move more; sit less. (2023, June 22). Centers for Disease Control and Prevention. (https://www.cdc.gov/physicalactivity/basics/adults/index.htm)

Healthy weight, overweight, and obesity among U.S. adults. (n.d.). National Health and Nutrition Examination Survey. (https://www.cdc.gov/nchs/data/nhanes/databriefs/adultweight.pdf)

CDC Newsroom. (2016, January 1). CDC. (https://www.cdc.gov/media/releases/2016/p0215-enough-sleep.html)

Osilla, E. V. (2022, September 12). Calories. StatPearls - NCBI Bookshelf. (https://www.ncbi.nlm.nih.gov/books/NBK499909/)

#
