# Trader Performance vs Market Sentiment Analysis

## Overview
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance using Hyperliquid trading data.

The analysis includes:
- Data cleaning and alignment
- Feature engineering (PnL, win rate, trade behavior)
- Sentiment-based performance analysis
- Trader segmentation
- Strategy recommendations
- Bonus: Predictive modeling and clustering

---

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab

**Required libraries:**
- pandas
- numpy
- matplotlib
- seaborn
- sklearn


---

## How to Run

### Google Colab (Recommended)

1. Open the notebook (`.ipynb`) in **Google Colab**

2. Upload the datasets manually:
   - Click on the **folder icon (left sidebar)**
   - Click **Upload**
   - Upload both CSV files:
     - Fear & Greed dataset
     - Historical Trader dataset

3. Update file paths in the notebook:

Replace:
```python
pd.read_csv("your_path_here.csv")