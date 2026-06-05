# Algerian Forest Fire Prediction System

An end-to-end Machine Learning web application that predicts the Fire Weather Index (FWI) using meteorological and environmental data from the Algerian Forest Fires Dataset.

The project combines data analysis, feature engineering, machine learning, and web deployment to provide real-time wildfire risk assessment through an interactive Flask application.

---

## Project Highlights

- Performed Data Cleaning and Exploratory Data Analysis (EDA)
- Applied Feature Engineering and Data Preprocessing
- Trained and compared multiple regression models
- Implemented Feature Scaling using StandardScaler
- Built a Flask-based web application for real-time predictions
- Designed an interactive user interface using HTML and CSS
- Added wildfire risk classification for better interpretability

---

## Machine Learning Models Evaluated

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

### Final Model Selected

**Ridge Regression**

Selected based on its performance and generalization capability on unseen data.

---

## Input Features

The model uses the following environmental parameters:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rainfall
- FFMC
- DMC
- ISI
- Fire Class
- Region

---

## Risk Assessment Levels

| FWI Score | Risk Level |
|------------|------------|
| < 5 | Low Risk |
| 5 - 15 | Moderate Risk |
| 15 - 30 | High Risk |
| > 30 | Extreme Risk |

---

## Tech Stack

### Machine Learning

- Python
- NumPy
- Pandas
- Scikit-Learn

### Web Development

- Flask
- HTML
- CSS

### Version Control

- Git
- GitHub

---

## Project Workflow

Dataset → Data Cleaning → EDA → Feature Engineering → Feature Scaling → Model Training → Model Evaluation → Model Serialization → Flask Deployment → Wildfire Risk Prediction

---

## Key Features

- Real-time Fire Weather Index Prediction
- Interactive Web Interface
- Multiple Model Comparison
- Risk Classification System
- End-to-End Machine Learning Pipeline

---

## Author

**Aniket Pattnaik**

Machine Learning & Data Science Enthusiast