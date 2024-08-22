# Bike Share Data Analysis Project

## Project Overview

This project involves analyzing a dataset from a bike sharing system to derive insights and make recommendations based on key performance indicators (KPIs). The analysis focuses on hourly revenue, profit and revenue trends, seasonal revenue, and rider demographics. The goal is to determine whether prices should be increased for the next year.

## Workflow

1. **Create a Database**: Set up a database to store and manage the bike share data.
2. **Develop SQL Queries**: Write SQL queries.
3. **Connect Power BI to Database**: Use Power BI to connect to the database and import data for analysis.
4. **Build a Dashboard in Power BI**: Design and create an interactive dashboard to visualize the data.
5. **Answer the Analysis Questions**: Analyze the data to answer specific business questions and make recommendations.

## Tools and Technologies

- **Docker**: Used to create a containerized environment for running SQL Server.
- **Azure Data Studio**: A cross-platform database management tool used for managing the database.
- **Power BI**: Used for creating interactive visualizations and dashboards.

## Dataset
```bash
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbl81V202ZlJZNlF2NVJ0T3BmeGxtT2Q1b1BXQXxBQ3Jtc0tsTjB2TGtqWU53NzBUMXg1UmxNblpFZEZpamJ0S1JFZFQ3NXZvSkxiTXBrTHhvdk1CMm4xNnhjd3k5SHgzQ0xiQ0dWVVNJc090cmRUTVZSdVMybFRRbm84b1dHMzRzNGFEbktvQUpNN2VMVEdobkV2SQ&q=https%3A%2F%2Fgithub.com%2FGaelim%2FYT_bike_share&v=jdGJWloo-OU
```
## Detailed Workflow

### 1. Create a Database

Since SQL Server and SQL Server Management Tools are not available for macOS, Docker was used to create a containerized SQL Server environment. 

**Steps:**
1. **Install Docker**: Ensure Docker is installed and running on your MacBook.
2. **Pull SQL Server Docker Image**: 
   ```bash
   docker pull mcr.microsoft.com/mssql/server:2022-latest
3. **Run SQL Server Container**:
   ```bash
   docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=Your_password' -p 1433:1433 --name sql_server_container -d mcr.microsoft.com/mssql/server:2022-latest
4. **Access SQL Server**: Use Azure Data Studio to connect to the SQL Server instance running in the Docker container.

### 2. Develop SQL Queries

Write SQL queries in Azure Data Studio to extract and analyze data from the database.

### 3. Connect Power BI to Database
### 4. Build a Dashboard in Power BI
