# Project_1

# Title: Magic Towns in Mexico 

## Description:
Magic Towns designation has been one of the most important initiatives to promote tourism in Mexico. Tourism is the 3rd 
source of income for the country. The reason why this project is relevant and important.  

In this study, 120 magic town were analyzed to know how touristy are they. The main objective is to answer the next questions:
Which towns are more worth visiting?                                                                                          
Which towns are more accessible to non local tourists?                                                                          
Which towns are closest to the biggest mexican cities?                                                                       
Which towns offer good quality accommodation? To answer this question we asses the availability, quantity, quality and types of hotels.
Which towns offer enough interest points that make visiting worthwhile?                         

## Dependencies and Setup
* For managing the calls to the APIs: time, requests, from requests.exceptions - HTTPError, pprint (pretty json) 
* For reading csv files: os, csv
* For dataframes and lists: pandas, numpy
* For figures and maps:  matplotlib.pyplot, from scipy.stats - linregress, from matplotlib.pyplot - figure, googlemaps and gmaps 

## Resources
list of Magic Towns in Mexico.- https://www.gob.mx/sectur/articulos/pueblos-magicos-206528

## APIs used 
Nearby Commercial Airports.- Places API https://console.cloud.google.com/                                                   
Accommodation information.- Hoteles.com API by RapidAPI   https://hotels4.p.rapidapi.com/                                        
Distance to major cities.-  Distance Matrix Api   https://console.cloud.google.com

## Findings about Hoteles.com API by RapidAPI
*The API manage the errors internally. Even when there's an error the status could be 200 OK. 
![error_status200](https://user-images.githubusercontent.com/64176733/84956024-38fa9b00-b0ad-11ea-9e26-13662a21e23a.jpg)

*Api performance showed possible concurrency problems. In some cases until the 3rd try was possible to get the results. Like in the next case: 
![concurrency](https://user-images.githubusercontent.com/64176733/84957864-fd61d000-b0b0-11ea-8c97-5ceab39c4cf3.jpg)



