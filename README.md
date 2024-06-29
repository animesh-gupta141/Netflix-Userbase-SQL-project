
# Netflix Userbase Analysis




## About
A Sql Analysis of netflix users and their subscription type in differnt countries
## Dataset 

Used Netflix_userbase dataset from [Kaggle](https://www.kaggle.com/datasets/arnavsmayan/netflix-userbase-dataset) 

The dataset provides a snapshot of a sample Netflix userbase, showcasing various aspects of user subscriptions, revenue, account details, and activity. Each row represents a unique user, identified by their User ID. The dataset includes information such as the user's subscription type (Basic, Standard, or Premium), the monthly revenue generated from their subscription, the date they joined Netflix (Join Date), the date of their last payment (Last Payment Date), and the country in which they are located.

Additional columns have been included to provide insights into user behavior and preferences. These columns include Device Type (e.g., Smart TV, Mobile, Desktop, Tablet) and Account Status (whether the account is active or not). The dataset serves as a synthetic representation and does not reflect actual Netflix user data. It can be used for analysis and modeling to understand user trends, preferences, and revenue generation within a hypothetical Netflix userbase.



## Schema

CREATE TABLE netflix.userbase 
(

    UserID INT PRIMARY KEY,
    SubscriptionType VARCHAR(50),
    MonthlyRevenue DECIMAL(10, 2),
    JoinDate DATE,
    LastPaymentDate DATE,
    Country VARCHAR(100),
    Age INT,
    Gender VARCHAR(10),
    Device VARCHAR(50),
    PlanDuration VARCHAR(50)

);
## SQL Questions

Questions to be asked from the dataset:-

Q1: What is the average monthly revenue per subscription type?

Q2:How many users joined in 2022?

Q3: Which country has the highest number of users?

Q4: What is the average age of users by subscription type?

Q5: How many users are using each type of device?

Q6: Which device is the most popular among users aged 30-40?

Q7: What is the total revenue generated from users in 2023?

Q8: Which subscription type has the most users?

Q9: How many users are there in each country by gender?

Q10: How many users made their last payment in June 2023?

Q11: How many users are there in total?

Q12: How many users joined in each year?

Q13: Which are the top 5 countries by user count?

Q14: What is the average join date for users?

Q15: What is the total monthly revenue from each country?
## Solution
[Answers](https://github.com/animesh-gupta141/Netflix-Userbase-SQL-project/blob/main/Answer.sql)