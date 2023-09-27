# Home_Sales

The goal of this project is to understand and analyze the data using SparkSQL. I wanted to try using Google Colab and get more experience with it. I started by importing and installing all the depencies and libraries related to Colab and then I began a SparkSQL session. I was able to read in the data from AWS and make a DataFrame. This led to a temporary table where I was able to answer some questions. SparkSQL is similar to SQL, so the syntax was the same, but not in postgres and with much more data. 

I answered the questions asked in the module. I filtered, sorted, and used group by with the data. I was able to look at the average price over time with different home like a four bedroom or a three bedroom and three bathroom. Then for the final query, I calculated the running time. This query asked for the view rating for houses euqal to or greater than $350,000. I cached the table and asked the same final query and running time. It was a bit faster with the cached data.

I created a parquet data format and a temporary table with the parquet data. I asked that final query and the running time again. This time the parquet data run time was faster than the first SparkSQL, but slower than the cached data. I uncached the data and everything was complete. 

One more thing to note. I tried to run this notebook in Google Colab a few days after I completed it and the findspark wasn't working. I was able to fix it and get everything to run by changing the spark version to 3.5.0 instead of 3.4.0.
