# Overview of Analysis

The purpose of this analysis is to help W. Avy, an investor, predict whether opening an ice cream shop, Surf N'Shake, in Oahu, Hawaii would be a wise investment. To determine whether the investment into this business would be profitable, W. Avy would have to be certain that the business would be sustainable year-round to attract the most business possible. An examination of monthly weather is important to determine consistency, as people are more likely to eat and enjoy ice cream and shakes when conditions are especially hot. This analysis helps prepare investors, like W. Avy, who seek to visualize trends prior to making business decisions.

A SQLite file containing Hawaii climate data with weather metrics, such as precipitation and temperature, was provided as a resource. The programming language used in this analysis was Python, coupled with Pandas library. SQLAlchemy was imported in the code to extract functions and create session queries to obtain weather for the months of June and December. Altogether, for this project SQLite, SQLAlchemy, and Flask were used in conjuction with each other to build on SQL database structure knowledge and querying methods.

# Results

Three major comparisons of June and December Temperatures in Oahu, Hawaii:

* For the month of June, statistically, there is a 19 Fahrenheit degree difference between the minimum and maximum temperature recorded for the month. 
* For the month of December, more fluctuation is seen on average. In the image of December statistics below, there is a 27 Fahrenheit degree difference between the minimum and maximum temperatures recorded for the month. 
* Despite these fluctuations, the mean and maximums remained comparable for both months. For June, the maximum temperature was 85F degrees vs. 83F degrees in December. Moreover, the mean temperature was 75F in June vs. 71F in December.

a. Average Temperatures Throughout the Months of June and December in Oahu, Hawaii:

<p float="left">
  
<img src="https://github.com/katmarcin/surfs_up/blob/4fe6b92b9c871fdbca60d74ff937b4739175250a/jantemps.png" width="220" height="570"/>

<img src="https://github.com/katmarcin/surfs_up/blob/8cc3b889af9d080accf7659c4c7c0d478604e829/dectemps.png">

</p>

b. Summary Statistics for the Months of June and Decemeber in Oahu, Hawaii.

<p float="left">
  
<img src="https://github.com/katmarcin/surfs_up/blob/f3c23acade25baf0e1757e0f53d7293151be3339/junestats.png">

<img src="https://github.com/katmarcin/surfs_up/blob/f3c23acade25baf0e1757e0f53d7293151be3339/decstats.png" width="180" height="275"/>

</p>

# Summary

Although warm weather is sometimes subjective, especially for ice-cream enthusiasts, both months prove to have fantastic warm weather and we can expect a successful ice-cream and shake business. A slight drop in temperature for December certainly would not push surfers aware either. However, if we want to be even more precise for W. Avy, to help with his determination of the business outcome, we prepared two more queries to gather more weather data for June and December. 


