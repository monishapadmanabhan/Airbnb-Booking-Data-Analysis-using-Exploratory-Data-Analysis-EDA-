# AirBnB Booking Data Analysis using Exploratory Data Analysis (EDA)

## Introduction
Exploratory Data Analysis (EDA) is an important step in understanding and analyzing datasets before building models or making decisions. This project performs EDA on an Airbnb booking dataset to uncover patterns, trends, and insights related to pricing, room types, locations, and user reviews.

The analysis includes data cleaning, preprocessing, statistical analysis, and visualization to better understand the structure of the dataset and identify meaningful relationships between variables.

---

## Project Overview
The objective of this project is to analyze Airbnb booking data using Python and visualization libraries. By performing EDA, we aim to understand how Airbnb listings vary in terms of price, room types, location distribution, and review patterns.

This project demonstrates key data analysis skills such as:
- Data cleaning and preprocessing
- Handling missing values
- Feature exploration
- Data visualization
- Extracting business insights from real-world data

---

## About Airbnb Platform
Airbnb is an online marketplace that connects people who want to rent out their properties with travelers looking for accommodation. Founded in 2008, Airbnb operates in more than 220 countries and offers millions of listings including apartments, houses, and unique properties such as cabins and treehouses.

The platform allows hosts to earn income from their unused spaces while providing travelers with flexible and affordable accommodation options.

---

## Dataset Description
The dataset used in this project contains information about Airbnb listings including host details, property characteristics, pricing, and review data.

Some key attributes in the dataset include:

- id – Unique identifier for each listing  
- name – Name of the Airbnb listing  
- host id – Unique identifier for the host  
- host name – Name of the host  
- neighbourhood group – Area where the property is located  
- neighbourhood – Specific neighborhood of the listing  
- latitude and longitude – Location coordinates  
- room type – Type of accommodation offered  
- price – Listing price  
- service fee – Additional service charges  
- minimum nights – Minimum number of nights required for booking  
- number of reviews – Total reviews received by the listing  
- last review – Date of the most recent review  
- availability 365 – Number of days the listing is available in a year  

---

## Tools and Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Data Cleaning and Preprocessing
Before performing analysis, the dataset was cleaned to ensure accuracy and reliability. The following steps were performed:

- Converted the **last review** column to datetime format  
- Filled missing values in important columns such as reviews per month  
- Removed records with missing listing names or host names  
- Converted price and service fee columns to numeric values  
- Removed duplicate records from the dataset  

These steps helped prepare the dataset for accurate analysis and visualization.

---

## Exploratory Data Analysis (EDA)

### Price Distribution
A histogram was used to visualize the distribution of listing prices.  
The results show that most listings fall within a moderate price range, while a few listings have very high prices.

### Room Type Distribution
A count plot was created to analyze the distribution of different room types.  
The majority of listings are **Entire homes/apartments** and **Private rooms**, while shared rooms and hotel rooms are relatively rare.

### Neighborhood Analysis
Listings were analyzed across different neighborhood groups.  
The results indicate that **Manhattan and Brooklyn have the highest number of listings**, suggesting that they are the most popular areas for Airbnb properties.

### Price vs Room Type
A box plot was used to compare pricing across different room types.  
Entire homes and hotel rooms generally have higher prices compared to private rooms and shared rooms.

### Reviews Over Time
A time-series plot was created to analyze review activity over time.  
This helps identify trends in guest engagement and seasonal booking behavior.

---

## Key Insights

### Pricing Distribution
- Most Airbnb listings fall within a moderate price range.
- A few high-priced listings indicate premium properties.

### Room Type Distribution
- Entire homes/apartments and private rooms dominate the listings.
- Shared rooms and hotel rooms represent a small portion of the dataset.

### Geographical Distribution
- Manhattan and Brooklyn have the highest concentration of listings.
- Queens, Bronx, and Staten Island have fewer properties.

### Price Comparison by Room Type
- Entire homes/apartments generally have the highest prices.
- Shared rooms tend to be the cheapest accommodation type.

### Seasonal Review Trends
- Review activity changes over time.
- Some periods show higher engagement, indicating seasonal demand.

---

## Conclusion
This project demonstrates how Exploratory Data Analysis can be used to understand real-world datasets and uncover important insights. By analyzing Airbnb booking data, we identified trends in pricing, room types, location distribution, and user engagement.

The insights obtained from this analysis can help hosts optimize pricing strategies, improve listing quality, and better understand market demand. Additionally, this project highlights the importance of data cleaning, visualization, and analytical thinking in data analysis workflows.

---

## Author
Monisha P  
Aspiring Data Analyst | Python | Power BI | SQL
