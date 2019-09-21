# capstone-1
Capstone project 1

Capstone Project 1 proposal:
Goal: Predicting the significance of Employee welfare benefit plans in the performance of stock price returns
over a 3-year time horizon for stocks in Russell 3000 using supervised learning ML models.
Background: The cash-based audited welfare metrics from the Department of Labor could be long-run
indicators of future stock performance

Problem to be solved: Build a regression model that would aim to predict the output of a continuous
value, the stock price returns for the Russell 3000 and the significance of different independent
variables in the movement of stock price returns.

Audience: Financial data firms or asset managers who would use the results of the analysis
for better stock selection based on the results of the predictive regression model.

Data being used: I would use the historical Russell 3000 constituent data for the training dataset and the
Department of Labor Benefit plan data on Employee Welfare and Retirement Benefit Plans.
Both are datasets publicly available from various sources. Some of the sources are:
https://www.ishares.com/us/products/239714/ishares-russell-3000-etf#holdings
https://www.efast.dol.gov/welcome.html

Methodology: I would solve the problem as a Supervised Learning regression model, given the
labeled training data (e.g. we already know the stock prices over the years as well as the values of the
independent variables, the welfare benefit factors). It would be Plain batch learning as there is no
continuous flow of data coming into our system and hence there is no particular need to adjust to
changing data rapidly, and the data is small enough to fit in memory.

Deliverables: I plan to write a code (and a corresponding slide deck) that builds the model to predict the
stock price returns for the Russell 3000 and the significance of different independent variables in the
movement of stock price returns, given the training data.
