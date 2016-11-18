#Hive Jaccard Index

```
sqlContext.sql("DROP TEMPORARY FUNCTION IF EXISTS jaccard")
sqlContext.sql("CREATE TEMPORARY FUNCTION jaccard_similarity AS 'hivemall.knn.similarity.JaccardIndexUDF'")
```
