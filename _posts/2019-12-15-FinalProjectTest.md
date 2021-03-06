---
title: "Final Project: Evaluation of Vehicle Crashes"
date: 2019-12-15
published: true
tags: [dataviz, matplotlib, folium]
excerpt: "This is some key data visualization in the final project."
folium-loader:
  folium-chart-1: ["charts/Fatality2018.html", "500"]
  folium-chart-2: ["charts/Injury2018.html", "500"]
  folium-chart-3: ["charts/Hour2018.html", "500"]
custom-css-list:
  - "assets/css/leaflet.timedimension.control.min.css"
toc: true
toc_sticky: true
---

This post contains some key data visualization from the final project in course Data Wrangling and Data Visualization. In this project, 
data is collected from NYPD. The data is trimmed to 2018 within Manhattan area. 

As safety issues becomes a concern for most vulnerable groups, pedestrians and cyclists, some analysis related to the patterns of vehicle
collisions will be helpful for future adjustments in transportation safety planning.



## Pedestrian and Cyclist Fatalities Caused by Vehicle Crashes in 2018 in Manhattan


The first map shows the fatalities happened in Manhattan in 2018. There are only 13 fatalities in total. But their locations are relatively
clustered around Central Park and Two Bridges. By clicking on the points on the map, it ables the pop-out window showing the number of killed
pedestrians and cyclists, and the number of injured pedestrians and cyclists.
<div id="folium-chart-1"></div>


## Pedestrian and Cyclist Injuries Caused by Vehicle Crashes in 2018 in Manhattan



The second map show the injuries happened in Manhattan in 2018. Among many injuries happened in New York, most of them only had one injuries.

<div id="folium-chart-2"></div>

## Vehicle Crashes by Hours in 2018 in Manhattan

Hitting 'play' on the button, the change of the heatmap in New York reveals the daily traffic trend. Althought night time is more unsafe in
terms of the transportation environment due to the lack of light, more crashes happened in day time.

<div id="folium-chart-3"></div>
