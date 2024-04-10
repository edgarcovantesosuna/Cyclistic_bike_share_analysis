# Case study: Cyclistic bike-share analysis

by Edgar Covantes Osuna.

## Content

This repository contains two solutions for the Google Data Analytics Capstone: Complete a Case Study, as part of the [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics).

The task titled "Case Study 1: How does a bike-share navigate speedy success?" consists of analyzing a case similar to what you might be asked for in a job interview.

The current repository contains several files and one folder used in the present analysis. Among the files included, there is a PDF containing the information related to the case study, the history and background. 

Two solutions presented in a Python and R Jupiter Notebooks (feel free to run them using Kaggle). Finally, a folder called `reports` where all the final reports are stored.

## Scenario

The scenario is based on a fictional company called Cyclistic, a bike-share company in Chicago. The **hypothesis** is that the director believes the company's future success depends on maximizing the number of annual memberships.

To do this, it is necessary to understand how the different customers behave, for this we need to study how *casual riders* (customers who purchase single-ride or full-day passes) and *annual members* (customers who purchase annual memberships) use Cyclistic bikes differently.

The **goal** for the team is to design a new marketing strategy to convert casual riders into annual members. And to achieve such goal the team has defined the following research questions that will guide the analysis:

1.  How do annual members and casual riders use Cyclistic bikes differently?

2.  Why would casual riders buy Cyclistic annual memberships?

3.  How can Cyclistic use digital media to influence casual riders to become members?

In this case, we will focus on the first question, provide insights about the different habits of casual riders and annual members using Cyclistic bikes.

## Obtaining the data set

We have used Cyclistic's historical trip data to analyze and identify trends. For this we have make use of the information contained in the following ZIP files ([available here](https://divvy-tripdata.s3.amazonaws.com/index.html)):

| ZIP file names          | Date Modified              | Size     |
|:------------------------|:---------------------------|:---------|
| Divvy_Trips_2019_Q1.zip | Nov 8th 2021, 04:05:26 pm  | 9.57 MB  |
| Divvy_Trips_2019_Q2.zip | Nov 8th 2021, 04:06:12 pm  | 28.72 MB |
| Divvy_Trips_2019_Q3.zip | Jan 24th 2020, 10:08:06 am | 42.36 MB |
| Divvy_Trips_2019_Q4.zip | Jan 24th 2020, 10:08:07 am | 18.40 MB |
| Divvy_Trips_2020_Q1.zip | May 26th 2020, 07:17:43 pm | 15.92 MB |

The reason we have chosen those files is to have the newest information for the analysis, the complete 2019 information, plus the 2020 Q1.
