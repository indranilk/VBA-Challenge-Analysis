# VBA-Challenge-Analysis

Overview of Project:
We analyzed different stocks in 2017 and 2018. We refactored the code to visualize different stock patterns and trends. We created different arrays and looped through each index of the array to calculate Ticker, Total Daily Volume, and Return for all stocks in 2017 and 2018. 

Result:

![image](https://user-images.githubusercontent.com/8925001/118417259-13349800-b668-11eb-9892-7a01abdac8b5.png)

In 2017 the code ran in about 0.66 seconds. All tickers except TERP had positive returns. There were four tickers (DQ, ENPH, FSLR, SEDG) with over 100% returns. Tickers AY and RUN were in the low range of 5-10%. TEPR had returns of -7.2%. 

![image](https://user-images.githubusercontent.com/8925001/118417271-28a9c200-b668-11eb-8fd2-d2c3c607cfdc.png)

In 2018 the code ran in about 0.60 seconds. ENPH and RUN were the only stocks with positive returns. The remaining stocks had negative returns. The tickers AY, SEDG, TERP, and VSLR were in the low range of -10 to 0 %. DQ and JKS had really low returns of less than -60%. 

Summary:

Refactoring the code helped get the right data for the returns. It makes the code more efficient by providing us the results faster. By looping through all the data we get the exact information including the ticker, volume and daily return.  

The original VBA script didn’t have any indexes, arrays, and loops to loop through all the rows of the spreadsheet. Without the refactoring we would just get the total volume and return for the year instead of each stock index for both years.
