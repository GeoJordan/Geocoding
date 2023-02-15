#### Project Status - Complete
# Geocoding with Python
## Introduction
An eCommerce client requests for a project, part of which require identification of regional location of their braches and their existing and potential clients, so their sales team can target these customers during promotion campaings. Because the dataset includes physical addresses and would like to plot them on a map, I had to geocode the address to generate their latitude and longitude co-ordinates. Upon a careful consideration, decided to use the following approach:

- obtain the eCommerce companys dataset (but for this example, I obtained the Kaggle pizza dataset),

- geocode the zip codes to obtain latitude and longitude using Nominatim,

- calculate distance of the branches from a starting point (e.g. Bend, Oregon) using GeoPy, then

- map the branches using Folium.

Please note that the file for the actual model is too large to be stored in this repository. Hence this project is a demonstration of only the mapping part of the project performed for the client.

## Technologies used
- GeoPy
- Folium
- Pandas
- Numpy
- Nominatium/Open Street Map (OSM)
- Google Colab

## Contribute
Thanks for considering contributing to this project.

## Contact
All feedback would be warmly recieved.


