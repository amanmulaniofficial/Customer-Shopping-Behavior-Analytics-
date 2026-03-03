# Customer-Shopping-Behavior-Analytics-project

Customer Shopping Behaviour Analytics
An end-to-end data analytics project where I analysed customer shopping data to answer real business questions using Python, SQL, and Power BI.

What I did
Started with a raw dataset of 3,900 customer records. Cleaned it up in Python — handled missing values, standardised column names, and created a couple of new features like age groups and purchase frequency in days.
Then wrote 10 SQL queries to dig into the data and answer questions like:

Which gender generates more revenue?
Do subscribed customers actually spend more?
Which products get discounted the most?
How do customers break down into New, Returning, and Loyal segments?

Used some more advanced SQL too — CTEs, window functions, conditional aggregation.
Finally pulled everything into Power BI to build a dashboard that ties it all together visually.

Tools

Python (Pandas) — cleaning & feature engineering
SQL — business analysis
Power BI — dashboard


Files
FileDescriptionCustomer_data.ipynbData cleaning & EDA notebookCustomer_Data.sqlAll 10 SQL queriescustomer_data.pbixPower BI dashboard

A couple of things I found interesting

Subscribed customers consistently spend more — big case for pushing subscriptions
Some products had a 100% discount rate, meaning nobody ever bought them at full price
The window function for ranking top products per category (Q8) was probably the most fun query to write
