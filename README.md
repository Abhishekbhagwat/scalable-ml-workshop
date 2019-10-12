# Big Data Analytics & Scalable Machine Learning @ iNTUition v6.0


This repo contains the files and descriptions for the Big Data Analytics and Scalable Machine Learning Workshop @ iNTUition v6.0 

##### Basic Requirements
   1. Python
   2. SQL
##### Recommended Requirements
   1. pandas
   2. Machine Learning concepts
   3. Jupyter


#### Step 1

Setup a [Databricks Community Edition](https://community.cloud.databricks.com/) account as we will be using their clusters to run our Spark jobs.

#### Step 2

1. On your console, click on the  `New Cluster` tab
2. Add in your cluster name let the other options stay in their default setting and then click on `Create Cluster`
3. Wait for a few seconds and verify that your cluster name appears on the final page.
4. Go back to the console by clicking on the Databricks logo button

#### Step 3

1. Create a new Notebook by clicking on the `Create Notebook` tab
2. Choose Python as your language and then click Create
3. Once the Notebook is created, you can verify your install by running the command
```python
import pyspark.sql
```

