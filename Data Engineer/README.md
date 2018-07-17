# Data engineering exercise 

### Instructions
1. Take the `data_engineer_clean_set.csv` (source) and build an ETL process that is robust against changes over time. 
2. The output should be a parquet file (destination).
3. When done send through your notebook so we can perform tests on your ETL process.

Tip: Schema tracking, unit tests, etc.

### Tooling
We prefer PySpark and jupyter notebooks, but you're welcome to use the tool you are familiar with.

To pull down and run a container with everything you need: `docker run -p 8888:8888 wesselr/data-engineering`

Contains HDFS, Spark, Jupyter, conda, the data and a notebook to get you started, good luck! 
