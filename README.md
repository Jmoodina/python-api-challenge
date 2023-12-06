# WeatherPy and VacationPy

## Project Introduction
Unlocking the true potential of data lies in its capability to provide conclusive answers. In this GitHub repository, we leverage the prowess of Python requests, APIs, and JSON traversals to address a fundamental question: "What is the weather like as we approach the equator?"

While the intuitive response might be, "It gets hotter," our objective is to delve deeper and substantiate this claim with data-driven insights. Join us on this journey as we explore and analyze weather patterns near the equator, employing Python's robust capabilities to fetch, process, and visualize key meteorological data. Let's uncover the nuances of equatorial weather through meticulous data exploration and evidence-based findings.

## Objective
The WeatherPy project focused on visualizing weather patterns across 500 cities at varying distances from the equator. Leveraging Python, the citipy library, and the OpenWeatherMap API, I created a robust model to represent diverse weather conditions.

## WeatherPy (Part 1)
### Key Deliverables:
1. Scatter Plots:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Linear Regression:

2. Computed linear regression for Northern and Southern Hemispheres.
Plots included regression lines, formulas, and r values.

### Findings:
- Temperature showed a clear correlation with latitude, with noticeable differences between  hemispheres.
- Humidity, cloudiness, and wind speed exhibited varied relationships.

## VacationPy (Part 2)
Objective: Utilized Geoapify API, geoViews Python library, and weather data to plan vacations based on ideal conditions.

### Key Deliverables:

1. Humidity Map:
- Created a map displaying points for each city, with point size corresponding to humidity.

2. Ideal Weather Conditions:
- Narrowed down city data to specified weather conditions (temperature, wind speed, cloudiness).

3. Hotel Information:
- Utilized Geoapify API to find the nearest hotel within 10,000 meters for each city.
Created a new DataFrame (hotel_df) with city, country, coordinates, and humidity information.

## Final Analysis Insights
The combined WeatherPy and VacationPy analysis provides a comprehensive exploration of weather patterns and facilitates strategic vacation planning based on personalized weather preferences. The interactive maps and data-driven insights enhance decision-making for travel enthusiasts.

Computed linear regression for each relationship, stratified by Northern and Southern Hemispheres.
Generated scatter plots with regression lines, model formulas, and r values.
