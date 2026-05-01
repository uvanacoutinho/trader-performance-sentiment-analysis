# Trader Performance vs Market Sentiment Analysis

## Overview
This project presents a data-driven analysis of how market sentiment (Fear/Greed) influences trader behavior and profitability on Hyperliquid. By combining transactional trading data with sentiment indicators, the study identifies patterns that drive trading outcomes across different market conditions.

## Objective
The objective of this analysis is to evaluate whether trader profitability is driven more by external market sentiment or by internal execution behavior, such as trade frequency, position sizing, and fee efficiency.

## Methodology
The analysis follows a structured approach:

- Data preparation: Cleaning, validation, and alignment of trader and sentiment datasets at a daily level  
- Feature engineering: Construction of key metrics including net PnL, trade frequency, volume, fee ratio, and trade efficiency  
- Exploratory analysis: Evaluation of performance and behavior across sentiment regimes  
- Behavioral segmentation: Classification of traders into archetypes (Scalpers, Whales, Retail) based on normalized activity patterns  
- Predictive modeling: Implementation of a Random Forest model to assess drivers of profitability and feature importance  

## Key Insights
- Profitability peaks during moderate Fear conditions, suggesting an optimal balance between opportunity and risk  
- Execution behavior is the primary driver of performance, with trade frequency and fee efficiency having greater impact than sentiment  
- High-frequency traders demonstrate more consistent outcomes across sentiment regimes  
- Profitability is unevenly distributed, with average performance influenced by a small number of high-impact trades  

## Tech Stack
- Python: Pandas, NumPy  
- Visualization: Seaborn, Matplotlib  
- Machine Learning: Scikit-learn (Random Forest Classifier)  

## How to Run
1. Clone the repository  
2. Open `analysis.ipynb` in Jupyter Notebook or Google Colab  
3. Run all cells to reproduce the analysis  

## Output
The notebook includes:
- Sentiment vs performance visualizations  
- Behavioral segmentation results  
- Trader archetype comparisons  
- Predictive modeling outputs and feature importance  

## Conclusion
The analysis demonstrates that while market sentiment provides useful context, trader execution behavior is the dominant factor influencing profitability. These findings can support the development of more effective trading strategies and platform-level interventions focused on execution efficiency and risk management.
