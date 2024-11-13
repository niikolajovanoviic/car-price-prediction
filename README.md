
# Analysis and Price Prediction of Used Renault Clio IV Cars

This project analyzes the price data for used **Renault Clio IV** models manufactured from 2012 to 2020. Using linear and polynomial regression models, it predicts prices based on the car's age.

## Contents
- [Data](#data)
- [Project Structure](#project-structure)
- [Results](#results)
- [License](#license)

## Data

The dataset contains the age (in years) and corresponding high and low prices for Renault Clio IV cars of various model years, excluding 2012 when Clio III was still in production.

```python
data = [
    [11,8000],[11,4999],  # Excludes 2012 due to Clio III production
    [10,7700],[10,4899],
    [9,8500],[9,5200],
    [8,8750],[8,4999],
    [7,9299],[7,6500],
    [6,10799],[6,3800],
    [5,11200],[5,6990],
    [4,10500],[4,6890]
]
```

## Project Structure

- **Data Setup**: Initializes data for the Renault Clio IV.
- **Linear Regression**: Analyzes linear depreciation over time and plots the results.
- **Polynomial Regression**: Fits a polynomial model to the data for more flexible predictions.
- **Price Prediction**: Predicts prices based on input age.

## Results

- **Annual Depreciation**: The model calculates the annual depreciation rate for Renault Clio IV.
- **Correlation Coefficient**: Shows the linear relationship strength between car age and price.
- **Polynomial Model Fit**: The polynomial regression provides an alternative model for predicting prices.

## License

This project is open-source and available under the MIT License.
