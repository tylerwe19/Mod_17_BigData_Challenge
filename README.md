# Mod_17_BigData_Challenge

## Overview
#### The purpose of this project is to analyze Amazon reviews. More specifically this compares and contrasts reviews from the paid Amazon Vine program vs unpaid Amazon reviews. I chose to analyze the dataset about sports products. The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in the sports dataset.
 --- 
 
## Results
 * How many Vine reviews and non-Vine reviews were there?
    * As seen below, there were a total of 334 reviews from the paid Vine service.
    * In drastic contrast, there were a total of 61,614 non-Vine reviews from the sports prodcut data source.

![Vine_reviews.png](https://github.com/tylerwe19/Mod_17_BigData_Challenge/blob/main/Deliverable2_Results/Vine_reviews.PNG)

![NonVine_reviews.png](https://github.com/tylerwe19/Mod_17_BigData_Challenge/blob/main/Deliverable2_Results/NonVine_reviews.PNG)

 * How many Vine reviews were 5 stars? What percentage of Vine reviews were 5 stars?
    * As seen below, there were 139 reviews with 5 stars which is ~42% of Vine Reviews.
    
![Vine_FiveStar_Count_Percentage.png](https://github.com/tylerwe19/Mod_17_BigData_Challenge/blob/main/Deliverable2_Results/Vine_FiveStar_Count_Percentage.PNG)

 * How many non-Vine reviews were 5 stars? What percentage of non-Vine were 5 stars?
    * As seen below, there were 32,665 5 star reviews which is ~53% of non-Vine reviews.
![NonVine_FiveStar_Count_Percentage.png](https://github.com/tylerwe19/Mod_17_BigData_Challenge/blob/main/Deliverable2_Results/NonVine_FiveStar_Count_Percentage.PNG)
 --- 
 
 
## Summary
##### Is there any positivity bias in the Vine program? No, there are not significantly more positive/5-star reviews in the Vine population than in the non-Vine population. In fact, there are less as the % of positive/5-star reviews in the Vine population is 11% less than the percentage of positive/5-star reviews in the non-Vine population (42% of Vine Reviews received 5 stars; 53% of non-Vine reviews received 5 stars). However, compared to the non-Vine population, the Vine population is significantly smaller. A data set that has a larger sample of Vine reviews would provide more confidence in the results. An additional analysis that you could do with this dataset would be to conduct a two-sample t-test comparing the Vine and non-Vine reivews, with the null hypothesis stating the mean Vine star rating roughly is not statistically different from the mean non-Vine star rating and the Alternative hypothesis stating the star-rating means of Vine and non-Vine reviews will be statistically different. In this case we're testing for positivity bias so we'll need to see if the Vine mean star-rating is statistically greater than the non-Vine mean star-rating.
 --- 
