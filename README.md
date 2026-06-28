# Restaurant Rating Prediction

## Project Overview
This project predicts restaurant ratings using Machine Learning. The dataset was cleaned, preprocessed, and used to train a Random Forest Regressor model.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- VS Code
- Jupyter Notebook

## Project Structure
Restaurant_Rating_Prediction/
│
├── dataset/
│   └── Dataset.csv
├── notebook/
│   └── Restaurant_Rating_Prediction.ipynb
├── models/
│   └── restaurant_rating_model.pkl
├── output/
│   └── processed_restaurant_data.csv
└── README.md

## Steps Performed
- Loaded the dataset
- Cleaned and preprocessed the data
- Removed unnecessary columns
- Encoded categorical features
- Split data into training and testing sets
- Trained a Random Forest Regressor
- Evaluated the model using MAE, MSE, RMSE, and R² Score
- Saved the trained model and processed dataset

## Model Performance
- Mean Absolute Error (MAE): 0.194
- Mean Squared Error (MSE): 0.088
- Root Mean Squared Error (RMSE): 0.296
- R² Score: 0.962

## Author
Greeta Jitson
