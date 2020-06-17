# Project_1

# Title:
Magic Towns in Mexico 

# Description:
Magic Towns designation has been one of the most important initiatives to promote tourism in Mexico. Tourism is the 3rd 
source of income for the country. The reason why this project is relevant and important.  

In this study, 120 magic town were analyzed to know how touristy are they. The main objective is to answer the next questions:
Which towns are more worth visiting?                                                                                          
Which towns are more accessible to non local tourists?                                                                          
Which towns are closest to the biggest mexican cities?                                                                       
Which towns offer good quality accommodation? To answer this question we asses the availability, quantity, quality and types of hotels.
Which towns offer enough interest points that make visiting worthwhile?                         

# Limitations 
**Technical: Api performance showed deficiencies (ie. concurrency problem)                                                   
**Assumptions used in correlation analysis: The metric “the number of hotels in town” is limited as a proxy of the level 
of touristic activity by the the fact that: Some towns are just one day visiting worthwhile (no more to see than 1 landmark, 
usually city center) or close enough to major cities.

# Dependencies and Setup
Matplotlib.pyplot, pandas, scipy.stats, numpy, linregress

# Resources
list of Magic Towns in Mexico.- https://www.gob.mx/sectur/articulos/pueblos-magicos-206528

# APIs used 
Nearby Commercial Airports.- Places API https://console.cloud.google.com/                                                   
Accommodation information.- Hoteles.com API by RapidAPI   https://hotels4.p.rapidapi.com/                                        
Distance to major cities.-  Distance Matrix Api   https://console.cloud.google.com

# Findings about Hoteles.com API by RapidAPI
** The API manage the errors internally. Even when there's an error the status could be 200 OK. 


