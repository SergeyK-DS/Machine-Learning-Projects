# Predicting Real Estate Prices in Melbourne

This project is based on analyzing real estate data in Melbourne and using machine learning models to predict property prices.

## Objectives

- Analyze real estate data
- Predict property prices using machine learning models

## Models Used

In this task, we will be using CatBoost, a gradient boosting library that handles categorical features well.

## Object Features

The dataset includes the following features of real estate properties:

- Suburb – Suburb or district
- Address – Address of the property
- Rooms – Number of rooms
- Type – Type of property:
  - h - house, cottage, villa, semi, terrace;
  - u - unit, duplex;
  - t - townhouse.
- Price – Price of the property
- Method – Method of sale:
  - S - property sold;
  - SP - property sold prior;
  - PI - property passed in;
  - VB - vendor bid;
  - SA - sold after auction.
- SellerG – Name of the real estate agent
- Date – Date of sale
- Distance – Distance to CBD in kilometers
- Postcode – Postal code
- Bedrooms2 – Number of bedrooms
- Bathroom – Number of bathrooms
- Car – Number of parking spaces
- Landsize – Land size in square meters
- BuildingArea – Building area in square meters
- YearBuilt – Year the property was built
- CouncilArea – Local government area
- Latitude – Latitude coordinates
- Longitude – Longitude coordinates
- Regionname – Region name
- Propertycount – Number of properties in the suburb
- ID – Property ID

## Additional Data

To obtain additional latitude and longitude data for suburbs with postal codes, you can use the following sources:

- [Matthew Proctor - Australian Postcodes](https://www.matthewproctor.com/australian_postcodes)

To create a map with latitude and longitude for suburbs, you can use the following source:

- [Data.gov.au - Suburb Locality Boundaries](https://data.gov.au/geoserver/vic-suburb-locality-boundaries-ps
