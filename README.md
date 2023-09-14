# Stock_pred_using_python

Future stock prediction using Python, Streamlit, and LSTM models

Overview:
- This project utilizes LSTM models in Python to predict future stock prices.
- It includes key features like : 
  1. Predicting stock prices for the next 1-60 days.
  2. Comparing the performance of two different stocks.
  3. Stock History of any stock

Features:

1. Future Stock Prediction (1-60 Days):
- The project employs LSTM (Long Short-Term Memory) models to forecast stock prices for future periods ranging from 1 to 60 days.
- Users can input a stock symbol, specify the prediction horizon, and receive forecasts along with confidence intervals.

2. Stock Comparison:
- The application allows users to compare the performance of two different stocks.
- By selecting two stock symbols, users can visualize and analyze how these stocks have historically performed relative to each other.

3. Stock History :
- By selecting any stock symbol, user can visualize and analyse the stock history of that particular stock.

4. Other features :
- It outlines the data collection, preprocessing, model training, and prediction processes.
- Key libraries and tools used, such as Python, Streamlit, and LSTM.
- The stock values taken are real time as we have used yfinancce openAPI for stocks.

How to Use:

1. Clone the Repository
2. Install Dependencies
3. Run the Application:
   streamlit run app.py
   
Project Structure:

- `app.py`: The Streamlit application code.
- `lstm_model.py`: LSTM model implementation for stock prediction.

Future Enhancements:
- Can make a better prediction model, using real time self training machine learning model.

Contributors:
- 1. Krishna Patel
  2. Kriyam Shah
  3. Dhruv Dave
  4. Mahim Jain
