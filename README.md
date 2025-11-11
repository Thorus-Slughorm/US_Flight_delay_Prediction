# US_Flight_delay_Prediction
 US Flight Delay Analysis &amp; Prediction (2015 Dataset)
This project explores US domestic flight delays using real data from the 2015 Flight Delays and Cancellations Dataset (Kaggle).
The goal is to understand why, when, and where flight delays occur, and to build a machine learning model that predicts whether a flight will be delayed by more than 15 minutes.
 
The project showcases a complete Data Analytics + Machine Learning pipeline, including data cleaning, visualization, feature engineering, and predictive modeling ideal for real-world business analytics and operations optimization.

 
# Objectives
 
Analyze flight delay patterns by airline, weekday, hour, and city
 
Identify top factors contributing to flight delays
 
Develop a Random Forest classifier to predict flight delays
 
Visualize and interpret results for business insights
 
 
# Dataset Details
 
Source: Kaggle - 2015 Flight Delays and Cancellations
Files Used:
 
flights.csv → Flight-level data (dates, times, delays)
 
airlines.csv → Airline names and codes
 
airports.csv → Airport locations and states
 
 
Size: ~5.8 million rows
Time Period: January–December 2015
 
 
# Data Cleaning & Preparation
 
Removed cancelled and diverted flights
 
Created unified date and day_name columns
 
Merged airline names and airport locations
 
Engineered new features:
 
scheduled_departure_hour, scheduled_arrival_hour
 
delay_category (On-time, Slight, Moderate, Severe)
 
 
Handled missing values and standardized column names
 
 
 
# Exploratory Data Analysis (EDA)
 
Average delays by airline, day of week, hour of day, origin city
 
Identified most delay-prone airports and airlines
 
Visualized distribution of delays using Matplotlib and Seaborn
 
 
# Key Insights:
 
1. Around 25–30% of flights experienced arrival delays.
 
  
 
2. Evening flights were more delay-prone due to accumulated delays during the day.
 
 
3. Busy airports like Chicago (ORD), Atlanta (ATL), and New York (JFK) showed the longest delays.
 
 
4. Flight distance showed little correlation with delay — delays were mostly operational.
 
 
# Predictive Modeling
 
Goal: Predict whether a flight will be delayed (>15 minutes).
 
Model Used: Random Forest Classifier
Libraries: scikit-learn, pandas, numpy
 
Feature Inputs:
 
Month, Day of Week
 
Scheduled Departure Hour
 
Distance
 
Airline, Origin City, Destination City
 
 
Results:
 
Accuracy: ~77%
 
Key Predictors: Airline, Departure Hour, Origin City
 
 
 
# Feature Importance Visualization
 
The top factors contributing to flight delays were visualized using a feature importance bar chart, showing that:
 
Airline choice
 
Origin city
 
Scheduled departure hour
had the strongest impact on whether a flight arrived late.
 
 
# Business Impact
 
This analysis can help:
 
Airlines improve scheduling and resource allocation
 
Airports identify high-delay routes for operational improvements
 
Passengers plan trips by understanding which times and days are more reliable
 
 
 
# Tools & Technologies
 
Category Tools
 
Data Analysis Python, Pandas, NumPy
Visualization Matplotlib, Seaborn
Machine Learning Scikit-learn (RandomForestClassifier)
Data Source Kaggle Dataset
Notebook Jupyter / Kaggle Notebook
 
 
 
# Folder Structure
 
US_Flight_Delay_Analysis/
│
├── flights.csv
├── airlines.csv
├── airports.csv
├── US_Flight_Analysis.ipynb
├── flight_delay_predictor.pkl
└── README.md
 
 # Future Improvements
 
Integrate weather data to improve prediction accuracy
 
Deploy a Streamlit web app for real-time delay prediction
 
Build an interactive Power BI dashboard for business use
 

# Author
 
👨‍💻 Tanish Dogra
Trainee Decision Scientist | Data Analyst & ML Enthusiast
📍 Passionate about solving real-world problems with data.
 
🔗 Kaggle Profile : https://www.kaggle.com/thorusslughorm
🔗 LinkedIn (https://www.linkedin.com/in/tanish-dogra)
 
