📖 Introduction

The Crop Recommendation System leverages machine learning algorithms to analyze various parameters such as soil nutrients, temperature, humidity, pH, and rainfall. By processing this data, the system predicts the most suitable crop to cultivate in a given area, thereby enhancing agricultural productivity.​
GitHub

✨ Features

Data Input: Accepts inputs for Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall.

Machine Learning Models: Implements algorithms like Random Forest, Decision Tree, and K-Nearest Neighbors for prediction.

User-Friendly Interface: Provides an intuitive interface for users to input data and receive crop recommendations.

Performance Metrics: Displays accuracy and other relevant metrics for model evaluation.​

📊 Dataset

Source: Kaggle - Crop Recommendation Dataset

Attributes:

N: Ratio of Nitrogen content in soil

P: Ratio of Phosphorous content in soil

K: Ratio of Potassium content in soil

Temperature: Temperature in degree Celsius

Humidity: Relative humidity in %

pH: pH value of the soil

Rainfall: Rainfall in mm

Label: Crop to be recommended​

🛠 Technologies Used

Programming Language: Python

Libraries:

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Web Framework: Flask (for deploying the model)​

📈 Model Performance

The system evaluates multiple machine learning models to determine the most accurate predictor for crop recommendation. Based on the evaluation:​
GitHub

Random Forest: Achieved an accuracy of 95% on the test set.

Decision Tree: Achieved an accuracy of 91% on the test set.

K-Nearest Neighbors: Achieved an accuracy of 88% on the test set.
