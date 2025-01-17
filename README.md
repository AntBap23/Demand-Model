# Time Series Analysis Project

## Overview
This project involves time series analysis using a retail dataset to predict the number of units sold in a given week. The analysis focuses on building, evaluating, and visualizing machine learning models to provide accurate forecasts for weekly sales.

## Objectives
- Predict the weekly units sold using machine learning models.
- Compare the performance of different models and visualize the results.
- Highlight the difference between predicted and actual sales through Tableau dashboards.

## Tools and Technologies
- **Python**: Used for data preprocessing, model building, and evaluation.
  - **Libraries**: scikit-learn, pandas, matplotlib, and numpy.
- **Tableau**: For creating visualizations and comparing predictions with actual data.
- **GitHub**: Repository for managing and sharing the project.

## Dataset
The dataset contains weekly retail sales data, including relevant features for modeling. The target variable is the number of units sold per week.

## Machine Learning Models
Two machine learning models were built and evaluated:

### 1. Random Forest Regressor
- A robust ensemble learning method using decision trees.
- Achieved approximately **85% accuracy** in predicting weekly sales.

### 2. Gradient Boosting Regressor
- A boosting method that combines weak learners to create a strong predictive model.
- Also achieved approximately **84% accuracy** in forecasting weekly sales.

Both models were validated using a fresh dataset to ensure generalization and reliability.

## Visualizations
- The predictions from both models were visualized in Tableau.
- **Line Charts**:
  - **Random Forest Regressor**: A comparison of predicted and actual weekly sales (uploaded as `RFG visual.png`).
  - **Gradient Boosting Model**: A similar comparison (uploaded as `GB visual.png`).
- The visualizations aggregate sales data by week to provide clear insights into the model’s performance over time.

### Screenshots
![Random Forest Regressor Visualization](RFG%20visual.png)
![Gradient Boosting Model Visualization](GB%20visual.png)

## Key Insights
- Both models performed well, achieving similar accuracy scores.
- The visualizations demonstrate that the models effectively capture sales trends while highlighting areas where predictions deviate from actual values.



## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/AntBap23/Time-series-analysis.git
   cd Time-series-analysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training script:
   open colab or jupyter notebook 
  
   ```
4. Visualize results in Tableau using the provided data files.

## Future Improvements
- Incorporate additional features to enhance model accuracy.
- Experiment with other machine learning models such as XGBoost or LSTM for time series forecasting.
- Automate the end-to-end pipeline for data preprocessing, model training, and visualization.

## Conclusion
This project demonstrates the use of machine learning and data visualization tools to analyze and predict time series data. The visualizations effectively communicate the model’s performance and highlight the trends in weekly retail sales.

For any questions or feedback, feel free to reach out or open an issue on this repository!


