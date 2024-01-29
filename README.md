# Recommendation-Engine-Creation-Challenge
# Comedy TV Recommendation System

## Overview
This project aims to develop a recommendation system for a new Abuja-based online Comedy TV. The goal is to optimize the platform's content using customer ratings, which are collected from popular comedy shows held in various parts of Nigeria. The company seeks to understand user preferences, identify content that aligns with business objectives, and provide a personalized viewing experience for its growing community of online and offline followers.

## Problem Statement
The primary task is to predict the ratings for specific comedy events per individual based on their ratings for another set of comedy. This predictive model will serve as the foundation for the recommendation system, allowing the platform to deliver content that resonates with each viewer.

## Dataset
- The dataset includes anonymous ratings provided by followers of the comedy online station.
- Ratings range from -5 to 5, reflecting the users' sentiments towards the comedy content.
- Each entry in the dataset corresponds to a combination of a user and a specific comedy event.

## Methodology
1. **Exploratory Data Analysis (EDA):**
   - Understand the distribution of ratings.
   - Analyze summary statistics and visualize the data to gain insights.

2. **Data Preprocessing:**
   - Handle missing values, if any.
   - Encode categorical variables and perform feature engineering.

3. **Model Training:**
   - Experiment with different regression models (e.g., Random Forest, Linear Regression, Gradient Boosting) to predict user ratings.
   - Fine-tune hyperparameters for optimal performance.

4. **Feature Engineering:**
   - Explore additional features such as comedian popularity and interaction features to enhance model accuracy.

5. **Evaluation:**
   - Use Root Mean Squared Error (RMSE) as the evaluation metric to assess the model's predictive performance.

6. **Recommendation System Integration:**
   - Incorporate the trained model into the platform's recommendation system to deliver personalized content suggestions.

## Files
- `train.csv`: Training dataset containing user ratings for comedy events.
- `test.csv`: Test dataset for predicting user ratings on new comedy events.

## Instructions for Use
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Explore the Jupyter notebooks for detailed analyses and model development.
4. The trained models can be found in the `models` directory.
5. Use the provided scripts for making predictions on new data.

## Results
- Model performance can be assessed using the provided evaluation metric (RMSE).
- The final model's predictions on the test set are available in the `submission.csv` file.

## Continuous Improvement
- Continuous monitoring and refinement of the recommendation system based on user feedback and evolving content preferences.
- Regular updates to the model and feature engineering strategies for enhanced accuracy.

Click on the link to go to main project file https://github.com/Ndo71292/Recommendation-Engine-Creation-Challenge/blob/main/Comedy%20Recommendation%20Engine.ipynb

Feel free to explore the codebase and reach out for any questions or collaborations!
