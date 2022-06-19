# Machine-Learning-Customer-Acquisiton
Analysis of a Term Deposit Product's Customer Acquisition by a Bank
Around the end of 2010, a Portuguese bank ran a telemarketing campaign for a term deposit product. A term deposit is comparable to a fixed deposit, in which money is deposited for a specific amount of time.
The bank had gathered information about the prospects' demographics, other financial goods they had purchased in the past (loans, deposits, etc), the number of times they were called, and so on throughout the campaign. They also kept track of the responses, such as whether the client had signed up for the term deposit product, which was the goal variable.
The marketing department at the bank wants to run a new telemarketing campaign for the same product. As a bank analysts, we'd like to use historical data to answer the following questions:


The Issue and the Business Goal
1.	Reduce customer acquisition costs by focusing on those who are most likely to purchase.
2.	To increase the response rate, or the percentage of people who reply to the campaign
3.	Customer information: Data about demographics and other financial goods such as house loans, personal loans, and so on.
4.	Data from the campaign: Information about prior campaigns (number of previous calls, number of days since the last call was made, etc.)
5.	Data on macroeconomics
6.	Variable to be targeted: Answer (Yes/No)

Questions to answer
Which prospects are more likely to buy (or respond) to the product?
What factors influence a person's decision to buy a term deposit?
How many prospects should we telemarket after we've determined the likelihood of a response?
How much will the model cut our marketing costs, and how many prospects will we gain?



Tasks
To overcome the problem, we should create a model that excludes the 'duration' variable. Because the marketing team's prospect data does not have a 'duration' field because the call has not yet been made. This will aid our comprehension of the relationship between the other variables and the response.

Set a corporate goal of obtaining 80 percent of total respondents at the lowest possible cost. From the available data of roughly 45,000 prospects, the total number of responders is the total number of prospects who responded.

Calculate the X in the top X percent based on this information, i.e., how many prospects should be phoned to accomplish the business objective.
Checkpoints
The following are the assignment's checkpoints:
1.	Prepare data and perform EDA.
2.	 Create a logistic regression model without include the 'duration' variable.
3.	Using the standard ways, choose variables.
4.	Sort the data points by response probability in decreasing order.
5.	Determine the best probability cut-off and present the evaluation metrics.
6.	Create a data frame containing the variables prospect ID, actual response, expected response, predicted response probability, call duration in seconds and call cost.
7.	Determine the number of top X percent prospects we should pursue in order to reach the company's goal.
8.	Report on the average duration of calls made to the top X percent of prospects.
9.	Make a lift graph
