**Azure Data Factory project on Employee and Department data.**

In this Databricks Azure project, you will use Parquet file formats to analyse the Emp_Dept dataset. As part of this you will deploy Azure data factory, data pipelines and visualise the analysis.

**𝗪𝗵𝗮𝘁 𝗶𝘀 𝗗𝗮𝘁𝗮𝘀𝗲𝘁 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀?**
Dataset Analysis is defined as the process of manipulating or processing unstructured data or raw data to draw useful insights and conclusions which will help derive key decisions that will add some business value. The dataset analysis process is followed by organizing the dataset, transforming the dataset, visualizing the dataset finally modelling the dataset to derive predictions for solving the business problems, making informed decisions and effectively planning for the future.

**𝗗𝗮𝘁𝗮 𝗣𝗶𝗽𝗲𝗹𝗶𝗻𝗲**
A data pipeline is a technique for transferring data from one system to another. The data may or may not be updated, and it may be handled in real-time (or streaming) rather than in batches. The data pipeline encompasses everything from harvesting or acquiring data using various methods to storing raw data, cleaning, validating, and transforming data into a query-worthy format, displaying KPIs, and managing the above process.

**𝗗𝗮𝘁𝗮 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀:**

-> The resource manager is created in Azure to categorise the resources required followed by Storage account for storing data required and the Creation of containers for uploading the dataset.

-> We have Azure Blob Storage Account where we are getting all row data (employee, department) in JSON format.

-> The pipeline is created to copy the data in JSON format from Azure Blob storage to Azure Blob storage in the format of CSV in Azure data factory.

-> The pipeline is created which will be able to join the employee and department file based on Department_ID and need to store into Emp_Dept container.

-> And also aggregated information of total department wise employee salary and grouping of Job_ID

-> The Container in Azure is created with the names Employee_data, Department_data, Emp_Dept_data and Aggregated_Data.

-> The Dataset files are uploaded in the Container in Azure.

