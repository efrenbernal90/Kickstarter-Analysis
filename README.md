# Kickstarting with Excel

## Overview of Project

### Purpose 

To compare the launch date and funding goals of *Fever* to other kickstarter campaigns.	

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Analysis of Outcomes Based on Launch Date](Resources/TheaterOutcomesbyLaunchDate.png)

### Analysis of Outcomes Based on Goals

![Analysis of Outcomes Based on Goals](Resources/OutcomesbyGoals.png)

### Challenges and Difficulties Encountered

Initial look into the data required some cleaning up and sorting.  Kickstarter data was filtered based on 'Parent category,' followed by converting Unix time stamps into standard date format (MM/DD/YYYY). 
Formula used to convert timestamps:
> =(((Ref cell/60)/60)/24)+DATE(1970,1,1)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
