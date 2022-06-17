# Arbitrage_Bitcoin
UW Fintech Bootcamp Module 3 Challenge

-------------

## Purpose of Project
Analyzing historical data from the crypto exchanges (Bitstamp & Coinbase) to   
identify arbitrage opportunities that are net profitable when factoring in a 1%  
processing fee

--------------

## Libraries & Resources
The following libaries we used in this program:  
    *Pandas  
    *Numpy  
    *Pathlib (note: Path only)  
    *Matplotlib  
  
Data from the program was included in the csv files included with assignment including:  
    *bitstamp.csv  
    *coinbase.csv  
  
Primary data used from each file was the Timestamp & Close data columns  
  
-------------
  
## Actions Taken  

Import data from supplied csv files  
Clean the data including:  
    - convert close price to a float  
    - remove duplicates  
    - remove empty cells  
<<<<<<< HEAD
Generate summary statistics for each file
Review delta between markets as seen below:

=======
Generate summary statistics for each file  
Review delta between markets as seen below:  
![bitstamp_vs_coinbase](https://user-images.githubusercontent.com/105887423/174191335-37f91ac1-aaab-4f3e-bbb3-ed981f654243.png)

Analyze data from 3 specific dates including:  

