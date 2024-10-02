# instagram_user_analytics_using_mysql

Project Description: 
This project focuses on analyzing user engagement, marketing metrics, and detecting 
abnormal activity on a simulated Instagram platform using SQL. The goal is to 
provide actionable insights to both the marketing team and investors by answering 
specific business-related questions. These include identifying the most loyal and 
inactive users, finding the most popular hashtags, determining the contest winners, 
analyzing user engagement metrics, and detecting potential fake or bot accounts. The 
analysis will help guide marketing efforts, ensure healthy user activity, and highlight 
any issues with platform integrity. 

Approach: 
To tackle the tasks and derive insights, I followed a structured approach: 
1. Data Understanding: I reviewed the database schema and familiarized myself 
with key tables, such as users, photos, likes, comments, tags, and follows. 
2. Task Execution:
o For user engagement, I calculated average posts per user and compared 
total photos to total users. 
o For bot detection, I identified users who liked every single photo. 
o For marketing insights, I analyzed the most loyal users, inactive users, 
contest winners, and popular hashtags. 
o I also analyzed the best day for launching ad campaigns by checking 
registration trends. 
3. SQL Queries: I wrote targeted SQL queries to extract the relevant data for 
each task. I used aggregation functions like COUNT(), AVG(), and GROUP 
BY to perform calculations and identify trends in user behavior. 
4. Data Analysis: After retrieving the data from SQL, I analyzed the results, 
focusing on patterns in user behavior, engagement, and suspicious activity

Tech-Stack Used: 
 MySQL Workbench (Version 8.0): I chose MySQL Workbench as it is a 
robust and user-friendly tool for SQL database management and allows easy 
execution of complex queries and database design. 
 SQL (Structured Query Language): SQL was used to query the data, 
leveraging its powerful aggregation, joining, and filtering capabilities to derive 
meaningful insights. 
 Data Modeling: The database schema was designed using a relational model 
with foreign key constraints to maintain referential integrity between entities 
(users, photos, comments, etc.). 

Insights: 
From the data analysis, several important insights were derived: 
1. Loyal Users: The platform's five oldest users have been consistently active 
since its inception, indicating strong user loyalty. 
2. Inactive Users: A significant number of users have not posted any photos, 
which suggests an opportunity for re-engagement through targeted campaigns. 
3. Contest Winner: The top 3 users with the most-liked photos were identified, 
with one standing out as the clear contest winner. 
4. Popular Hashtags: The top five most frequently used hashtags were identified, 
providing valuable insights for brand partners to optimize their content 
strategy. 
5. Ad Campaign Timing: Most user registrations occur on weekends, suggesting 
that weekend ad campaigns might reach the largest number of new users. 
6. Bot Detection: Several users were flagged for having liked every single photo 
on the platform, indicating potential bot activity.

Result: 
This project provided valuable insights into user behavior on the platform. By 
identifying loyal and inactive users, I helped the marketing team shape their 
engagement strategies. The detection of bot-like activity also helped the team 
consider future security measures to maintain platform integrity. The analysis 
of popular hashtags and registration trends allowed the marketing and product 
teams to make data-driven decisions about future campaigns and feature 
prioritization. This project has enhanced my understanding of user data analysis 
and has demonstrated how SQL can drive business strategy and improve 
platform health.

Quaries and Outputs:
A) Marketing Analysis
 1) marketing analysis

 
![Screenshot (95)](https://github.com/user-attachments/assets/e1ed75f6-ffd9-44fd-bcb7-aa8b3d408f0c)

2) inactive user engagement
   


![Screenshot (96)](https://github.com/user-attachments/assets/c180ca81-972f-4640-88e7-7af55443b86d)

3) contest winner declaration
   
![Screenshot (97)](https://github.com/user-attachments/assets/81f7e649-d4a1-44da-ade8-e703550623ab)

4) hashtag research 

![Screenshot (98)](https://github.com/user-attachments/assets/273a5030-d58f-4083-923c-bd5e80fef3c1)

5) ad campeign launch
   
![Screenshot (99)](https://github.com/user-attachments/assets/5b4c77a0-35bf-4bd2-9075-85b24b22cb84)

B)Investor Metrics 
1) user engagement
   

![Screenshot (100)](https://github.com/user-attachments/assets/6176591b-8fe6-4454-93b0-6e6af309002e)

total number of photos on Instagram divided by the total number of users. 

![Screenshot (101)](https://github.com/user-attachments/assets/e42eded8-1b0d-4f0d-bf67-4a16215e3dcd)

2) bots and fake accounts
   

![Screenshot (102)](https://github.com/user-attachments/assets/eaed761a-85da-463a-a7e1-2128824fa9d8)
