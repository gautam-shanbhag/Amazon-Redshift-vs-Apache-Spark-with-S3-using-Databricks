<h1>Comparison of data processing on cloud using Spark with S3 and Redshift </h1>

<h3>Introduction</h3>
Cloud computing is the on-demand delivery of compute power, database storage, applications, and other IT resources through a cloud services platform via the internet with pay-as-you-go pricing [5]. Cloud has opened gateways to big data processing due to its distributed framework. In this project, we will be comparing PaaS systems Spark (using data storage as S3) on Databricks, which is an open source cluster-computing framework for data processing with Redshift, which is a data ware housing system, which stores and analyses large amounts of data. 
	
<h3>Amazon Redshift</h3>
Amazon Redshift is a data warehouse cloud service that helps companies to store and analyse large amounts of data, up to the petabyte scale. It forms a part of the large cloud-computing platform Amazon Web Services. It is built on top of technology from the massive parallel processing (MPP) data warehouse company ParAccel (later acquired by Actian), to handle large-scale data sets and database migrations. It is an enterprise-class relational database query and management system. It is based on a PostgreSQL 8.0.2, but has made many modifications in that version. It makes use of JDBC and ODBC connections to interact with other applications. It supports client connections with many types of applications, including business intelligence (BI), reporting, data, and analytics tools. There is a consensus that high performance and low costs are key advantages of using Amazon Redshift. Amazon Redshift achieves efficient storage and optimum query performance through a combination of massively parallel processing, columnar data storage, and very efficient, targeted data compression encoding schemes

<h3>Spark</h3>
Spark is an open source unified analytics engine maintained by Apache software Foundation for large-scale data processing. It is a general-purpose cluster computing framework. On top of the Spark core data processing engine, there are libraries for SQL, machine learning, graph computation, and stream processing, which can be used together in an application. Application developers and data scientists incorporate Spark into their applications to rapidly query, analyse, and transform data at scale. Tasks most frequently associated with Spark include ETL and SQL batch jobs across large data sets, processing of streaming data from sensors, IoT, or financial systems, and machine learning tasks.
 
<h3>Conclusion:</h3>
Even though spark and Redshift are comparable when it comes to data processing, it all boils down to the requirement of the user. Redshift being a data ware house is preferable when the goal is to archive the data and requires periodical processing of large amount of data, having easy scalability it is suited for applications where the data is ever growing and of different types. However, spark comes handy when we need to process large amounts of data continuously; it is capable of handling streaming data and building machine learning algorithms.
	
<h2>References:</h2>
[1]	Online reference - https://spark.apache.org/
[2]	Image reference - https://www.youtube.com/watch?v=ZTFGwQaXJm8
[3]	https://aws.amazon.com/s3/
[4]	https://spark.apache.org/docs/latest/sql-programming-guide.html
[5]	https://aws.amazon.com/what-is-cloud-computing/
[6]	https://databricks.com/product/unified-analytics-platform
[7]	https://dbengines.com/en/system/Amazon+Redshift%3BSpark+SQL
[8]	https://docs.aws.amazon.com/redshift/latest/mgmt/welcome.html
[9]	https://docs.aws.amazon.com/redshift/latest/mgmt/managing-clusters-console.html
[10]	https://docs.aws.amazon.com/redshift/latest/mgmt/generating-user-credentials.html


