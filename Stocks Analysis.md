# Stocks Analysis

## Putting together a spreadsheet that can easily analyze stock data at scale

### We want to put together a spreadsheet that provides us with a clear analysis of the provided data, while also making the code scalable as we receive more data and need to do deeper analysis

## Results & Summary

### Comparison of stock performance between 2017 and 2018

![VBA_Challenge_2017](https://user-images.githubusercontent.com/16244455/136484803-85a9427c-463d-4796-8108-cd97b912396a.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/16244455/136484813-19073e60-3511-4ddf-8181-5ab29562b6c8.png)

- In 2017 almost all the stocks see a positive return, while in 2018 almost all the stocks see a negative return
- Stocks ENPH and RUN both saw positive returns in both 2017 and 2018
- While DQ saw the largest positive return in 2017, it saw the largest negative return in 2018

### Comparison of execution times between original and refactored code
- The refactored code ran with a considerably lower execution time for both 2017 and 2018

### Summary
- The advantages of refactoring this code is that it will be considerably easier to scale as we add in more years and more Tickers
- The disadvantages was that as we tried to factor in more automation, the code sprawled pretty quickly.  It was difficult to keep things together, and took considerably more trial and error to get variables, loops, and conditionals to align, especially when going between nested and non-nested loops.
