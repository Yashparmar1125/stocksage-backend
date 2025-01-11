# Stock Price Prediction Using Machine Learning

## Project Overview
This project predicts stock prices using machine learning techniques and presents the results with a full-stack web application. The backend collects and processes historical stock data, calculates technical indicators, and uses an XGBoost model to predict the next day's stock price and future prices. The frontend, built with React and Next.js, provides an interactive UI to display stock predictions, actual vs predicted prices, and related technical indicators.

## Features
- **Backend**:
  - **Data Collection**: Downloads historical stock data from Yahoo Finance.
  - **Technical Indicators**: Calculates key technical indicators like SMA, EMA, RSI, OBV, and Bollinger Bands.
  - **Prediction**: Uses the XGBoost model to predict the next day's stock price and future prices.
  - **Evaluation**: Measures the model's accuracy using MSE and R-squared metrics.
  
- **Frontend**:
  - **Next.js**: Framework used for the React-based frontend.
  - **Stock Data Visualization**: Displays stock predictions, actual prices, and technical indicators.
  - **User Interface**: Interactive forms to input stock ticker symbols and view predictions for future prices.

## Tech Stack
- **Frontend**:
  - React
  - Next.js
  - Tailwind CSS (for styling)
  
- **Backend**:
  - Python (Flask)
  - XGBoost for Machine Learning
  - Pandas for data manipulation
  - Yahoo Finance API (via yfinance library)

- **Others**:
  - Pandas TA for calculating technical indicators
  - Matplotlib for visualizations
  - scikit-learn for model evaluation
  
## Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Yashparmar1125/Stock-Price-Prediction.git
   cd stock-price-prediction

2.  Install backend dependencies:

     ```bash
    cd server/backend
    pip install requirements.txt

### Frontend Setup

1.  Navigate to the frontend directory:
    ```bash
    cd stock-sage

2.  Install frontend dependencies:
    ```bash
    npm install

### Running the Application

1.  **Start the Backend Server**:

    -   Navigate to the `backend` directory and run the server:

        ```bash
        cd backend
        python app.py

    -   The backend API will be accessible at `http://localhost:8000`.
    
   2.  **Start the Frontend Server**:

       -   Navigate to the `stock-sage` directory and start the development server:

          ```bash
           cd frontend
           npm run dev

   The frontend will be accessible at `http://localhost:3000`.

Usage
-----

1.  On the frontend, you can input a stock ticker symbol (e.g., `AAPL` for Apple).
2.  The backend will fetch historical data, calculate technical indicators, and return the stock's predicted next-day price and future prices.
3.  The frontend will display the stock's actual vs predicted prices for the last 30 days and future predictions for the next 10 days, along with the calculated technical indicators.


---
## Contributing
We welcome contributions to enhance the SCMS! Follow these steps to contribute:

1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For any queries or support, feel free to reach out:
- **Author**: Yash Parmar
- **GitHub**: [https://github.com/Yashparmar1125](https://github.com/Yashparmar1125)
- **Email**: [yashparmar11y@gmail.com](mailto:yashparmar11y@gmail.com)


Acknowledgments
---------------

-   This project uses the XGBoost library for regression modeling.
-   The technical indicators are calculated using the `pandas_ta` library.
-   Data is retrieved via the `yfinance` library.

