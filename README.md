# Stock Forecast App 📈

This Stock Forecast App is built using Streamlit, Prophet, yFinance, and Plotly. It provides an interactive web application to visualize and predict stock prices for popular stocks like Google (GOOG), Apple (AAPL), Microsoft (MSFT), and GameStop (GME).

Features 🚀
Stock Selection:
Choose from a set of predefined stocks for analysis and forecasting.

Customizable Forecast Period:
Use a slider to select the number of years (1-4 years) for forecasting future stock prices.

Real-Time Data Loading:
The app fetches historical stock data from Yahoo Finance (yFinance API) starting from January 1, 2015, up to today's date.

Raw Data Visualization:

Displays the most recent stock data in tabular form.
Includes interactive line charts showing stock opening and closing prices using Plotly.
Prophet-Based Forecasting:

Implements Facebook's Prophet for time-series forecasting.
Predicts future stock prices based on historical data.
Provides interactive forecast plots and component breakdowns.
Libraries Used 🛠️
Streamlit: To build the web application interface.
yFinance: To fetch historical stock market data.
Prophet: For time-series forecasting.
Plotly: For creating interactive charts.
How It Works 📝
Select a stock from the dropdown menu.
Set the forecast period using the slider (1-4 years).
The app:
Downloads historical stock data using yfinance.
Prepares the data for forecasting using Prophet.
Predicts future trends and visualizes them interactively.
View raw data, forecast plots, and detailed forecast components.
Running the App 🖥️
To run this app locally:

Install the required dependencies:
bash
Copy code
pip install streamlit fbprophet yfinance plotly
Save the script (e.g., app.py) in your working directory.
Run the app using:
bash
Copy code
streamlit run app.py
Open the provided local URL (e.g., http://localhost:8501) in your browser.
Example Screenshots 🌟
![image](https://github.com/user-attachments/assets/11ef1ba8-a8b3-4ddf-8209-28b67f35a45d)







Main Interface
![image](https://github.com/user-attachments/assets/688b857c-08f9-4316-8782-a8c65cbe692f)

Forecast Plot
![image](https://github.com/user-attachments/assets/d548cb89-7ac7-4a26-96da-6c51d6d6d728)

![image](https://github.com/user-attachments/assets/ee918df9-8bee-4de2-87c9-211771f284c8)

![image](https://github.com/user-attachments/assets/a93bd7bb-a2f8-43cf-a7c0-a52c53bb1ddd)


Future Enhancements 🛠️
Add more stock datasets.
Integrate additional forecasting algorithms for comparison.
Provide options to download the forecast data.
Feel free to contribute and enhance this app! 😊
