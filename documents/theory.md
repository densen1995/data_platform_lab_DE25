**Notes: ETL pipeline Glossary**

- Ingest -> Bringing/reading  raw data into the system, example CSV/JSON files using Pandas
- Storage -> Cleaning datasets and saving in a structured format(example PostgreSQL database)
    - *As CSV outputs , in PostgreSQL using Psycopg3*
- Transform -> Cleaning , validation , structuring data , flagging suspicious data, example using Pandas
    - *Example, converts price to  numeric, reject invalid rows and impossible values, flag data.*
- Access -> Retrieving and analyzing data(example, generating analytics ready data or SQL queries for BI reports)
    - *Analytics generated example: average price, median price, total  products, most expensive products.*


**Psycopg3**
- Database management/driver tool for python 
- Connecting Python to  a database, example, DuckDB, PostgreSQL
- Executing SQL
- Bulk loading data/file(CSV, JSON and others) into databse

**Pydantic**
- Data validation and schema enforcement library before database insertion 
- Enforce data structure

**Filtering/Exploring**
- Filtering in the database based on analytical/business requirements using different methods/tools , example Pandas, SQL 
- Might involve getting/extracting information required by stakeholders by creating more tables in a database with even new columns (alias)
- Example: agrregation; average, median, ranking, total, queries, exceptions etc,  using Pandas or can better be done when data is transformed and stored in a database.

**Ingestion into a database (PostgreSQL) using PGAdmin**

- Querying the database (table analytics_summary)after creating and importing the csv file.
- Generating a graphical insight of the table through a bar chart in pgAdmin:

<image src= "analytics_summary.png", width=500>
