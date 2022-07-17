# Ranking-documents-using-Pyspark
This project is about implementing an inverted index using Apache Spark for building the index and a relational database for storing the index using PySpark. Storing the index in a database leveraged the benefit of using the B-Tree data structure offered by a relational database instead of building it from the scratch. 

Steps followed:

1. Building the index using a document collection. 
2. Creating database tables for storing the inverted index. 
3. Implementing the keyword search functionality. 
4. Implementing result ranking using the TF-IDF measure. 
5. Implementing a simple interface for giving keyword queries and showing results. 
