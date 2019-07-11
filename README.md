# Basic_DataModelling

# Classification
Build a model using the data in LoanData (The data comes from The Lend- ing Club).

Data Set Information: The data LoanData train.csv and LoanData test.csv is on loans given by The Lending Club. A lot of information on these loans is publicly available. We have taken 10,000 of these loans and sim- plified the data to 11 variables, (you can download the original data at https://www.lendingclub.com/info/download-data.action):
• loan amnt: The amount of money loaned (in US dollars).
• term: The length of time of the loan (in months)
• int rate: The interest rate.
• installment: The amount due to be paid in each installment (in US dollars)
• grade: An assessment of the ‘quality’ of the loan (based on some es- timate of the likelihood that the loan will be repaid, with A being a loan most likely to be repaid and F being the least likely to be repaid).
• home ownership: A variable indicating whether the borrower owns their home, has a mortgage or rents.
• annual inc: The income of the borrower (in US dolloars)
2
      
• verification: Whether the income was verified by The Lending Club
• loan status: Whether the loan was repaid in full ”Fully Paid”, or the
loan was not repaid ”Charged Off”.
• delinq 2yrs: The number of times in the past 2 years that the borrower has been more than 30 days late in the payment of a debt.
• pub rec: The number of derogatory records of the borrower.

# Regression

In this task you will use the auto mpg data to build a linear regression model in order to predict a car’s fuel efficiency based on its other characteristics: ”The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes.” (Quinlan, 1993)
1. mpg: continuous, target variable 2. cylinders: multi-valued discrete 3. displacement: continuous
4. horsepower: continuous
5. weight: continuous
6. acceleration: continuous
7. model year: multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance)
