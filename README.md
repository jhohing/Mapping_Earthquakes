# Mapping_Earthquakes

## Project Overview
The objective of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world.\
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Results

### Create a Mapbox account, setup *config.js* and open *index.html*
To interact with the maps API the user have to visit [mapbox.com](https://www.mapbox.com/), create a Mapbox account and retrieve the access token.

As shown below, the [index.html](https://github.com/jhohing/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html) calls for the Mapbox API key in the *config.js* file. 
<p align="center">
    <img src="https://user-images.githubusercontent.com/74940620/213617530-03ce11fa-c7ce-481e-8780-83ef3372f411.png"> 
</p>

The user would have to save the token key in *config.example.js* and rename the file *config.js*: <p align="center"><img src="https://user-images.githubusercontent.com/74940620/213617693-f5237702-0744-49b7-a71e-eaff34932bc9.png"></p>
<br>
To open the *index.html* file, open the command line, navigate to the main folder and on the command line, enter `python -m http.server`.

### Interactive Maps Views

<p align="center">
    <img src="https://user-images.githubusercontent.com/68669675/97132486-193b4980-1715-11eb-9a2e-a4c46b64562e.png">
    Streets view
</p>
<br>
<p align="center">
    <img src="https://user-images.githubusercontent.com/68669675/97132553-530c5000-1715-11eb-8440-af9e07854c03.png">
    Satellite view
</p>
<br>
<p align="center">
    <img src="https://user-images.githubusercontent.com/68669675/97132602-7a631d00-1715-11eb-90ba-8b250f172913.png">
    Dark view
</p>
