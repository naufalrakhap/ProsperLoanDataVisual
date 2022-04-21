# Loan Data
## by Naufal Rakha Pratama


## Dataset

I choose the data set of loan data from prosper, it is consisted of more than 80 variables that need to be selected at first, which variables will be included for my analysis. Then it comes up with I chose around 18 variables for further analysis, by using drop function I eliminate another variables that less to my concern. After all the variables been collected, next check the existing nan value by using df.info function, then after identify the location of nan value, I start to eliminate this thing by using dropna function. The checking of duplicates are also being done, by using duplicated then also followed by drop duplicates, I delete the duplicate data. Next I change the data type of 'amount delinquent' column from float type into integer type, since the 'amount delinquent' data has only content of integer value, without any decimal, and this is due to preparation for exploratory analysis.

## Summary of Findings

When doing exploratory steps, I make 15 visualizations which consist of 8 univariate exploration, 4 bivariate exploration and lastly 3 multivariate exploration. Here below the list of my exploration summary finding as follow :
Univariate Exploration:
1. The most borrower who borrow the money has the occupation as other,professional,computer programmer, executive, teacher, administrative assistant, analyst, sales-commision, accountant, clerical and sales-retail respectively from top 1 to top 10.

2. Mostly the borrower monthly income is around 4000-5000 dollars. There is also found an outlier since if we do calculate the statistic data, there is someone who borrow the money whose monthly income is up to 1750000 dollars.

3. The most borrower if we categorized it by employment status is employed type with the percentage of 63%, then in second place it is followed by full time type with 23.6 %, and next followed by self-employed,not available,other,part-time, not employed and retired with percentage of 5.6%,2.8%,2.3%,0.9%,0.7% and 0.7% respectively.

4. Most of the loan status in this data set still on progress/current with the total percentage of 51.68%, then in second place it is followed by completed status with the percentage of 32 %, in the third place is chargedoff 10.3% and fourth place status is defaulted with 3.8 %. The rest of status is below 1 % with several status such as past due, final payment in progess and cancelled.

5. The highest borrower rate could be found in the range of 0.30 - 0.33.

6. The main reason of borrower to borrow the money is debt consolidation, next in the second place with the count quantity of around 10000 is not mentioned the reason/not available, in the third place is other, then home improvement and 5th place is for business purposes.

7.  Mostly the amount delinquent value is around 100-1000 USD.

8. The top 10 of state/address which mostly the borrower come from, California with the count of almost 14000, then New York,Florida,Texas,Illnois,Georgia,Ohio,Michigan,Virginia,New Jersey and North Carolina respectively. 

Bivariate Exploration:

9. The data variable of amount deliquency has tendency to be lower with the increase value of borrowers monthly income. It does make sense if the borrower has higher income, they could pay the deliquent therefore they don't have any debt anymore. However it is still found that some borrowers whose income is higher has higher debt as well.

10. The higher duration of borrower being employed, the less recommendations that they got.

11. The highest mean of borrower rate comes from the state of North Dakota with around 0.212 proportion, then next in second place is Alabama with 0.211 proportions. Most of the proportions/rate mean of top 10 state in USA have value of around 0.20.

12. Most of the borrower, no matter their how much their income range, the reason why they mostly borrow the money is because of debt consolidation purposes, then it is followed by another reason such as business, home improvement, other/not mentioned reason, not available reason etc. The highest debt consolidation proposal comes from borrower whose income range between $50,000-74,999.

Multivariate Exploration:

13. We could know that the higher monthly income, it will result in the lower of amount delinquent. And if this condition connected to borrower status employment, the employed borrower tends to have higher amount of delinquent and higher quantity of the borrower from any other type of employment. Then in second place is followed by full time borrower, there are also some full timer whose amount delinquent as high as employed type yet the data not so many and so spread as employed type. And there is also small amount of selm-employed borrower whise amount of delinquent is as high as the two type borrowers (employed and full time) however the quantity is very tiny. Laslty the retired type of borrower has lower amount of delinquent if it s compared to full time, employed and self employed.

14.  The higher amount of delinquent that owned by borrower, the borrower rate will be likely to increase as well. It has slight positive trend betwwen Amount of Delinquent and Borrower Rate. And if these two variables are compared with duration of employment, this variable seems to spread all over each point in variable of delinquent amount. Based on this fact, we could restate that the employment duration clearly doesn't have any correlation with another two variables, since both longer or shorter employment duration has variety of amount of delinquent as well as borrower rate.

15. The employed borrower has the highest mean term when borrowing the money (Mean data from all the state), then in second place is follwed by other type borrower, and the third one comes from self employed type borrower.

As a conclusion, we can conclude that from this loan data set, there is some interesting point to be noted especially when it comes to the variable of monthly income, amount of delinquent, employment status. If we refer to univariate exploration most the borrower has monthly income around 5000 US Dollars, and also the employment status which mostly borrow the money is employed type borrower. Then if we look to multivariate plot of these variables by adding amount of delinquent as the third variable, we could summarize that the higher monthly income of borrower, the amount of delinquent will be lower and employed type borrower which has the most spread data, as well as the highest monthly income and amount of delinquent.


## Key Insights for Presentation

Based on the result of previous exploration steps, there are 3 visualizations which will be polished up and will be brought into explanatory visualization in order to present the loan data from prosper. I believe that these 3 visualizations will almost convey all the information of this data set. The variables such as monthly income of borrower, the amount if delinquent as well as employment status will be presented in three types of visualization, univariate, bivariate and multivariate. The only thing for touching up the explanatory visualization by adding labels, title and any other minor change.