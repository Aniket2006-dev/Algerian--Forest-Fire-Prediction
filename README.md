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
## Application screenshots

<img width="959" height="508" alt="Screenshot 2026-06-06 015410" src="https://github.com/user-attachments/assets/cb68d046-3b9d-42a6-b717-c7bd3950d8a4" />

<img width="959" height="508" alt="Screenshot 2026-06-06 015141" src="https://github.com/user-attachments/assets/948eddd7-352d-4363-885b-aecc2141f3b7" />

<img width="959" height="506" alt="Screenshot 2026-06-06 015216" src="https://github.com/user-attachments/assets/f368ef02-a8e6-4290-b576-569e8a07ad90" />

<img width="959" height="508" alt="Screenshot 2026-06-06 015322" src="https://github.com/user-attachments/assets/a28cce22-0a60-4729-81f6-ce7b398f230f" />


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

## Live Application

[Open Live Demo](http://algerian-forest-fire-prediction-env-1.eba-2qbsypdm.ap-southeast-2.elasticbeanstalk.com)


## Author

**Aniket Pattnaik**

Machine Learning & Data Science Enthusiast
