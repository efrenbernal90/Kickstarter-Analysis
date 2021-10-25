# Kickstarting with Excel

## Overview of Project

### Purpose 

To compare the launch date and funding goals of *Fever* to other kickstarter campaigns. 	

## Analysis and Challenges

Campaign's Outcomes were charted based on Launch Date and Financial Goals

### Analysis of Outcomes Based on Launch Date

Analysis shows that May had the highest amount of outcomes based on launch date (111 successful, 52 failed, 3 canceled).

![Analysis of Outcomes Based on Launch Date](Resources/TheaterOutcomesbyLaunchDate.png)

### Analysis of Outcomes Based on Goals

Analysis of these data shows a negative trend when comparing higher funding goals to success, as shown in the chart below.  Those campagins whose goals were less than $1000 showed the highest success outcomes(76%), while campaigns whose funding goals were between $45,000 and $49,999 were least sucessful (0%).

![Analysis of Outcomes Based on Goals](Resources/OutcomesbyGoals.png)

### Challenges and Difficulties Encountered

Initial look into the data required some cleaning up and sorting.  

-Kickstarter data was filtered based on 'Parent category,' followed by the addition of a Subcategory column to allow for filtering based on specific genre  

-Unix time stamps converted into standard date format (MM/DD/YYYY). 
Formula used to convert timestamps:
> =(((Ref cell/60)/60)/24)+DATE(1970,1,1)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The most amount of successful theater kickstarter campaigns launched in the month of May (111 Outcomes), suggesting that Fever's best chance of success is to launch in May.
  2. There are similar outcomes for successful (37) and failed (35) campaigns launched in the month of December.

- What can you conclude about the Outcomes based on Goals?
  1. Campaigns that targeted between $15,000 and $19,999 as funding goals had equal chance of failing or succeeding (50%). 
 
- What are some limitations of this dataset?

This analysis is limited by only the percent amount of campaign outcomes, with the lowest success outcome met 0% and 17% of their goal (between
$45,000 and $49,999 and <$50,000 respectively). Campaigns that set a goal between $15,000 and $19,999 had equal probaility of succeeding or failing, however, based on the data used in this analysis it is unknown as to why.  
Knowning more about each backer are could provide more insight on successful fundraising.
We could also look further into what affects launch date by filtering searches by year.  The month of May had the highest outcomes total, but it is uncertain what may help it succeed beyond the funding (which also has limitations). 

- What are some other possible tables and/or graphs that we could create?

A descriptive statistical analysis of the funding can be used as insight for potential outliers in funding goals.  
A box plot can also be created to compare failed and successful camapaigns based on the descriptive statistics, this way any potential outliers can be visualized.  

