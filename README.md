# Dynamic Migration ETL Job: Oracle to MySQL

Welcome to the repository for the Dynamic Migration ETL (Extract, Transform, Load) Job, tailored to simplify the migration process from Oracle databases to MySQL using Talend Open Studio for Big Data (version 8.0.1). This guide provides instructions for getting started:
  
## Getting Started

1. **Prerequisites:** Ensure you have Talend Open Studio for Big Data version 8.0.1 installed on your machine.

2. **Download the Project:**
   - Clone this repository or download it as a ZIP file and extract it to your preferred location.

3. **Import the Project in Talend:**
   - Open Talend Open Studio for Big Data.
   - create a new project.
   - import the project (u downloaded) to the new project u created in talend.
   - Select job designs > case study > Dynamic_ETL_Oracle_to_MySQL.
   - Create the database in Mysql.
  

## Running the ETL Job

1. **Configure Database Connections:**
   - u will need to modify two components (Oracle_connection,MYSQL_connection) to suit the properities like(username, hostname,database,schema,password). 


2. **Run the ETL Job:**
   - Right-click the ETL job in the Project Explorer and select `Run`.
   - Choose the appropriate execution context, and the job will execute the migration.

4. **Monitor and Verify:**
   - Monitor the job execution for any errors or warnings.
   - Verify the data and schema in the MySQL database to ensure successful migration.

## Walkthrough Video

Explore a detailed walkthrough of the Dynamic Migration ETL Job and its capabilities in the following video:

[![Dynamic Migration ETL Job Video](https://github.com/Mohamedlabib25/Dynamic_Migration_from_Oracle_to_MySQL-/assets/132618266/f0d0b9e5-e460-4319-8b14-c131f084c45e)](https://github.com/Mohamedlabib25/Dynamic_Migration_from_Oracle_to_MySQL-/assets/132618266/f0d0b9e5-e460-4319-8b14-c131f084c45e)

Experience the efficiency and power of dynamic migration with our ETL job, making your Oracle to MySQL migration process smooth and effective.
