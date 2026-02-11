# Airline Customer Booking Prediction

## Project Overview
This project builds a machine learning model to predict whether a customer will complete a flight booking. The goal is to help airlines identify high-intent customers and improve marketing strategies.

## Objective
Predict booking completion using customer booking data and compare multiple machine learning models to select the best-performing one.

## Dataset
The dataset contains customer booking information including:
- Number of passengers
- Sales channel
- Trip type
- Purchase lead time
- Flight duration
- Extra services
- Booking origin
- Booking completion status (target variable)

## Project Workflow
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Model training:
   - Logistic Regression
   - Decision Tree
   - Random Forest
5. Model evaluation and comparison
6. Feature importance analysis

## Results
- Random Forest achieved the best performance based on F1-score.
- Customer behavior features were the strongest predictors.
- Key features:
  - Purchase lead time
  - Flight duration
  - Total extras
  - Route
  - Booking origin

## Key Insight
Customers selecting additional services and traveling on longer or high-value routes were more likely to complete bookings.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
ba-customer-booking-prediction/
│
├── data/
├── notebooks/
│   └── analysis.ipynb
├── outputs/
│   └── feature_importance.png
├── presentation/
│   └── BA_prediction_summary.pptx
├── requirements.txt
└── README.md

## Author
**Yashvardhan Shah**  
B.Tech Computer Science (AI & ML)  
GitHub: https://github.com/yashvardhanshah
