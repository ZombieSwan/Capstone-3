![image](https://github.com/ZombieSwan/Capstone-3/assets/128863293/dc08a28e-2ea0-4327-a7d8-2087904b2706)




# NASDAQ 100 Trend Classification: Machine Learning's Approach to Identifying Major Turning Points

## Introduction
This project develops a classification model using machine learning to forecast significant peaks and valleys in the NASDAQ 100 index. Our approach utilizes broad economic and market indicators to identify major turning points in the index for the period from 2007 to 2023.

## Objectives
The primary objective is to create a machine learning model that:
- Accurately predicts substantial movements in the NASDAQ 100 index.
- Leverages diverse economic indicators and market data for predictions.
- Assists investors in making informed decisions based on model forecasts.

## Data Sources
Data has been sourced from reputable financial databases and platforms, including:
- Yahoo Finance
- NASDAQ
- Federal Reserve Economic Data (FRED)

## Methodology
The methodology adopted for this project includes:
- **Data Smoothing**: Applying a 10-day moving average to the data to reduce noise and emphasize longer-term trends.
- **Peak and Valley Detection**: Utilizing SciPy's `find_peaks` function to identify significant peaks and valleys in the index.

- ![image](https://github.com/ZombieSwan/Capstone-3/assets/128863293/79958f1b-c652-4001-86cc-41249ba76a4b)


The project's cornerstone is the LSTM (Long Short-Term Memory) model, which was selected for its ability to effectively capture time-series patterns and temporal dependencies crucial for trend classification. The model has undergone careful training with the following strategies to ensure robustness and accuracy:

- **Early Stopping and Learning Rate Reduction**: These techniques were employed to prevent overfitting and enhance the efficiency of the training process.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: To counteract the class imbalance within the dataset, SMOTE was utilized, ensuring that the model was trained on a balanced dataset, which is vital for achieving reliable classification metrics.

- ![image](https://github.com/ZombieSwan/Capstone-3/assets/128863293/ca292539-b19f-456e-8144-c2cae89ae0e6)


### Final Test Results
The LSTM model demonstrated exemplary performance with a final test accuracy of approximately 92.09%. This indicates that, when presented with new, unseen data, the model was able to correctly predict the trend classifications with a high degree of precision. This level of accuracy showcases the model's capability to generalize well and underscores the effectiveness of the methodologies employed during training.

