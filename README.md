# Primetrade.ai-Assignment
Data analysis project exploring how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance using Hyperliquid trading data. Includes data cleaning, exploratory analysis, trader segmentation, and strategy insights.

# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Project Overview

This project analyzes how **Bitcoin market sentiment (Fear vs Greed)** influences trader behavior and trading performance on the **Hyperliquid trading platform**.

The objective is to identify patterns between market psychology and trader decisions, and to derive **actionable insights** that could help design smarter trading strategies.

This project was completed as part of a **Data Science / Data Analytics Intern assignment**.

---

## 🎯 Objectives

- Analyze relationship between **market sentiment** and **trader profitability**
- Study behavioral changes under Fear vs Greed conditions
- Measure trader performance metrics such as:
  - Daily PnL
  - Win rate
  - Trading frequency
  - Position bias (Long vs Short)
- Segment traders based on behavior
- Generate data-driven trading insights and strategy recommendations

---

## 📂 Datasets

### 1️⃣ Bitcoin Market Sentiment (Fear & Greed Index)

Contains daily market sentiment classification.

**Columns:**
- `timestamp`
- `value`
- `classification` (Fear / Greed)
- `date`

🔗 Dataset Link:  
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

---

### 2️⃣ Historical Trader Data (Hyperliquid)

Contains detailed trade execution records.

**Key Fields:**
- Account
- Coin
- Execution Price
- Size Tokens / Size USD
- Side (Buy/Sell)
- Timestamp IST
- Closed PnL
- Transaction details

🔗 Dataset Link:  
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ⚙️ Project Workflow

### 1. Data Preparation
- Loaded datasets
- Cleaned column names
- Converted timestamps to datetime format
- Aligned datasets on daily date level
- Merged trader data with sentiment data

### 2. Feature Engineering
Created analytical metrics:
- Daily PnL per trader
- Win/Loss indicator
- Trading frequency
- Long vs Short ratio
- Trader activity segmentation

### 3. Exploratory Data Analysis
Analyzed:
- Profitability across Fear vs Greed markets
- Behavioral changes in trading patterns
- Distribution of trader profits
- Sentiment-based performance differences

### 4. Visualization
Generated charts including:
- PnL distribution by sentiment
- Trading behavior comparison
- Sentiment impact analysis

### 5. Insights & Strategy Recommendations
Derived actionable rules based on observed patterns.

---

## 📊 Key Insights

- Trader profitability varies significantly between Fear and Greed market conditions.
- Trading behavior changes depending on market sentiment.
- Certain trader segments perform consistently better under specific sentiment regimes.
- Market psychology strongly influences risk-taking behavior.

---

## 🧠 Strategy Recommendations

Example data-driven rules:

- Reduce leverage exposure during Fear sentiment periods.
- Increase trade participation selectively during Greed markets.
- Frequent traders adapt better to sentiment shifts compared to infrequent traders.

---

## 📁 Project Structure
