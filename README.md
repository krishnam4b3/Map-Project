# Map-Project

# Udacity FEND Neighborhood Map Project
This app is to demonstrate the ability to use a js framework (`knockout.js`) & Google Maps API.
The application was made as a the penultimate final project for Udacity's Front-End Nanodegree.

## Code
JS - There are quite a few here and I will try explain as best as possible without becoming too convoluted.
- `knockout-3.4.2.js` (Knockout framework)
- `main.js` (Main application file)
- `mapview.js` (Contains the styles for the custom Google Maps look)
- `locationsdata.js` (Contains myLocations to populate the map)

HTML - `index.html` is where all the magic happens and all the data is binded.

CSS - 'styling.css' (Contains Styles of the page)

## Features
A Google Maps implemenation that shows you the best places (in my opinion) to visit around Bhimavaram, India.
The site is fully responsive and will run on your tiniest screens all the way to the largest screen you can think of.
You get a full screen Google Map, populated with my favorite locations, along with a list of the locations beside the map that can be clicked on and also filtered so you can nail down what you want without any other distractions.

## APIs
Google Maps API is used here to show the map and generate the markers etc.
Foursquare API is used to pull more information on my favorite locations and provide a more complete listing when you click on the marker and the infoWindow shows up.(If any information regarding the location is not in the Foursquare API will show like undefined.)

## Installation
Clone or download this repo and simply open the index.html file and enjoy!
You can make modifications to the locations and add your own in the `js/locationsdata.js` file.

## Reference
I took reference for this project in github.com.
