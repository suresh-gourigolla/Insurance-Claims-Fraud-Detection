# Insurance-Claims-Fraud-Detection
Business case:
Insurance fraud is a huge problem in the industry. It's difficult to identify fraud claims.

Data is stored in different systems and its difficult to build analytics using multiple data sources. Copying data into a single platform is time consuming.

Business solution:
Use S3 as a data lake to store different sources of data in a single platform. This allows data scientists / analysis to quickly analyze the data and generate reports to predict market trends and/or make financial decisions.

Technical Solution:
Use Databricks as a single platform to pull various sources of data from API endpoints, or batch dumps into S3 for further processing. ETL the CSV datasets into efficient Parquet formats for performant processing.
