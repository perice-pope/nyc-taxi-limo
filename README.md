# Welcome to Perice's NYC Taxi & Limo!

Hi! Thanks for taking the time to read my solution. You can get to the databricks notebook by going to this link. I have made access to it public. 


# How to Run Code 

Download and open notebook 
Click on **run all** and the code will run and create the parquet summary file
Can also click on CSV download at second to last command  

## About My Solution 

I chose spark on Databricks because of the concept of RDD! Spark uses Resilient Distributed Dataset (RDD) to achieve faster and efficient MapReduce operations. For example, I was able to process 50 million rows per minute with this solution!  

If we were going to run this on our machines (which IDK about processing 50GB on a laptop) :D ....but I would go about it another way using some multi threaded solution. 

I noticed there was some dirty data, the life of a data guy! I used 12345 as payment type because there were many many payment types. 
