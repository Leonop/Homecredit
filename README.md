# Homecredit
Home credit interview case
Modelling Exercise

Scenario
You are a data analyst in bank and have the budget to contact only 100 people as part of a new marketing campaign. 
You can offer these customers 1 of 3 different products:
1.	Mutual Fund (MF)
2.	Credit Card (CC)
3.	Consumer Loan (CL)
Each of these 100 people can only receive 1 offer for 1 product.
The 100 people should not have been part of the previous marketing campaign (See description of data below).

Goal
Your goal in this task is to select the best 100 people and which product to offer them based on maximum potential revenue.

Your selection should be driven by the following key points:
1.	How likely the customer is to accept an offer from each product.
2.	How much revenue would be gained if the customer took that offer.

Description of data
In the attached excel spreadsheet you will find information for 1,615 of the bank’s clients.

This spreadsheet has the following 5 worksheets: 
1.	Description of data fields. 
2.	Social-demographical data (age, gender, tenure in the bank)
3.	Products currently owned + product balances (current account, saving account, mutual funds, overdraft, credit card, consumer loan).
4.	Behavioral data from clients products - Inflow/outflow on current account, aggregated card turnover (monthly average over past 3 months) 
5.	Sales and revenue data from a previous marketing campaign.
a.	60% of the 1,615 clients in the data have this information, this data should be used for modelling. 
b.	We assume all clients were given an offer for the 3 products MF,CC,CL (1 means they took the offer, 0 they didn’t).
c.	The 100 clients to select as you final answer should be chosen from the remaining 40% (the 646 clients that are not included in this dataset). 

Suggested Approach
1.	Compile a modelling dataset with potential model variables.
2.	Build predictive models to answer the 2 key points in the goal section above.
3.	Use these models to determine the clients maximum estimated revenue for this marketing campaign.

Questions
1.	Which clients are more likely to buy consumer loan? 
2.	Which clients are more likely to buy credit card? 
3.	Which clients are more likely to buy mutual fund? 
4.	Which clients are to be targeted with which offer? General description. 
5.	What would be the expected revenue based on your strategy? 
6.	How well do your models perform?
7.	How did you ensure the models would continue perform well once applied to the 40% of clients?

Results format
Our preferred software in which to complete this analysis would be Python or SAS, however if this is not possible you may use other software.

Please provide the following:
1.	A summary document (maximum of 2 pages) providing a simple explanation of the steps you took and the key results from the above questions.
2.	An example of your work such as Python/R/SAS scripts used in the analysis.
