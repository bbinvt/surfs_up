# surfs_up

## Overview of the Project
### Purpose
The purpose of this project is to query our SQLite data base using SQLalchemy and perform our analysis. By using the SQL queries and converting them into dataframes we can easily extract the desired outputs to help us make our investment decision. 

### Resources
- The data is stored in the SQLite file and can be found ![here](https://github.com/bbinvt/surfs_up/blob/afc729eb39b77af46d5106335acdff0f6472f5b3/hawaii.sqlite)
- The analysis was performed in a jupyter notebook and can be found ![here](https://github.com/bbinvt/surfs_up/blob/afc729eb39b77af46d5106335acdff0f6472f5b3/SurfsUp_Challenge.ipynb)

## Results:
#### Three Main Takeaways
- Our sample size for June temperatures (1700 observations) and December (1517 observations) provide us with a large enough sample size to make our decision. 
- The Average Temperature for June (74.94 F) and December (71.04 F) are more than adequate to both surf and eat icecream - both averages are suprisingly similar, at least compared to the typical Canadian climate!
- The Range of Temperatures throughout 64 - 85F (June) and 56 - 83F (December) should also give us confidence in our decision to invest. 

![Figure 1: June Temperature Statistics](https://github.com/bbinvt/surfs_up/blob/a7260e28c1f26392ed5cedc723fabd889f0d82cb/june_temp_stats.png)

![Figure 2: December Temperature Statistics](https://github.com/bbinvt/surfs_up/blob/a7260e28c1f26392ed5cedc723fabd889f0d82cb/dec_temp_stats.png)

## Summary

#### Recommendations
Based on temperature we can feel confident in our investment to open a surfshop & icecream shop, during both seasons the temperature is warm enough to make both activities viable. 

#### Additional Analysis
To perform this analysis I created a function - to make the process efficient and highly reusable. With a simple change of variables we can use the structure of the function to extract the precipitation data - which would be important to look at - who wants to eat icecream or surf in the rain? Another way of looking at this data would be to create a graph. Gather the data for each month of the year across our dataset, then plot the average temperatures and superimpose the average precipitation in each month - that could make our decision even easier. 

![Figure 3: Temperature Extract Function](https://github.com/bbinvt/surfs_up/blob/afc729eb39b77af46d5106335acdff0f6472f5b3/temp_extract_func.png)
