I chose the Prosper Loan Data dataset. The Prosper Loan Data Set has over 81 different parameters for 113,000 different loans since 2009

For exploritory phase I used .info() and .describe() to get a better understanding of the different types of parameters. I also looked for the number of null values included in each column

I created new dataframes with parameters I would like to peform analysis on with null values removed.

I decided to focus on the borrower APR and see what other parameters could be used as predictors for determining borrower APR.

I looked at the distribution of borrower APR, prosper Rating and Credit Score Range Upper

I then compared the borrower APR with Prosper Rating, estimated return  and credit score range.

In the multivariate analysis I created visualizations comparing borrower APR with both credit score range upper and prosper rating. I also created a visualization that compared borrower APR, credit score range upper and estimated return.

I found less variablitiy with estiamted returns for loans with higher credit scores and prosper ratings.

I found that there was a strong negative correlation between Borrower APR and Prosper Rating. I also found that there is a positive correlation between  Estimated Return Borrower APR. I also found that the higher the credit score the lower the borrower APR and the higher the Prosper Rating.



