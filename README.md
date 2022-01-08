# Challange Module 9 surfs_up

## Overview of the analysis
The purpose of the analysis was to provide information on temperature trends on Oahu, Hawaii in the months of June and December. This will provide an insightful trend at two separate points of the year in order to help determine if the surf and ice cream shop business is sustainable year-round. 

## Results 
Using Python, Pandas functions and methods, as well as SQLAlchemy we filtereted the data column of the Measruement table in the `hawaii.sqlite` databse to retrieve all the temperatures for the month of June (Deliverable 1) & December (Deliverbale 2). We then converted those temparatures to a list and created a DataFrame from the list to generate the summary of the statistics. Below are two images of results, one DataFrame is for June statistics, second DataFrame is for December Statistics. 

![This is an image](https://github.com/AleksKostrycka/surfs_up/blob/main/Resources/Summary%20of%20June%20Statistics.png?raw=true)
![This is an image](https://github.com/AleksKostrycka/surfs_up/blob/main/Resources/Summary%20of%20December%20Statistics.png?raw=true)

* The results above indicate that the average temperature in June is ~75 degrees and 4 degrees higher than December ~71 degrees. This represents (5.6%) decrease in the temperature between the two months defined. This is inline with the expectation that the summer months are warmer than winter months in Hawaii, however this is also an indication that helps us determine if the surf and ice cream shop business is sustianable year-round. With the temperature drop of only (%5.6) this is a positive affirmation that the surf and ice cream shop business would be sustainable in June and December. 
* The standard deviation (SD) above further helps define the temperature variation between June and December. In the resutls it is clear that the SD in the month of June is 3.25, while December it is 3.74. This is indicative of the fact that within the month of June the recorded remperatures are much closer to the mean, or average than in December. The SD is higher in December meaning that the recorded temperatures through out the month vary more wildly. This means that in the month of June the temp. might be more stready and predictable to support the day to day operations of the surf and ice cream shop. In December while still a warm month in Oahu, the temp will vary more day to day and will be more unpredictable. This does not mean that the shop will not be sustainable through out the winter months, it simply means that there will be days where the temp is lower and the shop might have less business. 
* Another key difference in temperatures between June and December is the minimum and maximum temperatures. While the max is quite close between the two months, June - 85 and December 83, the min is much further apart, June - 64 and December - 56. This indicates that while the temp highs between the 2 seasons are quite similar the temp lows differences might deter some cusomters to frequent the shop in winter months. 
## Summary
Based on the above results
