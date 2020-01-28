# solarPowerMapper

The solar installation Tool can be run locally by going to the indexl.html from any browser depending on where one may choose to store the file.
I am accessing it by typing /home/samuel/Developer/solarPowerMapper/index.html for example.
It will work as long as there is an internet connection in order to get the proper libraries.

I used the leaflet.js framework for this as it provided everything I needed to create the maps,style it with the tiles I wanted,
search bars, drawing tools, and it's free.

The only assumption I made was when calculating the nominal power I used 5.5 as a factor for kWh/m^2/day taken from this map.
This factor is constant across the whole map.
https://www.solar-electric.com/learning-center/solar-insolation-maps.html/#Map1
