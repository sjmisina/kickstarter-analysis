# Kickstarting with Excel
Analyst: <code><i> Stanley Misina, Columbia University Data Analytics Bootcamp</i></code><br />
Systems Used: <i><code> Microsoft Excel </i></code><br />
Data Source Provided: <i><code> Kickstarter provided cvs </code></i>

## Overview of Project
Client is considering Kickstarter to fund an upcoming theatrical play. Based on key data provided by Kickstarter, analysis needs to be performed to help identify the project's best chance at success.

### Purpose
Provide data analysis for upcoming Kickstarter project. Client wants to consider an appropriate start date and funding levels to determine best success rate.

## Analysis and Challenges
- Kickstarter data provided is from 2009-2017
- Data for 2018-2020 could effect results; however, this sample size is appropriate to determine general trends

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes Based on Launch Date](Theater_Outcomes_vs_Launch.png)
- Y-axis is number of Kickstarter projects of Theater&Plays subcategory
- X-axis is month of Kickstarter Launch

### Analysis of Outcomes Based on Goals
![Theater Outcomes vs Goals](Outcomes_vs_Goals.png)
- Y-axis is percentage of successful, Failed, and Canceled Kickstarter projects of total projects in available date range
- X-axis illustrates the different tiers of the goal set for the kickstarter projects

### Challenges and Difficulties Encountered
- Data provided requires complex parsing and calculation to effectively sort and identify trends to be provided in this analysis
- Launch date data determined by pivot table built by analyst

## Results
- Analysis determines that client's best chance at project funding success is to launch a Kickstarter in May with a target funding level of less than $5000
- Alternative months that could be considered for considerable success rates are projects launched in June and July
- Success rates are stongest for projects with a goal of raising less than $5000
- Although there are strong success rates found between $35,000 and $45,000, the sample size is very small, so not considered a reliable trend
