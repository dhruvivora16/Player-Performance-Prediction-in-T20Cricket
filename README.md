# Player Performance Prediction in T20 Cricket

## Overview

This project focuses on predicting cricket player performance in T20 matches using Machine Learning techniques and historical cricket data. The system analyzes player statistics, recent performance trends, opponent information, venue conditions, and match-related factors to forecast the number of runs a player is likely to score in upcoming matches.

The project combines data preprocessing, feature engineering, machine learning modeling, and data visualization to build an intelligent cricket analytics system.

---

## Objectives

* Predict player performance using historical cricket data
* Analyze player consistency and recent form
* Apply machine learning algorithms for sports analytics
* Generate meaningful insights using data visualization
* Support data-driven decision-making in cricket

---

## Dataset

The dataset contains ball-by-ball T20 cricket match data stored in JSON format. The data includes:

* Player names
* Runs scored
* Balls faced
* Strike rate
* Match venue
* Opponent team
* Match information

The raw data is transformed into structured tabular datasets for machine learning analysis.

---

## Project Workflow

### 1. Data Collection

* Collected historical T20 cricket match data
* Combined multiple JSON match files
* Organized player and match-level statistics

### 2. Data Preprocessing

* Removed missing and inconsistent values
* Converted JSON data into tabular format
* Aggregated ball-by-ball records into player-level statistics

### 3. Feature Engineering

Created important features such as:

* Previous match runs
* Previous strike rate
* Average runs of last 3 matches
* Average runs of last 5 matches
* Opponent encoding
* Venue encoding
* Match pressure indicators

### 4. Model Training

The project uses:

* Random Forest Regressor

The model is trained to learn patterns between historical player performance and future outcomes.

### 5. Prediction

The trained model predicts:

* Expected player runs
* Performance trends
* Player consistency

### 6. Model Evaluation

Evaluation metrics used:

* Mean Absolute Error (MAE)
* R² Score

Model Performance:

* MAE ≈ 11.75
* R² Score ≈ 0.50

---

## Exploratory Data Analysis (EDA)

The project includes:

* Run distribution analysis
* Player trend analysis
* Feature importance analysis
* Actual vs Predicted comparisons
* Strike rate analysis
* Venue-based performance analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Visualizations Included

* Actual vs Predicted Runs
* Feature Importance Graph
* Distribution of Player Runs
* Top Run Scorers
* Strike Rate Analysis
* Runs vs Strike Rate
* Venue Performance Analysis

---

## Project Structure

```text
Cricket-Player-Performance-Prediction
│
├── notebooks/
│   └── player_performance_prediction.ipynb
│
├── reports/
│   └── player_performance_prediction.pdf
└──
```

---

## Key Findings

* Recent player performance is the strongest predictor of future performance
* Feature engineering significantly improves prediction accuracy
* Random Forest performs effectively for cricket analytics
* Machine learning provides better insights compared to traditional statistical methods

---

## Future Scope

Future improvements can include:

* Real-time match prediction
* Weather and pitch condition analysis
* Deep learning models
* Player-specific prediction systems
* Web-based interactive dashboard
* Live IPL analytics integration

---

## Applications

* Team selection support
* Match strategy planning
* Player performance evaluation
* Cricket analytics research
* Sports data science projects

---

## Developed By

Dhruvi Vora
