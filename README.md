# Trader-Behaviour-vs-Market-Sentiment-Analysis
"Analyzes Hyperliquid trader data with Fear–Greed index to explore how market sentiment impacts profitability and trade sizes. Includes data cleaning, merging, visualizations, and statistical tests in Python using Google Colab."
google colab:https://colab.research.google.com/drive/1he35TIiLkwDoKzpyItjmrY3CkpCP-BYE?usp=sharing

## Steps to Run
1. Open `notebook_1.ipynb` in Google Colab.
2. Upload the original trade (XLSX) and sentiment (CSV) datasets.
3. Run all cells to:
   - Clean & merge data
   - Generate summary stats
   - Create visualisations
   - Perform statistical tests
4. Outputs are saved automatically into the `csv_files/` and `outputs/` folders.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- scipy

Install dependencies:
```bash
pip install pandas matplotlib seaborn scipy
