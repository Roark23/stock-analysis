# stock-analysis
## Overview of Project
The purpose of this project was to help Steve analyze many stocks over time to understanding their trends and performances. We analyzed about a dozen stocks, but we want to refactor our code to be able to process and analyze thousands of stocks. We created a solution code to loop through all the data at one time to collect key information relating to a stocks trading volume and return over time.
## Results
### Stock Performance through 2017 and 2018
After analyzing the stocks in 2017 and 2018, we can draw some data driven conclusions regarding stock performances. Of the 12 stocks analyzed in 2017, only the TERP stock had a negative return (-7.2%). ![Stocks_2017](Stocks_2017.png)
It's evident when looking at the stock performances in 2018 ![Stocks_2018](Stocks_2018.png) that the stocks overall performed way better in 2017. Only 2 of the stocks had positive returns in 2018 comparedto the 11 stocks with positive returns in 2017. Many stocks had drastic changes from 2017 to 2018. For example, Steve's parents wanted to look at DQ for a potential investment. DQ had a 199.4% return in 2017 and a -62.6% return the next year with it trading at roughly 3x the daily volume. 
### Refactored Code
We successfully refactored the code to be able to loop through many stocks and find the necessary information. The goal was to maximize how efficient the solution code is by looking at how fast the code ran. It's evident the code ran much faster after we refactored it. On average, the code run time for Stocks in 2017 went from 0.7851563 seconds to 0.0859375 seconds. ![2017_Refactored_Code_Run_Time](VBA_Challenge_2017.png) ![2017_Code_Run_Time](VBA_Challenge_2017_oldrun.png)
For 2018, the average code run time went from 0.8242188 seconds to 0.1171875 seconds. ![2018_Refactored_Code_Run_Time](VBA_Challenge_2018.png) ![2018_Code_Run_Time](VBA_Challenge_2018_oldrun.png)
## Summary
Refactoring is an essential part of the coding process. Refactoring the code is a process of making the code run as efficient as possible. The process doesn't involve adding any new functionality. It's critical that we take the time to refactor our code as there are many ways to improve the coding proccess and execution.
### Advantages/Pros
There are many advantages/pros to refactoring the original VBA script. Refactoring allows you to better understand the code adn how it's operating. Advantages of refactoring code making the code more efficient by eliminating or combining steps in the process. This results in using less memory and allows the code to run faster. We can improve the logic of our VBA script when refactoring which is evident in this stock analysis.
### Disadvantages/Cons
There are not many disadvantages/cons to refactoring. Usually, it's just a tedious process to refactor and can take up valuable time that may be needed elsewhere. It's also possible to mess up the code and make it not work when you are refactoring it, but yoy can usaually revert back to the code you had previously. 
### Overall, it may take valuable time to refactor code but it provides many advantages by essentially making the code run more efficiently.
