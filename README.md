Trader Behavior Analysis vs. Market Sentiment
This repository contains my submission for the Junior Data Scientist assignment. The project analyzes historical trading data alongside the Fear & Greed Index to uncover patterns in trader behavior.

Project Goal
The main objective was to answer the question: How does a trader's performance (profitability, volume, etc.) relate to the overall market sentiment? The goal was to identify hidden signals that could lead to smarter trading strategies.

File Structure
The project is organized into the following folders and files:

/notebooks/: Contains the Google Colab notebook with the full analysis.

notebook_1.ipynb: The primary analysis, which covers data cleaning, exploratory data analysis, and a comparison of profitable vs. unprofitable traders.

/csv_files/: Contains the two original datasets used for this analysis.

historical_data.csv: Trading data from Hyperliquid.

fear_greed_index.csv: Bitcoin Fear & Greed Index data.

/outputs/: Contains all the charts and visualizations generated from the notebooks.

ds_report.pdf: A non-technical, one-page summary of the key findings and recommendations.

Key Insights from the Analysis
Contrarian Strategy Wins: The most successful traders in this dataset followed a contrarian strategy. They actively bought assets when market sentiment was in "Fear" or "Extreme Fear."

Panic Selling Leads to Losses: Unprofitable traders showed a clear pattern of selling their assets during these same fearful periods, suggesting that emotional decisions led to their losses.

How to Run the Analysis
Prerequisites: All you need is a web browser and a Google account.

Open in Google Colab: The notebook is designed to run in Google Colab. Simply open the .ipynb file from the /notebooks folder.

Upload Data: When prompted or at the start of the notebook, upload the two .csv files from the /csv_files folder into the Colab session.

Run All Cells: You can run the cells sequentially to reproduce the entire analysis and all the charts.
