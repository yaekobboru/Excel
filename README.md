# Overview of the project.

Louise wants to start crowd funding campaign to help fund her play Fever with estimated budget over $10,000. This project analyzes data of funded projects from www.gofundme.com to determine campaign fare based on launch dates and funding goals.
The dataset is comprised of 9 years of sample data collected from nine countries with goal and pledged amount of different fund-raising categories.
## Analysis and Challenges
###### Analysis
Data extraction is made from website and stored in the kickstarter excel sheet to generate relevant charts to support decision making. Determining periodic outcomes output and calculating outcomes based on goals significantly contribute for the required outcome.
Extracted data set has “ launched_at” column which is Unix time stamp that should be converted to excel date . pivot tables created to aggregate monthly outcomes count filtered by category and years.
charts created from the pivot table for pictorial representation of theater outcomes based on launch date and percentage of count of outcomes based on goal calculated
Excel  COUNTIF function applied to calculate goal ranges per outcome status. Distinct reference table used to lookup outcome statuses for the function.
Count of successful, failed and cancelled calculated with corresponding percentages  to create charts based on range of goals.
###### Challenges
possible challenges or difficulties could be encountered from not using absolute referencing for calculating look up values.
Some of other possible tables and/or graphs are :-

###### Tables                 
  *  Location Table (Region, state, county, city, Zipcode)
  *  Backers Table

###### Graphs
  *  Outcomes based on backers count
  *  Television outcomes by deadline
  *  Goal vs pledged amount by country
  *  Food Outcomes by Launch Date
  *  Count of outcomes per parent category

## Conclusions and Recommendations
crowd funding campaigns on Theater category launched in May and June are the most successful.
Cancelled campaigns for theater have insignificant count compared to successful and failed campaigns.
55% of campaigns at Loiuse’s estimated budget range were successful.
Dataset broadly holds data at country level. Data set should include data at state and city level to evaluate outcomes per location. 



