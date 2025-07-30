# Gold-Price-Prediction
# 🪙 Gold Price Prediction using Machine Learning

This project predicts the price of gold using historical financial indicators and machine learning models. The goal is to model the relationship between gold prices and key economic factors such as crude oil prices, exchange rates, and stock market indices.

---

## 📊 Problem Statement

Gold is a key economic commodity whose price is influenced by multiple market factors. Accurately predicting gold prices can benefit investors and analysts. This project builds predictive models based on historical data to estimate gold prices.

---

## 📁 Dataset Information

- **Source**: [Kaggle or internal source]
- **Rows**: ~2,000+
- **Format**: CSV
- **Target Variable**: `Gold_Price`

### 🔑 Example Features

| Feature         | Description                            |
|------------------|----------------------------------------|
| Date             | Date of the record                     |
| SPX              | S&P 500 index value                    |
| Oil_Price        | Crude oil price                        |
| USD_INR          | USD to INR exchange rate               |
| Silver_Price     | Price of silver                        |
| Interest_Rate    | Interest rate (optional)              |
| Gold_Price       | 💡 Target column: price of gold (in USD or INR) |

---

## 🧰 Tools & Technologies

- Python 3.x
- pandas, NumPy
- seaborn, matplotlib
- scikit-learn
- XGBoost / LightGBM / RandomForest
- Jupyter Notebook

---

## 🔬 Exploratory Data Analysis (EDA)

- Distribution of gold prices
- Correlation between gold price and market indicators
- Time series trends
- Heatmaps, boxplots, and pairplots

---

## 🔄 Data Preprocessing

- Handled missing values
- Converted date to datetime format
- Created additional features (month, year)
- Scaled features using `StandardScaler`
- Split data into train and test sets

---

## 🧠 Machine Learning Models

| Model                 | Metrics Used              |
|----------------------|---------------------------|
| Linear Regression     | R², RMSE, MAE             |
| Decision Tree         | R², RMSE, MAE             |
| Random Forest         | R², RMSE, MAE             |
| XGBoost               | R², RMSE, MAE             |

---

## 📈 Evaluation Metrics

- **R² Score** (coefficient of determination)
- **RMSE** (Root Mean Squared Error)
- **MAE** (Mean Absolute Error)

📌 **Sample Results:**

| Model            | R² Score | RMSE   | MAE    |
|------------------|----------|--------|--------|
| Random Forest    | 0.9994   | 26.42  | 17.88  |
| XGBoost          | 0.9991   | 30.15  | 20.47  |
| Linear Regression| 0.9842   | 112.78 | 83.62  |


Conclusion

Gold price is highly correlated with crude oil prices and currency exchange rates.
Ensemble models like Random Forest and XGBoost provide superior predictive accuracy.
Project demonstrates the effectiveness of data science in financial forecasting.



---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/gold-price-prediction.git
cd gold-price-prediction













