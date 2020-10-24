# PyBer_Analysis

## Overview of the Analysis
Created a sumary DataFrame of PyBer by city type. Then using Pandas and Matplotlib, I created a multiple-line graph tha shows the total weekly fares for each city type. By creating this DataFrame it will share insight on how it can be used for the decision-makers at PyBer.

## Results

Below is a snippet of the summary dataframe that i created. The columns are defined as they are created in the order. 

```Python
pyber_summary_df = pd.DataFrame({
          "Total Rides": total_rides_city, 
          "Total Drivers": total_drivers_city, 
          "Total Fares": total_fare_city,
          "Average Fare per Ride": avg_fare_per_ride, 
          "Average Fare per Driver": avg_fare_per_driver})

```
Our results from the summary Dataframe is below:

