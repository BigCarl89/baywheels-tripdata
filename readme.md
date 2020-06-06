# BayWheels Dataset Exploration
## by Alberto Carlone


## Dataset

This dataset contains anonymized data of approximately 300000 BayWheels bike rental in the San Francisco Bay area during January 2020.  
In this dataset we have complete data on rental duration, start and end timestamps, start and end station coordinates, bike ID and User Type (Customer or Subscriber).  
The dataset is available here: https://s3.amazonaws.com/baywheels-data/index.html.



## Summary of Findings

During the exploration i found that rentals were more common during Monday-Friday (working days) than on Saturday-Sunday (weekend) and, during working days, the peaks are around 8:00 and 17:00 so this leads me to consider the rental are made for commuting.  
Looking at the geographical location of all the rentals, they begin and end in San Francisco, Oakland and San Jose and the routes made start and end in the same city. This further reinforce the hypotesis that rentals are made for commuting in the same city.
I took an exploration also on the split between normal customers and subscribers, finding that they follow the same pattern of rental duration during the different hours of the day and during each days of the week. Looking at the subscribers in each of the three cities, i found that in Oakland more rentals are made by normal customers than subscribers.


## Key Insights for Presentation

For the presentation i want to focus on the peculiar distribution of rentals during days/hours and on the geographical location of those rentals.
