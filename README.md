### Stock Price Analysis and Visualization

This code performs an analysis and visualization of historical stock prices for four major technology companies: Apple (AAPL), Google (GOOG), Microsoft (MSFT), and Amazon (AMZN). Here's a simple explanation of the key steps involved:

1. **Data Fetching**:
   - The code fetches historical stock price data for the specified companies from Yahoo Finance using the `yfinance` library.
   - The data is fetched for the past year from the current date.

2. **Data Preparation**:
   - The fetched data is stored in separate DataFrames for each company.
   - A new column `company_name` is added to each DataFrame to identify the company.

3. **Concatenation**:
   - All company DataFrames are concatenated into a single DataFrame for combined analysis.

4. **Summary Statistics**:
   - Summary statistics (mean, standard deviation, min, max, etc.) are generated for each company's adjusted closing prices.

5. **Visualization**:
   - **Closing Prices**: Plots showing the adjusted closing prices for each company over the past year.
   - **Volume**: Plots showing the trading volume for each company over the past year.
   - **Moving Averages**: Plots showing the adjusted closing prices along with 10-day, 20-day, and 50-day moving averages for each company.
   - **Daily Returns**: Plots showing the daily percentage change in adjusted closing prices for each company.
   - **Daily Return Histograms**: Histograms showing the distribution of daily returns for each company.

### Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `yfinance`

### Usage

1. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn yfinance
   ```

2. **Run the Script**:
   ```bash
   python main.py
   ```

### Note

- The code uses the `yfinance` library to fetch data. Ensure you have an active internet connection.
- The visualizations provide insights into the stock price trends, trading volume, and daily returns for the selected companies.

---

This code provides a basic framework for analyzing and visualizing stock data. You can extend it by adding more companies or performing additional analyses.
