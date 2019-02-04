# Data engineering exercise 

### Instructions
1. Take the `data_engineer_clean_set.csv` (source) and build an ETL process that is robust against changes over time. 
2. The output should be a parquet file (destination).
3. When done send through your notebook so we can perform tests on your ETL process.

### Important 
* Please ensure each of the above points are completed before submitting. 
* To complete this exercise your ETL process should be able to handle or flag issues such as schema changes, data issues, nulls etc.
* This assessment is designed to show that you can develop and maintain complex ETL processes. This position is not just an admin position, it is much more, so please show us that in your submission.

### Tooling
We prefer PySpark and Jupyter notebooks, but you're welcome to use the tool you are familiar with.

To pull down and run a container with everything you need: `docker run -p 8888:8888 wesselr/data-engineering`

Contains HDFS, Spark, Jupyter, conda, the data and a notebook to get you started. 

Good luck! 
