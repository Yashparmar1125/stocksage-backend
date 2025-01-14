Here's an updated version of your project overview, incorporating some formatting improvements and enhancements:

---

# Stock Price Prediction Using Machine Learning

## Project Overview
This project utilizes machine learning techniques to predict stock prices and presents the results via a full-stack web application. The backend collects and processes historical stock data, computes technical indicators, and leverages an XGBoost model to predict the next day's stock price and future prices. The frontend, developed using React and Next.js, provides an interactive UI to display stock predictions, actual vs. predicted prices, and associated technical indicators.

## Features

### **Backend**:
- **Data Collection**: Fetches historical stock data from Yahoo Finance.
- **Technical Indicators**: Calculates key technical indicators like:
  - **SMA** (Simple Moving Average)
  - **EMA** (Exponential Moving Average)
  - **RSI** (Relative Strength Index)
  - **OBV** (On-Balance Volume)
  - **Bollinger Bands**
- **Prediction**: Uses the XGBoost model to forecast the next day's stock price and future prices.
- **Evaluation**: Assesses the model's performance using metrics like MSE (Mean Squared Error) and R-squared.

### **Frontend**:
- **Next.js**: Framework used for building the React-based frontend.
- **Stock Data Visualization**: Displays stock predictions, actual prices, and technical indicators.
- **User Interface**: Features interactive forms for entering stock ticker symbols and viewing future price predictions.

## Tech Stack
- **Frontend**:
  - React
  - Next.js
  - Tailwind CSS (for styling)
  
- **Backend**:
  - Python (Flask)
  - XGBoost for Machine Learning
  - Pandas for data manipulation
  - Yahoo Finance API (via `yfinance` library)

- **Additional Libraries**:
  - Pandas TA for calculating technical indicators
  - Matplotlib for visualizations
  - scikit-learn for model evaluation

## Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Yashparmar1125/Stock-Price-Prediction.git
   cd stock-price-prediction
   ```

2. Install backend dependencies:
   ```bash
   cd server/backend
   pip install -r requirements.txt
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd stock-sage
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

### Running the Application

1. **Start the Backend Server**:

   - Navigate to the `backend` directory and run the server:
     ```bash
     cd backend
     python app.py
     ```
   - The backend API will be accessible at `http://localhost:8000`.

2. **Start the Frontend Server**:

   - Navigate to the `stock-sage` directory and start the development server:
     ```bash
     cd frontend
     npm run dev
     ```
   - The frontend will be accessible at `http://localhost:3000`.

## Usage
1. On the frontend, input a stock ticker symbol (e.g., `AAPL` for Apple).
2. The backend will fetch historical data, calculate technical indicators, and return the predicted next-day price and future prices.
3. The frontend will display the actual vs. predicted prices for the last 30 days and future predictions for the next 10 days, along with the relevant technical indicators.

---

## Contributing
We welcome contributions to enhance this project! Follow these steps to contribute:

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

---

## Acknowledgments
- This project utilizes the **XGBoost** library for regression modeling.
- The **technical indicators** are calculated using the `pandas_ta` library.
- Data is fetched via the **yfinance** library.

---

Feel free to replace the placeholders with more specific details if needed! This updated version should provide a more structured and comprehensive overview of your project.