# challenge
Problem Description

Design a REST API service that, given a set of sales records, returns top k most frequently purchased products of the day. Your system needs to maintain the ranking in a robust manner and should be handle any "top k" requests with fast responses.

If you look inside the zip file, there should be a csv file named "orders.csv" that contains initial dataset. Treat that as the initial dataset for your data.

These sets of API's are required:
1.	Top K Selling Products API: Given two timestamps of "begin", "end", and integer K, return the top K most selling products within the time window from "begin" until "end" 

For example, imagine there is function called "topSellingProducts". The sample inputs would be something like 
[ begin: "2017-04-02 06:04:23", end: "2017-04-10 10:04:23", and k: 10].

2.	Sales Order API: Inserts and gets a sales record. A sales record includes the following attributes: customer_id [string], product [string], count [int], created_at [timestamp], updated_at [timestamp]

For example, sample inputs might be something like
[ "C14253434", "Nike Shoes", 4, "2017-04-02 06:04:23", "2017-04-02 06:04:23"]

You can use your best judgment and knowledge of REST service to design the API signatures. The exact signatures are intentionally open-ended for you to decide. 

