# Car Price Predictor

## Project Overview
This project builds a machine learning model to predict the selling prices of used cars. It uses features such as the car's age, present price, kilometers driven, fuel type, and transmission type to make predictions. The model employs linear regression and Lasso regression for analysis and performance evaluation.

## Features
- **Data Loading and Preprocessing**: Loading the car dataset and handling missing values.
- **Exploratory Data Analysis**: Visualizing and analyzing the distribution and relationships of features.
- **Model Training**: Using linear regression and Lasso regression for price prediction.
- **Model Evaluation**: Assessing model performance through metrics like mean absolute error and R² score.

## Technologies Used
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/parthdave333/car-price-predictor.git

2. Open the Jupyter Notebook:
   ```bash
      jupyter notebook Car_Price_Prediction.ipynb

3. Run the cells step-by-step to train and test the model.

   
## Dataset
The dataset includes:

Car_Name: The model name of the car.
Year: The year the car was purchased.
Selling_Price: The price at which the car is being sold (target variable).
Present_Price: The car's current market price.
Kms_Driven: The number of kilometers the car has been driven.
Fuel_Type: Type of fuel used (e.g., Petrol, Diesel, CNG).
Seller_Type: Whether the seller is a dealer or an individual.
Transmission: Type of transmission (e.g., Manual, Automatic).
Owner: Number of previous owners.

## Results
The trained models are evaluated using performance metrics, ensuring accurate prediction of car prices.

## Future Improvements
Exploring other regression algorithms for better performance.
Adding more features for a more comprehensive analysis.
Tuning hyperparameters for optimization.

## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.
