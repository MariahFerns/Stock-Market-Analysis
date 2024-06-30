# 📈Stock Market Analysis and Risk Assessment

## Introduction
This project focuses on extracting, analyzing, and visualizing stock performance data to understand and assess the risk of stocks based on their performance history. The stocks analyzed include Apple, Google, Microsoft, and Amazon, with an initial deep dive into Amazon's stock.

## Objectives
- Use Python libraries such as Pandas, Seaborn, and Matplotlib to extract and analyze stock data.
- Visualize stock performance and analyze various risk metrics.

## Dataset Description
The dataset consists of stock data for the following companies:
- Apple
- Google
- Microsoft
- Amazon

## Methodology
### Data Preparation
1. **Read Data from Yahoo Finance**:
   - Directly read stock data from the Yahoo Finance website using Python.

2. **Data Cleaning**:
   - Perform necessary cleaning to ensure the data is ready for analysis.

### Analysis
1. **Change in Stock Price Over Time**:
   - Analyze and visualize how the stock price has changed over time.

2. **Stock Volume Over Time**:
   - Visualize the change in the stock’s trading volume over time.

3. **Moving Average of Stocks**:
   - Calculate and visualize the moving average for various stocks.

4. **Daily Return Average**:
   - Calculate the daily return average for each stock.

5. **Trend Analysis**:
   - Add a new column ‘Trend’ based on the 'Daily Return' to indicate stock performance trends.
   - Visualize the trend frequency using a Pie Chart.

6. **Correlation Analysis**:
   - Analyze and visualize the correlation between the daily returns of different stocks.

## Folder Structure
- `data/`: Contains any dataset files (if downloaded).
- `notebooks/`: Jupyter notebooks for individual and combined stock analysis.
- `src/`: Python scripts for data extraction, cleaning, and analysis.
- `api/`: Api code (if any).
- `models/`: Trained models and saved results.
- `docs/`: Output files including visualizations and analysis results.

## Installation and Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MariahFerns/Stock-Market-Analysis.git
   cd Stock-Market-Analysis

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

3. Run Jupyter Notebooks:
   Navigate to the notebooks/ folder and open the notebooks to explore data analysis and model development.

4. Run Scripts:
   Use the scripts in the scripts/ folder to extract data, perform cleaning, and conduct the analysis.

## Results and Findings
**Price Movement:**
- The stock prices of Apple, Google, Microsoft, and Amazon show distinct trends and fluctuations over time.

**Trading Volume:**
- Trading volumes vary significantly across the stocks, with certain periods showing higher trading activity.

**Moving Averages:**
- Moving averages provide a clearer view of the stock trends, helping identify long-term movement patterns.

**Daily Returns:**
- Daily return analysis highlights the volatility of each stock.

**Trend Analysis:**
- Trend analysis shows the frequency of positive and negative returns, aiding in understanding stock behavior.

**Correlation:**
- Correlation analysis reveals how closely the stocks' daily returns move in relation to each other.

## Conclusion
This project offers a comprehensive analysis of stock performance, providing insights into price movement, trading volume, trends, and correlations. These findings can assist in making informed investment decisions and assessing stock risks.
