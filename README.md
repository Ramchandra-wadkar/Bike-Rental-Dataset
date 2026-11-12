# Bike-Rental-Dataset

# Dataset
Bike sharing systems are a new version of traditional bike rentals where the whole process from membership, rental and return back has been automated. features of the dataset as follows:
instant: record index
dteday : date
season : season (1:winter, 2:spring, 3:summer, 4:fall)
yr : year (0: 2011, 1:2012)
mnth : month ( 1 to 12)
hr : hour (0 to 23)
holiday : weather day is holiday or not (extracted from [Web Link])
weekday : day of the week
workingday : if neither weekend nor holiday, it is 1; otherwise 0.
weathersit :
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog
temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
hum: Normalized humidity. The values are divided to 100 (max)
windspeed: Normalized wind speed. The values are divided to 67 (max)
casual: count of casual users
registered: count of registered users
cnt: count of total rental bikes including both casual and registered

# Insights
• Summer records the highest number of bike rentals, indicating stronger customer demand during this season.

• The bike rental demand is significantly higher from June to September compared to the other months, indicating increased customer activity during this period.

• Bike rental activity is highest on the 4th and 5th days of the week, indicating increased customer demand on these days compared to the rest of the week.

• The bike rental demand peaks between June and September, particularly on the 4th and 5th days of the week. Additionally, the highest rental activity occurs during the evening hours, between 4:00 PM and 7:00 PM. These periods represent peak demand, suggesting an opportunity to improve bike availability and operational planning during high-traffic hours.


# Model Selection
*    The Gradient Boosting model demonstrates predictive performance compared to the other evaluated models, achieving high accuracy and a lower RMSE, making it a suitable choice for the given dataset.
*    The Linear Regression model having lower predictive accuracy and overall performance than the other regression models, indicating that it is not the most suitable choice for the given dataset.
*    The Decision Tree and Random Forest models deliver satisfactory predictive results, positioning them as intermediate-performing models among the regression algorithms evaluated.
