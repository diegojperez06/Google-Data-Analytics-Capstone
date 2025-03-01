# Google-Data-Analytics-Capstone
Analyzing and Developing Marketing Campaign

- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Datasource](#datasource)
- [Data Analysis Process](#data-analysis-process)
- [Conclusion](#conclusion)


### Project Overview
--- 
This project aims to provide data-driven decisions by working through the data analysis process. As an analyst working for a fictional online bike shop I am tasked with preparing a marketing campaign to turn casual riders into annual memebers. By first understanding the main difference between the  annual memebers and casual riders, an executive presentation was put together to provide a meaningful marketing campaign.


### Business Objective
---
The company has noted that the future success and growth of the organization will come by maximizing the number of annual memeberships. Therfore my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will develop a new marketing campaign and initiaves to promote casual riders into annual members. 

### Datasource
---
The company maintains its trip data in different monthly file, which have been downloaded from the Internet. For my project I have used 2024 Q4 data (October, November and December) due to the large file sizes of each individual datasheet. 

https://divvy-tripdata.s3.amazonaws.com/index.html

### Data Analysis Process
---

#### Ask

In the beginning stages, identifying the business task and key stakeholders is crucial. As previously stated, this project's main task is to provide our executive team with data-driven marketing recommendation to attract casual riders into purchasing annual memberships.

#### Prepare

Once the business task has been clearly identified I began by preparing the data. Cyclistic's trip data is located in a public database. I will export the necessary month for the analysis (Q4) and store in Excel. Data is organized in a tabular form, with each ride documented in rows.

#### Process

Prior to analyzing the data, I used Excel's Power Query to intergrate the files and clean the data.

 1) Join the files from my saved folder to Excel's Power Query
 2) Removed any blank data for column end_lat as this was software error in the data gathering process
 3) Removed unncessary columns that were present in some of the files (ex. starting latitude name)
 4) Added calculated columns to be used in the analysis. These include "Ride_length" and "weekday"
 5) Exported query into table format in Excel.

#### Analysis

Main task was to determine the differernt patterns between casual riders and annual riders. A series of pivot tables were created to do this to identify trends and relatipnships. 

Key Findings: 
Casual riders ride for longer periods of time(especially on weekdays) as they typically use bikes for consequential rides. Annual members ride the bike for consistent amount of time throughout the week, usually for work.

#### Share

Sharing the findings to the executive team using professional PowerPoint slidedeck. This allows for a compelling data-story that builds upon itself. Guiding the audience towards the process taken to reach the recommendations. Please view short slidedeck for final presentation/recommendations.

https://docs.google.com/presentation/d/1WIsXdSpofDCBdt0KJvdTzSg3TfnrMH9z/edit#slide=id.p1

### Conclusion
---
Given the relax nature of casual riders, to convert them into annual members it was recommended that cost-effective perks be implemented for leisure riding habits. 

Overall this project displayed the ability to work through the data analysis steps to come to accurate and meaningful business decisions. 






