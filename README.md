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
  
Generate summary statistics for each file  
Review delta between markets as seen below:  
![bitstamp_vs_coinbase](https://user-images.githubusercontent.com/105887423/174191335-37f91ac1-aaab-4f3e-bbb3-ed981f654243.png)

Analyze data from 3 specific dates including:  
   - 28 January 2018  
   - 6 February 2018  
   - 20 March 2018  

Calculate arbitrage profits for each particular day assuming a return greater than 1%  
![Jan cumulative profits](https://user-images.githubusercontent.com/105887423/174199105-902c29ef-3741-4c64-bc69-43398d409be7.png)

![Graphical Cumulative Profits](https://user-images.githubusercontent.com/105887423/174199114-e9f2d063-10e8-4c03-abd7-9bdb87d3edc0.png)

------------  

## Conclusion

All the data points to a scenario where the market is correcting a strong arbitrage that existing in January of 2018.  
   - Total potential profit on 28 January was $350K
   - By February 6 it had dropped to $10K
   - I was unable to find any arbitrage opportunities in March that were greater than the 1% threshold that was established
