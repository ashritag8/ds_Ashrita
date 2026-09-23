# Bitcoin Market Sentiment & Trader Behavior Analysis

This project analyzes the relationship between Bitcoin market sentiment 
(Fear & Greed Index) and actual trader performance, using Hyperliquid 
trading logs (211,000+ trades). It includes both a Python-based 
exploratory analysis and an interactive Power BI dashboard built on 
the same data.

## Key Insight
Trader profitability and activity peak sharply on "Fear" days — both 
realized PnL and trade volume are highest when market sentiment is 
fearful. Activity drops noticeably during "Greed," "Extreme Greed," 
and "Neutral" periods.

## What's in this repo
- `trade.pbix` — Power BI dashboard: DAX measures, Power Query data 
  cleaning (including Unix timestamp conversion and data type 
  correction), and a modeled relationship between trade and sentiment 
  data
- `notebook_1.ipynb` — Python analysis (Pandas) merging and exploring 
  the same datasets
- `ds_report.pdf` — written summary of findings
- `csv_files/` — source data: Hyperliquid trade log and Bitcoin Fear 
  & Greed Index
- `outputs/` — exported charts and results

## Tools Used
**Power BI**: DAX, Power Query, data modeling  
**Python**: Pandas, Matplotlib, Seaborn  

## Notebook
Google Colab Notebook Link: [Open Here](https://colab.research.google.com/drive/1MwOR5B9cnyKpLImfYIppzn_3FLavUcOT?usp=sharing)
