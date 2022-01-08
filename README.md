# Challange Module 9 surfs_up

## Overview of the analysis
The purpose of the analysis was to provide information on temperature trends on Oahu, Hawaii in the months of June and December. This will provide an insightful trend at two separate points of the year in order to help determine if the surf and ice cream shop business is sustainable year-round. 

## Results 
Using Python, Pandas functions and methods, as well as SQLAlchemy we filtereted the data column of the Measruement table in the `hawaii.sqlite` databse to retrieve all the temperatures for the month of June (Deliverable 1) & December (Deliverbale 2). We then converted those temparatures to a list and created a DataFrame from the list to generate the summary of the statistics. Below are two images of results, one DataFrame is for June statistics, second DataFrame is for December Statistics. 

![This is an image](https://github.com/AleksKostrycka/surfs_up/blob/main/Resources/Summary%20of%20June%20Statistics.png?raw=true)
![This is an image](https://github.com/AleksKostrycka/surfs_up/blob/main/Resources/Summary%20of%20December%20Statistics.png?raw=true)

* The results above indicate that the average temperature in June is ~75 degrees and 4 degrees higher than December ~71 degrees. This represents (5.6%) decrease in the temperature between the two months defined. This is inline with the expectation that the summer months are warmer than winter  months in Hawaii, however this is also an indication that helps us determine if the surd and ice cream ship business is sustianable year-round. With the temperature drop of only (%5.6) this is a positive affirmation that the suirf and ice cream shop business would be sustainable in June and December. 
