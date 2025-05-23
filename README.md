
# Microsoft Stock Market Analysis Project

## Overview
This project analyzes historical stock data for Microsoft Corporation (MSFT) from 1986 to 2025. It explores trading behavior, price trends, volatility, and the effects of external events on Microsoft's stock over time. The goal is to extract insights by answering key analytical questions through Python and data visualization.

---

## Key Questions Answered

1. **What are the historical periods of highest volume?**  
   - Identified major spikes in volume, notably on:
     - **March 13, 1986** – Microsoft's IPO.
     - **August 1989** – Microsoft Office release.
     - **April 2006** – Strong quarterly earnings and upcoming product releases.
     - **June 1994** – No clear event, possibly panic selling (indicated by negative open-to-close percentage).

2. **When did Microsoft stock experience its most significant drop in closing price, and what was the context?**  
   - The most significant drop occurred on **October 19, 1987 (Black Monday)** — a global stock market crash that severely impacted equities, including MSFT.

3. **When did MSFT show unusually high volatility?**  
   - Observed major spikes in 30-day rolling volatility during:
     - **Black Monday (1987)**
     - **Global Financial Crisis (2008)**
     - **COVID-19 Pandemic (2020)**
   - These events correspond to significant uncertainty and rapid price fluctuations.

4. **How do moving averages compare to actual prices during major events?**  
   - Analyzed 30-day and 100-day SMAs alongside closing prices during key periods.
   - Noted that during crises, actual prices often dipped below both moving averages, signaling bearish trends and market pessimism.

5. **How does trading volume change during periods of high volatility?**  
   - Volatility was segmented into Low, Medium, and High categories using quantile-based binning.
   - Volume increases with volatility:
     - **Higher median volume** in high volatility periods.
     - **Wider interquartile range (IQR)** and **numerous outliers**, especially in high-volatility scenarios.
   - Conclusion: **High volatility is associated with both increased and more variable trading activity.**

6. **Are there price drops that correspond to increased volume?**  
   - Flagged days with daily returns less than -2%.
   - Found that **average volume is significantly higher on price drop days** compared to normal days.
   - Boxplot visualization confirms that traders tend to react strongly on days of significant price drops, likely due to fear or major news.

---

## 🛠️ Tools & Libraries Used
- **Python**: Data processing and analysis
- **Pandas & NumPy**: Data manipulation and statistical analysis
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development

---

##  Dataset
- Source: **Kaggle**
- Data: Microsoft (MSFT) stock price history from **1986 to 2025**
- Fields used: `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`, derived features like SMA, volatility, price-volume signals, etc.

---

##  Visualizations & Analysis Highlights
- Time series plots of closing price, volume, and moving averages
- Volatility trend using 30-day rolling standard deviation
- Price vs. volume signal feature
- Boxplots comparing volume across volatility and price drop conditions
- Annotated plots for major historical financial events

---

##  Conclusion
This project highlights how stock data can reveal insightful patterns, particularly when linked with external global events. Analyzing moving averages, volatility, and volume can offer predictive clues about market sentiment and investor behavior.

---

 *Created by: Shriram Balaji*
