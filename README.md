# Simple ETL Example: PySpark DataFrame to MongoDB Collection

In this simple example we extract data from a CSV file into a PySpark Dataframe.  
The file is local in this example, but could have been inside an HDFS, a S3 data lake, or the data could have been retrived from an API endpoint.  The file could also have been of any file type (eg: Avro, Parquet, Json, etc..)

We then explore the data, and perform some transformations on it before loading it into a MongoDB collection for retrieval.
