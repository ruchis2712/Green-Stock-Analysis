# Challenge 2
## Green-Stock-Analysis

### Objective
The file analyzes daily stock data to produce a summary of stock performances based on traded volume and returns for the selected year. This enables an informed decision by the investor

### Structure
The file has 2 tabs for yearly data and a Summary Analysis tab that has All Stocks Analysis

### Macro Logic Used in the file
The macro broadly follows the steps below:

(1) For the selected year, it goes into the relevant sheet and finds the number of Unique stock tickers and initializes 4 arrays for all tickers to store Ticker Name, Traded Total Volume, the Start Price and the End Price

(2) It then loops through the data and reads it into these arrays for each unique ticker

(3) FInally it write all these arrays to the summary sheet and formats the data to show good and bad performing stocks at a glance

### Findings: ENPH ticker stock has provided consitent positive returns in both 2017 and 2018. It also has a high trading volume
