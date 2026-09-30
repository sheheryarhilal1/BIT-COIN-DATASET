# ₿ Bitcoin Data Analysis & Visualization

![Bitcoin](https://img.shields.io/badge/Bitcoin-Data%20Analysis-orange)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## 📌 Project Overview

This project focuses on **Bitcoin historical price data analysis and visualization** using Python.

The objective is to explore Bitcoin market data, clean and process the dataset, identify price trends, analyze market behavior, and create meaningful visualizations that can support data-driven insights.

The project uses historical Bitcoin/USD data and demonstrates practical **Data Analytics, Data Cleaning, Exploratory Data Analysis (EDA), and Data Visualization** techniques.

---

## 🎯 Objectives

* Analyze historical Bitcoin price movements
* Clean and preprocess raw Bitcoin data
* Handle missing and inconsistent values
* Explore Bitcoin price trends over time
* Analyze Open, High, Low and Close prices
* Study trading volume
* Identify important market patterns
* Create meaningful visualizations
* Present analytical findings using Python

---

## 🗂️ Project Structure

```text
Bitcoin-Data-Analysis/
│
├── assets/
│   ├── bitcoin-dashboard.png
│   ├── bitcoin-price.png
│   ├── bitcoin-analysis.png
│   └── ...
│
├── Bitcoin Data.ipynb
├── btcusd_1-min_data.csv
├── README.md
└── ...
```

> **Note:** All visualization images used in this README are stored inside the `assets/` folder of the same repository.

---

## 🛠️ Technologies & Tools

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Excel/CSV Dataset**
* **Data Visualization**
* **Exploratory Data Analysis**

---

## 📊 Dataset

The project uses historical **BTC/USD 1-minute price data**.

The dataset contains market information such as:

| Column    | Description                               |
| --------- | ----------------------------------------- |
| Timestamp | Date and time of the recorded market data |
| Open      | Opening Bitcoin price                     |
| High      | Highest Bitcoin price during the interval |
| Low       | Lowest Bitcoin price during the interval  |
| Close     | Closing Bitcoin price                     |
| Volume    | Trading volume                            |

---

## 🔄 Data Analysis Workflow

```text
Raw Bitcoin Dataset
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Missing Value Handling
        ↓
Date & Time Processing
        ↓
Exploratory Data Analysis
        ↓
Price Trend Analysis
        ↓
Data Visualization
        ↓
Business / Market Insights
```

---

## 🧹 Data Cleaning

The dataset was inspected and prepared before performing analysis.

The cleaning process included:

* Loading the CSV dataset using Pandas
* Checking dataset dimensions
* Checking data types
* Detecting missing values
* Handling duplicate records
* Converting timestamps into readable date/time format
* Sorting records chronologically
* Preparing numerical columns for analysis

Example:

```python
import pandas as pd

df = pd.read_csv("btcusd_1-min_data.csv")

print(df.head())
print(df.info())
print(df.isnull().sum())
```

---

## 📈 Bitcoin Price Analysis

The analysis explores Bitcoin's historical price behavior using:

* Opening price
* Closing price
* Highest price
* Lowest price
* Trading volume
* Time-based trends

### Bitcoin Price Trend

![Bitcoin Price Trend](assets/PriceAnalysis.PNG)

The visualization helps identify how Bitcoin prices changed throughout the selected historical period.

---

## 📊 Exploratory Data Visualization

Different charts were created to understand the behavior of the Bitcoin market.

### Price Movement

![Bitcoin Analysis](assets/InsightAnalysis.PNG)

The price movement visualization provides a clearer view of Bitcoin's historical fluctuations.

### Dashboard / Visualization

![Bitcoin Dashboard](assets/Executive.PNG)

The dashboard combines important analytical views to make the dataset easier to understand.

> If your actual image filenames are different, replace the filenames above with the exact names available inside the `assets` folder.

---

## 🔍 Key Analysis Areas

### 1. Price Trends

Analyzed Bitcoin's price movement over time to identify periods of:

* Growth
* Decline
* High volatility
* Relative stability

### 2. High & Low Prices

Compared the highest and lowest prices to understand the daily/periodic price range.

### 3. Trading Volume

Analyzed trading volume to understand changes in market activity.

### 4. Open vs Close

Compared opening and closing prices to identify price movement within different periods.

### 5. Market Volatility

Observed significant price fluctuations to understand periods of higher market activity.

---

## 💡 Insights

The analysis provides a practical understanding of:

* Bitcoin's historical price behavior
* Price volatility
* Market activity through trading volume
* Relationship between Open, High, Low and Close prices
* Long-term and short-term price movements
* Patterns that can be explored further through advanced time-series analysis

These findings are **descriptive observations from historical data**, not investment advice or predictions of future Bitcoin prices.

---

## 📓 Jupyter Notebook

The complete analysis and visualizations are available in:

```text
Bitcoin Data.ipynb
```

The notebook contains the Python code used for:

* Data loading
* Data preprocessing
* Data cleaning
* Exploratory analysis
* Visualization
* Statistical exploration

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd Bitcoin-Data-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Bitcoin Data.ipynb
```

---

## 📌 Project Highlights

* Historical Bitcoin market data analysis
* Large time-series dataset
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Price trend visualization
* Trading volume analysis
* Python-based analytics
* Jupyter Notebook implementation
* GitHub-ready project structure

---

## 🚀 Future Improvements

This project can be extended with:

* Interactive Plotly dashboards
* Power BI Bitcoin dashboard
* Moving Average analysis
* RSI indicator
* MACD analysis
* Candlestick charts
* Correlation analysis
* Time-series forecasting
* Machine Learning models
* Automated data collection through APIs

---

## 👨‍💻 Author

**Sheheryar Ahmed**

**Data Analyst | Power BI Developer | Python | SQL | Data Visualization**

GitHub:
https://github.com/sheheryarhilal1

---

## ⭐ If You Find This Project Useful

Feel free to explore the notebook, review the visualizations, and use the project as a reference for learning **Python Data Analysis and Visualization**.

**Made with Python, Pandas & Data Visualization.**


## 📊 Project Visualizations

### Bitcoin Price Analysis

![Bitcoin Price Analysis](./assets/PriceAnalysis.PNG)

### Bitcoin Dashboard

![Bitcoin Dashboard](./assets/Executive.PNG)

### Bitcoin Data Visualization

![Bitcoin Volatility](./assets/VolatilityAnalysis.PNG)

### Bitcoin Volume

![Bitcoin Volume](./assets/VolumeAnalysis.PNG)

### Bitcoin Timeline

![Bitcoin Time INtelligence](./assets/TimeIntelligence.PNG)
