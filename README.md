# Overview of Analysis

The purpose of this analysis is to help W. Avy, an investor, predict whether investing in an ice cream shop, Surf N'Shake, in Oahu, Hawaii would be worth the capital. To determine whether the investment into this business would be profitable, W. Avy needs to be certain that the business would be sustainable year-round to attract the most business possible. W. Avy understands the restaurant industry is a risky arena and the success of a small-business such as a restaurant is dependent on my many factors. An examination of monthly weather is important to determine consistency, as people are more likely to eat and enjoy ice cream and shakes when conditions are especially hot. This analysis helps prepare investors, like W. Avy, who seek to visualize trends prior to making business decisions.

An SQLite file containing Hawaii climate data with weather metrics, such as precipitation and temperature, was provided as a resource. The programming language used in this analysis was Python, coupled with Pandas library. SQLAlchemy was imported in the code to extract functions and create session queries to obtain weather data for the months of June and December in Oahu, Hawaii. Altogether, for this project SQLite, SQLAlchemy, and Flask were utilized collectively to build on SQL database structure knowledge and querying methods.

# Results

Three Major Comparisons of June and December Temperatures in Oahu, Hawaii:

* For the month of June, statistically, there is a 19 Fahrenheit degree difference between the minimum and maximum temperature recorded for the month. 
* For the month of December, more fluctuation is seen on average. In the image of December statistics below, there is a 27 Fahrenheit degree difference between the minimum and maximum temperatures recorded for the month. 
* Despite these fluctuations, the mean and maximums remained comparable for both months. For June, the maximum temperature was 85F degrees vs. 83F degrees in December. Moreover, the mean temperature was 75F in June vs. 71F in December. Minimum temperatures for the two months were relatively close, differing by only 8F degrees. 

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

To be more precise with our Oahu climate data for W. Avy, and to help with his determination of the business outcome, we prepared two more queries to gather more weather data for June and December. W.Avy expressed curiosity towards visualizing average temperatures at different weather stations dispersed throughout Oahu. Because of its mountainous terrain, one side of Oahu may be colder and more precipitous than the other. The query performed below pulls average temperatures from the nine weather stations on Oahu for the month of June. In this data visualization, we can see there is approximate 6 Fahrenheit degree difference exhibited on the same island of Oahu, but in different locations. This shows W.Avy the climate variety that can exist on any given day anywhere on the island. 

<img src="https://github.com/katmarcin/surfs_up/blob/ce1e6024b13ba9a35384ad7be487560a66bae23f/station.png" width="540" height="295"/>

Another query was performed to visualize temperature differences recorded by different stations across Oahu in December. The data reveals an approximate 4 degree temperature difference on any given day in December across Hawaii. December exhibits less temperature variability than June, but by only 2F degrees. 

<img src="https://github.com/katmarcin/surfs_up/blob/cde726bf31fa27da70582bcb98b3099da4e22ccd/decstation.png" width="540" height="295"/>

Although December sees more temperature variability throughout the month, the temperature is more consistent throughout the island than it is in June. More consistency is seen throughout the month of June, however temperature varies throughout the island. These determinations are important for honing in on potential locations for Surf N'Shake shop. W.Avy, a surfing expert, is keen on location and climate for determining the success of the business.

A slight drop in temperature for December certainly would not push surfers, locals, or tourists away. Although warm weather is sometimes subjective, especially for ice-cream enthusiasts, both months prove to have fantastic warm weather and we can expect a successful business for Surf N'Shake. 





