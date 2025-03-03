# **LSTM-Based Prediction for Volatility 75 Index (V75)**  

## **Project Overview**  
This project implements a **Long Short-Term Memory (LSTM) model** to predict the price movements of the **Volatility 75 Index (V75)**, a highly volatile synthetic index. The model leverages deep learning to analyze historical price trends and forecast future values, helping traders make data-driven decisions.  

## **Key Features**  
✅ **Time Series Forecasting:** Uses LSTM to capture long-term dependencies in V75 price movements.  
✅ **Data Preprocessing:** Handles missing values, normalizes prices, and creates sequences for training.  
✅ **Performance Evaluation:** Uses RMSE and visualization techniques to assess model accuracy.  
✅ **Hyperparameter Tuning:** Optimized for better prediction accuracy.  

## **Dataset & Preprocessing**  
- Data consists of **historical Volatility 75 Index (V75) price movements**.  
- Steps include:  
✅ **Normalization** using MinMaxScaler  
✅ **Creating time-based sequences**  
✅ **Splitting into training and test sets**  

## **LSTM Model Architecture**  
- **Input Layer:** Takes past price sequences as input.  
- **LSTM Layers:** Captures long-term patterns in V75 price movements.  
- **Dense Output Layer:** Predicts the next price point.  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam for efficient learning  

## **Results & Performance**  
- Achieved **[mention RMSE or accuracy]** on the test set.  
- Model predictions closely follow actual price trends.  
- Performance visualized using **matplotlib & seaborn**.  

## **Future Improvements**  
🚀 Experiment with **Bidirectional LSTM** for improved accuracy.  
🚀 Implement **Attention Mechanisms** to enhance feature importance.  
🚀 Deploy as an API for real-time V75 price forecasting.  

## **Author**  
👤 **Your Name** – [GitHub Profile](https://github.com/sirbob12)  

  

