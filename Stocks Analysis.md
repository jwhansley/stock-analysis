# Stocks Analysis

## Putting together a spreadsheet that can easily analyze stock data at scale

### We want to put together a spreadsheet that provides us with a clear analysis of the provided data, while also making the code scalable as we receive more data and need to do deeper analysis

## Results & Summary

### Comparison of stock performance between 2017 and 2018

- In 2017 almost all the stocks see a positive return, while in 2018 almost all the stocks see a negative return
- Stocks ENPH and RUN both saw positive returns in both 2017 and 2018
- While DQ saw the largest positive return in 2017, it saw the largest negative return in 2018

### Comparison of execution times between original and refactored code
- The refactored code ran with a considerably lower execution time for both 2017 and 2018

### Summary
- The advantages of refactoring this code is that it will be considerably easier to scale as we add in more years and more Tickers
- The disadvantages was that as we tried to factor in more automation, the code sprawled pretty quickly.  It was difficult to keep things together, and took considerably more trial and error to get variables, loops, and conditionals to align, especially when going between nested and non-nested loops

## Results


- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Launching a campaign between May and June is more likely to see a successful campaign
2. Launching a campaign in December is not ideal as it’s the only month where the amount of failed campaigns is close to the amount of successful campaigns.


- What can you conclude about the Outcomes based on Goals?
1. Don't launch anything above a $45000 goal
2. Keeping a campaign below $5000 makes it pretty likely to succeed

- What are some limitations of this dataset?
1. We don’t know what happened between launch and close.  How were these campaigns marketed and promoted to drive sign ups.  Are there big donors or professional marketers that are impacting successful campaigns
2. We don’t know what other types of funding these plays have.  Is Kickstarter the only funding available


- What are some other possible tables and/or graphs that we could create?
1. I was interested in looking at the average backing amount as well as the amount of backers per month to see if there’s a particular month where people are more generous or have a higher likelihood to back a campaign
2. Continuing to filter down to "plays" and "musicals" within the "theater" parent category could give us better insight, as "spaces" are irrelevant to our campaign and may skew the numbers.
