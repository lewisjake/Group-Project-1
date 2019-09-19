# Group-Project-1

#An app for locating a brewery or bar in a user-selected city.

API's Used:  OpenBrewery, Google Maps

Created with:  HTML, CSS, Javascript, JQuery, Firebase, Bootstrap

# HTML & CSS - Bill Coury
Biggest accomplishment was getting the bubbles to work over the background image.  Tried to make a very basic looking page with large containers to make it easy for viewing on multiple devices.

# Google Maps Platform - Jeff Corpuz
Working through the google maps platform was tough. Initially, I thought I would only one of their services for the project. I ended up using one key tied to 14 different services to make sure I had everything covered.  Also, I now have a greater apperication for documnetation.  I felt that I have read more documentation than writing code. For example, to avoid charges to the api key, I had to use their Places Search service with Autocomplete.  Autocomplete restricted the search to just cities within the US and further restriceted the search to only the viewport of the map.  

# OpenBreweryDb API - Jacob Lewis
Using the openbrewerydb.org API I was able to pull from their database using ajax. We chose to use the search by city parameter to return up to 20 breweries in that city. We found that this API was limited because they did not have much brewery data on smaller cities. We ran a for loop on the return data and wrote the results to a div called brew-list on the html using jQuery.
