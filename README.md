
# Udacity FEND Neighborhood Map Project
The Project is the final project for Udacity's Full Stack Web Developer Nanodegree.

# Author
Tej Poudel - Student FSND 

# Project Overview
This is the Udacity Neighborhood Map Project. It's intended as a challenge to put together a website from various APIs. This includes making function calls to Google Maps and other location-based services like Foursquare.

## Files
CSS - Two files make up the CSS files that are local. Bootstrap CSS is CDN based and not local, just easier to update as it is currently using **Bootstrap 4 Alpha**. CSS files indluded:
- `bootstrap-vertical-menu.css` 
- `mapStyles.css`

JS - Only main files are included here:
- `knockout-3.4.2.js` (Knockout framework)
- `app.js` (Main application file)
- `styles.js` (Contains the styles for the custom Google Maps look)
- `markers.js` (Contains myLocations to populate the map)

HTML - `Index.html` is where all the magic happens and all the data is binded.

## Features
You get a full screen Google Map, populated with my Santa Rosa Californi's Public Transportation Stops locations, along with a sidebar with a list of the locations that can be clicked on and see the information about the location.

## APIs
Google Maps API is used here to show the map and generate the markers etc.
Foursquare API is used to pull more information of public Transportation and provide a more complete listing when you click on the marker and the infoWindow shows up.

## Installation
Clone or download this zip file open it and simply open the index.html file and enjoy!
You can make modifications to the locations and add your own in the `js/markers.js` file.
