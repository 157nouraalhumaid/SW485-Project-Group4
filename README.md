# SW485-Project-Group10
1. Problem Statement
Understanding real estate rental prices is crucial for both property owners and renters. This project aims to develop a machine learning-based recommendation system that predicts rental prices based on key property attributes such as land area, location, ratings, and property type. By analyzing historical rental data, the system will provide insights into pricing trends, rating distributions, and market behavior.
This project will leverage:
•	Supervised learning for price prediction
•	Unsupervised learning for property clustering
•	Generative AI to extract insights from the dataset
________________________________________
2. Motivation
The real estate market is dynamic, influenced by multiple factors, making price estimation complex. Our project aims to:
•	Provide an intelligent recommendation system that helps users understand price variations based on location, property type, and other factors.
•	Assist property owners in pricing their rentals competitively based on real market data.
•	Help renters make data-driven decisions when choosing rental options.
•	Enable accurate and efficient real estate rental predictions using machine learning and data analytics.
________________________________________
3. Dataset Overview
•	Source: Kaggle - Real Estate Rental Prices
•	Dataset Description: This dataset contains real estate rental price data designed for market analysis and predictive modeling. It includes:
o	Property Name – Identifies the rental property.
o	Land Area (Size in sqm) – Measures the size of the rental unit.
o	Price per Night – Rental cost for short-term stays.
o	Neighborhood & City – Location-based information.
o	Ratings & Number of Reviews – Quality indicators based on customer feedback.
o	Property Category – Type of rental property (apartment, villa, etc.).
The dataset enables various analyses, including predicting rental prices, clustering properties, and understanding market trends.
________________________________________
4. General Information
•	Number of Observations (Rows): 16,913
•	Number of Features (Columns): 10
•	Types of Variables:
o	Categorical: Property type, city, neighborhood
o	Numerical: Price per night, land area, number of reviews
o	Text: Property name
________________________________________
5. Dataset Columns & Data Types
Column Name	Type	Description
التصنيف	Categorical	Property type (e.g., "Studio", "Apartment")
المدينة	Categorical	City where the property is located
الحي	Categorical	Neighborhood within the city
اسم العقار	Text	Name of the rental property
سعر الليلة	Numerical	Rental price per night (in local currency)
المساحة	Numerical	Property size in square meters (sqm)
عدد المقيمين	Numerical	Maximum number of occupants allowed
التقييم	Numerical	Average user rating of the property
الرقم	Numerical	Property ID (Index)
________________________________________
6. Dataset Preprocessing
Before using this dataset for machine learning, preprocessing steps were applied:
•	Converted سعر الليلة (Price per Night) from text to numerical format.
•	Checked and handled missing values.
•	Encoded categorical features where necessary.
________________________________________
7. Team Members & Roles
Name	Role
Noura Alhumaid	Data Preprocessing & Documentation
Mashael Alqabbani	Dataset Description & Source Information
Asma Alshehri	Data Exploration & Visualization
Walah Alhmemedy	Data Preprocessing & Documentation
Sarah Alkanhal	Data Preprocessing & Documentation

