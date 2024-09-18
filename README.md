# AWSproject-Aakash

Objective Project 1 

In Project 1, I aimed to use the data of the migration of the City of Vancouver data to an AWS cloud platform. The focus of this project is to build an efficient data analytics pipeline, which will provide better infrastructures for processing, analyzing, and visualizing data for various departments of the city. The emphasis will be on scalability and security. Using the cloud infrastructure, the project would strive towards smoothing out the data management of the city for easy access and decision-making. It will help in seamlessly handling big volumes of data, which include advanced analytics and insight visualizations, through a scalable and secure system that will meet the increasing needs of the city's data.







Table of Contents 

   •	Methodology

   •	Data Discovery

   •	Data Pipeline Design

   •	Data Analysis

   •	Data Visualisation

   •	Data Publishing


Methodology 

Data Analytical Question Formulation 

Data for the years 2022 and 2023 were dug into, showing the metric called "Awarded Contracts." The metric will show the percentage of calls handled in the years 2022 and 2023, respectively.



![image](https://github.com/user-attachments/assets/ae1f1fce-00dc-456a-9207-237afcbf1089)

Data Discovery 
Concentrated on the process of 'Awarded Contracts Metrics' inside the Government and Finance division of the city of Vancouver.

Below is the data utilized for the project1.  

![image](https://github.com/user-attachments/assets/db2275d2-715d-4c32-914c-ce7769097491)


Data Storage Design 

Safe data storage was achieved by using Amazon S3, where data was classified into three stages: Landing, Raw, and Curated. 

  •	Dataset Preparation 

  •	Data Collection

  •	ETL processes

  •	Data cleaning using AWS Glue DataBrew 


Data Pipeline Design 

For Data processing  Draw.io is being used.

![image](https://github.com/user-attachments/assets/0257cc26-3f5f-4985-bcff-3b04436560b5)

![image](https://github.com/user-attachments/assets/c8f15782-77b3-41da-9c92-63e8b7e68f9c)


Data Analysis 

Executed utilizing AWS Athena for querying and providing valuable information.

  •	AWS Services

  •	Amazon S3 for storage

  •	EC2 for computation

  •	AWS Glue for ETL processes

  •	Athena for data analysis.




Data Pipeline Implementation


  •	Utilized AWS Glue for Extended Transaction Lifetime (ETL) operations.


  •	These transformation processes included schema modifications, aggregate, and union actions.


  •	To modify the structure of the 2022 and 2023 dataset, all unnecessary columns have been removed and the columns BID_ID, Year, Awarded, and Award Category  have been retained and renamed. 


  •	An aggregate operation has been used to combine the entries of the 'Year' column in the dataset for the years 2022 and 2023.


  •	In order to generate a combined dataset from the records of 2022 and 2023, the Union function has been used to produce a new output by combining all the records from the two comparable input datasets. 


At this point, undesired columns have been removed using the alter schema procedure. 
Derived Column: The matrix is computed at this step by executing the SQL function. Successfully managed awarded contracts


![image](https://github.com/user-attachments/assets/1022cd1e-0baf-42f1-b140-df65dedcec22)

Data Analysis 

  •	The data analysis was conducted utilizing AWS Athena architecture. 
  
  •	Analysis of the dataset content was conducted using a SQL database.

Below is the data derived from the database of  AWS Athena:  

![image](https://github.com/user-attachments/assets/fd126d31-9e87-4167-b612-d5ae68a14f29)


Result 

  •	Amazon EC2 was used to establish a General Server and Web Server for both internal and external data access.
  
  •	Issued the yearly analysis report detailing the proportion of Awarded Contracts for public access.

![image](https://github.com/user-attachments/assets/a1708f30-8488-4c7d-ac8b-a97ed3288a50)

Insights and Findings 3

In 2022, the 'Awarded contract' for the City of Vancouver achieved a call handling rate of 285, therefore demonstrating a commendable level of efficiency in award management. 
The proportion of calls managed decreased somewhat to 285.

This decreases, however insignificant, suggests a little deterioration in the efficiency of processing calls compared to the prior year. 

Between 2022 and 2023, there is a significant decline in the proportion of awarded contracts effectively managed. This may be attributed to many things, including a surge in bid category or difficulties in allocating resources.


Costing 

For Team Assignment 1 our detailed team assignment costing is mentioned below as per the AWS services used by every team member:

  •	Amazon S3: Estimated annual expense of $285.846 for storage across four buckets.

  •	AWS Glue DataBrew: Estimated yearly cost of $32.04 for cleaning and restructuring datasets.

  •	AWS Glue: Estimated total cost of $13.20 for ETL job runs.

  •	Amazon Athena: Estimated annual expense of $35.76 for querying and analysis.

  •	EC2: Total yearly cost of $225.96 for hosting general and web servers.

Conclusion
This study demonstrates the efficacy of using AWS cloud services for extensive data analytics and emphasizes the potential to automate data processes and obtain valuable insights for urban administration.



Project 2 
The aim of this research is to effectively compute the student graduation rates for the years 2022, 2023, and 2024 at the University Canada West (UCW) with precision. This initiative aims to use sample data, including student records and course completion statistics, to provide significant insights into student performance, detect patterns, and provide data-driven suggestions to enhance future graduation rates.

