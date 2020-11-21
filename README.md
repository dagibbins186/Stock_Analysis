# Stock_Analysis
          <head>
            <title>**Project Background**</title>
          </head>
A client sought insights into green-energy-investing. This project examines the stocks' performance over time. At the press of a button, cacluations of the daily volume and the return of stocks run. This macro prevents cumbersome calcuations and human error.
**Results**
Upon opening the worksheet, the client is prompted to run an analysis.
![Run%20Analysis%20Image](https://github.com/dagibbins186/Stock_Analysis/blob/main/Resources/Run%20Analysis%20Image.png)
When the client clicks the button, a prompt appears.
![Prompt](https://github.com/dagibbins186/Stock_Analysis/blob/main/Resources/Prompt.png)
If the client enters 2017, then a table appears with this year's results.
![2017_Analysis_Results](https://github.com/dagibbins186/Stock_Analysis/blob/main/Resources/2017_Analysis_Results.png)
The results show a fruitful year for green energy. Positive returns appear in green. Negative returns display in red. Among the stocks that the client watches, 11/12 turned a profit. The DQ stock did the best at (199%). They story changes if the client clears the worksheet, and enters 2018 to arrive at results.
![2018_Analysis_Results](https://github.com/dagibbins186/Stock_Analysis/blob/main/Resources/2018_Analysis_Results.png) In 2018, only 2/12 green stocks showed positive returns: ENPH and RUN. ENPH and RUN also performed well in 2017. Their consistency over time suggests they may be better investments than other green stocks in this portfolio. 
**Summary**
Over a few iterations, the code was restructured without changing its behavior. For instance, instead of hard coded numbers, the script looks for the last row. If the data set grew, the code could adapt to this change. Continuously improving code, makes it easier to work with. Other updates made the statements easier to read, which facilitates reproducability over time. Code refracturing also made the calculation process faster. For example, the code was put into an array. An array run's the information through memeory. This is more efficient than going to the worksheet, getting a value, reading it and writing back a value. With these updates, this process ran in 39410 seconds versus 63417 seconds.
