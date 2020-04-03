# **Udacity Ford GoBike ReadMe**

## **Introduction**
Ford GoBike is a bike sharing company in San Fransisco that has provided data for its trips from 2017 to 2020.

The goal of the project is to analyze this data and develop insights into the growth of ridership and other interesting trends in the features.

## **Overview of Dataset**
From the AWS server the data was programmatically downloaded and unzipped. 28 different csv files were retrieved and merged to form a master dataset. BeautifulSoup, requests and zipfile were the key packages that were used for this task.

The dataset contains 6 million rows and 14 columns and is about 1.2Gb in size. This data was cleaned for analysis. There were several duplicate rows that were removed. Data type for timestamps were changed to datetime format. Separate columns for year, month and hours were also added for easier analysis later on.

The key columns for interest for us are the duration, the start time and end time of the rides. The rides in each year, hour, weekday and the starting and ending stations are also useful for analysis.

## **Key Insights**
The analysis has identified stations and their corresponding peak demand for bikes on an hourly basis. Moreover, following conclusions were drawn from the presentation-

1.	The bike rides are very popular between 7am to 10am and 4pm to 7pm on weekdays.

2.	Weekdays have considerably more ride demand than weekends.

3.	There seems to be a steady rise in ridership from 2017 to 2020. However, clipper rental method and customer type did not grow as much as app-based rental and subscriber type.

4.	People mostly prefer short rides lasting between 5 min and 10 min on weekdays, but on an average around 16 min long rides on the weekends.

