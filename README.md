
<p align="center">
 <h2 align="center"> Web Design Challenge </h2>
 <h1 align="center"> Interactive Dashboard </h1>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#background">Background</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#landing-page">Landing Page</a>
    </li>
    <li>
      <a href="#visualization-pages">Visualization Pages</a>
    </li>
    <li>
      <a href="#comparisons-page">Comparisons Page</a>
    </li>
    <li>
      <a href="#data-page">Data Page</a>
    </li>
  </ol>
</details>

<!-- Background -->
## Background
Using HTML, CSS, and Bootstrap, this project aims to develop an interactive visualization dashboard website deployed on GitHub Pages. The visualization is built on an earlier project, [Python API Challenge](https://github.com/asmvm/Python_API_Challenge), an anlysis of weather conditions of 500+ cities across the world of varying distance from the equator. This project was completed to fulfill Georgia Tech's Data Science and Analytics certificate.


### Built With
* [Bootstrap](https://getbootstrap.com/)
* HTML
* CSS


## Landing Page

The [landing page](https://asmvm.github.io/Web_Design_Challenge/WebVisualizations/weather_dashboard_index.html) provides a background of the project and an interactive menu to navigate to all visualizations and data. Thumbnails to each visualization page analyzing humidity, windspeed, max temperature, and cloudiness vs latitude is providede on the landing page.  

![Landing Page](saved_images/landing_page.PNG)

## Visualization Pages
A visualization page is designed for each scatter plot, including a description of the plot and significance of the data. Select any of the links below to view a screenshot or navigate to the plots menu in the [landing page](https://asmvm.github.io/Web_Design_Challenge/WebVisualizations/weather_dashboard_index.html).

![MaxTemperature vs Latitude](saved_images/max_temp_vs_latitude.PNG)
* [Humidity vs Latitude](https://github.com/asmvm/Web_Design_Challenge/blob/master/WebVisualizations/humidity.html)
* [Cloudiness vs Latitude](https://github.com/asmvm/Web_Design_Challenge/blob/master/WebVisualizations/cloudiness.html)
* [Wind Speed vs Latitude](https://github.com/asmvm/Web_Design_Challenge/blob/master/WebVisualizations/windspeed.html)

## Comparisons Page
Scatter plots illustrating relationship between temperature, humidity, cloudiness, and windspeed vs latitude. Max Temp displayed below. Select links to plots to view remaining plots:

![Temperature (F) vs. Latitude](saved_figures/lat_vs_maxtemp.png)
* [Humidity (%) vs. Latitude](saved_figures/lat_vs_humidity.png)
* [Cloudiness (%) vs. Latitude](saved_figures/lat_vs_cloudiness.png)
* [Wind Speed (mph) vs. Latitude](saved_figures/lat_vs_windspeed.png)


## Data Page
Linear regression is run on each relationship, while also looking at cities in Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). A linear regression function was created to optimize the code when creating the plots:

![Northern Hemisphere - Temperature (F) vs. Latitude](saved_figures/northernhem_maxtemp_vs_lat.png)
* [Southern Hemisphere - Temperature (F) vs. Latitude](saved_figures/southern_hem_maxtemp_vs_lat.png)
* [Northern Hemisphere - Humidity (%) vs. Latitude](saved_figures/northern_hem_humidity_vs_lat.png)
* [Southern Hemisphere - Humidity (%) vs. Latitude](saved_figures/southern_hem_humidity_vs_lat.png)
* [Northern Hemisphere - Cloudiness (%) vs. Latitude](saved_figures/northern_hem_cloudiness_vs_lat.png)
* [Southern Hemisphere - Cloudiness (%) vs. Latitude](saved_figures/southern_hem_cloudiness_vs_lat.png)
* [Northern Hemisphere - Wind Speed (mph) vs. Latitude](saved_figures/northern_hem_windspeed_vs_lat.png)
* [Southern Hemisphere - Wind Speed (mph) vs. Latitude](saved_figures/southern_hem_windspeed_vs_lat.png)



