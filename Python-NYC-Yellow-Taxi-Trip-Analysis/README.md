# NYC Yellow Taxi Trip Data Analysis 🚖📊

This project analyzes the New York City Yellow Taxi Trip Dataset to uncover insights about taxi usage patterns, fare distributions, trip distances, and other key transportation metrics. The dataset contains millions of rows representing taxi trips in NYC, including timestamps, locations, fares, and passenger details.

## Main Columns:

- tpep_pickup_datetime, tpep_dropoff_datetime: Trip start and end timestamps
- passenger_count: Number of passengers
- trip_distance: Distance traveled (miles)
- fare_amount: Fare paid for the trip
- payment_type: Method of payment (e.g., cash, card)
- pickup_longitude, pickup_latitude: Pickup location
- dropoff_longitude, dropoff_latitude: Dropoff location
- tip_amount, tolls_amount, total_amount: Additional financial details

## Libraries Used

- import pandas as pd  
- import numpy as np  
- import matplotlib.pyplot as plt  
- import seaborn as sns  
- import datetime as dt

## Data Cleaning

- Converted datetime columns to proper datetime64 type
- Dropped rows with missing fare_amount, trip_distance, and datetime values
- Removed trips with:
- Zero or negative distance or fare
- Zero passengers
- Fare above the 99th percentile (outliers)

## Exploratory Data Analysis (EDA)
- Checked distribution of fare amounts, trip distances, and passenger counts
- Evaluated temporal patterns: hourly, daily, weekly trends
- Mapped pickup and dropoff coordinates for spatial analysis
- Compared fares and tips by payment type

## Insights 
- ~12.6 million records analyzed after cleaning
- Typical fare: ~$11.62
- Average trip distance: ~13.5 miles
- Outlier trips removed (e.g., fares > 99th percentile)
- Most common trips occur with 1 or 2 passengers.
- Cash payments are more common for short, cheap trips.
- Tip amount distribution skews right; higher tips are rare.
- Peak hours show surge in trip count around 8 AM and 6 PM.
- Spatial density shows Midtown and Downtown as top zones.
