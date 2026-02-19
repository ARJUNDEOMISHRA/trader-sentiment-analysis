# trader-sentiment-analysis
# Hyperliquid Trader Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader performance on the Hyperliquid platform. The objective is to understand how sentiment affects trader profitability, behavior, and risk-taking, and to generate actionable trading strategy recommendations.

This analysis combines trader execution data with market sentiment classification to uncover patterns that can improve trading decisions.

---

## Repository Contents

* `Trader_Sentiment_Analysis.ipynb` — Main notebook containing full analysis, charts, and insights
* `README.md` — Project documentation and summary
* `requirements.txt` — Required Python libraries

---

## Setup Instructions

### Step 1: Install Python libraries

Run the following command:

```
pip install -r requirements.txt
```

Or install manually:

```
pip install pandas numpy matplotlib seaborn jupyter
```

---

## How to Run

1. Open Jupyter Notebook
2. Open the file:

```
Trader_Sentiment_Analysis.ipynb
```

3. Click:

```
Run → Run All Cells
```

The notebook will:

* Load datasets
* Clean and merge data
* Generate charts and tables
* Display insights and strategy recommendations

---

## Output Charts and Tables

The notebook generates the following outputs:

* Average PnL during Fear vs Greed sentiment
* Win rate comparison across sentiment conditions
* Trade frequency comparison
* Trade size comparison
* Trader segmentation analysis
* Correlation heatmap
* Summary statistics tables

These visualizations help identify relationships between sentiment and trader performance.

---

## Methodology

The following steps were performed:

1. Loaded Bitcoin Fear & Greed Index dataset and Hyperliquid trader dataset
2. Cleaned datasets by handling missing values and removing duplicates
3. Converted timestamps and aligned datasets using date
4. Merged sentiment classification with trader execution data
5. Created performance metrics such as:

   * Closed PnL
   * Win rate
   * Trade size
   * Trade frequency
6. Performed behavioral analysis across Fear and Greed periods
7. Segmented traders based on trade size and activity level
8. Generated visualizations and correlation analysis
9. Derived insights and strategy recommendations

All analysis is reproducible using the provided notebook.

---

## Key Insights

1. Traders achieve higher average profitability during Greed sentiment compared to Fear sentiment.

2. Win rates are higher during Greed periods, indicating traders perform better in positive market conditions.

3. Trading activity increases during Greed sentiment, showing traders are more active when market confidence is high.

4. Trade sizes tend to be larger during Greed sentiment, indicating increased trader confidence and risk-taking.

5. Larger traders generally achieve better performance, suggesting capital size and experience contribute to improved results.

Overall, market sentiment strongly influences trader behavior and performance.

---

## Strategy Recommendations

Based on the analysis, the following strategies are recommended:

1. Reduce trading risk during Fear sentiment due to lower profitability and win rates.

2. Increase trading activity during Greed sentiment when market conditions are more favorable.

3. Use market sentiment as an external indicator to guide trading decisions.

4. Apply stronger risk management during Fear periods to minimize losses.

5. Focus on consistent trading strategies rather than aggressive trading during uncertain market conditions.

These strategies can help improve trading performance and risk management.

---

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Reproducibility

This analysis is fully reproducible. Running the notebook from top to bottom will regenerate all outputs, charts, and insights.

---

## Author

Data Science Intern Candidate
Hyperliquid Trader Performance Analysis Project
