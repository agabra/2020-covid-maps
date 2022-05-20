# Andrew Gabra
# 05/02/2022
# Lab 3: Web Map Application

In this lab I created a choropleth map which represnts covid-19 rates and a proportional symbols map that represents covid-19 cases. The library that I used is Mapbox, which helped me create both maps.

For the covid-19 rates map, it uses colors to represnt the 2020 covid cases per thousand residents for each county. The darker the color the higher rate it will be. For example counties with covid rates that fall in between 80 and 100 will be in dark red. This map also has the hover feuture, when you hover your cursor on any county it will show the rate in the top right box. The data was colocted from New York Times and I used QGIS to export a geoJsoon file from the shapefile that was provide that inlcudes all of rates.

## Coivd-19 Rate (Cases per thousand residents) Map
![ScreenShot](/img/map1.png)

## Map Link: https://agabra.github.io/2020-covid-maps/map1.html 

For the covid-19 cases, it uses circles to represnt the 2020 covid death cases for each county. For example, smallest circle with the lightest color repreents counties that have less than 100 cases and the biggest anddarkest circle represnts counties that have more than 1000 cases and less than 10100 cases. You could also click on the circles and it will provide the amount of cases.The data was colocted from New York Times and I used QGIS to export a geoJsoon file from the shapefile that was provide that inlcudes all of rates.

## Coivd-19 Cases Map
![ScreenShot](/img/map2.png)

## Map Link: https://agabra.github.io/2020-covid-maps/map2.html
