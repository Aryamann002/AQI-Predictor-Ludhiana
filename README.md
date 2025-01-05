# Air Quality Forecasting for Ludhiana - AI Capstone Project (Class 12 CBSE)

## Overview

This repository contains the code, data, and trained models for our AI capstone project focused on air quality forecasting in Ludhiana, India. As part of our Class 12 CBSE curriculum, we aimed to create an AI model to predict PM2.5 and PM10 levels, using historical data. We have used machine learning to create a tool that can provide localized and real-time predictions of air quality, to help the community make more informed decisions about their exposure to air pollution.

## Team Members

*   **Aryamann Sharma:** Project Leader, AI Specialist, Prototype Builder, Coder, Tester
*   **Madhav Rana:** Data Expert, Video Producer, Tester
*   **Niyamat:** Information Researcher, Marketing, Communications Leader

## Project Goals

*   Develop an AI-powered system to forecast PM2.5 and PM10 levels in Ludhiana.
*   Utilize historical air quality data to train a machine learning model.
*   Provide practical, accurate information about air pollution to the community.
*  Document the process of creating an AI project, from start to finish.

## Technologies Used

*   **Programming Language:** Python
*   **Libraries:**
    *   pandas
    *   scikit-learn
    *   joblib
    *   matplotlib
    *   seaborn
  

## Data

*   **Data Sources:**
    *  (https://www.kaggle.com/datasets/abhisheksjha/time-series-air-quality-data-of-india-2010-2023)
*   **Data Used:** Historical hourly air quality data including PM2.5 and PM10 concentrations, with date and time stamps.
*  **Data Preprocessing:**
    * Date conversion.
    * Feature engineering for time series analysis.
    * Imputation using KNN Imputer.

## Repository Structure

*   `/`:
    *   `PB003.csv`: Raw dataset.
    *   `PB003_preprocessed.csv`: Preprocessed dataset.
    *    `trained_model_PM10.joblib`: Trained model for PM10 forecasting
    *   `trained_model_pm25.joblib`: Trained model for PM2.5 forecasting
    *   `training.py`: Python script for data preprocessing and model training.
      *    `prediction.py`: Python script for making predictions and generating visualizations.
      *  `eval_pm10.py`: Python script for evaluation and testing of PM10 model.
      *  `eval_pm25.py`: Python script for evaluation and testing of PM2.5 model.
     * `november_2025_predictions.csv`: Predictions of PM2.5 and PM10 for November 2025.
    *   `PB003_predictions.csv`: Model output file.
      *   `PB003_features_pm10.joblib`: Saved features for PM10 model training
    *   `PB003_features_pm25.joblib`: Saved features for PM2.5 model training
    *   `PB003_preprocessed_df.joblib` Preprocessed dataframe file.


## Key Findings

*   The model is able to achieve a good level of accuracy in prediction of PM2.5 and PM10. (Include your actual metrics from your eval scripts here)
*   The visualizations in the `eval_pm10.py` and the `eval_pm25.py` show that PM2.5 and PM10 levels in Ludhiana are very high in the winter months, from 2017 to 2023.
 *   The visualization in `prediction.py` shows a general trend of PM2.5 and PM10 levels in November 2025.

## Team Learnings

*   We gained a deeper understanding of the challenges involved in creating AI projects, including data processing, model training, and testing.
*   We understand the importance of effective collaboration in creating a useful AI solution.
*   We now realize the potential of technology to create a positive social impact.
*   We are now better aware of the limitations of AI, and what is required to make it better.

## Limitations

*   Our model is trained on historical data and may not be as accurate on new situations.
*  The synthetic data used for prediction is created by using monthly averages, and is not as reliable as models that have been trained with the relevant data.
*   The evaluation of the model is based on metrics and visual interpretation, and there is a limited method to account for user experience.

