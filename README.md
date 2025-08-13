This project investigates how cryptocurrency trading behavior relates to overall market sentiment using the Fear and Greed Index.

##  Objective

To explore correlations between trading activity (e.g. profit, volume, leverage, side) and market sentiment (Fear, Greed, etc.) and identify patterns for smarter trading strategies.


##  Folder Structure

ds_shrutishah/
├── notebook_1.ipynb # 
├── csv_files/
│ ├── historical_data.csv # Raw trading data
│ ├── fear_greed_index.csv # Sentiment data
│ └── merged_data.csv # Cleaned + merged dataset
├── outputs/
│ ├── *.png / *.jpg # All visualizations
├── ds_report
|  ├── ds_report.pdf
│  ├── colab_output_report.pdf
└── README.md # This file


##  Data Sources

- `historical_data.csv`: Trade info — execution price, size, side, fee, PnL, etc.
- `fear_greed_index.csv`: Daily sentiment scores and categories.

---

## Key Insights

- **Fear** is the most common sentiment across trading days.
- Highest **total profit (Closed PnL)** occurred during 'Fear' and 'Extreme Greed' periods.
- Traders tend to **take larger positions** (Size USD) when the sentiment is fearful.
- **Fee distributions** are more spread during Fear and Neutral phases.
- **BUY trades dominate** in Fear, while **SELL trades increase** in Greed.
- Correlation heatmap revealed a strong relationship between size tokens & USD, and a weak link between sentiment score and execution price.
- Optional clustering grouped traders by average leverage, size, and PnL.

---

## Tech Stack

- **Google Colab**
- **Python** (pandas, seaborn, matplotlib)

---

