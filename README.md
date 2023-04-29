# thingsspeak_solar_weather-station

This is a scetch for an Solar weather station. 
You need to fill in your wifi credentials and thingspeak details.
I measures the battery voltage. For that, you need to solder an voltage divider on pin A0.
This scetch uses deep sleep to save battery life. I wakes up every 4 minutes, but you can change the interval.
Connect D0 to rst for the deep sleep to work.
