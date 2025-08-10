
# 📈 AI-Powered Stock Trading Strategy

An interactive **Streamlit web application** that uses **machine learning** to predict stock price movements and generate a trading strategy.  
The app fetches historical stock market data, processes it, trains multiple ML models, and visualizes predictions with performance metrics.

---

## 🚀 Features
- **Real-Time Data Fetching**: Uses `yfinance` to download historical market data for any given stock ticker.
- **Data Preprocessing**: Cleans, transforms, and engineers features for better model performance.
- **Machine Learning Models**: Includes algorithms such as **XGBoost**, **LightGBM**, and **Random Forest** for prediction.
- **Model Evaluation**: Displays accuracy, precision, recall, F1-score, and confusion matrix.
- **Interactive Visualizations**: Generates stock price trends, feature importance charts, and prediction plots.
- **User-Friendly Interface**: Allows users to input a stock ticker and run analysis directly in the browser.

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**:  
  - Data Processing: `pandas`, `numpy`  
  - Visualization: `plotly`, `matplotlib`  
  - Machine Learning: `scikit-learn`, `xgboost`, `lightgbm`, `imbalanced-learn`, `shap`  
  - Data Source: `yfinance`  
  - Web App: `streamlit`

---

## 📂 Project Structure
```

├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

````

---

## 📊 Workflow
1. **Input Stock Ticker**: User provides stock ticker (e.g., `AAPL`, `TSLA`).
2. **Fetch Data**: Download historical stock data from Yahoo Finance.
3. **Feature Engineering**: Create technical indicators & lag features.
4. **Train Models**: Fit ML algorithms on historical data.
5. **Evaluate Performance**: Display metrics and confusion matrix.
6. **Visualize Results**: Plot predictions, trends, and feature importances.

---

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/stock-trading-strategy.git

# Navigate to the project folder
cd stock-trading-strategy

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
````

---

## 🌐 Live Demo

[View the Deployed App](https://ai-powered-stock-trading-strategy-bwb9uuvrxhjaacxysjlonx.streamlit.app/#analysis-results)

---

## 📜 License

This project is licensed under the MIT License.

```

---

```
