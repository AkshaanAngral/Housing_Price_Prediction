# Housing Price Prediction

## Project Description

This project aims to predict housing prices based on various features, including area, main road proximity, basement availability, and furnishing status. It involves several steps:

1. **Data Loading**: The data is loaded from a CSV file using pandas.

2. **Data Exploration**: The data is explored to understand its structure, check for missing values, and gain insights into the distribution of features.

3. **Baseline Prediction**: A baseline prediction is created using the mean price as the predicted value for all instances.

4. **Linear Regression Model**: A Linear Regression model is trained using the area feature to predict housing prices.

5. **Feature Engineering**: Categorical features are one-hot encoded to be used in the Linear Regression model.

6. **Enhanced Model**: A new model is trained using multiple features, including one-hot encoded categorical variables.

7. **Model Evaluation**: The performance of both models is evaluated using the Mean Absolute Error (MAE).

## Dependencies

This project requires the following Python libraries:

- pandas
- matplotlib
- sklearn
- category_encoders


## Data Description

The "Housing_test_data.csv" file contains the following columns:

- `area`: The area of the property in square feet.
- `price`: The price of the property in the respective currency.
- `mainroad`: Whether the property is located near the main road (1 for yes, 0 for no).
- `basement`: Whether the property has a basement (1 for yes, 0 for no).
- `furnishingstatus`: The furnishing status of the property (furnished, semi-furnished, unfurnished).

## Usage

1. Ensure you have installed the required dependencies mentioned above.
2. Clone this repository to your local machine.
3. Place the "Housing_test_data.csv" file in the same directory as the code files.
4. Run the "housing_analysis.ipynb" Jupyter Notebook or "housing_analysis.py" Python script to execute the analysis and modeling.

## Conclusion

This project demonstrates how to use a Linear Regression model to predict housing prices based on various features. It compares the baseline prediction with the model's performance after feature engineering. The results provide insights into the relationship between housing prices and the area of the property.

## Acknowledgment

The dataset used in this project is sourced from [www.Kaggle.com](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data).


