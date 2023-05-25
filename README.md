For the purposes of this project, I have  computed various Key Performance Indicators (KPIs) for an e-commerce company, RetailCorp Inc. I have been provided real-time sales data of the company across the globe. The data contains information related to the invoices of orders placed by customers all around the world. 

 

At the industry level, an end-to-end data pipeline is built for this purpose. Tools such as HDFS(Hadoop Distributed File System) are used to store the data that is processed by the real-time processing framework and then shown on a dashboard with tools such as Tableau and PowerBI. The image given below is an example of such a complete data pipeline.

![git_img1](https://github.com/Mohammed-Zeeshaan-Saqeeb/Retail-Data-Analysis--Using-Pyspark-Kafka-Hadoop/assets/77388869/6c5371d0-b3fd-4763-a4d4-f926eea4077b)


This project will be focusing on the ‘Order Intelligence’ part of this data pipeline. 
The image given below shows the architecture of the data pipeline that we will follow in this project.

![git_img2](https://github.com/Mohammed-Zeeshaan-Saqeeb/Retail-Data-Analysis--Using-Pyspark-Kafka-Hadoop/assets/77388869/64d8f82a-4b87-4d6f-97a5-451ed2648f17)


Broadly,I have performed the following tasks in this project:

1.Reading the sales data from the Kafka server

2.Preprocessing the data to calculate additional derived columns such as total_cost etc

3.Calculating the time-based KPIs and time and country-based KPIs

4.Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis
