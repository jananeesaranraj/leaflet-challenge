
# leaflet-challenge

leaflet-part-01---->> https://jananeesaranraj.github.io/leaflet-challenge/Leaflet-Part-1

leaflet-part-02---->>https://jananeesaranraj.github.io/leaflet-challenge/Leaflet-Part-2

**Background**

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

**Part 1: Create the Earthquake Visualization**

 Completed the following steps:
 
 1. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed Links to an external site.page and choose a     dataset to visualize.
 
 2. From the dataset,the JSON representation of "All Earthquakes from the Past 7 Days" is pulled for the visualization.
 
 3. Using Leaflet, created a map that plots all the earthquakes from the dataset based on their longitude and latitude.
   
   * The data markers should will reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes          appear larger,and earthquakes with greater depth should appear darker in color.
  
   * Included popups that provide additional information about the earthquake when its associated marker is clicked.
   
   * Created a legend that will provide context for the map data.
   

  ![Leaflet_Part1](https://user-images.githubusercontent.com/112193116/211363361-14a9abc9-f8e0-48de-90b6-bc162ec83dc1.png)
   
**Part 2: Gather and Plot More Data**
   
 Performed the following tasks:
 
  * Plotted the tectonic plates dataset on the map in addition to the earthquakes.
  
  * Added other base maps to choose from.

  * Put each dataset into separate overlays that can be turned on and off independently.

  * Added layer controls to the map.
  
   ![Leaflet_Part2](https://user-images.githubusercontent.com/112193116/211363337-eab0b27e-d0f1-4ac0-8db3-c94eb7bc0368.png)
   
   
