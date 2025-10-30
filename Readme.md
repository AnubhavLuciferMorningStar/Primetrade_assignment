# Data Science Assignment — PrimeTrade Web3 Trading Team

## 👨‍💻 Candidate
**Anubhav Sharma**

## 📁 Project Overview
This project explores the relationship between **trader performance** and **Bitcoin market sentiment (Fear vs. Greed)** using data from Hyperliquid and the Fear & Greed Index.

The analysis identifies how trading behavior (profitability, risk-taking, leverage, and volume) aligns or diverges from overall market sentiment and uncovers patterns that can guide smarter trading strategies.

## 📊 Folder Structure
```
ds_anubhav_sharma/
├── Primetrade_assignment.ipynb          # Main analysis notebook
├── aggregated_outputs/                  # Processed and aggregated CSVs
│   ├── daily_aggregates.csv
│   ├── account_daily.csv
│
├── csv_files/                           # Original or intermediate CSV files
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│
├── outputs/                             # Charts, statistical results & cluster data
│   ├── total_pnl_by_sentiment.png
│   ├── sentiment_correlation.png
│   ├── account_clusters.csv
│
└── Primetrade_assignment_report.pdf     # Final summarized report
```

## ⚙️ Steps Performed
1. Data loading and preprocessing from Google Drive
2. Timestamp normalization and feature engineering
3. Daily and per-account aggregation of trader metrics
4. Correlation analysis between market sentiment and trader performance
5. Statistical tests (t-test, Mann–Whitney U)
6. Trader segmentation using K-Means clustering
7. Visualization of key insights

## 📈 Key Insights
- Market **Greed** sentiment showed **negative correlation** with trader PnL and volume.
- Traders tend to perform better during **Fear** phases (contrarian tendency).
- **K-Means clustering** identified distinct trader profiles (low-risk, high-risk, consistent performers).
- Contrarian and risk-aware strategies can potentially improve returns during high-sentiment phases.

## 🧰 Tools & Libraries
- **Python**, **pandas**, **NumPy**, **matplotlib**, **seaborn**
- **scikit-learn**, **SciPy**, **Google Colab**
- **GitHub** for version control and submission

## 📄 Deliverables
- `Primetrade_assignment.ipynb` — Main notebook with all analyses
- `Primetrade_assignment_report.pdf` — Summary report with insights and recommendations

## 🚀 How to Reproduce
1. Open `Primetrade_assignment.ipynb` in Google Colab.
2. Mount your Google Drive and adjust file paths if necessary.
3. Run all cells sequentially to regenerate outputs and figures.
4. Review visualizations and reports in the `outputs/` folder.

## 🏁 Conclusion
This project demonstrates how sentiment-driven market behavior affects trader performance. The insights can guide trading strategies, risk management, and portfolio optimization in Web3 trading environments.
