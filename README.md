# Association-Rules---Apriori
Association Rules for items most frequently bought together.

This is my first project to find items usually bought together in the last 2 years 2018-2020. I have pulled out 100000+ transactional data from AccPacc Database. This script cleans the messy data extracted from the databse (orginally in Accounting format). Additionally, the Python script here automatically sorts the data into nice tabular format before running the Apriori algorithm. 

Assuming Accpacc outputs data in the same Accounting format, you can use this script to find items bought together. Recommender metrics (Support, confidence and Lift) are also calculated for your convinience. 

This project helps the sales team, especially for big sale days like Black Friday. The items grouped by the Apriori algorithm can be put on a sales template and serves as a reminder recommend items to customers. 


# Implementation

1. Go to Accpac, and download customer data as a .csv file. 
2. Ensure Python is running from the same relative path 
3. Make necessary changes to the script e.g trading period
4. Run the script


