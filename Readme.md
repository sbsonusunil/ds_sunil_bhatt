readme_content = """
# Web3 Trading – Data Science Assignment

## Candidate: Sunil Bhatt

Project Overview
This project analyzes the relationship between trader behavior and Bitcoin market sentiment using historical trade data and sentiment scores. The objective is to uncover patterns that can help improve trading strategies in Web3 markets.

Datasets Used
1. Bitcoin Market Sentiment Dataset
   - Columns: Date, Classification (Fear / Greed)

2. Historical Trading Dataset
   - Columns include: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.

Folder Structure
ds_sameer_bhatt/
	Traders behavior insights.ipynb
 
csv_files/
	daily_metrics.csv
	daily_metrics_with_sentiment.csv
	merged_df.csv
	trader_df.csv
	sentiment_df.csv

 outputs/
	pnl_vs_sentiment.png
	Correlation Heatmap of Trader Metrics.png
	Average Trade Size vs Total Daily PnL.png
	Win Rate by Market Sentiment.png
	Distribution of PnL by Market Sentiment.png


ds_report.pdf
README.md

Instructions to Run
1. Traders behavior insights.ipynb in Google Colab.
2. Run all cells from top to bottom.
3. Folder structure will be created automatically.
4. Processed data and visualizations will be stored in csv_files and outputs folders.

Libraries Used
- pandas
- numpy
- matplotlib
- plotly
- seaborn
-scipy
-spacy

Notes
- All datasets are provided as CSV files in csv_files/.
- Charts are saved as PNG images in outputs/.
