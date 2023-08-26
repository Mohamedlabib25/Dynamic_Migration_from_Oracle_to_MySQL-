# Dynamic Migration ETL Job:  Data Migration

Welcome to the repository for the Dynamic Migration ETL (Extract, Transform, Load) Job ,a versatile solution designed to simplify the migration process between various source and target databases using Talend Open Studio for Big Data (version 8.0.1). This guide provides instructions for getting started:

## Key Features:
This single ETL job can do all of these :-
 - Flexible Schema and Constraints Migration: Migrate schema components, including data types, sizes, primary keys, foreign keys, and unique constraints.

 - Data Transformation: Extract data from the source (HR schema for Oracle DB in our case), transform it to match the target data types and formats (like date formats), and load it efficiently into the destination tables (in MySQL DB).


## Getting Started

1. **Prerequisites:** Ensure you have Talend Open Studio for Big Data version 8.0.1 installed on your machine.

2. **Download the Project:**
   - Download Dynamic ETL RAR File > unzip it

3. **Import the Project in Talend:**
   - Open Talend Open Studio for Big Data.
   - Create a new project.
   - Import the project (you downloaded) into the new project you created in Talend.
   - Select job designs > Dynamic_ETL_Oracle_to_MySQL.
   

## Running the ETL Job

1. **Configure Database Connections:**
   - Create the necessary target database tables in MySQL.
   - Modify the properties of two components (Oracle_connection and MYSQL_connection) to match your database settings, including username, hostname, database, schema, and password.

3. **Run the ETL Job:**
   - Right-click the ETL job in the Project Explorer and select `Run`.
   - Choose the appropriate execution context, and the job will execute the migration.

4. **Monitor and Verify:**
   - Monitor the job execution for any errors or warnings.
   - Verify the data and schema in the target database to ensure successful migration.

## Walkthrough Video

Explore a detailed walkthrough of the Dynamic Migration ETL Job and its capabilities in the following video:



https://github.com/Mohamedlabib25/Dynamic_Migration_from_Oracle_to_MySQL-/assets/132618266/57e5d01b-29ab-4036-b817-447e48a1f520


## Notice:
- You can modify this job to handle different scenarios and databases by adjusting the database connections, and some other few components. This ETL framework provides the flexibility to migrate data across a wide range of source and target databases.
- You can use licensced version of Talend which has dynmaic schema feature which will make this large etl so simple with using fewer number of components.

