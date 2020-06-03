# Solar Panels Study
I installed 32 solar panels on my roof over the Thanksgiving in 2019. It was by far the biggest DIY project I've ever done in my entire life. 
The solar panel controller and monitor unit came with a data collection capability. It not only collected solar energy production but also 
the household energy consumption. I started playing with the number and decided to make this into a fun data science project.

## Location
My house is located in Austin, Texas where sun is abundant though out the entier year. 

## Solar panels 
I puchased 32 panels from a online solar wholesale store called wholesalesolar.com. They were panels made by Mission Solar here in San Antonio, 
Texas. My roof did not have a lot of area facing south, which is considered to be the best direction. Therefore, I had to break them up into
different parts on the roof and microinverters are considered to be best fitted to handle solar panels facing different directions. 
I purchased 32 microinverters made by Enphase. They are installed behind the back of each individual panel. 

## Weather
Weather data was scraped from internet to correlate with energy production and consumption data. I purchased an API key from openweathermap.org
and scraped the data from their website. The sun location was scraped from sunearthtools.com.

## Key features of this study
- Temperature
- Heat index
- Humidity
- Precipitation
- Pressure
- Wind
- Sun location: elevation and azimuth

## Model used
I started off with a simple regression model

## Prediction
For predicting the future solar panel production, I used last year's weather parameters assuming they will be similaar on average. The sun location is calculated which should be accurate 
enough for the purpose of this study. 
