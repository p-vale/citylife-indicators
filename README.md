# citylife-indicators

This repository contains analyses for smart cities and quality of life indicators. 

## Methodological notes

It isn't an exhaustive set for quality of life or smart cities evaluations. However, I plan to add examples for each type of indicator I've encountered in my projects. 

Please note that public code and data must comply with GDPR guidelines, thus the analyses are somewhat limited. Specifics are provided below and in each file. 


## Indicators

### Dog parks coverage
This is a prime example of for neighbourhood services evaluation. The indicator calculates the percentage of population within a 500 meter buffer from dog parks. 
Uses data from url.  

Limitations: geolocalized population data isn't open, thus the coverage is calculated as percentage of area within 500m from dog parks over total area. Ideally, once the buffer area is complete, the result would be number of residents within the buffer area over total residents.  

### Industry variety
This indicator evaluates how diverse are the economic activities in the city and in each neighbourhood, which districts are more active and how each is characterized. For example, in this case-study the city center is characterized by shops and personal services, the hinterland by agricolture and the port by trades and factories. 
Uses local data. 

Limitations: only the main activity of each company is evaluated. This is an arbitrary decision. 

### Population
This file contains general demographic indicators: age, gender, nationality, families. 

Limitations: geolocalized population data isn't open, thus the indicators are simple and based on synthetic data. 

### School coverage
Similarly to the Dog parks coverage, this indicator shows the distribution of schools in the city by grade. However, the coverage relative to users of the service isn't available.

Limitations: geolocalized population data isn't open, thus only the physical distribution of schools in the districts is shown. 

  
*Next: neighbourhood service with street network;*
