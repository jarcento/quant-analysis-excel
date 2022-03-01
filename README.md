# Statistical analysis of BRK.A
Basic statistical analysis of a share of stock: Berkshire Hathaway Inc. Class A (BRK.A)  
Shows how MS Excel can be used to perform a statistical analysis of empirical data.
## Data
Historical data: daily stock prices (Mar. 1980 to Feb. 2022) downloaded from [Yahoo Finance](https://finance.yahoo.com/quote/BRK-A/).
- Range in days: 15,323
- Range (rounded) in years: 42
## Purpose
- Calculates the daily returns of the stock.
- Constructs a table with the descriptive statistics.
- Constructs a histogram of the returns (normal distribution.)
- Constructs a 95% and a 99% confidence interval for the mean return.
- Performs two sided hypothesis testing for the mean return (H0 is mean equals zero) at a significance level of 5%.
   - Computes the probability of a Type 1 error
   - Computes the probability of a Type 2 error assuming a mean return of 0.5%
- Assuming that returns follow the normal distribution, computes the probability of observing:
   - a daily return of less than -4%
   - a daily return of more than 2%
   - an annual return of less than -20%
   - a quarterly return of more than 7%
- Chooses a second random sample of 40 observations from base sample. Uses the RAND and VLOOKUP functions to automatically generate the sample.
- Calculates the number of days for which the return of the stock is positive or zero (uses the IF 
function). Tests the hypothesis that the proportion is equal to 50% (at a significance level of 5%.)
