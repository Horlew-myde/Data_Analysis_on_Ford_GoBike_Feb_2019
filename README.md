# Insight into demand for Ford Go Bikes (February 2019)

## by Olumide Johnson Amune


## Dataset

> This is the Final Project for Udacity's Data Analyst Nanodegree Course. in which I analysed Ford GoBike dataset of San Fransisco area from February 2019 to give insight into this Data (note: data was obtained from udacity site (https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)).

> This data consisted of 183,412 ride data info from Ford GoBike Bike services. The attributes included duration_sec, start_time, end_time, start_station_id, end_station_id, start_station_name, end_station_name, bike_id, user_type, month, day, and hour details. which i wrangled, cleaned to get a better insight for anyone who is interested. however the Raw data is also included in this folder for improvements, new areas, further anlysis and comparisons

#### Libraries Used:
The following Python library was utilised for this:
* Pandas
* Numpy
* Matplotlib
* Seaborn 

#### Included Files:

* `exploration_phase_ford_go_bike.ipynb` - this contains all gathering, assessing, cleaning and exploratory analysis.
* `exploration_phase_ford_go_bike.html` - the equivalent html file for the above.
* `slide_deck_.ipynb` - the notebook that forms the slide deck.
* `201902-fordgobike-tripdata.csv` - Raw Dataset.
* `Ford_GoBike(2019_feb).csv` - Cleaned Dataset.


## Summary of Findings:

> NOTE: The distance between the start station and end station is the covered distance of the ride. And the distance between the given corrdiantes was recalculated to kilometers. Also the time start was recalculated in to morning, afternoon, evening and night respectively.

> In the presentation, looking at the distribution of trip duration, age and gender.its observed that the majority of trips were around 10 minutes, Men were seen to use the service more and those in their mid 20s to mid 30s. then one can look at the relationship between duration and age and then gender with the violin plots, scatter plots and bar plots I provided.

* Most of the users are subscribers.
* Majority of the rides were taken on weekdays excluding weekends.
* Majority if the rides were short duration rides.
* Majority of the rides were not long in terms of the distance.
* Ride demand are fairly constant on weekdays (Mon-Fri) then decreses on weekends. Also, peak times is highest on 8:00 and 17:00 during weekdays, suggesting that users are likely  office commuters.
* Customer uses the bike for more duration on average than Subscribers.
* On weekdays rides increased at 8:00, and 17:00 while on weekends the ridership increases between 11:00 to 15:00


## Key Insights for Presentation

> The Customers have the longer average ride duration
> Saturdays and sundays have the longer ride duration
> The female customers have the longer ride duration
> The rides used are more during the weekdays while there is a huge drop in the number of ride over the weekends.
> Subscribers tend to take more rides as compared to casual users. The difference between both is huge. Subscribers account for 79% of the total rides taken when only 21% were taken by casual users.
> Majority of the rides were between 10 to 20 minutes


######################################################################################################################################
Access the slides by running the following command on terminal
`
jupyter nbconvert slide_deck.ipynb --to slides --post serve --template output_toggle
