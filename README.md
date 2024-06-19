# Car Price Prediction Model

## Overview
This project focuses on predicting car prices based on various attributes using machine learning techniques. The dataset used contains information about cars including their name, company, year of manufacture, kilometers driven, fuel type, and price.

## Dataset
The dataset (`quikr_car.csv`) was sourced from [Quikr](https://www.quikr.com/), a classifieds platform in India, and has been cleaned and preprocessed for analysis. Key steps included handling missing values, converting data types, and cleaning inconsistent entries in the data.

## Project Structure
The project is structured as follows:
- **Data Cleaning and Preparation**: Initial cleaning steps to ensure the dataset is suitable for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing relationships between variables to understand how they affect car prices.
- **Modeling**: Utilizing linear regression to build a predictive model for car prices.
- **Model Evaluation and Selection**: Evaluating the model using metrics such as R-squared and selecting the best-performing model.
- **Model Deployment**: Saving the final model using pickle for future predictions.

## Files
- `Car_Price_Prediction.ipynb`: Jupyter Notebook containing the entire data analysis, modeling, and evaluation process.
- `Cleaned_Car_data.csv`: Cleaned dataset used for modeling.
- `LinearRegressionModel.pkl`: Serialized model ready for deployment.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Conclusion
This project demonstrates how machine learning can be applied to predict car prices based on various attributes. It provides a structured approach to data cleaning, exploratory analysis, model development, and deployment.
