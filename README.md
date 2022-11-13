#  Prosper Loan Data Exploration


## Dataset

Prosper loan data made available through Udacity. Using this URL: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000, it was downloaded. Each loan in this dataset has 81 characteristics, including the loan amount, borrower rate (or interest rate), current loan status, borrower income, and many more. There are 113,937 loans in this dataset.

To see how organised and clean the data was, I did data wrangling on it. Since each row represented an observation and each column a variable, the data wasn't too messy. There weren't any extra copies. It was necessary to link columns like Credit grade and prosperRating (Alpha). Many values were missing and certain datatypes were incorrect. I chose the relevant variable and those that would be required for the analysis. I sanitised the data carefully so as not to lose too much information.

## Summary


I performed an exploratory analysis on the distribution of each feature I chose, examining the distribution of each variable and how they related to one another. I discovered that the percentfunded variable had very weak correlations with other variables, likely as a result of the PercentFunded values of 1.0 being the majority in the loan observations.

One of the interesting facts found when examining the distribution of interesting univariables was that California State has the most borrowers. When I looked at the borrowers' work status, I found that the majority of them were either employed or had full-time jobs. Further research into their source of income led me to the conclusion that they typically earn between $25,000 and $74,999 per month, with a right-skewed monthly income distribution, and that they typically make less than $30,000. Additionally, their income ratio is right-skewed.
As I continued my bivariance analysis to look at the links between the two variables in the data, I found that there was a strong correlation between "Recommendations" and "friends that invest," but little to no association between LenderYield and PercentFunded.
Finally, regarding Multivariant exploration,
- CurrentlyInGroup and lenderYield have a significant correlation when plotted with PercentFunded.
- When plotted with PercentFunded, CreditScoreRange and lenderYield have a strong correlation.
- When plotted with PercentFunded, MonthlyLoanPayment and lenderYield show a strong relationship.

## Key Insights for Presentation

I focused on demonstrating variation in variables with percent funded and determining attributes of loan observations with percentFunded for the presentation.
After that, I used percentFunded to examine a variety of category data and some numerical data. I was able to see the pattern I mentioned in the explanation visualisation slide when I used boxplots to examine the link between categorical data and the percent financed.
I utilised a scatterplot for the numerical data and some categorical data, plotted lenderyield and percentfunded to gain more insights, and summarised the pattern seen in the PowerPoint.
