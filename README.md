# Solar Panels Study
I installed 32 solar panels on my roof over the Thanksgiving in 2019. It was by far the biggest DIY project I've ever done in my entire life. 
The solar panel controller and monitor unit came with data collection capability. It not only collected solar energy production but also 
the household energy consumption. I started playing with the data and decided to make this into a fun data science project.

## Location
My house is located in Austin, Texas where sun is abundant through out the entier year. 

## Solar panels 
I puchased the solar panels from an online solar retail store called wholesalesolar.com. The panels were made by Mission Solar here in San Antonio, Texas. My roof did not have a lot of space facing south, which is considered to be the best direction. Therefore, I had to break them up into different sections on the roof. Microinverters are considered to best options for solar panels facing different directions since they control each panel separately. 
The microinverters made by Enphase. They are installed behind the back of each individual panel. 
Each solar panel is rated for 330 W output and 32 of them make the total capacity at 10.6 kW. 

## Weather
Weather data was scraped from internet. I wanted to see how the weather parameter correlates with energy production and consumption data. I purchased an API key from openweathermap.org and scraped the data from their website. The sun location, elevation and azimuth were scraped from sunearthtools.com.

## Key features of this study
- Temperature
- Heat index
- Humidity
- Precipitation
- Pressure
- Wind
- Sun location: elevation and azimuth

## Model used
I started off with a simple linear regression model and further tested other regression models.

## Prediction
For predicting the future solar panel production, I used last year's weather parameters assuming they are going to be similar to this year's future weather data on average. The sun location is calculated from sunearthtools.com. It should be accurate enough for the purpose of this study. 
