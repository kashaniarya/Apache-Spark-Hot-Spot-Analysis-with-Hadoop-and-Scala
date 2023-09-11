# Apache-Spark-Hot-Spot-Analysis-with-Hadoop-and-Scala
Project focuses on performing spatial queries on a large database containing geographic data and real-time customer locations from a taxi company. The objective is to use Apache Spark and Scala to analyze spatial data and extract valuable insights for operational and strategic decisions.

Key Objectives:

Set up Apache Spark and utilize dataframes for data management.
Write Scala code and execute it.
Work with geospatial data and perform queries on it.

Technology Requirements:

Apache Spark
SparkSQL
Scala
Java
Hadoop

Project Description:

The project involves using Scala and Apache Spark to analyze a provided dataset. 
This analysis helps extract essential information for making informed operational and strategic decisions. The technology enables access to significant geographic locations that can be used for planning and enhancing customer service.

Tasks:

Hot Zone Analysis: 
Perform a range join operation between rectangle and point datasets to calculate the "hotness" of rectangles based on the number of points within them.

Hot Cell Analysis: 
Apply spatial statistics to spatio-temporal big data to identify statistically significant spatial hot spots using Apache Spark. This task involves implementing a Spark program to calculate the Getis-Ord statistic for NYC Taxi Trip datasets.

Input Data Format:

Point data: The input point dataset represents the pickup points of New York Taxi trips.
Zone data (only for hot zone analysis): Zone data is provided.

Output Data Format:

Hot Zone Analysis: List of zones with their counts, sorted by "rectangle."
Hot Cell Analysis: Coordinates of the top 50 hottest cells, sorted by their G-score.
