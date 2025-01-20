# Uber Fare Prediction

## Description  
This project focuses on predicting Uber ride fares using a machine learning model—**Random Forest Regressor**. The goal is to estimate fares based on ride distance, ride category, and time, showcasing how historical data can be used for better fare predictions. This project highlights the potential of machine learning in pricing analysis for users and businesses.

---

## Features
- Predicts fares based on ride details such as distance and category.
- Analyzes and visualizes model accuracy with various metrics and graphs.
- Leverages historical ride data to train and evaluate the machine learning model.

---

## Technologies Used
- **Python**: Programming language for data processing and modeling.
- **pandas & numpy**: For efficient data manipulation and analysis.
- **scikit-learn**: For building and evaluating machine learning models.
- **geopy**: To calculate distances between pickup and drop-off points.
- **matplotlib & seaborn**: For creating visualizations.

---

## Dataset  
The dataset includes:
- **Start date/time** and **end date/time**  
- **Pickup and drop-off locations**  
- **Distance traveled**  
- **Ride category**  
- **Ride purpose**  
- **Fare** (target variable)

Place the dataset in the specified directory as per the code instructions.

---

## Setup and Installation
### Prerequisites
- Python 3.x installed
- Libraries listed in `requirements.txt`

### Steps
1. Clone the repository:  
   ```bash
   git clone https://github.com/poorvashetye/Uber_Fare_Prediction.git
   cd Uber_Fare_Prediction
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the script:
Execute the Python script or Jupyter Notebook to train the model and view predictions.

## Model Performance
The Random Forest Regressor performed exceptionally well:
Mean Absolute Error (MAE): 0.7
Mean Squared Error (MSE): 0.55
Root Mean Squared Error (RMSE): 0.74
R² Score: 0.99
The model explains 99% of the variance in fare predictions.

## Usage
1. Load your dataset in the correct format.
2. Run the provided script to train the model.
3. Input ride details (e.g., distance) to get fare predictions.

## Future Improvements
Add features like traffic conditions or peak-hour pricing for better accuracy.
Optimize the model with hyperparameter tuning.
Create a user-friendly interface for real-time fare prediction.
