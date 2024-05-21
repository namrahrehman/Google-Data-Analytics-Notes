A <strong>database</strong> is a collection of data stored in a computer system. <strong>Metadata</strong> is data about data. Metadata tells you where the data comes from, when and how it was created, and what it's all about.

#### Relational database
A relational database is a database that contains a series of related tables that can be connected via their relationships. For two tables to have a relationship, one or more of the same fields must exist inside both tables. They also present the same information to each collaborator by keeping data consistent regardless of where it’s accessed.

In a non-relational table, you will find all of the possible variables you might be interested in analyzing all grouped together. This can make it really hard to sort through. This is one reason why relational databases are so common in data analysis: they simplify a lot of analysis processes and make data easier to find and use across an entire database. 

There are two types of keys that connect tables in relational databases.:
- A **primary key** is an identifier that references a column in which each value is unique.
  - Used to ensure data in a specific column is unique
  - Uniquely identifies a record in a relational database table
  - Only one primary key is allowed in a table 
  - Cannot contain null or blank values
  -  A primary key may also be constructed using multiple columns of a table. This type of primary key is called a **composite key**.
- A **foreign key** is a field within a table that's a primary key in another table.
  - A column or group of columns in a relational database table that provides a link between the data and two tables
  - Refers to the field in a table that's the primary key of another table
  - More than one foreign key is allowed to exist in a table
![image](https://github.com/namrahrehman/Google-Data-Analytics-Notes/assets/93483806/ce2d376e-f4e1-48a3-9f98-a928a663c0a5)

---

#### Metadata
Metadata is used in database management to help data analysts interpret the contents of the data within the database. Regardless of whether you are working with a large or small quantity of data, metadata is the mark of a knowledgeable analytics team, helping to communicate about data across the business and making it easier to reuse data. In essence, metadata tells the who, what, when, where, which, how, and why of data. Metadata ensures that you are able to find, use, preserve, and reuse data in the future. Data analysts use metadata to combine data, evaluate data, and interpret a database.

3 common types of metadata:
- **Descriptive**: Metadata that describes a piece of data and can be used to identify it at a later point in time.
- **Structural**: Metadata that indicates how a piece of data is organized and whether it's part of one or more than one data collection.
- **Administrative**: Metadata that indicates the technical source of a digital asset.

Putting data into context is probably the most valuable thing that metadata does, but there are still many more benefits of using metadata.
- Metadata creates a single source of truth by keeping things consistent and uniform.
- Metadata also makes data more reliable by making sure it's accurate, precise, relevant, and timely.

#### Metadata repository
A database specifically created to store metadata. These repositories describe where metadata came from, keep it in an accessible form so it can be used quickly and easily, and keep it in a common structure for everyone who may need to use it. Using a metadata repository, a data analyst can find it easier to bring together multiple sources of data, confirm how or when data was collected, and verify that data from an outside source is being used appropriately.

Metadata repositories make it easier and faster to bring together multiple sources for data analysis. They do this by describing the state and location of the metadata, the structure of the tables inside, and how data flows through the repository. They even keep track of who accesses the metadata and when.

Metadata is stored in a single, central location and it gives the company standardized information about all of its data. This is done in two ways. First, metadata includes information about where each system is located and where the data sets are located within those systems. Second, the metadata describes how all of the data is connected between the various systems.

#### Data governance
A process to ensure the formal management of a company’s data assets. This gives an organization better control of their data and helps a company manage issues related to data security and privacy, integrity, usability, and internal and external data flows.

Metadata specialists organize and maintain company data, ensuring that it's of the highest possible quality. These people create basic metadata identification and discovery information, describe the way different data sets work together, and explain the many different types of data resources. Metadata specialists also create very important standards that everyone follows and the models used to organize the data.

---

CSV = Comma-separated values. A CSV file saves data in a table format. CSV files use plain text and are delineated by characters, such as a comma. A delineator indicates a boundary or separation between two things. A CSV file makes it easier for data analysts to examine a small part of a large dataset, import data to a new spreadsheet, and distinguish values from one another.

When you work with spreadsheets, there are a few different ways to import data: Other spreadsheets [In Google Sheets, you can use the IMPORTRANGE function], CSV files [In Google Sheets, you can use the IMPORTDATA function in a spreadsheet cell to import data using the URL to a CSV file], HTML tables (in web pages) [In Google Sheets, you can use the IMPORTHTML function]. 

---

#### Sorting data
Arranging data into a meaningful order to make it easier to understand, analyze, and visualize.

#### Filtering
Showing only the data that meets a specific criteria while hiding the rest. A filter simplifies a spreadsheet by only showing us the information we need.

---

[BigQuery](https://cloud.google.com/bigquery/docs) is a data warehouse on Google Cloud that data analysts can use to query, filter large datasets, aggregate results, and perform complex operations.

### SQL best practices
This concise guide highlights key practices for crafting clear, readable, and efficient SQL queries:

**Capitalization & Case Sensitivity:**

* Use uppercase for clause starters (SELECT, FROM, WHERE) and functions (SUM(), COUNT()).
* Employ lowercase for column names (refer to snake_case section).
* Use CamelCase for table names (refer to CamelCase section).
* Be mindful of potential case sensitivity variations between SQL dialects (e.g., BigQuery vs. MySQL).

**Single vs. Double Quotes:**

* Generally, prefer single quotes for strings (e.g., 'US').
* Utilize double quotes when strings contain single quotes (e.g., "Shepherd's pie").

**Adding Comments:**

* Include comments using `--` for single-line or `/* */` for multi-line comments.
* Comments enhance readability and explain query logic.

**Naming Conventions:**

* Adopt snake_case (lowercase with underscores) for column names (e.g., total_tickets).
* Use CamelCase (capitalized first letter for each word) for table names (e.g., TicketsByOccasion).
* Avoid spaces in names.
* Adhere to company naming conventions for consistency, if applicable.

**Indentation:**

* Maintain lines at or below 100 characters for improved readability.
* Proper indentation promotes better code structure and understanding.

**SQL Text Editors:**

* Leverage SQL text editors (Sublime Text, Atom) for color coding and advanced editing features.
* Utilize advanced features like multi-line indent deletion and insertion.
* Explore regular expressions (regex) for complex string pattern searching and replacement.

By following these guidelines, you can write professional and maintainable SQL queries that enhance your data analysis workflow.


---


### Glossary

* **Administrative metadata:** Information about the technical source and origin of a digital asset.
* **CSV (comma-separated values) file:** A plain text file where commas separate values within each record.
* **Data governance:** The formal process of managing and overseeing an organization's data assets.
* **Descriptive metadata:** Information that describes a piece of data, aiding in its identification at a later time.
* **Foreign key:** A field within a database table that references the primary key of another table, establishing a relationship between them.
* **FROM clause (SQL):** Part of a database query that specifies the table(s) from which data will be retrieved.
* **Geolocation:** The geographic location of a person or device determined through digital information.
* **Metadata:** Data that provides information about other data, essentially "data about data."
* **Metadata repository:** A centralized database specifically designed to store metadata.
* **Naming conventions:** Standardized guidelines for file names, ensuring consistency in describing file content, creation date, and version.
* **Normalized database:** A database structure where each table stores related data, minimizing redundancy and improving data integrity.
* **Notebook:** An interactive programming environment allowing users to create data reports, visualize data, and showcase data analysis skills. 
* **Primary key:** A unique identifier within a database table that references a specific column where each value is distinct.
* **Redundancy:** The unnecessary duplication of the same data element across multiple locations within a database.
* **Schema:** A formal description of how data is organized, defining the structure and relationships between data elements.
* **SELECT clause (SQL):** Part of a database query that specifies the specific columns or data points to be retrieved from a table.
* **WHERE clause (SQL):** Part of a database query that defines the conditions or filters that the retrieved data must meet.
* **World Health Organization (WHO):** A specialized agency of the United Nations responsible for international public health leadership and coordination.


---



