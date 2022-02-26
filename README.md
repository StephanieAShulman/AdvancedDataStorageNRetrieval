# Surfs_Up
![tiny_oahu](https://user-images.githubusercontent.com/30667001/153775997-c7d36783-96d1-4e3a-9dc7-b73791c4f109.png)

As part of a master plan to move to Oahu where a surfing lifestyle could be funded by a successful ice cream-meets-surf supply business, this project required an understanding of data storage and retrieval to convince potential investors that inclement weather won’t disrupt possible profits at the proposed site.

# Resources
* Data Sources: hawaii.sqlite weather data, climate_analysis.ipynb starter notebook
* Software: Python 3.7.6, Jupyter Notebook 6.4.5, Visual Studio Code 1.63, SQLite3 3.37.0, Flask 1.1.2
* Libraries: Matplotlib, Pandas, NumPy, datetime, SQLAlchemy

# Project Overview
After creating the engine, automap schema and reflect tables, a session link was established with the database to query data. Precipitation data was accessed and saved into a dataframe. Plots were created from existing data to demonstrate changes in rainfall. While annual rainfall statistics were provided from nine separate stations, the station with the greatest number of readings was determined to be a good proxy for overall precipitation and annual temperature ranges.

![Precep_Temp](https://user-images.githubusercontent.com/30667001/153778423-a7ec6bdf-461d-4e48-9107-70594734ac0d.png)

Flask was used to build webpages that would allow a demonstration of these results to potential investors. Five routes total were created, with the output accessible via an http:// web address.

![smaller_routeStation](https://user-images.githubusercontent.com/30667001/153777305-d3902137-b38e-48be-b157-2c120df04614.png)

In final preparation for the presentation, summary statistics for temperatures in the months of June and December were generated to determine if the Surf n’ Shake Shop was sustainable year-round.

# Results
*	Average Oahu temperatures were similar in June (75°F) and December (71°F).
*	The range between cooler and warmer days was greater in the winter (between a low of 56°F to a high of 83°F) than in the summer (64°F to 85°F).
*	The overall interpretation is that the weather does not fluctuate greatly between the winter and summer months.

![temps_small](https://user-images.githubusercontent.com/30667001/155849457-e8493395-6417-4f4d-b1df-b60ecea11f1c.png)

To guarantee Surf n' Shake Shop funding and success at the coming investor meeting, a wider analysis should be conducted that includes:
* Precipitation and temperature should be combined to determine if one weather condition impacts another, depending on month.
* Precipitation and temperature by season. While June and December may be a good proxy based on tourist months, the plan to operate year-round should include an analysis that considers whether there may be times when shop items are less likely to be in demand and what the plan is for those times.
