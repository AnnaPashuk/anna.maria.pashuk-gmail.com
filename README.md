## Project name: Hotels App

Check it out: https://github.com/AnnaPashuk/Coursework/tree/master/hotelsmap_django_html/HotelsApp


Video preview: https://youtu.be/bps6DY_wudk 
https://github.com/AnnaPashuk/Coursework/blob/master/docs/video_presentation.avi


## Table of contents

* [Description](#Description)

* [Input and Output data](#Input-and-Output-Data)

* [Program structure and content](#Program-structure-and-content)

* [Installation](#Installation)

* [Usage examples](#Usage-examples)

* [Contributing](#Contributing)

* [Credit](#Credit)

* [Licence](#Licence)



## Description
This Hotels App is a website, where you can enter a city on any language and receive information about it.
On the right will be general theoretical information about the city.
Under the city name will be generated a map with all markers of hotels in the city. Map can be regulated as you wish and can be opened on a full screen.
Under the map will be generated a list with hotels in the city with their full name, address and rating.
All next seach of the city will be generated a new map, but information and hotels list will be appended under previous cities.
This will help the tourist to create his own route and view all information about cities at the same time and on the same page.

## Input and Output

All input data was loaded with Google Maps API : https://cloud.google.com/maps-platform/?_ga=2.228158749.1663879752.1589873602-2070032628.1586961081
All output data is represented on a website.

 ## Program structure
 
 [main module](https://github.com/AnnaPashuk/Coursework/tree/master/hotelsmap_django_html/HotelsApp) - The whole Django application.
 [HotelsApp](https://github.com/AnnaPashuk/Coursework/tree/master/hotelsmap_django_html/HotelsApp/HotelsApp) - general application module
 [map](https://github.com/AnnaPashuk/Coursework/tree/master/hotelsmap_django_html/HotelsApp/map) - main page

 

 
 
 ### Example modules
 

 [ADT module](https://github.com/AnnaPashuk/Coursework/blob/master/adt/city_array.py)
 
 [testingADT module](https://github.com/AnnaPashuk/Coursework/blob/master/adt/city_array_test.py)
 
 [create hotels set with API](https://github.com/AnnaPashuk/Coursework/blob/master/examples/hotels_set.py)
 
 [example of JSON](https://github.com/AnnaPashuk/Coursework/blob/master/examples/city_hotels.json)
 
 [data.json](https://github.com/AnnaPashuk/Coursework/blob/master/examples/data.json) - example of JSON file we get after API requests.
 
 [example of wikipedia lib work](https://github.com/AnnaPashuk/Coursework/blob/master/examples/wikipedia_lib_test.py)

 [key.py](https://github.com/AnnaPashuk/Coursework/blob/master/examples/key.py) - you need to add your API key in this module

 [pictures_examples](https://github.com/AnnaPashuk/Coursework/tree/master/pictures_examples) - examples of site work and ADT structure.

## Installation

Clone repasitory: 
git clone https://github.com/AnnaPashuk/Coursework

Install:

```bash
pip install requests
```

```bash
pip install django
```

```bash
pip install wikipedia
```

Also you need Google Maps API 
You gen get it here: https://cloud.google.com/maps-platform/?_ga=2.228158749.1663879752.1589873602-2070032628.1586961081

## Usage examples

Site interface:
![](https://github.com/AnnaPashuk/Coursework/blob/master/pictures_examples/site_interface.jpg)



![](https://github.com/AnnaPashuk/Coursework/blob/master/pictures_examples/hotels_list1.jpg)


![](https://github.com/AnnaPashuk/Coursework/blob/master/pictures_examples/hotels_list2.jpg)

## Credit

* Anna Pashuk, Ukrainian Catholic University, 2020

## Licence


