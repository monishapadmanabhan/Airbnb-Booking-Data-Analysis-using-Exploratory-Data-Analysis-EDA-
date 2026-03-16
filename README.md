AirBnB Booking Data Analysis using Exploratory Data Analysis (EDA)

Introduction
Exploratory Data Analysis (EDA) is an important step in understanding and analyzing datasets. In this project, EDA is performed on an Airbnb booking dataset to discover patterns, trends, and insights related to pricing, room types, locations, and user reviews.

Project Overview
The objective of this project is to analyze Airbnb booking data using Python and visualization libraries. The analysis focuses on cleaning the dataset, exploring its structure, and identifying patterns in listings, pricing, and customer engagement.

About Airbnb Platform
Airbnb is an online marketplace that connects people who want to rent out their homes with travelers looking for accommodation. Founded in 2008, the platform operates in more than 220 countries and provides millions of listings including apartments, houses, and unique properties. It allows hosts to earn income from their unused spaces while offering travelers flexible and affordable accommodation options.

Dataset Description
The dataset contains information about Airbnb listings including host details, property characteristics, pricing, and reviews.

Important columns in the dataset include:
id – Unique identifier for each listing
name – Name of the listing
host id – Unique identifier of the host
host name – Name of the host
neighbourhood group – Area where the property is located
neighbourhood – Specific neighborhood of the listing
latitude and longitude – Geographic coordinates of the property
room type – Type of accommodation offered
price – Price of the listing
service fee – Additional charges
minimum nights – Minimum nights required for booking
number of reviews – Total reviews received by the listing
last review – Date of the latest review
availability 365 – Number of days the property is available in a year

Tools and Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Data Cleaning and Preprocessing
Before performing the analysis, the dataset was cleaned to ensure accuracy. The last review column was converted into datetime format. Missing values in important columns were handled, and records with missing listing names or host names were removed. Price and service fee columns were converted into numeric format, and duplicate records were removed.

Exploratory Data Analysis
Different visualizations were created to understand the dataset and identify patterns.

Price Distribution
The price distribution shows that most Airbnb listings fall within a moderate price range, while a few listings are priced significantly higher.

Room Type Distribution
Most listings are either entire homes or private rooms. Shared rooms and hotel rooms represent a much smaller portion of the listings.

Neighborhood Analysis
Listings are mainly concentrated in popular areas such as Manhattan and Brooklyn. Other areas like Queens, Bronx, and Staten Island have fewer listings.

Price Comparison by Room Type
Entire homes and apartments generally have higher prices compared to private rooms and shared rooms.

Reviews Over Time
The analysis of reviews over time shows variations in user engagement. Certain periods have higher review activity, which may indicate seasonal trends in bookings.

Key Insights
Most Airbnb listings are priced within a moderate range, with a few premium listings at higher prices.
Entire homes and private rooms dominate the available listings.
Manhattan and Brooklyn have the highest concentration of properties.
Entire homes generally cost more than private rooms and shared rooms.
Review activity shows variations over time, indicating seasonal trends in demand.

Conclusion
This project demonstrates how exploratory data analysis can be used to understand real-world datasets. By analyzing Airbnb booking data, important trends in pricing, room types, location distribution, and customer engagement were identified. These insights can help hosts improve their listing strategies and help travelers make informed accommodation choices.

Author
Monisha P
