# OIBSIP_05
# Sales Price Prediction

This project aims to predict the sales price of a product based on advertising budget spent on different media channels (TV, radio, newspaper).

## Dataset
The dataset used for this project is the `Advertising.csv` file, which contains data about advertising budgets and sales figures.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- matplotlib

You can install the required packages using the following command:
`pip install -r requirements.txt`


## Usage
1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook `sales_price_prediction.ipynb` to train and evaluate the model.
4. Use the `predict_sales` function to make predictions based on new input data.

## Model Evaluation
The model was evaluated using the R-squared metric, which measures the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Predictions
You can make predictions using the `predict_sales` function by providing the advertising budget for TV, radio, and newspaper.

