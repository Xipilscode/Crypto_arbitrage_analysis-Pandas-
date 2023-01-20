# Crypto_arbitrage_analysis-Pandas-

# Project Title

This Jupyter notebook contains the code for collecting, preparing, and analyzing financial data from 2 different exchanges on Bitcoin closing prices to identify arbitrage opportunities. The code begins by importing and reading in CSV files containing financial data.

Next, the data is cleaned by removing missing and erroneous values. The cleaned data is then analyzed through summary statistics and visualizations. Then it is used to select specific time periods for deeper analysis.

The analysis focuses on specific time period by selecting three dates to evaluate for arbitrage profitability. One date is chosen from early in the dataset, one from the middle of the dataset, and one from the last year of the time period. For each of the three selected dates, the code generates summary statistics and creates a box plot. The big-picture view provided by these visualizations helps to gain a better understanding of the data before performing arbitrage calculations.

Finally, the code calculates the Arbitrage Profits for the selected dates. The results of this analysis can be used to identify potential arbitrage opportunities in the financial data.

---

## Technologies

This application is written with Python 3.7 and uses:
   * Jupyter notebook
   * pandas library
   * pathlib module
   

---

## Installation Guide

1. To ceate new conda development environment run the following code in terminal :
```python
conda create --name anaconda
```
2. To install Jupyter lab: 
```python
conda pip install jupyterlab
```
3. To install Pandass lybrarie:
```python
conda pip install pandas
```
4.Open **crypto_arbitrage.ipynb** file in Jupyter notebook.  
  
---

## Usage

1. Choose the columns of data on which to focus your analysis: The first step in analyzing the data is to select the specific columns of data that will be used for the analysis. This may include selecting specific columns of data from the DataFrame such as timestamp and close prices.

2. Get the summary statistics and plot the data: The next step is to generate summary statistics for the selected columns of data and create visualizations such as line and box plots to gain a better understanding of the data. This can be done using the **describe()** function and the **plot()** function from the Pandas library.

3. Focus your analysis on specific dates: Once a general understanding of the data has been gained, the analysis can be focused on specific dates to identify potential arbitrage opportunities. This can be done using the **loc()** function to select specific dates and plotting the data for those dates.

4. Calculate the arbitrage profits: The final step is to calculate the arbitrage profits for the specific dates selected in the previous step. This can be done by comparing the prices of the same asset on different exchanges and calculating the difference between them. The results of this calculation can be used to identify potential arbitrage opportunities.

---

## Contributors
Alex Likhachev

---

## License

MIT

