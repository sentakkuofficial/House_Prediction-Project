# House_Prediction-Project   :derelict_house:
Students will able to predict future house prices

In this project, we aim to forecast future New York housing prices. To do this, we’ll combine economic data from the Federal Reserve with housing data from Zillow. After merging and preparing the dataset, we’ll train a Random Forest model to predict whether house prices will go up or down.

We’ll evaluate the model’s performance using backtesting and then refine it by adding new features to improve accuracy.

This project can also be adapted to focus on housing markets in specific U.S. metro areas.

### Project Steps :dart:
* Load the datasets
* Clean and combine the data
* Build an initial machine learning model and evaluate its performance
* Improve the model’s accuracy
* Perform diagnostics to identify further improvements
## Code   :desktop_computer:

The full implementation for this project is available [here](https://github.com/sentakkuofficial/House_Prediction-Project).

File Overview
prices.ipynb – Jupyter Notebook containing all the code for the project
Local Setup
Installation

To run this project locally, install the following:

* Jupyter Notebook
* Python 3.8 or higher

* Required Python Packages:

   * pandas

   * yfinance

   * scikit-learn
## Data :mag_right:

You’ll need several CSV files to run this project. These are included in the repository, but you can also download updated versions:

Federal Reserve Data
* CPI dataset: [CPIAUCSL.csv](https://fred.stlouisfed.org/series/CPIAUCSL)

* Rental vacancy rate: [RRVRUSQ156N.csv](https://fred.stlouisfed.org/series/RRVRUSQ156N)

* Mortgage interest rates: [MORTGAGE30US.csv](https://fred.stlouisfed.org/series/MORTGAGE30US)

[Zillow Data](https://www.zillow.com/research/data/)

* ZHVI (weekly raw data): Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_month.csv

* Median sale price (weekly, all homes): Metro_median_sale_price_uc_sfrcondo_week.csv
