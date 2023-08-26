# Dynamic Migration ETL Job: Universal Data Migration

Welcome to the repository for the Dynamic Migration ETL (Extract, Transform, Load) Job, a versatile solution designed to simplify the migration process between various source and target databases using Talend Open Studio for Big Data (version 8.0.1). This guide provides instructions for getting started:

## Getting Started

1. **Prerequisites:** Ensure you have Talend Open Studio for Big Data version 8.0.1 installed on your machine.

2. **Download the Project:**
   - Clone this repository or download it as a ZIP file and extract it to your preferred location.

3. **Import the Project in Talend:**
   - Open Talend Open Studio for Big Data.
   - Create a new project.
   - Import the project (you downloaded) into the new project you created in Talend.
   - Select job designs > case study > Dynamic_ETL_Oracle_to_MySQL.
   - Create the necessary target database tables in MySQL.

## Running the ETL Job

1. **Configure Database Connections:**
   - Modify the properties of two components (Oracle_connection and MYSQL_connection) to match your database settings, including username, hostname, database, schema, and password.

2. **Run the ETL Job:**
   - Right-click the ETL job in the Project Explorer and select `Run`.
   - Choose the appropriate execution context, and the job will execute the migration.

3. **Monitor and Verify:**
   - Monitor the job execution for any errors or warnings.
   - Verify the data and schema in the target database to ensure successful migration.

## Walkthrough Video

Explore a detailed walkthrough of the Dynamic Migration ETL Job and its capabilities in the following video:

[![Dynamic Migration ETL Job Video](https://github.com/Mohamedlabib25/Dynamic_Migration_from_Oracle_to_MySQL-/assets/132618266/f0d0b9e5-e460-4319-8b14-c131f084c45e)](https://github.com/Mohamedlabib25/Dynamic_Migration_from_Oracle_to_MySQL-/assets/132618266/f0d0b9e5-e460-4319-8b14-c131f084c45e)

## Notice:
You can modify this job to handle different scenarios and databases by adjusting the database connections, and some other few components. This ETL framework provides the flexibility to migrate data across a wide range of source and target databases.

