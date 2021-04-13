## Communicate Ford Bike Data Findings

- Data exploratoration: univariate relationships and multivariate relationships.

- Data explanatoration: create slide deck that have the required slides to do visualizations to communicate my results.

## Dataset
In this project I performed an exploratory analysis on data provided by Ford GoBike, a bike-share system provider, using Python visualization techniques. The goal is to figure out what variables possess the most influential power on a bike sharing service. I did the analysis on 2019 year data
dataset downloaded form [here](https://s3.amazonaws.com/baywheels-data/index.html)

Each trip is anonymized and includes:
- Trip Duration
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer)

## Data Wrangling Process

1. Columns that have missing values:
    - start_station_id
    - start_station_name
    - end_station_id
    - end_station_name


2. Convert start_time and end_time to timestamp format.


3. For further analysis start_time and end_time need to be separated into hour, day and month columns.


4. Some columns need to be changed into another type
    - user_type
    - start_station_id
    - end_station_id
    - duration_mins
    - bike_id


5. Drop unwanted columns for analysis.
### Features of interest in your dataset

- Understand he number of subscribers/customers in the dataset and which of them are more valuable to the company.

- The time for which the bike is rented on an average and the distance in miles travelled by different classes of users.

- Understand whether the start time of rentals differ between subscribers and customers.

- The locations which sees the most rentals among different classes of users.
### Observed Relationships of features of interest

- There is a relationship between time of rental and user type. 
- There is a relationship between Distance travelled, Rental Duration for Subscribers. 
- There is a relationship between user type and start station from where bikes are rented. 

### Interesting interactions between features

- Subscribers rented the bikes for less time than customers but travelled more they seems to be in hurry.

- Relationship between start Day, start Hour and user type which give a hint about the nature of the user type.
- subscribers seems to be students and employees and customers seems to be tourists. 

## Summary
- Subscribers uses bikes as transportation option. 

- Subscribers are regular customers who are making rides to/from work or school, renting a bike at 7-9am and 4-6pm on weekdays

- Customers rent bikes for exploring the Bay area and they could be tourists. 

- Customers could be tourists who use bikes to explore the Bay area mainly on weekends.