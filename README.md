# Home_Sales

### **Goal**
To use Spark SQL to determine key metrics about home sales data.
### **Tools**
Spark, SparkSQL
### **Steps**
- Read the AWS S3 bucket into a DataFrame and created a temporary view.
- Ran quiries to determine diffetent metrics about the data.
- Cached the temporary table, ran a query, and comared the runtime to uncached runtime.
- Partitioned by the "date_built" and ran the same query to compare the runtime.
- Uncached the temporary table and verified it.

  *I recieved support from an AskBCS Learning Assistant.*
