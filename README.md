# LinearRegression-Project
Uber fare prediction using machine learning by analyzing pickup/drop off coordinates, fare amounts, passenger counts, and travel distances calculated via the Haversine formula.
Uber Fare Analysis & Distance Prediction 🚗
This repository contains a Python notebook (Google Colab) that performs Exploratory Data Analysis (EDA) and preprocessing on an Uber dataset of 200,000 trips to predict fare amounts based on pickup/dropoff locations and other key variables.

Key Features of the Project:
Data Cleaning & Handling: Dropped unnecessary index columns, handled missing values by imputing medians in dropoff coordinates, and filtered out anomalies (e.g., negative fare amounts and passenger overloading of more than 6 people).

Feature Engineering: Implemented the Haversine Formula from scratch to calculate the physical geodesic distance (in km) between pickup and dropoff points using latitude and longitude coordinates.

Temporal Feature Extraction: Extracted high-value features such as hour, day_of_week, and month from raw pickup_datetime to analyze peak hours and seasonal trends.

Exploratory Data Analysis (EDA): Visualized relationships (like Fare vs. Distance) using scatter plots via seaborn and matplotlib to identify ride patterns and pricing behavior.

Tech Stack Used:
Language: Python (Jupyter Notebook/Google Colab)

Libraries: pandas, numpy, matplotlib, seaborn

Tips:

Repository parameters select karte waqt Topics/Tags main ye keywords daal dena: uber-fare-prediction, data-science, haversine-formula, feature-engineering, eda, data-cleaning.
