# week9_assignment
Working With The DOM To Add Animation To Maps 

This repository is a sample project to demonstrate how to move marker (any type) on a specifiq path on the google map.
Since since it's a required feature when implementing or drawing a path bettween two point.

MAPBOX
  mapbox is an open-source platform that allows you to create and display maps on a web page. 
The mapboxgl JavaScript library is part of the Mapbox ecosystem. It allows you to add all sorts of customizations to the map.

In this project, i have creates using the MBTA bus data to determine stops between Harvard and MIT. 
Then,  add an animated marker on the map to highlight the bus routes.

following steps are used to animate marker:

step1:Create a Mapbox account and get the access token
step2:Add the access token to the mapboxgl instance defined in the mapanimation.js
ste3:Create a marker and add it to the map using the mapboxgl pre-built functions.
step:4The function move() is called when the button "Show stops between MIT and Harvard" is selected. This is how you can start the marker animation.
step5:If your code works, you should be able to see a marker moving from one bus stop to the next on the map.
