First I have selected the datasets.

I have created an databricks account using community edition and created a cluster.

Now i have initiated spark session and imported the files into databricks using AWS S3 Buckets which are nothing but the stirage on the cloud.

Next I have created the StructType and created the table structure.

#FEATURE ENFGINEERING
Here, I have removed the null values and removed the columns which aren't required like for Example, I have removed teh columns called wides abd noballs as I require only valid deliveries.

Next, I have formated the year.


Next I have changed the dataframe using .createOrReplaceTempView, so that I can apply the SQL Queries.

Later, I have written code in Pyspark to create visualizations.
 
