# Data-Analytics-Project
This contains my Data Analytics with Project Management Bootcamp final project. In this project, I performed comprehensive analysis employing a range of tools including Microsoft Excel, SQL. Subsequently, I used Tableau to create visual representations of the findings and Canva to present the key insights and recommendations.
# About the Dataset
As part of my project, I used a financial dataset consisting of a number of credit card customers, including their demographics. This dataset was from Kaggle and was originally obtained from a website with the URL https://leaps.analyttica.com/home. This dataset consists of 10,127 customers mentioning their age, salary, marital status, credit card limit, credit card category and much more. There are nearly 18 features. There are only 16.07% customers who have churned.

# Business Challenge
A manager at the bank is disturbed with more and more customers leaving their credit card services. They have requested that I predict for them who is going to get churned so they can proactively go to the customer to provide them with better services and turn customers' decisions in the opposite direction.

A few key questions:

How many customers have churned (attrition flag = 1)
How does churn (attrition) look across the different demographics?
What's the average utilisation?

# Objectives
1.Conduct analysis and identify how many customers have churned (left the credit card services).
2'Understand how customer churn differs across the different demographics.
3'Predict the customers that are likely to churn based on analysis, so that the bank manager can provide them with better services.

# Tools used
1.Microsoft Excel
2.Power BI
3.SQL

# Data Cleaning
The majority of the data cleaning was done using Microsoft Excel. The dataset did not need a significant amount of cleaning. As part of the cleaning process:

I checked for any duplicates and was able to identify that there were no duplicates within the dataset.
I inserted an additional column for the customer age bracket (Young Adult, Middle Age, Age) to simplify later analysis.
I used conditional formatting to quickly highlight bank customers within the income category of "less than $40K".
I inserted a few new columns for utilisation ratio categorisation (Low and High) and average utilisation percentage.

#Analysis and Findings
How many customers have churned (attrition flag = 1)?
Using the COUNTIF function, it was identified that 1,627 customers had churned (out of 10,127 customers).

How does churn (attrition) look across the different demographics?
I started my analysis using Microsoft Excel before moving on to  SQL for more advanced analysis:

In Microsoft Excel, I was able to identify that most of the customers who had atttrited were from the female gender (930). Analysis also showed that the majority of customers as a whole were also females at 4,428. I also identified that atrittion count was highest within the middle age customer bracket (1,384). Insights also highlighted that 3,561 customers had an income of less than $40k which was the majority. When looking at the customers card type, a significant amount of customers who had attrited held a blue card type (1,286), which amounted to 92.9% of attrited customers.
Lastly, I did some data exploration using SQL to understand customers' behaviour based on the customer utilisation ratio. The utilisation ratio was slightly higher for females than males for customers who had attrited. I also looked at the customers' dependent count for both genders. The average dependent count was 2.

What's the average utilisation?
Analysis using both Microsoft Excel and SQL highlighted that the average utilisation ratio was 0.27.

#Visualisations and Dashboard
I then created a dashboard using Power BI to visualise my main findings.

# Recommendations and Insights
1.The bank manager should focus on the areas where the bank is losing customers based on demographics. The insights showed that churn is typically coming from Females, the Middle Aged, those who are Married and Single, Blue Card Holders and those with a dependent count of 2/3 dependents.
2.The bank could offer incentives by introducing rewards/special offers to those customers and also monitor their competitior's offerings. It is possible that customers are churning to competitors or are not finding much value in the credit card services. The bank manager can use the information gained from the utilisation ratio and other variables e.g. card type for females, to strategise on the best approach.
3.The bank should also be more proactive with communication. They could increase frequency of customer contacts to keep customers up to date with services and incentives, to ask for feedback, and to identfy any issues as early as possible. Customer churn is currently 16.07% which can be deemed as low, however taking the necessary measures now can help to keep customer churn low, avoid increase in attrition numbers, and possibly bring in new customers.
Data Source: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers - https://leaps.analyttica.com/
