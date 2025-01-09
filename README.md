# Storm Database Analysis and Prediction

This repository contains files and resources for analyzing and predicting patterns in hurricane data using historical records and machine learning techniques. The project employs data cleaning, exploratory analysis, and LSTM (Long Short-Term Memory) models to predict future hurricane trends.

## Files in this Repository

- **atlantic.csv**: Historical hurricane data for the Atlantic region.
- **pacific.csv**: Historical hurricane data for the Pacific region.
- **cleaning.ipynb**: A Jupyter Notebook for cleaning and preprocessing the hurricane data.
- **LSTM.ipynb**: A Jupyter Notebook implementing the LSTM model for hurricane prediction.

## Dataset Description

The data is sourced from the NOAA Hurricane Database (HURDAT2) and contains detailed historical information on hurricanes and tropical storms in the Atlantic and Pacific basins. Key attributes include:
- **Storm Name**: The name of the storm.
- **Storm ID**: A unique identifier for each storm.
- **Date**: Timestamp of the observation.
- **Time**: Time of the observation.
- **Record Identifier**: Special status of the observation (e.g., landfall, maximum intensity).
- **System Status**: Classification of the storm (e.g., hurricane, tropical storm).
- **Maximum Wind Speed**: Recorded wind speed in knots.
- **Minimum Pressure**: Minimum central pressure in millibars.
- **Coordinates**: Storm's latitude and longitude.

The dataset can be accessed at [Kaggle - NOAA Hurricane Database](https://www.kaggle.com/datasets/noaa/hurricane-database/data).

## Project Objectives

1. Clean and preprocess the hurricane data for further analysis and modeling.
2. Conduct exploratory data analysis (EDA) to uncover trends and patterns in the data.
3. Use an LSTM neural network to predict hurricane behavior based on historical data.

## Key Findings

- Significant patterns in hurricane activity were identified, such as peak hurricane seasons and intensities.
- The cleaned dataset ensures consistency and accuracy, addressing issues like missing or duplicate data.
- LSTM models were trained to predict hurricane characteristics with promising accuracy, showcasing the potential for machine learning in weather prediction.

## How to Use

1. **Data Cleaning**: Run the `cleaning.ipynb` notebook to preprocess the raw hurricane data.
2. **Prediction**: Use the `LSTM.ipynb` notebook to train and evaluate the LSTM model for hurricane prediction.
3. **Datasets**: The `atlantic.csv` and `pacific.csv` files serve as the primary data sources for the project.

## Tools and Libraries

The following Python libraries were used in this analysis:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `tensorflow`
- `keras`
- `scikit-learn`

## Author

**Name**: [Your Name]  
**Affiliation**: [Your Institution/Organization]  
**Project Submission Date**: [Submission Date]

**Source**:
> NOAA Hurricane Database. Available at [Kaggle](https://www.kaggle.com/datasets/noaa/hurricane-database/data).
