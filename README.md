# DataHackathon

# College Data Hackathon: Predicting Taxi Demand

Welcome to the repository for the College Data Hackathon, where we tackled the intriguing challenge of predicting taxi demand in New York City. Leveraging a dataset containing information about taxi drivers and historical ride data, our team embarked on an exciting journey to develop a predictive model capable of estimating the required number of taxis for specific dates and hours.

## Hackathon Overview

- **Event:** College Data Hackathon on Taxi Demand Prediction
- **Date:** 11-12 May 2023
- **Team Members:** Tal Krispin
                    Yuval Chabra
                    Matan Dekel

## Problem Statement

The hackathon presented us with a real-world problem: given a comprehensive dataset with details about taxi drivers in New York and historical ride data, we were tasked with building a model that could accurately predict the number of taxis needed at any given date and hour. The goal was to utilize data analysis and machine learning to optimize taxi fleet management and improve transportation efficiency.

## Approach

Our approach can be summarized in a few steps:

1. **Data Exploration:** We began by thoroughly exploring the dataset, gaining insights into its structure and identifying key variables relevant to taxi demand prediction.

2. **Feature Engineering:** We engineered meaningful features from the data, including factors like the date and hour, which were crucial for accurate predictions.

3. **Model Selection:** After careful consideration, we selected the Random Forest algorithm as our model of choice due to its ability to handle complex relationships in the data.

4. **Model Training and Evaluation:** We split the dataset into training and testing sets, trained the Random Forest model, and fine-tuned its parameters to achieve the best predictive performance.

5. **Prediction:** With a trained model in place, we were able to make predictions about taxi demand for specific dates and hours, which could aid in resource allocation.

## Repository Structure

- `data/`: This directory contains the provided dataset in Excel (".xlsx") format.

- `notebooks/`: Explore Jupyter Notebook files in this directory to see our data exploration, feature engineering, model training, and prediction steps.

- `model/`: Here, you'll find the serialized version of the trained Random Forest model, ready for potential deployment.




