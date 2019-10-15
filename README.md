# databricks-cosmosgraph

This scala  notebook has dependency on following jars 
For interacting with cosmos graph db : azure_cosmosdb_spark_2_4_0_2_11_1_3_4_uber.jar
For graphframes : graphframes_0_7_0_spark2_4_s_2_11.jar

The example also uses the kaggle dataset for san francisco station.csv (vertexes) and trip .csv(edges) between them. 
However we can substitue any csv dataset on the cluster and use the columns accordingly.

The notebook can be trigerred as an ADF activity to upload the graph to cosmos db.
