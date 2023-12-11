# Visualizing Seattle Traffic Collisions 2022-2023

[Map Application Link](https://noah-rarick.github.io/seattle-collisions/heatmap.html)

Navigating the intricate web of Seattle's streets involves a delicate balance of vehicles, pedestrians, and infrastructure. Prioritizing safety in this dynamic environment requires a comprehensive understanding of car collision patterns. To address this need, we present an interactive map showcasing vehicle collisions across the greater Seattle area. The map features a thematic heat map illustrating the frequency of these collisions and offers information on the number of injuries resulting from each collision.  

![Basic Picture of our Map](https://github.com/noah-rarick/seattle-collisions/blob/main/img/Map-Overview-2.png)

Users can utilize a slider to explore collision data within specified date ranges, offering insights into the patterns throughout the year. This slider allows a selective range between March of 2022 and December of 2023. Adjusting the slider on the left side of the map will reveal collisions that occurred between the 2 specified date ranges, with the start date being on top and the end date on the bottom.

![Basic Picture of our Map with a refined range](https://github.com/noah-rarick/seattle-collisions/blob/main/img/Map-Overview.png)

Changing the ranges of the map allows us to reveal the trends in traffic collisions during the different months of the year. Filtering these data points allows us also to focus on the individual points to reveal more information as well. Since our map is interactive, the user can zoom to achieve a detailed inspection of each individual incident.

![Image that shows the clicking feature](https://github.com/noah-rarick/seattle-collisions/blob/main/img/click-feature.png)

As another feature of interactivity, clicking these points reveals access to more information about each incident. This additional information includes details about the number of injuries, collision type, and the name of the street which the collision took place. These individual incident dots also provide information based on their color, categorizing them based on the number of injuries that occurred in the incident. The values of these colors are shown in the legend that appears on the left side of the map. This allows for quick analysis of the points, revealing which areas are more prone to injury when compared with others.


### Project Objective
The primary goal of this project is to provide a visual representation designed to educate and inform both the general public and government officials about the occurrence and frequency of traffic collisions in the city. The visualization identifies high-risk areas, offering valuable insights to the local community and enhancing awareness among pedestrians navigating these neighborhoods. This can encourage pedestrians to be extra alert of accidents in these high frequency areas, or even convince them to alter their routes to lower frequency areas. For government agencies such as the Seattle Department of Transportation and Sound Transit, this information is instrumental in driving targeted improvements and implementing changes in areas prone to frequent collisions. This map could be a key tool utilized in future planning to strive toward making the streets a safer place for everyone. This might stimulate additional research aimed at examining the attributes of regions with elevated accident and injury rates, uncovering whether specific features contribute to a higher incidence of accidents. In essence, the objective of this project is to enhance the safety of Seattle for every resident and reduce the number of vehicle collisions for the future.


### Data Source
The dataset utilized in this project is sourced from the Seattle Department of Transportation, a municipal agency dedicated to planning, designing, and maintaining the city's transportation infrastructure. Specifically, the dataset reflects the locations of collisions based on Seattle traffic police reports. While the original dataset contained comprehensive collision information, our focus narrowed to the scale of collisions, the number of injuries sustained, and pedestrian involvement. To streamline and enhance our dataset, we selected a subset covering the past year and eliminated irrelevant columns to optimize the size of our geoJson file.

### Technology Utilized
The key application library powering our project is the Mapbox GL JS library. This technology empowers us to create interactive maps and visualizations, providing an engaging platform for users to explore and comprehend the dynamics of traffic collisions in Seattle. Leveraging this advanced library, we ensure a seamless and informative user experience, allowing for a deeper understanding of the data presented. We utilized the heatmap base layer for the zoomed-out visualization and a point layer for the zoomed-in map to provide multiple forms of analysis for the collision data. Github allowed us to host our GeoJSON data and collaborate with one another using different branches.

### Importance and Impact
Beyond its technical aspects, the project's significance lies in its potential to contribute to public safety and urban planning. By shedding light on the spatial distribution of traffic collisions, the map serves as a tool for proactive decision-making. Viewers can directly see neighborhoods that need more attention due to the heat map style, adding a thematic element to visualize danger. It enables civic engagement by informing residents about safety concerns in their neighborhoods and empowers government officials to enact targeted interventions. This web map also offers a very user-friendly platform to explore and understand traffic collision dynamics, ensuring all individuals can access and understand this information equally. Through this collaborative approach, we strive to foster a safer and more informed community. Hopefully, with all this information provided Seattle can strive to be a safer place for all drivers and pedestrians for years to come.  	


### Acknowledgements

[Seattle GeoData – Collisions All Years](https://data-seattlecitygis.opendata.arcgis.com/datasets/sdot-collisions-all-years-2/explore)
