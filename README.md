# capstone-1
Capstone project 1 
Capstone Project 1 proposal:
Predicting the significance of Employee welfare benefit plans in the performance of stock price returns
over a 3-year time horizon for stocks in Russell 3000.
Background: The cash-based audited welfare metrics from the Department of Labor could be long-run
indicators of future stock performance
1. What is the problem you want to solve?
Answer: I want to build a regression model that would aim to predict the output of a continuous
value, the stock price returns for the Russell 3000 and the significance of different independent
variables in the movement of stock price returns.
2. Who is your client and why do they care about this problem? In other words, what will your client
do or decide based on your analysis that they wouldn’t have done otherwise?
Answer: Clients are financial data firms or asset managers who would use the results of the analysis
for better stock selection based on the results of the predictive regression model.
3. What data are you using? How will you acquire the data?
Answer: I would use the historical Russell 3000 constituent data for the training dataset and the
Department of Labor Benefit plan data on Employee Welfare and Retirement Benefit Plans.
Both are datasets publicly available from various sources. Some of the sources are:
https://www.ishares.com/us/products/239714/ishares-russell-3000-etf#holdings
https://www.dol.gov/agencies/ebsa/about-ebsa/our-activities/public-disclosure/foia/form-5500-
datasets
4. Briefly outline how you’ll solve this problem. Your approach may change later, but this is a good
first step to get you thinking about a method and solution.
Answer: I would solve the problem as a Supervised Learning regression model, given the
labeled training data (e.g. we already know the stock prices over the years as well as the values of the
independent variables, the welfare benefit factors). It would be Plain batch learning as there is no
continuous flow of data coming into our system and hence there is no particular need to adjust to
changing data rapidly, and the data is small enough to fit in memory.
5. What are your deliverables? Typically, this includes code, a paper, or a slide deck.
Answer: I plan to write a code (and a corresponding slide deck) that builds the model to predict the
stock price returns for the Russell 3000 and the significance of different independent variables in the
movement of stock price returns, given the training data.
