# 9.7_Delhivery_feature_engineering
Business Case: Delhivery - Feature Engineering

# Delhivery - Feature Engineering 📊

![Delhivery Logo]([https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/1280px-Netflix_2015_logo.svg.png](https://en.wikipedia.org/wiki/Delhivery#/media/File:Delhivery_Logo_(2019).png))

Welcome to the Delhivery Feature Engineering project! 🎉 In this repository, we delve into the world of Delhivery to Make sense out of the raw data and help the data science team to build forecasting models on it. Clean, sanitize and manipulate data to get useful features out of raw fields

## About Delhivery 🚚

Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.

The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

## Business Problem 📈

The company wants to understand and process the data coming out of data engineering pipelines:
• Clean, sanitize and manipulate data to get useful features out of raw fields
• Make sense out of the raw data and help the data science team to build forecasting models on it

## Dataset 📋

The dataset at the heart of this exploration includes a comprehensive listing of all the TV shows and movies available on Netflix. Here are some of the key features:
- **Show_id**: Unique ID for every movie or TV show.
- **Type**: Identifier - Is it a movie or a TV show?
- **data**: tells whether the data is testing or training data.
- **trip_creation_time**: Timestamp of trip creation.
- **route_schedule_uuid**: Unique Id for a particular route schedule.
- **route_type**: Transportation type.
- **FTL**: Full Truck Load - FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way.
- **Carting**: Handling system consisting of small vehicles (carts).
- **trip_uuid**: Unique ID given to a particular trip (A trip may include different source and destination centers).
- **source_center**: Source ID of trip origin.
- **source_name**: Source Name of trip origin.
- **destination_center**: Destination ID.
- **destination_name**: Destination Name.
- **od_start_time**: Trip start time.
- **od_end_time**: Trip end time.
- **start_scan_to_end_scan**: Time taken to deliver from source to destination.
- **is_cutoff**: Unknown field.
- **cutoff_factor**: Unknown field.
- **cutoff_timestamp**: Unknown field.
- **actual_distance_to_destination**: Distance in Kms between source and destination warehouse.
- **actual_time**: Actual time taken to complete the delivery (Cumulative).
- **osrm_time**: An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) and gives the time (Cumulative).
- **osrm_distance**: An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative).
- **factor**: Unknown field.
- **segment_actual_time**: This is a segment time. Time taken by the subset of the package delivery.
- **segment_osrm_time**: This is the OSRM segment time. Time taken by the subset of the package delivery.
- **segment_osrm_distance**: This is the OSRM distance. Distance covered by the subset of the package delivery.
- **segment_factor**: Unknown field.

## 🚀 Mission 🚀

To get you started, here are some questions you might consider:

- Basic data cleaning and exploration
- Build some features to prepare the data for actual analysis. Extract features from the fields.
- In-depth analysis and feature engineering2

## Concepts Used 
- Feature Creation
- Relationship between Features
- Column Normalization /Column Standardization
- Handling categorical values
- Missing values - Outlier treatment / Types of outliers

## 📈 Let's Get Exploring 📊

Now that you're armed with questions and a powerful dataset, it's time to embark on your journey. Feel free to fork this repository, clone it to your local machine, and start diving into the code and data. Don't forget to share your findings and insights with the community.

Remember, the more we learn from this data, the better we can help companies like Delhivery around the world! 🌎🍿

Happy learning! 🚀👨‍💻🎬
