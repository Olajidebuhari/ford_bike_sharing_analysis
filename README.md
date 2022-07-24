# Ford bike sharing data exploration
## by Olajide Buhari


## Dataset

The data set is made up of 183412 entries of bike sharing trip information. Each entry carries
atrributes associated with;
- Time of the ride (duration_sec, start_time, end_time)
- location of the ride (start_station_id, start_station_name, end_station_id, end_station_name)
- rider (user_type, member_birth_year, member_gender, bike_share_for_all_trip)
- The bike used (bike_id)

## Summary of Findings

 The bike sharing service enjoyed varying level of patronage from diverse group of riders.
 One of the the Most notable finding in this analysis is the time around which this service peaks. 
 Most Rides start_time is around 8am (before work hour hour) and around 5pm (after work hour) on weekdays. 
 Usually, most of these rides end between 0 to 1 hour from the 'start time'. However, on weekends, the 
 service peaks across so many hours of the day, between 9am to 9pm. 

Another interesting insight is the age distribution. The least users of this service are the elderly whose
pattern of usage also indicates no significant difference between their weekday and weekend use.


## Key Insights for Presentation

The insights i was probing for is basically the demography of the riders of this bike sharing service and 
the pattern of usage. The violin plots of the **days of the week** against the **start hour** shows a significant
pattern of rides, which indicate that most of the rides on weekdays are as a means of transportation to work and back
from work. Further more, the barplots shows a break down in the usage of the service by demograghy with conclusion that subscribed male Young adult use the service the most.