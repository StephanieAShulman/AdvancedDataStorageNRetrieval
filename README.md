# Surfs_Up
![tiny_oahu](https://user-images.githubusercontent.com/30667001/153775997-c7d36783-96d1-4e3a-9dc7-b73791c4f109.png)

As part of a master plan to move to Oahu where a new lifestyle of daily surfing can be funded by a successful Surf n’ Shake shop, this project requires an understanding of data storage and retrieval to convince potential investor W.Avy that weather won’t disrupt possible profits. The goal of this analysis was to illustrate how known weather patterns might affect the proposed site.

## Resources
* Data Sources: hawaii.sqlite weather data, climate_analysis.ipynb starter notebook
* Software: Python 3.7.6, Jupyter Notebook 6.4.5, Visual Studio Code 1.63, SQLite3 3.37.0, Flask 1.1.2
* Libraries: Matplotlib, Pandas, NumPy, datetime, SQLAlchemy

## Project Overview
After creating the engine, automap schema and reflect tables to keep code separated, a session link was established with the database to query data. Precipitation data was accessed and saved into a dataframe and plotted to demonstrate changes in rainfall over the entire known time. Annual rainfall statistics were provided from nine separate stations. The station with the greatest number of readings was determined to be a good proxy for overall precipitation and served as a source for a graph of annual temperature ranges.

![Precep_Temp](https://user-images.githubusercontent.com/30667001/153778423-a7ec6bdf-461d-4e48-9107-70594734ac0d.png)

Flask was used to build webpages, with five routes total created. Once the routes were created and the Flask app run, output could be accessed via an http:// web address.

![smaller_routeStation](https://user-images.githubusercontent.com/30667001/153777305-d3902137-b38e-48be-b157-2c120df04614.png)

In final preparation for the presentation, the database was again accessed as before to retrieve temperatures for the months of June and December and summary statistics generated for each.

