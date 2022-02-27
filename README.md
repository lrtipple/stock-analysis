# Stock Market Analysis & Refactor VBA code and Measure Performance

## Overview of Project
This project used my knowledge of VBA to refactor code to make the program use less space and run faster. The program I created, compiled an output of stock market performance in 2017 and 2018.

## Analysis Results
  The overll analysis of the stock market performance concludes that 2017 yielded an average of 67.3% return where 2018 yielded a -8.5% return. 2018 was not a good year for these tickers. 
There were two tickers that had a relatively high return, ENPH (81.9%) and RUN (84%). 
Overall volume each year was similar, average 3.2 billion transactions between all 12 tickers reviewed. 
More specifically looking at the DQ ticker that the client was initially interested in, in 2017 the return was 199% where in 2018 the return was -63%. 
The volume for that ticker in 2017 was on 35,796,200 (3 times as much in 2018). This would not be a good investment stock. 
The DQ stock likely launched in 2017, inflating the return, but over the first full year the return steeply declined.
Out of the 12 tickers provided, I would recommend ENPH and RUN.

![2017 stock analysis](https://user-images.githubusercontent.com/99093289/155895806-bd8b3af3-e5a7-494c-96a3-98af949a49b4.PNG)
![2018 stock analysis](https://user-images.githubusercontent.com/99093289/155895802-c4381f97-9f95-4a24-add2-d9762bbf0344.PNG)

### Code Perfomance Summary and Refactoring
  As I reflect back to my week with creating this program and learning about nested loops, the steps it takes to get to restuls, and then the capability of refactoring, I am wowed! 
My original code took 1.117188 seconds (for 2017) and .875 seconds (for 2018) to run. 
After refactoring the code to use arrays and only 1 for loop, my 2017 code ran in .1523438 seconds and my 2018 code ran in .125 seconds.
The total word count went from 650 to 428 (this includes the comments). I struggled to understand the array and the refactoring challenge. I spent many hours reviewing the material and googling. 
Overall, I understand the concepts taught, and the importance of refactoring to save space/ultimately time.
It is time consuming to code, but for repetative data analyses, coding and refactoring can save an unthinkable amount of time.   

![2017 time elapsed](https://user-images.githubusercontent.com/99093289/155895787-c9c2021b-e02a-438c-a022-3153c1286c2b.PNG)
![2018 time elapsed](https://user-images.githubusercontent.com/99093289/155895797-18b4ba04-92a2-477d-b54a-4ffeab17c74b.PNG)
