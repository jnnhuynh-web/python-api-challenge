# Python-API-Challenge

This repository uses the [Open Weather Map API] (https://openweathermap.org/api), and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Using Pandas, Matplotlibs, a Python script was created to build a series of scatter plots to showcase the following relationships:
  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude

Three observable trends based on the observable data are as follows:
1.	The most notable trend with significant correlation was for latitude vs. max temperature.
  
  a.	This looks to be a negative parabolic curve, where the latitude plays a significant role in the max temp. The places with the latitude of 0 (equator), had the highest max temp, while going more north or south correlates with a drop in temperature.
2.	There is no correlation between latitude and cloudiness.
  
  a.	However, different places at different latitudes can have the same cloudiness. The most notable percentages of cloudiness are as  follows: 0% (no clouds), 40%, 75%, and 100% (high clouds). 
  b.	There also looks to be a cloud system that spends the southern hemisphere at 90% cloud coverage on 2019/11/17.

3.	There was no correlation between latitude and humidity, or windspeeds.
  
  a.	This suggests that these 2 factors are independent from each other. 
