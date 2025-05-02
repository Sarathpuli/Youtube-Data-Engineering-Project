# Youtube-Data-Engineering-Project
Youtube data Cleaning, Processing and Analysis
**Overview**
This Project focuses on Load, Store and Analyse the Structured and Unstructured Youtube Data using AWS Services based on video categories and the trending metrics.

**Project Goals**
1. Data Ingetion - Build a process to ingest the data from different sources like kaggle, internet, youtube API.
2. ETL System - Extract the data, Transform the data into required format, and load the data and required s3 storage buckets.
3. Data Lake - We will create a centralized repo to store the data collected.
4. Scalability - Make sure data and process is scalable as per the data changes
5. Cloud - Since, the data is huge we need to use cloud to process and perform the analytics. In this project we will be using AWS.
6. Reporting - Build a dashboard to get answers to the questions we had earlier.

**AWS Services used**
Amazon S3: Object Storage Services to store the data.
AWS IAM: Identity Access Management to manage the access b/w servers and users.
AWS Glue: Serverless Data Integration Service to prepare, combine data for analytics, application development.
AWS Lambda: Computational Service that helps to run code without managing/creating any servers.
AWS Athena: Interactive Query Services for S3 data, we can query without loading data saparately. 
QuickSight: Quicksight is a scalable, serverless, embedded Machine-learning Powered BI Service tool.

**PowerBI or Tableau**
1. Used to show dashboards.

**Dataset**
Kaggle dataset 
YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity and/or reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

**Architechture Diagram**

![image](https://github.com/user-attachments/assets/9dbc7624-88e4-42b0-b7d4-c523f256dc75)

**Step by Step Approch**
1. Download the dataset from kaggle
2. Create a S3 bucket where we call it as "Landing Area". ("sarath-de-on-youtube-raw-useast1-dev")
3. load .json and .csv files into S3 bucket using bash commands (Verify .sh file)
4. 
