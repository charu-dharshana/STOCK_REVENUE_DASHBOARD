# STOCK_REVENUE_DASHBOARD
# Historical Stock and Revenue Analysis Dashboard

This project focuses on analyzing the historical stock prices and revenue data of prominent companies like Tesla and GameStop. Using Python as the backbone, this project extracts and visualizes the data in an interactive and visually appealing dashboard.

## Project Overview

This dashboard provides a dual visualization of:
- **Historical Share Prices**: Depicting stock market performance.
- **Historical Revenue**: Showing the financial growth or decline.

## Key Features

- **Data Extraction**:
  - Used the `yfinance` API for fetching stock data.
  - Implemented `yfinance`'s `Ticker` function to extract Tesla and GameStop stock data.
  
- **Web Scraping**:
  - Utilized `requests` and `BeautifulSoup` libraries to scrape Tesla and GameStop revenue data.
  - Parsed and processed the data to align with the stock data timeline.

- **Interactive Visualization**:
  - Leveraged the `Plotly` library for plotting interactive line graphs.
  - Created subplots showcasing the historical share prices and revenue data.
  - Enhanced interactivity with zoom and range slider features.

## Dashboard Snapshots

### Tesla Stock and Revenue Data
![Tesla Dashboard](TESLA.png)

### GameStop Stock and Revenue Data
![GameStop Dashboard](GAMESTOP.png)

## Tools and Libraries

- **Programming Language**: Python
- **Libraries Used**:
  - Data Handling: `pandas`
  - Stock Data: `yfinance`
  - Web Scraping: `requests`, `BeautifulSoup`
  - Visualization: `plotly`

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-revenue-dashboard.git
   cd stock-revenue-dashboard
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Follow the notebook instructions to generate the dashboard.

## Insights and Applications

This dashboard provides valuable insights into:
- **Tesla**: Exponential stock price growth aligning with increasing revenues.
- **GameStop**: Stock price volatility with revenue fluctuations over time.

## Future Enhancements

- Add more companies to expand the analysis.
- Integrate live data updates for real-time visualization.
- Enhance the dashboard UI for better user experience.

## Conclusion

This project showcases the power of Python in financial data analysis, combining data extraction, processing, and interactive visualization into one cohesive dashboard.
