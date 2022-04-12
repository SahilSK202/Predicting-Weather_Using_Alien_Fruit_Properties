# Predicting-Weather_Using_Alien_Fruit_Properties

https://machinehack.com/hackathon/odetocode_predicting_weather_using_alien_fruit_properties/overview
### Overview
Tredence is a data science and AI engineering company focused on solving the last mile problem in analytics. The ‘last mile’ is defined as the gap between insight creation and value realization. Tredence is 1,500-plus employees strong with offices in Foster City, Chicago, London, Toronto and Bangalore, with the largest companies in retail, CPG, hi-tech, telecom, travel and industrials as clients.

### Problem Statement

The year is 2050 and a team of astronauts from all over the world went on a mission to an Exoplanet and discovered a vast amount of life and awesome weather. The scientists began collecting data samples of fruits found in their landing site and were curious by their shape and size. They collected data for more than a solar year of the planet to understand the fruit growing conditions in different weathers. 

To analyze data and grow fruits similar to earth, they began transmitting data back to the Earth, however, due to solar radiation, some data got corrupted and got lost in transmission. Back on Earth, the scientists figured they need to identify the type of climate the exoplanet has based on the properties of the fruit with the existing challenge of missing data. Help the scientists identify the earth-like season in which the fruit must have grown using the data collected.


# About Data

- We have 42748 rows and 14 columns in the Training dataset
- We have 18321 rows and 14 columns in the Testing dataset

### Data Dictionary:
#### Independent Variables
1. edible-poisonous: edible=e, poisonous=p
2. cap-diameter: float number in cm
3. cap-shape: bell=b, conical=c, convex=x, flat=f, sunken=s, spherical=p, others=o
4. cap-color: brown=n, buff=b, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y, blue=l, orange=o, black=k
5. does-bruise-bleed: bruises-or-bleeding=t,no=f
6. gill-attachment: adnate=a, adnexed=x, decurrent=d, free=e, sinuate=s, pores=p, none=f
7. gill-color: see cap-color + none=f
8. stem-height: float number in cm
9. stem-width: float number in mm
10. stem-color: see cap-color + none=f
11. has-ring: ring=t, none=f
12. ring-type: cobwebby=c, evanescent=e, flaring=r, grooved=g, large=l, pendant=p, sheathing=s, zone=z, scaly=y, movable=m, none=f
13. habitat: grasses=g, leaves=l, meadows=m, paths=p, heaths=h, urban=u, waste=w, woods=d
#### Dependent variable
14. season: spring=s, summer=u, autumn=a, winter=w
