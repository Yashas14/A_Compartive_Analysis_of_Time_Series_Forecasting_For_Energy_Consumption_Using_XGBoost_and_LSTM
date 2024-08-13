# 🌟 **A Compartive Analysis of Time Series Forecasting For Energy Consumption Using XGBoost and LSTM**

## 🎯 **Business Objective**

In this project, we tackle the challenge of accurately forecasting energy consumption using the powerful XGBoost algorithm, combined with the advanced LSTM model. By analyzing historical data, we aim to provide insights that can help optimize energy usage and improve resource allocation.

This work represents the research presented in our paper titled *"Time Series Forecasting for Energy Consumption Using XGBoost and LSTM,"* which was published at the IEEE 2024 Asia Pacific Conference on Innovation in Technology (APCIT) held in Mysuru, India, on July 26-27, 2024.

### **Goals:**
- Predict future energy consumption trends.
- Enhance decision-making processes for energy management.
- Provide actionable insights for policymakers and stakeholders.

### 📊 **Data Description**

We use the PJME Hourly Energy Consumption dataset, which includes hourly energy consumption data. This dataset is crucial for developing a model that can forecast energy consumption patterns with high accuracy.

### **Dataset Breakdown:**
- Training Data: 70% of the total data
- Validation Data: 15% of the total data
- Test Data: 15% of the total data

The data includes the following features:
- Datetime: The timestamp of the energy consumption reading.
- Energy Consumption: The amount of energy consumed (in MW).

### 🛠 **Methodology**

1. **Data Collection**  
   Historical energy consumption data is gathered from reliable sources.
   
2. **Data Preprocessing**  
   - Handling missing values.
   - Removing outliers.
   - Normalizing and scaling the data.
   
3. **Feature Engineering**  
   - Creating time-based features (hour, day, month).
   - Identifying seasonal trends.
   - Incorporating external factors (e.g., weather conditions).
   
4. **Model Implementation**
   - **XGBoost**: We utilized the XGBoost algorithm to train the predictive model, focusing on its strength in handling tabular data and boosting performance.
   - **LSTM**: Long Short-Term Memory (LSTM) networks were employed to capture the sequential dependencies and temporal patterns in the time series data, making them particularly effective for long-term forecasting.
   - Hyperparameter tuning for optimal performance.
   
5. **Model Evaluation**
   - Assessing the models using metrics like MAE, RMSE, and accuracy.
   - Comparing results between XGBoost, LSTM, and hybrid approaches.
   
6. **Results Analysis**
   - Interpreting the model's predictions.
   - Visualizing the forecasted trends.

### 🚀 **Results**

The combination of XGBoost and LSTM models demonstrated impressive accuracy in forecasting energy consumption, with the following performance metrics:
- Mean Absolute Error (MAE): 3538.94
- Root Mean Square Error (RMSE): 4325.35
- Accuracy: 89.05%

### 🔮 **Future Enhancements**
- **Incorporate Additional Variables**: Including more external factors such as weather data, economic indicators, and policy changes.
- **Hybrid Models**: Further exploration of hybrid models combining XGBoost with other machine learning and deep learning techniques for improved accuracy.
- **Enhanced Interpretability**: Developing methods to make the model's predictions more interpretable for stakeholders.
- **Hyperparameter Tuning**: Further fine-tuning of hyperparameters and expanding the dataset for better model performance.

### 📂 **Repository Contents**
- **Dataset**: Historical energy consumption data used for training and evaluating the models.
- **Source Code**: Implementation of the XGBoost and LSTM models, along with associated scripts.

### 👥 **Connect With Me:**

**Yashas D** [Connect on LinkedIn](https://www.linkedin.com/in/yashasd2004/)
Feel free to reach out for any questions or collaboration opportunities!
