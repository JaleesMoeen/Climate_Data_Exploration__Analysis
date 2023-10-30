# Climate_Data_Exploration__Analysis
 Climate analysis and data exploration of a climate database

# Explore
Hey, let's explore the climate changes for a best holiday


### 1 Introduction 


- We have a sqlite databsse for the data of climate for a location to explore the data.

- Basis on the data analysis we can plan much better about in what days we cna go for the vacation holiday and what other preparations we need with respect to temperature changes in climate.

- We will use the Jupyter Notebook for data exploration and also create a Flask app to display the information in json format using API.


![Alt text](images/1_flask.webp)



### 2 Prerequisites

-  Python and SQLAlchemy use to do a basic climate analysis and data exploration of our climate database.

-  Specifically, we use SQLAlchemy ORM queries, Pandas, and Matplotlib.


![Alt text](images/2_sqlalchemy.png)



### 3 Explore the Climate Data

#### 3.1 Connection to Database


![Alt text](images/3_libraries.png)


Use the SQLAlchemy create_engine() function to connect to my SQLite database.


![Alt text](images/4_engine.png)


Use the SQLAlchemy automap_base() function to reflect your tables into classes, and then save references to the classes named station and measurement.


![Alt text](images/5_session.png)


Link Python to the database by creating a SQLAlchemy session.


#### 3.2 Inspection of Tables

Two tables are identified by the inspection of the database and here is the data in first 10 rows.

##### 3.2.1 Measurement Table


![Alt text](images/6_measurement.png)


##### 3.2.2 Station Table


![Alt text](images/7_station.png)


### 4 Exploratory Analysis


The analysis for the precipitation and station table is performed.


#### 4.1 Precipitation Analysis

Precipitation analysis using the bar plot shows the summary of the percipitation data. (Sorted by Date)



![Alt text](images/8_percipitation.png)



#### 4.2 Station Analysis


Station analysis display the temperature observations of the data from August 2016 to August 2017. 


![Alt text](images/9_tobs.png)



### 5 Flask API for Climate Data






