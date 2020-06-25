# Project 1: Driving Licenses, Traffic Accidents and Casualties Analysis


## Problem Statment

As an analyst team in the General Department of Traffic under the Ministry of Interior, we used datasets for traffic accidents in 2016 - 2017 and driving licenses issued from 1993 - 2017 to give recommendations that are best to help reduce traffic accidents and road injured in Saudi Arabia. We do this because of new traffic rules and fines were [implemented in October 2016.](http://live.saudigazette.com.sa/article/164574/New-traffic-laws-in-15-days)


## Executive Summary

We found one issue that the General Department of Traffic should focus on:
- Number of accidents and road injured in Makkah, Riyadh and Eastern region have the higher level than other. This is due to the population density of these regions. Re-investigate the traffic laws of these regions, in addition to providing public transportation.


## Data Dictionary

### Traffic_Accidents

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|int|Traffic_Accidents|In which year the accident happened|
|**region**|object|Traffic_Accidents|In which region the accident happened|
|**casualties**|object|Traffic_Accidents|Type of casualties ( just accident - dead - injured )|
|**value**|int|Traffic_Accidents|Value of the casualty|
|**geo_point_2d**|object|Traffic_Accidents|Coordinate of the region|
|**x**|object|Traffic_Accidents|The latitude coordinate of the associated region|
|**y**|object|Traffic_Accidents|The longtitude coordinate of the associated region|


### Driving_Licenses

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|int|Driving_Licenses|in what year the driving license was issued|
|**region**|object|Driving_Licenses|In which region the driving license was issued|
|**driving_licenses**|int|Driving_Licenses|The number of driving licenses issued|
|**geo_point_2d**|object|Driving_Licenses|Coordinate of the region|
|**x**|object|Driving_Licenses|The latitude coordinate of the associated region|
|**y**|object|Driving_Licenses|The longtitude coordinate of the associated region|


## Conclusions and Recommendations

Makkah, Riyadh and Eastern region have the highest level of accidents. On the other hand, Al-Baha, Najran and Northern Boarder have the lowest mean of dead. Plus, we think that increasing population density in a specific region leads to increased accidents and injuries. So, the population data will be more helpful.

#### Recommendations:
 - Aviod driving in Riyadh, Makkah and Eastern region or places with heavy traffic, especially in rush hours and seasons.
 - Driving in Al-Baha, Najran and Northern Boarder could be more safe.
 - Must doubling the penalties for violations that cause accidents.
 - Improve road infrastructure to avoid accidents.
 
#### Additional data:
  - Population data is very important in our investigation to be sure about the ratio of accidents and injuerd.
  - Accidents causes data will be useful to put new penalties on the main causes of accidents.
