

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
  - Python (Django)
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
   git clone https://github.com/Yashparmar1125/stocksage-backend.git
   cd backend
   ```

2. Install backend dependencies:
   ```bash
   pip install -r requirements.txt
   ```


### Running the Application

1. **Start the Backend Server**:

   - Navigate to the `backend` directory and run the server:
     ```bash
     cd backend
     python manage.py runserver
     ```
   - The backend API will be accessible at `http://localhost:8000`.

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

