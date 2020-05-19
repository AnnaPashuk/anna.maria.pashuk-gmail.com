## Project name: Hotels App

Check it out: https://github.com/AnnaPashuk/Coursework/tree/master/hotelsmap_django_html/HotelsApp


Video preview: 


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
 
 

 
 
 ### Example modules
 
 [create hotels set with API](https://github.com/AnnaPashuk/Coursework/blob/master/examples/hotels_set.py)
 
 [example of JSON](https://github.com/AnnaPashuk/Coursework/blob/master/examples/city_hotels.json)
 
 [example of wikipedia lib work](https://github.com/AnnaPashuk/Coursework/blob/master/examples/wikipedia_lib_test.py)

 [ADT module](https://github.com/AnnaPashuk/Coursework/blob/master/adt/city_array.py)
 
 [testingADT module](https://github.com/AnnaPashuk/Coursework/blob/master/adt/city_array_test.py)

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


