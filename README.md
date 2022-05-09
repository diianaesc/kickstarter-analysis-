# Kickstarting with Excel

## Overview of Project
-	Louise would like to understand how different campaigns fared in relation to both their launch dates and their funding goals

### Purpose
-	Use Excel to visualize the outcomes of a campaign based on their launch dates and their funding goals to make data driven decisions

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
-	The launch date analysis was performed by first collecting data from all years and breaking it down by Months and by the 3 different outcomes. 
-	A line chart was created to visualize the relationship between outcomes per launch months 

![Theater_Outcomes_vs_Launch png](https://user-images.githubusercontent.com/104380112/167516454-a99c5fda-1a60-497d-af45-41ce9ff3e78e.png)


### Analysis of Outcomes Based on Goals
-	The funding goals analysis was performed by grouping projects into goal amounts using the COUNTIFS formula and calculating the percentage outcome for each range. 
-	Then creating a line chart to visualize the relationship between goal amount and percentage of successful, failed and canceled

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104380112/167516463-27e14974-6a20-4dad-a85d-8c3b8f62af55.png)


### Challenges and Difficulties Encountered
-	Making sure the COUNTIFS formula had the correct ranges on every cell 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - The number of successful outcomes is larger between the months of May to July. The number of successful outcomes decrease between the months of October to December
  -	Canceled projects has no correlation with Launch Date as it does not fluctuate between months

- What can you conclude about the Outcomes based on Goals?
  -	Projects with a goal of less than 15,000 have a higher success rate and projects with a goal higher than $45,000 have a lower success rate

- What are some limitations of this dataset?
  -	There can be more external factors that can affect the outcome of a project that might not be included in the dataset

- What are some other possible tables and/or graphs that we could create?
  -	Build a table to see how different campaigns performed based on the duration of the project 
  -	Build a graph to compare how different campaigns performed based on the location or country 
