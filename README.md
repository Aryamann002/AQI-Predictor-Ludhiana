# Air Quality Forecasting for Ludhiana - AI Capstone Project (Class 12 CBSE)

## Overview

This repository contains all the code, data, models, and documentation for our AI capstone project focused on air quality forecasting in Ludhiana, India. As part of our Class 12 CBSE curriculum, we set out to tackle the problem of air pollution by developing an AI model that provides accurate and localized forecasts. This project utilizes machine learning to provide insights into the current and predicted air quality by using historical data. This is meant to be an educational tool, to help people make more informed decisions about their exposure to PM2.5 and PM10 pollutants, particularly in highly polluted cities such as Ludhiana.

## Team Members

*   **Aryamann Sharma:** Project Leader, AI Specialist, Prototype Builder, Coder, Tester
*   **Madhav Rana:** Data Expert, Video Producer, Tester
*   **Niyamat:** Information Researcher, Marketing, Communications Leader

## Project Goals

*   Develop an AI-powered system to predict PM2.5 and PM10 levels in Ludhiana.
*   Provide hourly air quality forecasts for the next 12-24 hours.
*   Showcase how machine learning can be used to address real-world issues.
*   To learn practical data analysis and machine learning skills.
*   To educate the community about air pollution by using technology.

## Technologies Used

*   **Programming Language:** Python
*   **Libraries:**
    *   pandas: For data manipulation and analysis.
    *   scikit-learn: For implementing machine learning models (RandomForest, LSTM).
    *   joblib: For saving and loading trained models.
    *   matplotlib & seaborn: For creating visualizations.
*   **AI Tools:**
    * Teachable Machine (for initial prototyping).

## Data

*   **Data Sources:**
    *   https://www.kaggle.com/datasets/abhisheksjha/time-series-air-quality-data-of-india-2010-2023
*   **Data Used:** Historical hourly air quality data (PM2.5, PM10, and other relevant pollutants), date and time stamps
* **Preprocessing:**
    *  Date and time conversion to DateTime objects
    * Feature engineering for time series analysis (hour, day, month).
    * Imputation of missing data using KNN Imputer

## Project Structure

*   `data/`: Contains our raw dataset, and the final preprocessed dataset (`PB003.csv`, `PB003_preprocessed.csv`).
*   `models/`: Includes the trained machine learning models (PM2.5 and PM10 models, `.joblib` files).
*   `notebooks/`: Any Jupyter Notebook that are relevant to the project.
*  `scripts/`: Includes all relevant python scripts
    * `training.py`: Implements the data preprocessing steps and trains the machine learning models.
    * `prediction.py`: Creates predictions of future air pollution values and visualizes these results.
    * `eval_pm10.py`:  Provides the evaluation for the PM10 model, including visualizations and metrics.
    * `eval_pm25.py`: Provides the evaluation for the PM2.5 model, including visualizations and metrics.

## How to Run the Code

1.  **Clone the Repository:**
    ```bash
    git clone [your repository url]
    ```

2.  **Install Dependencies:**
    ```bash
    pip install pandas scikit-learn joblib matplotlib seaborn
    ```

3.  **Run the Scripts:**
     *   Run `training.py` to train and create new models and preprocessing.
    *  Run `eval_pm10.py` to see the results of the PM10 model.
    *  Run `eval_pm25.py` to see the results of the PM2.5 model.
     *  Run `prediction.py` to generate a prediction and visualization.
  4.  All files should now be present in your local folder as shown in the image we have discussed.

## Key Findings

*   Our model demonstrates a good level of performance in predicting PM2.5 and PM10 levels. (Include some key metrics here from your `evaluation.py` script)
*   Our analysis shows that air pollution levels in Ludhiana tend to be higher during the winter months. (Explain this more using your visualizations).
*  You can look into the specific visualizations in the scripts to learn more about our models performance.
*  The visualization in the `prediction.py` shows the general trend of PM2.5 and PM10 for the month of November 2025.

## Team Learnings

*   We have learned the importance of balancing technical needs with user needs.
*   We have understood the importance of data collection, processing and ethical data usage.
*   We have learned the importance of team work in completing an AI project and the impact of good communication.
*   We have realized the potential for AI to address real-world problems, and have been inspired to find ways to create a positive social impact.

## Limitations

*   The model is trained on data from 2017-2023 and does not include real-time sensor data.
*   The predictions may not be highly accurate for specific areas, or for days outside the training dataset.
*   The model's prediction may not be as reliable if the data from the next year is drastically different from what was seen in the previous years.

## Future Improvements

*   Integrate real-time sensor data for more accurate and localized forecasts.
*   Expand forecasting periods.
*   Develop a user-friendly mobile app for better accessibility.
*  Incorporate more data such as data on pollution sources.
*  Create a user community to allow users to share information and tips.
