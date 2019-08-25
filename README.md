

#### Performance Analysis

1. Calculate and plot cumulative returns. Does any portfolio outperform the S&P 500?

Yes Algo 2 & Berkshire Hathaway. 

2. Calculate the cumulative terms by month and year. What were the best returns in 2017? What were the best returns for December 2018?

2017: Berkshire 

2018: Algo 1

#### Risk Analysis

1. Create a box plot for each of the returns. Which box has the largest spread? Which has the smallest spread?

Largest: Berkshire

Smallest: Algo 2

2. Calculate the standard deviation for each portfolio. Which portfolios are riskier than the S&P 500?

Riskier: Tiger Global Mgmt & Berkshire Hathaway

#### Rolling Statistics

1. Plot the rolling standard deviation of the firm's portfolios along with the rolling standard deviation of the S&P 500. Does risk increase for each of the portfolios at the same time risk increases in the S&P?

Risk increases for all portoflios in a similar fashion, Algo 1 didnt seem to be as risky and had the lowest correlation to S&P500. Second was Tiger Global which showed surprising risk in times when S&P500 didnt show volatility. 

2. Construct a correlation table for the algorithmic, whale, and S&P 500 returns. Which returns most closely mimic the S&P?

Soros, Bershire and Algo 2. 

3. Choose one portfolio and plot a rolling beta between that portfolio's returns and S&P 500 returns. Does the portfolio seem sensitive to movements in the S&P 500?

Yes Custom portfolio had a higher Beta than the S&P500. 1.21 Beta compared to S&P 500. 

### Plot Sharpe Ratios

Investment managers and their institutional investors look at the return-to-risk ratio, not just the returns. (After all, if you have two portfolios that each offer a 10% return, yet one is lower risk, you would invest in the lower-risk portfolio, right?)

1. Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot.

2. Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios.

Only Algo 1 outperforms  S&P500. Algo 2 has a lower sharpe than S&P 500 and other whale portfolios. 

### Create Custom Portfolio

Harold is ecstatic that you were able to help him prove that the algorithmic trading portfolios are doing so well compared to the market and whales portfolios. However, now you are wondering whether you can choose your own portfolio that performs just as well as the algorithmic portfolios. Investigate by doing the following:



3. Add your portfolio returns to the DataFrame with the other portfolios and rerun the analysis. How does your portfolio fair?

AAPL, GOOG & COST are the custom portfolio and they outperform the S&P 500. 
---



---

## Hints

* The Pandas functions used in class this week will be useful for this assignment.

* Be sure to use `head()` or `tail()` when you want to look at your data but don't want to print to a large DataFrame.

---

## Submission

1. Create a Jupyter Notebook containing your data preparation, analysis, and visualizations. Put your analysis and answers to the assignment questions in raw text (markdown) cells in the report.

2. Submit your notebook to a new GitHub repository.

3. Add the URL of your GitHub repository to your Assignment when submitting via Bootcamp Spot.

---

© 2019 Trilogy Education Services
