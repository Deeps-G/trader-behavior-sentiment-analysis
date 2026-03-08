## IMPORTANT NOTE
## Dataset
The second dataset historical_data.csv used in this project is large and not included in the repository.
Download it here:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

## Files:
- historical_data.csv
- fear_greed_index.csv
## Notebook Preview
If GitHub fails to render the notebook, view it here:
https://nbviewer.org/github/Deeps-G/trader-behavior-sentiment-analysis/blob/main/Data_science_internship_round_0.ipynb
  
# Trader Behavior vs Market Sentiment Analysis

This project analyzes how market sentiment (Fear/Greed Index) influences trader behavior and profitability using historical trading data.

## Methodology
- Data cleaning and timestamp alignment
- Merging sentiment data with trading activity
- Feature engineering and behavioral metrics
- Visualization of trading patterns

## Key Insights
1. Trader profitability becomes more volatile during Fear periods.
2. Trade sizes increase during Greed sentiment, suggesting risk-seeking behavior.
3. Traders exhibit a stronger long-position bias during optimistic sentiment.

## Strategy Recommendations
- Reduce leverage during Fear markets to manage volatility risk.
- Favor momentum-based long strategies during Greed sentiment.

## Bonus Analysis
- Random Forest predictive model for trade profitability
- KMeans clustering to identify trader behavior archetypes.

## Files
- `Untitled24.ipynb` — main notebook
- `historical_data.csv` — trading dataset
- `fear_greed_index.csv` — sentiment dataset
