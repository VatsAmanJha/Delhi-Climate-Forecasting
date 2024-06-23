# Delhi Climate Forecasting

This repository contains the code and analysis for forecasting Delhi's climate using historical climate data and the Prophet forecasting model.

## Overview

The project aims to analyze and forecast temperature trends in Delhi based on historical climate data. The analysis includes exploratory data analysis (EDA) to understand seasonal patterns, correlations between temperature and other weather variables, and forecasting using the Prophet library.

## Project Structure

- `archive/`: Contains the historical climate data CSV files (`DailyDelhiClimateTrain.csv` and `DailyDelhiClimateTest.csv`).
- `Delhi_Climate_Forecasting.ipynb`: Jupyter Notebook containing the code for data preprocessing, EDA, and forecasting.
- `README.md`: This file providing an overview of the project and repository..

## Installation

To run the code locally, you need Python and the following libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- plotly
- Prophet

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib plotly prophet
```

## Usage

1. Clone the repository:

```bash
git clone git remote add origin https://github.com/VatsAmanJha/Delhi-Climate-Forecasting.git
```

2. Navigate to the project directory:

```bash
cd delhi-climate-forecasting
```

3. Open and run the Jupyter Notebook `Delhi_Climate_Forecasting.ipynb` to replicate the analysis and forecasts.

## Results

- The analysis provides insights into Delhi's climate trends, seasonal patterns, and correlations between temperature, humidity, and wind speed.
- The forecasting models (uni-variate and multi-variate) predict future temperature trends based on historical data, providing valuable information for climate prediction and planning.