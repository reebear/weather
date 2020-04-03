# Weather python script

I took the liberty to steal - ahem - borrow from different projects git (please see the links below) to put together my own weather application in Python. 

These are my requirements:
- read data from OpenWeatherMap for my area
- store them into a database (sqlite3)
- change the database to influxDB
- use grafana to add some visual sugar to the data
- script is to run via cron
- everything should be running on a Raspberry Pi

While working on the python script, I found out that is way better to put all the necessary constants into an ini file (greetings to bygone Windows days). So I found a scripts which uses this functionality and adapted it into mine.

## Links 
1. OpenWeatherMap: https://openweathermap.org/city
