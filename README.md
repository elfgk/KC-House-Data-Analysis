# KC House Data Analysis

This project focuses on analyzing house price data for King County, Washington. The goal is to explore the dataset, perform data cleaning, feature engineering, and build a machine learning model to predict house prices.
Dataset: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

## Project Overview

The dataset used in this project contains information about homes sold in King County, including house features such as square footage, number of bedrooms, location, and more. This project includes the following steps:

1. **Exploratory Data Analysis (EDA):**
   - Visualizing the data to understand trends, distributions, and correlations.
   - Identifying missing values and outliers in the data.

2. **Data Preprocessing:**
   - Cleaning the data by handling missing values, encoding categorical variables, and scaling numerical features.

3. **Feature Engineering:**
   - Creating new features that can improve model performance.

4. **Modeling:**
   - Building machine learning models (such as linear regression, decision trees, etc.) to predict house prices.

5. **Model Evaluation:**
   - Evaluating models using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Dataset

The dataset used in this project contains information about houses sold in King County, WA. It includes the following features:

- `id`: Unique ID for each house
- `date`: Date when the house was sold
- `price`: Price of the house
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `sqft_living`: Square footage of the house
- `sqft_lot`: Square footage of the lot
- `floors`: Number of floors in the house
- `waterfront`: Whether the house has a waterfront view (1 if true, 0 if false)
- `view`: Quality of the view (a rating from 0 to 4)
- `condition`: Condition of the house (a rating from 1 to 5)
- `grade`: Grade of the house (a rating from 1 to 13)
- `sqft_above`: Square footage of the house above ground
- `sqft_basement`: Square footage of the basement
- `yr_built`: Year the house was built
- `yr_renovated`: Year the house was renovated
- `zipcode`: ZIP code of the house's location

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: For machine learning models and evaluation.

## Getting Started

To run the analysis on your local machine, follow these steps:

1. Clone or download the repository:

   ```bash
   git clone https://github.com/elfgk/KC-House-Data-Analysis.git
  ```

2. Install the required Python libraries.
3. Open the kc-house.ipynb Jupyter notebook and follow the steps.

