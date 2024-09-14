
# COURSE NAME : FULL STACK DATA SCIENCE , MACHINE LERNING , ARTIFICIAL INTELLIGENCE, GEN AI

## MODULE 1 : DATA BASE MANAGEMENT SYSTEM

## 1. Introduction to DBMS
- Definition and Overview of DBMS
- Characteristics of DBMS
- Applications of DBMS
- DBMS vs. File System

## 2. What is DBMS?
- DBMS Components
- Types of DBMS (Hierarchical, Network, Relational, Object-Oriented)

## 3. Relational Data Models
- Introduction to Relational Model
- Concepts: Relations, Tuples, Attributes, and Domains
- Relational Schema
- Keys: Primary, Foreign, Candidate, and Composite

## 4. Data Integrity Rules
- Entity Integrity
- Referential Integrity
- Domain Integrity
- User-defined Integrity

## 5. Normalization
- Need for Normalization
- First Normal Form (1NF)
- Second Normal Form (2NF)
- Third Normal Form (3NF)
- Boyce-Codd Normal Form (BCNF)
- Denormalization

## 6. Introduction to Data Processing Methods - Client/Server
- Client-Server Architecture Overview
- Multi-tier Architectures
- Data Distribution in Client/Server Systems

## 7. Oracle Architecture
- Oracle Instance and Database
- SGA and PGA
- Oracle Background Processes
- Physical Structure: Datafiles, Redo Log Files, Control Files
- Logical Structure: Tablespaces, Segments, Extents, Blocks

## 8. SQL (Structured Query Language)
- Overview of SQL: DDL, DML, DCL, and TCL
- SQL Commands and Syntax

## 9. Creating Tables
- Basic CREATE TABLE Syntax
- Defining Data Types for Columns
- Creating Temporary Tables

## 10. Identify Columns
- Choosing Primary Keys and Foreign Keys
- Identifying Constraints for Columns

## 11. Integrity Constraints
- Types of Constraints: NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, CHECK
- Managing Constraints: Enabling, Disabling, Dropping

## 12. Adding, Updating, and Dropping Columns
- ALTER TABLE Syntax for Adding, Modifying, and Dropping Columns

## 13. Transaction and Locking
- Concept of Transactions
- ACID Properties of Transactions
- Implicit and Explicit Locking
- Lock Types: Shared, Exclusive
- Deadlocks and Resolution

## 14. SQL Functions
- Single-Row Functions (String, Numeric, Date, Conversion)
- Aggregate Functions (SUM, AVG, COUNT, MIN, MAX)

## 15. Grouping Data
- GROUP BY Clause
- HAVING Clause

## 16. Using ROLLUP and CUBE
- Introduction to ROLLUP and CUBE
- Data Aggregation with ROLLUP and CUBE
- Practical Use Cases

## 17. Query Row Limits and Row Offsets
- FETCH FIRST, OFFSET, LIMIT, and ROWNUM Usage in Queries

## 18. Joining Tables
- Inner Joins, Outer Joins (LEFT, RIGHT, FULL)
- Cross Join and Self Join

## 19. ANSI Join
- Introduction to ANSI SQL JOIN Syntax
- Advantages of Using ANSI Join Over Traditional Join Syntax

## 20. Subqueries
- Types of Subqueries: Single-Row, Multi-Row, Correlated Subqueries
- Subquery in SELECT, INSERT, UPDATE, and DELETE Statements

## 21. Working with TOP-N Analysis
- Concept of TOP-N Analysis
- Using ROWNUM or LIMIT for TOP-N Queries

## 22. Views
- Creating Views
- Updating Data through Views
- Dropping Views

## 23. Materialized Views
- Difference Between Views and Materialized Views
- Refreshing Materialized Views
- Usage of Materialized Views in Performance Optimization

## 24. Using Indexes
- Types of Indexes: B-tree, Bitmap, Function-Based Indexes
- Creating and Managing Indexes
- Impact of Indexes on Performance

## 25. Security
- User Privileges and Roles
- Granting and Revoking Privileges
- Managing User Access Control

## 26. Flashback Query
- Using Flashback Query to Recover Data
- Limitations of Flashback Query

## 27. MERGE Statement
- Syntax and Use Cases of the MERGE Statement for UPSERT Operations

## 28. Multitable Insert
- Syntax for Multitable INSERT
- Conditional and Unconditional Multitable Insert

## 29. Using Regular Expressions
- Introduction to Regular Expressions in Oracle
- REGEXP_LIKE, REGEXP_INSTR, REGEXP_REPLACE, REGEXP_SUBSTR Functions

## 30. Fine-Grained Dependency Tracking
- Introduction to Dependency Tracking
- Managing Object Dependencies


#### Module 2 : Python Programming 

# Python Important Topics

## 1. Variables and Data Types
- Definition of variables
- Assignment and reassignment of variables
- Dynamic typing in Python
- Data types:
  - Integer
  - Float
  - String
  - Boolean
  - List
  - Tuple
  - Set
  - Dictionary
  - NoneType
- Type conversion (casting)
- `type()` and `isinstance()`

## 2. Operators
- Arithmetic Operators: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Assignment Operators: `=`, `+=`, `-=`, etc.
- Comparison Operators: `==`, `!=`, `>`, `<`, `>=`, `<=`
- Logical Operators: `and`, `or`, `not`
- Bitwise Operators: `&`, `|`, `^`, `~`, `<<`, `>>`
- Identity Operators: `is`, `is not`
- Membership Operators: `in`, `not in`

## 3. Control Flow (if, elif, else, loops)
- `if` statements
- `else` statements
- `elif` for multiple conditions
- Nested `if-else` structures
- `for` loops (iterating over lists, tuples, strings, etc.)
- `while` loops (loop until a condition is met)
- Loop control:
  - `break`
  - `continue`
  - `pass`
- Nested loops
- `else` clause with loops

## 4. Functions
- Defining functions using `def`
- Function parameters and arguments
- Return values
- Default arguments
- Keyword arguments
- Variable-length arguments (`*args`, `**kwargs`)
- Recursive functions
- Anonymous functions (`lambda`)
- Scope and Lifetime of variables
- Higher-order functions (passing functions as arguments)

## 5. Lists, Tuples, Sets, Dictionaries
- Creating and accessing lists
- List methods: `append()`, `remove()`, `pop()`, `sort()`, etc.
- Slicing lists
- Tuples: Immutable collections
- Tuple operations
- Set: Unordered collections
- Set operations: union, intersection, difference, etc.
- Dictionary: Key-value pairs
- Dictionary methods: `get()`, `keys()`, `values()`, etc.
- Iterating over dictionaries

## 6. List Comprehensions
- Creating lists using loops in one line
- Conditional list comprehensions
- Nested list comprehensions
- Creating dictionaries using comprehensions
- Set comprehensions

## 7. String Manipulation
- Creating and accessing strings
- String slicing
- String methods: `upper()`, `lower()`, `replace()`, `split()`, `strip()`, etc.
- String formatting with `format()`, f-strings, `%` operator
- String concatenation
- Escape sequences
- Multiline strings
- Regular Expressions (Regex)

## 8. File Handling
- Opening files using `open()`
- Reading from files: `read()`, `readline()`, `readlines()`
- Writing to files: `write()`, `writelines()`
- File modes: `r`, `w`, `a`, `b`
- Closing files
- Using `with` statement for file handling (context manager)
- File paths (absolute vs relative paths)
- Handling binary files
- CSV file handling using Python's `csv` module

## 9. Exception Handling
- `try`, `except` blocks
- Handling multiple exceptions
- `finally` clause
- `else` clause
- Raising exceptions with `raise`
- Custom exceptions
- Exception hierarchy in Python

## 10. Modules and Packages
- Importing modules (`import`, `from ... import`)
- Standard library modules
- Creating your own modules
- Python packages (`__init__.py`)
- Installing external packages using `pip`
- Understanding Python's package structure
- Namespace packages

## 11. Object-Oriented Programming (OOP)
- Creating classes and objects
- Attributes and methods
- Constructor: `__init__()`
- Inheritance
- Polymorphism
- Encapsulation and abstraction
- `super()` function
- Method overriding
- Class methods and static methods
- Dunder (Magic) methods (`__str__`, `__repr__`, `__len__`, etc.)
- Properties and getters/setters

## 12. Iterators and Generators
- Iterators: `__iter__()` and `__next__()`
- Creating iterators from collections
- Generators using `yield`
- Generator expressions
- `next()` function
- Using `for` loops with iterators and generators
- Advantages of generators (memory efficiency)
- Infinite iterators

## 13. Decorators
- Functions as first-class objects
- Higher-order functions
- Creating decorators
- Applying decorators using `@`
- Chaining multiple decorators
- Function decorators and class decorators
- Decorators with arguments
- Built-in decorators: `@staticmethod`, `@classmethod`

## 14. Lambda Functions
- Syntax of lambda functions
- Use cases of lambda functions
- Lambda with `map()`
- Lambda with `filter()`
- Lambda with `reduce()`
- Limitations of lambda functions
- Nested lambdas

## 15. Regular Expressions
- Basics of regular expressions
- `re` module functions: `search()`, `match()`, `findall()`, `sub()`, etc.
- Special characters: `.` , `^`, `$`, `*`, `+`, `?`, etc.
- Character classes and ranges
- Quantifiers
- Grouping and capturing
- Lookahead and Lookbehind assertions

## 16. Date and Time Handling
- Importing `datetime` and `time` modules
- Current date and time
- Formatting dates and times
- Parsing strings into dates
- Timezones
- Timedelta for date arithmetic
- Sleep and delays using `time.sleep()`

## 17. Multithreading and Multiprocessing
- Creating threads using `threading` module
- Thread synchronization using `Lock`, `Semaphore`
- Thread-safe operations
- Creating processes using `multiprocessing` module
- Inter-process communication
- Differences between threads and processes
- Parallelism vs concurrency
- Using `Pool` for process pools

## 18. JSON and XML Parsing
- Working with JSON in Python: `json` module
- Parsing JSON from strings and files
- Writing JSON to files
- Working with nested JSON objects
- Parsing XML using `xml.etree.ElementTree`
- Finding elements, attributes, and values in XML
- Writing XML files

## 19. Virtual Environments
- Creating virtual environments with `venv`
- Activating and deactivating virtual environments
- Managing dependencies in virtual environments
- Using `requirements.txt` files for dependencies
- Pipenv and Poetry for managing environments
- Isolating projects with virtual environments

## 20. Web Scraping (BeautifulSoup, Scrapy)
- Using `requests` module to fetch web pages
- Parsing HTML with `BeautifulSoup`
- Navigating HTML trees
- Extracting data from tags
- Handling dynamic content with Scrapy
- Scrapy spiders and items
- Managing request headers and cookies
- Avoiding scraping bans (using proxies, user-agents)

## 21. Unit Testing (`unittest`, `pytest`)
- Writing unit tests using `unittest`
- Test cases, suites, and runners
- Assertions in tests
- Mocking in unit tests
- Test-driven development (TDD)
- Testing with `pytest`
- Fixtures and parameterized testing

## 22. Database Connectivity (SQLite, MySQL)
- Connecting to databases using `sqlite3` and `MySQLdb`
- Executing SQL queries in Python
- Fetching data from the database
- Inserting and updating records
- Handling database transactions
- Database connection pooling
- Using ORMs like SQLAlchemy

## 23. Logging
- Setting up logging using the `logging` module
- Logging levels: DEBUG, INFO, WARNING, ERROR, CRITICAL
- Configuring logging formatters and handlers
- Writing logs to files
- Rotating log files
- Custom loggers
- Logging exceptions

## 24. Working with APIs (Requests Module)
- Introduction to REST APIs
- Using the `requests` module to make API calls
- Handling GET, POST, PUT, DELETE requests
- Handling request headers and parameters
- Parsing JSON responses
- Authentication (API keys, OAuth)
- Error handling in API calls

## 25. Flask/Django for Web Development
- Introduction to web frameworks: Flask vs Django
- Setting up a basic Flask app
- Flask routes and templates
- Handling form data in Flask
- Building a basic Django project
- Django models, views, and templates
- Django ORM for database interactions
- Handling static files in Django

## 26. Pandas
- Reading and writing data (CSV, Excel, JSON)
- DataFrame operations (selection, filtering, indexing)
- Data cleaning (handling missing values, duplicates)
- Grouping and aggregating data
- Merging, joining, and concatenating DataFrames
- Pivot tables and crosstabs
- Time series analysis in Pandas
- Handling large datasets

## 27. NumPy
- Creating and manipulating arrays
- Indexing, slicing, and reshaping arrays
- Array broadcasting
- Vectorized operations
- Statistical operations on NumPy arrays
- Linear algebra using NumPy
- Random number generation
- NumPy performance optimization

## 28. Matplotlib (Data Visualization)
- Creating basic plots: line, bar, scatter, histogram
- Customizing plots (titles, labels, colors)
- Subplots and multiple figures
- Plotting time series data
- Handling figure size and resolution
- Saving plots to files
- Plot styling (themes, gridlines)

## 29. Seaborn (Statistical Data Visualization)
- Creating advanced plots: violin plot, box plot, heatmap
- Pair plots and correlation plots
- Working with categorical data
- Statistical functions in Seaborn
- Customizing Seaborn plots
- Combining Seaborn with Matplotlib

## 30. Plotly (Interactive Data Visualization)
- Creating interactive line, bar, and scatter plots
- Plotly Express for quick visualizations
- 3D plots with Plotly
- Interactive choropleth maps and geographic data visualization
- Customizing interactive charts (hover info, sliders)
- Dash for building web apps with Plotly

## 31. Streamlit (Building Data Apps)
- Installing and setting up Streamlit
- Creating interactive dashboards
- Uploading and displaying data
- Building forms with input widgets
- Displaying charts and plots in Streamlit
- Handling file uploads
- Deploying Streamlit apps
