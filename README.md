# Crypto-Sentiment-Trading-Analysis
An analysis of crypto trading performance across market sentiment states.
# Quantitative Trading & Market Sentiment Analysis

## 📌 Executive Summary
This project analyzes the performance of cryptocurrency trading strategies across varying states of market sentiment (from 'Extreme Fear' to 'Extreme Greed'). Using historical trade data merged with a Fear & Greed Index, this analysis moves beyond basic average profitability to calculate **Expected Value (EV)**, Win/Loss asymmetries, and temporal (Day of Week) edges. 

The core finding reveals a highly profitable **Contrarian Edge**: short-selling during periods of 'Extreme Greed' yields the highest mathematical expected value of any market condition.

## 🛠️ Tech Stack & Tools
* **Data Processing & Statistical Testing:** Python (Pandas, NumPy, SciPy)
* **Interactive Data Visualization:** Plotly (HTML Dashboards)
* **Executive Dashboarding:** Power BI (DAX, Power Query)

---

## 📊 Executive Dashboard
*The interactive Power BI dashboard provides a macro-view of profitability alongside granular Risk/Reward metrics.*

![Dashboard Overview]

---

## 💡 Key Business Insights

### 1. The Contrarian Edge (Expected Value)
While trend-following (Buying during Greed) yields moderate win rates, the data proves a massive asymmetry when trading contrarian. **Selling (Shorting) during 'Extreme Greed'** holds the highest Expected Value (EV) per trade. The market is highly susceptible to corrections when FOMO peaks.


### 2. The Illusion of the "Average" (Risk/Reward Asymmetry)
Looking purely at average PnL masks underlying risk. The Risk/Reward Matrix reveals that during certain extreme conditions, the Win Rate actually drops below 50%. However, the strategy remains profitable because the **Average Win magnitude drastically outpaces the Average Loss**.

### 3. The Weekend Effect (Temporal Analysis)
Because cryptocurrency trades 24/7, liquidity fluctuates heavily on weekends. The temporal analysis indicates that while there are no inherently "losing" days, middle-of-the-week trading (Wednesdays) sees a significant dip in average profitability compared to weekend volatility.

---

## 📂 Repository Structure
* `DS_Trading_Task.ipynb`: The core data pipeline, including data cleaning, integration, T-Testing, and EV modeling.
* `DS_task_visualize.pbix`: The final interactive Power BI dashboard.
* `/CSV_Exports`: The aggregated statistical tables driving the visual models.
* `/HTML_Dashboards`: Interactive Plotly charts for web-based exploration.

## 🚀 How to Run
1. To view the data engineering and statistical analysis, open the `DS_Trading_Task.ipynb` notebook.
2. To explore the interactive visual models, open the `.pbix` file in Power BI Desktop, or open the standalone `.html` files in any web browser.
