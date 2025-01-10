# Stock Clustering Analysis Using K-Means

This project involves clustering stock data into groups based on their returns and variance using the K-Means clustering algorithm. The analysis provides insights into stock trends, enabling investors to categorize stocks as bullish, moderately bullish, moderately bearish, or bearish. The project also saves clustered data into separate CSV files for further analysis.


## Data Source
- The stock data is sourced from Yahoo Finance using historical stock price data.
- Data includes key metrics such as daily returns and variance calculated from the stock price data over a specific time period.

## Features

**1) Data Preprocessing** :

Stock data is analyzed for two key parameters: Returns and Variance.

**2) K-Means Clustering** :

Stocks are clustered into four distinct groups:
- **Cluster 0 (Bearish)** : High risk with significant negative returns.
- **Cluster 1 (Moderate Bullish)** : Stable stocks with low variance.
- **Cluster 2 (Bullish)** : High-return stocks with manageable risk.
- **Cluster 3 (Moderate Bearish)** : Underperforming stocks with potential for recovery.

**3) Stock Trend Classification** :

- Stocks are labeled as Bullish, Moderate Bullish, Moderate Bearish, or Bearish based on their cluster assignments.

**4)Grouping and Saving** :

- Stocks are grouped by trends (Bullish, Moderate Bullish, Moderate Bearish, Bearish).
- CSV files are saved for each trend with the date of saving included in the filename (e.g., Bullish_stocks_2025-01-09.csv).

**5) Visualization** :

- Scatter plots visualize clusters, showing the relationship between Returns and Variance.

## How to Use

**1)Clone the Repository** :

```bash
git clone https://github.com/your-repo-name.git
cd your-repo-name
```
**2)Install Dependencies** :

- Ensure you have Python 3.x installed.
- Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```
**3)Run the Jupyter Notebook** :

- Open the Stock_Clustering.ipynb file in Jupyter Notebook or any compatible environment.
- Follow the step-by-step code cells to preprocess data, perform clustering, and analyze results.

**4)Save and Analyze Results** :

- After running the notebook, the results will be saved as CSV files for each trend.

## Output

**CSV Files** : Clustered stock data saved as separate CSV files based on trends:

- Bullish_stocks_<date>.csv
- Moderate_Bullish_stocks_<date>.csv
- Moderate_Bearish_stocks_<date>.csv
- Bearish_stocks_<date>.csv
- Plots: Visualizations of clusters using scatter plots to understand stock behavior.

## Conclusion
This project provides valuable insights for investors:

- **Cluster 2 (Bullish)** : High returns, manageable risk; ideal for growth investments.
- **Cluster 1 (Moderate Bullish)** : Low risk, stable returns; suitable for conservative investors.
- **Cluster 0 (Bearish)** : High-risk stocks with significant negative returns; should be avoided.
- **Cluster 3 (Moderate Bearish)** : Underperforming stocks; invest cautiously with potential recovery opportunities.