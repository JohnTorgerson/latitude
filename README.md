# Web Design Challenge

### Build / Host a website called "latitude"
Populate it with visualized raw data, and analysis scatter plots of climate conditions as they relate to distance from the Equator

### Finished Product Website Link

https://johntorgerson.github.io/latitude/

##### Authors:
* John Torgerson (JohnTorgerson)
---

##### Tools & Supplies:
* Image files, CSV file, Pandas
* CSS, Bootstrap, html, & Github
---

### Guide to Repo Contents:

* `index.html` is code for the landing page
* `data.html` is code for the data table page
* `comparisons.html` is code for the comparisons page
* `table.html` is an output only file from converting .csv to .html
* `app.py` is conversion code for .csv to .html

* In folder, `assets`/`css` are the following 6 tables:
    1. `lat_style.css` is a css style sheet
   
* In folder, `assets`/`images` are the following 5 images:
    1. `CloudinessInWorldCities.png` is a scatter plot of Cloudiness in relation to the equator
    2. `JPL.NASA.RelHumidity22.07.31.jpg` is an interactive map of humidity measurements over a world map taken from the same day the data was retrieved
    3. `HumidityInWorldCities.png` is a a scatter plot of Humidity in relation to the equator
    4. `TemperatureInWorldCities.png` is a scatter plot of Temperatures in relation to the equator
    5. `WindSpeedInWorldCities.png` is a scatter plot of Wind speed in relation to the equator
    
* In folder, `Resources` are the following 6 tables:
    1. `city_data.csv` is a table containing climate measurements from randomly generated cities around the globe on July 31, 2022

* In folder, `Visualizations` are the following html files:
    1. `cloudiness.html` is code for the cloudiness visualization page
    2. `humidity.html` is code for the humidity visualization page
    3. `temp.html` is code for the temperature visualization page
    4. `windspeed.html` is code for the wind speed visualization page
---

### Observations:
*Over the course of populating this little web tree with components and data, it became very apparent that working out functionality should always be done 1st, to completion before populating with desired content. This will be a big time saver for next time. 

---

### Credits and Special Thanks

* Thanks to Sanoo Singh for suggesting I use pandas to convert my data
* Thanks to Dr. Colin Barquist for helping me desing my web navigation tree
* Thanks to Jet Propulsion Labratories/NASA & their AIR project for a homepage cover image which can be referenced, duplicated, or manipulated here: https://airs.jpl.nasa.gov/map/?p=2&c=-3952711.606132813,-5224623.756621094&r=78271.516953125&t=2022-07-31&l=49:1:41&cl=1 