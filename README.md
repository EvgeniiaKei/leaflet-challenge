# leaflet-challenge
Module 15

![earth](https://github.com/user-attachments/assets/ff9d810f-67b4-4b71-824f-d74a48a710c7)


# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualise their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualise USGS data that will allow them to better educate the public and other government organisations (and hopefully secure more funding) on issues facing our planet.

# Tools Used
 - HTML
 - CSS
 - Leaflet
 - geojson API
 - d3.js

# Instructions
The instructions for this activity are broken into two parts:
  - Part 1: Create the Earthquake Visualisation
  - Part 2: Gather and Plot More Data (Optional with no extra points earning)

# Part 1: Create the Earthquake Visualisation

First task is to visualise an earthquake dataset. Complete the following steps:
1. Get your dataset. To do so, follow these steps:
   - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualise. The following image is an example screenshot of what appears when you visit this link:

     <img width="725" alt="1" src="https://github.com/user-attachments/assets/2336fbf1-6fb0-436e-93df-d6ad7a85bc43">

     
   - When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualisation. The following image is a sampling of earthquake data in JSON format:



2. Import and visualise the data by doing the following:

<img width="941" alt="image" src="https://github.com/user-attachments/assets/0ab2488e-4420-41a6-a914-eef1ede047bb">

   
   - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
      - Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by colour. Earthquakes with higher magnitudes should 
        appear larger, and earthquakes with greater depth should appear darker in colour.
      - Hint: The depth of the earth can be found as the third coordinate for each earthquake.
   - Include popups that provide additional information about the earthquake when its associated marker is clicked.

<img width="618" alt="image" src="https://github.com/user-attachments/assets/d57be271-e5aa-4704-8c07-ebed0b92f5ae">

   - Create a legend that will provide context for your map data.

     <img width="118" alt="image" src="https://github.com/user-attachments/assets/4f5f20ee-1406-43b5-bd77-5968e8ea570e">


# Link to deployed GitHub page: 
