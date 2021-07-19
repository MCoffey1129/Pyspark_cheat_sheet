Pyspark_cheat_sheet
===

Spark Documentation:  
https://spark.apache.org/docs/latest/api/python/  
https://spark.apache.org/docs/latest/api/python/getting_started/quickstart.html#Selecting-and-Accessing-Data
https://spark.apache.org/docs/2.1.0/api/python/pyspark.sql.html

MLLIB specific documentation:  
https://spark.apache.org/docs/latest/ml-guide.html

Python libraries

```python
from pyspark.mllib.____ import ______
from pyspark import SparkConf, SparkContext

from pyspark.sql import *
spark = SparkSession.builder.getOrCreate()


