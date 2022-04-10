# BikeSharing
## Purpose
The purpose of this module is to provide a visual analysis of NYC bike sharing service to help inform potential investors in a similar business in Des Moines, IA.  The completed analysis is provided in this Tableau Story [[link here](https://public.tableau.com/app/profile/laura.zacharda.jones3891/viz/BikeSharing_16495506129620/BikeSharingData?publish=yes)].

## Request
Specific information we were asked to provide includes:

* The length of time that bikes are checked out for all riders and genders
* The number of bike trips for all riders and genders for each hour of each day of the week
* The number of bike trips for each type of user and gender for each day of the week.

## Analysis

### Ridership
An initial look at the NYC data includes the number of rides, gender and customer type.
![Ridership](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Ridership.png)
* This is analysis of >2M rides
* The riders are predominantly male with a small portion of riders without declared gender and approximately 25% of riders being female.
* Approximately 80% of all riders are subscribers.  These riders provide consistent income.

### Ride Duration
The image below demonstrates that the average ride duration is less than an hour with most rides lasting less than 30 minutes.  
![ride duration](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Ride_Duration.png)

Further analysis of the ride duration (see image below) clearly shows the higher utilization of the service by males.
![ride duration gender](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Ride_Duration_by_Gender.png)

### Time of Day - Day of Week
#### Overall data
In order to understand utilization patterns, we looked at the number of rides by hour and by day of the week.
![trips_hour_day](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Trips_by_hour_day.png)
The highest utilization rates occur on weekdays during what would be identified as morning and evening commute times. 

#### Gender specific
The second evaluation of time of day / day of week utilzation includes gender.  
![weekday_hour_gender](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Weekday_Hour_Gender.png)
This view again demonstrates the dominance of male ridership and confirms the high utilization on weekdays during commute hours.  However, it also shows females follow a similar ridership pattern.  I noticed a dip in ridership on Wednesday evenings in both the male and female population.  I would speculate religious activies traditionally occuring on Wednesday evenings may impact this time-frame.

#### Customer Type
The last analysis of the weekday/hour utilization compares subscribers to customers.
![trips by hour gender and type](https://github.com/LauraZJ/BikeSharing/blob/main/Images/Trips_by_hour_gender_type.png)
This graphic confirms that most riders are subscribers, predominantly male, and a high volume of rides take place during the week.  The higher number of rides by customers take place on the weekend, which would lead one to believe that these customers may be tourists.  I found it particularly interesting to note that the higher volume of 'unknown' gender riders are customers as opposed to subscribers.  

### Bike Utilization
When considering the cost of maintaining bikes in this type of service, one would need to consider bike utilzation.  This image displays the utilization of all bikes in the dataset.  
![bike utilization]()
Clearly, not all bikes are used equally.  The highly used bikes will require much more maintenance and replacement.  Rotation of bikes according to their lifecycle would be recommended.  I would suggest adding newer bikes to the high volume locations, shifting less utilized bikes to lower volume stations.

### Location Data
#### High Volume Locations
Understanding the location of the volumes is important to help with both providing sufficient supply and knowing where to place marketing dollars.  In the images below, we see that the high volume stations for both starting and ending are very near each other.  This corresponds with duration data.
![high stations]()

#### Location Volume by Rider Type
I chose to compare the ride volume by location and customer type.  
![location-rider type]()
This analysis demonstrated that the subscriber tended to rent bikes in the business districts while the customers (likely tourists) rented in the more scenic / touristy locations.

## Recommended Further Analysis
Given that the interest is in starting a bikesharing service in Des Moines, I would recommend performing a similar analysis of a city with similar demographics to get a more 'apples-to-apples' comparison.  However, to further analyze the NYC data, I would recommend the following additional visualizations:
* Map the location of the bikes with the highest utilization rates as well as mapping the location of the bikes with the lowest utilization rates.  The benefit of this would be to demonstrate the rotation of bike locations would likely even out the wear-and-tear on each bike, or to establish a replacement cycle.
* If you intend to market to a specific age group, it would be beneficial to analyze the age of the rider by location.  This would advise to what type of environment each age group tends to navigate.
 
