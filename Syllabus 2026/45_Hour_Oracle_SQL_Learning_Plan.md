# 45-Hour Oracle SQL Learning Plan

## Overview
This comprehensive learning plan will take you from SQL basics to advanced Oracle SQL concepts, covering querying, data manipulation, performance optimization, and database administration.

---

## Learning Plan

| Hour | Topic Name | Sub Topics | Assignment |
|------|------------|------------|------------|
| 1-2 | Introduction to Oracle SQL | • What is SQL and Oracle Database<br>• Installing Oracle Database (or using Oracle Cloud)<br>• SQL Developer setup<br>• Database concepts (tables, rows, columns)<br>• Data types in Oracle<br>• Basic SELECT statements | **Assignment 1:** Set up Oracle Database environment (use Oracle Cloud Free Tier or local installation). Install SQL Developer. Connect to the database and write your first SELECT query to retrieve data from a table. |
| 3-4 | Filtering and Sorting | • WHERE clause<br>• Comparison operators<br>• Logical operators (AND, OR, NOT)<br>• IN, BETWEEN, LIKE operators<br>• NULL handling (IS NULL, IS NOT NULL)<br>• ORDER BY clause<br>• DISTINCT keyword | **Assignment 2:** Write queries using WHERE clause with various conditions. Use comparison operators, logical operators, IN, BETWEEN, LIKE. Handle NULL values. Sort results using ORDER BY. Use DISTINCT to remove duplicates. |
| 5-6 | Functions and Expressions | • String functions (UPPER, LOWER, SUBSTR, CONCAT, TRIM)<br>• Numeric functions (ROUND, TRUNC, MOD, ABS)<br>• Date functions (SYSDATE, TO_DATE, TO_CHAR, ADD_MONTHS)<br>• CASE expressions<br>• NVL, NVL2, COALESCE functions | **Assignment 3:** Write queries using string, numeric, and date functions. Create CASE expressions for conditional logic. Use NVL, NVL2, and COALESCE to handle NULL values. Format dates and numbers. |
| 7-8 | Joins | • INNER JOIN<br>• LEFT OUTER JOIN<br>• RIGHT OUTER JOIN<br>• FULL OUTER JOIN<br>• Self joins<br>• Multiple table joins<br>• Join conditions and performance | **Assignment 4:** Write queries using all types of joins (INNER, LEFT, RIGHT, FULL OUTER). Create self-joins. Join multiple tables (3+ tables). Analyze join performance using execution plans. |
| 9-10 | Aggregations and Grouping | • Aggregate functions (COUNT, SUM, AVG, MIN, MAX)<br>• GROUP BY clause<br>• HAVING clause<br>• ROLLUP and CUBE<br>• GROUPING SETS<br>• DISTINCT in aggregations | **Assignment 5:** Write queries with aggregate functions. Use GROUP BY to group data. Filter groups using HAVING. Implement ROLLUP, CUBE, and GROUPING SETS for multi-dimensional analysis. |
| 11-12 | Subqueries and CTEs | • Single-row subqueries<br>• Multiple-row subqueries<br>• Correlated subqueries<br>• EXISTS and NOT EXISTS<br>• Common Table Expressions (CTEs)<br>• Recursive CTEs | **Assignment 6:** Write queries using single-row and multiple-row subqueries. Implement correlated subqueries. Use EXISTS and NOT EXISTS. Create CTEs and recursive CTEs to solve complex problems. |
| 13-14 | Window Functions | • ROW_NUMBER, RANK, DENSE_RANK<br>• LAG and LEAD functions<br>• FIRST_VALUE and LAST_VALUE<br>• SUM, AVG, COUNT as window functions<br>• PARTITION BY and ORDER BY in windows<br>• Window frame specifications | **Assignment 7:** Write queries using window functions. Use ROW_NUMBER, RANK, DENSE_RANK for ranking. Implement LAG and LEAD for accessing previous/next rows. Use FIRST_VALUE and LAST_VALUE. Create window aggregations with PARTITION BY. |
| 15-16 | Set Operations and Hierarchical Queries | • UNION, UNION ALL<br>• INTERSECT<br>• MINUS<br>• Hierarchical queries (CONNECT BY, START WITH)<br>• LEVEL pseudocolumn<br>• PRIOR keyword | **Assignment 8:** Write queries using UNION, UNION ALL, INTERSECT, and MINUS. Create hierarchical queries using CONNECT BY and START WITH. Use LEVEL and PRIOR keywords. Query organizational charts or tree structures. |
| 17-18 | Advanced SQL Features | • PIVOT and UNPIVOT<br>• MERGE statement<br>• Multi-table INSERT<br>• Flashback queries<br>• Regular expressions (REGEXP_LIKE, REGEXP_SUBSTR) | **Assignment 9:** Use PIVOT and UNPIVOT to transform data. Write MERGE statements for upsert operations. Implement multi-table INSERT. Use flashback queries to access historical data. Apply regular expressions for pattern matching. |
| 19-20 | INSERT, UPDATE, DELETE | • INSERT statements (single row, multiple rows)<br>• INSERT with SELECT<br>• UPDATE statements<br>• DELETE statements<br>• TRUNCATE vs DELETE<br>• Transaction control (COMMIT, ROLLBACK, SAVEPOINT) | **Assignment 10:** Write INSERT statements for single and multiple rows. Use INSERT with SELECT. Update data using UPDATE statements. Delete data using DELETE and TRUNCATE. Control transactions using COMMIT, ROLLBACK, and SAVEPOINT. |
| 21-22 | DDL and Schema Management | • CREATE TABLE<br>• ALTER TABLE (add, modify, drop columns)<br>• DROP TABLE<br>• Constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, CHECK, NOT NULL)<br>• Indexes (CREATE INDEX, DROP INDEX)<br>• Views (CREATE VIEW, DROP VIEW) | **Assignment 11:** Create tables with various data types. Add constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, CHECK, NOT NULL). Modify tables using ALTER TABLE. Create indexes for performance. Create and use views. |
| 23-24 | Query Optimization | • Execution plans (EXPLAIN PLAN)<br>• Index usage<br>• Query hints<br>• Statistics gathering<br>• Cost-based optimizer<br>• Common performance issues | **Assignment 12:** Analyze query performance using EXPLAIN PLAN. Create appropriate indexes. Use query hints when necessary. Gather table statistics. Identify and fix common performance issues. |
| 25-26 | Advanced Topics | • Partitioning concepts<br>• Materialized views<br>• PL/SQL basics (procedures, functions)<br>• Triggers<br>• Sequences and synonyms | **Assignment 13:** Understand table partitioning. Create materialized views. Write basic PL/SQL procedures and functions. Create triggers for data validation. Use sequences and synonyms. |
| 27-28 | Complex Queries and Reporting | • Building complex reports<br>• Data quality checks<br>• Data validation queries<br>• Audit queries<br>• Performance tuning real queries | **Assignment 14:** Build complex reporting queries combining multiple techniques. Write queries for data quality checks and validation. Create audit queries. Optimize real-world queries for performance. |
| 29-30 | Advanced Window Functions | • Advanced window frame specifications<br>• ROWS vs RANGE<br>• Window function performance<br>• Multiple window functions in one query<br>• Window functions with joins<br>• Analytical functions deep dive | **Assignment 15:** Use advanced window frame specifications. Compare ROWS vs RANGE. Optimize window function performance. Use multiple window functions in single queries. Combine window functions with joins. |
| 31-32 | Advanced PL/SQL | • PL/SQL blocks and structure<br>• Variables and data types<br>• Control structures (IF, LOOP, CASE)<br>• Cursors (implicit and explicit)<br>• Exception handling<br>• Packages and procedures | **Assignment 16:** Write PL/SQL blocks. Use variables and control structures. Implement cursors for data processing. Handle exceptions. Create packages and procedures. Build reusable PL/SQL code. |
| 33-34 | Database Administration Basics | • User management<br>• Roles and privileges<br>• Tablespace management<br>• Backup and recovery concepts<br>• Database security<br>• Monitoring and maintenance | **Assignment 17:** Create and manage database users. Assign roles and privileges. Work with tablespaces. Understand backup and recovery. Implement security measures. Monitor database performance. |
| 35-36 | Advanced Partitioning | • Range partitioning<br>• List partitioning<br>• Hash partitioning<br>• Composite partitioning<br>• Partition pruning<br>• Partition maintenance | **Assignment 18:** Implement different partitioning strategies (range, list, hash, composite). Understand partition pruning. Perform partition maintenance operations. Optimize queries using partitioning. |
| 37-38 | Performance Tuning Advanced | • SQL tuning advisor<br>• Automatic SQL tuning<br>• Index types and strategies<br>• Query rewrite<br>• Parallel execution<br>• Result caching | **Assignment 19:** Use SQL tuning advisor. Enable automatic SQL tuning. Create different index types. Implement query rewrite. Use parallel execution. Implement result caching. |
| 39-40 | Data Warehousing Concepts | • Star and snowflake schemas<br>• Fact and dimension tables<br>• ETL processes with SQL<br>• Data warehouse queries<br>• OLAP operations<br>• Reporting queries | **Assignment 20:** Design star and snowflake schemas. Create fact and dimension tables. Build ETL processes using SQL. Write data warehouse queries. Perform OLAP operations. Create reporting queries. |
| 41-42 | Advanced SQL Techniques | • Dynamic SQL<br>• XML and JSON in Oracle<br>• Spatial data types<br>• Advanced regular expressions<br>• Model clause<br>• Pattern matching | **Assignment 21:** Use dynamic SQL. Work with XML and JSON data. Handle spatial data types. Apply advanced regular expressions. Use MODEL clause. Implement pattern matching. |
| 43-44 | Real-World Scenarios | • Complex business logic in SQL<br>• Data migration scripts<br>• Data quality and validation<br>• Reporting and analytics<br>• Integration with applications<br>• Best practices | **Assignment 22:** Implement complex business logic. Create data migration scripts. Build data quality checks. Create comprehensive reports. Integrate SQL with applications. Follow best practices. |
| 45 | Capstone Project | • End-to-end SQL project<br>• Database design<br>• Data loading and transformation<br>• Complex reporting and analytics<br>• Performance optimization<br>• Documentation and presentation | **Assignment 23:** Complete a comprehensive capstone project. Design database schema, load and transform data, create complex reports, optimize performance, and document entire solution. Present your work. |

---

## Recommended Resources

### Documentation
- Oracle SQL Documentation
- Oracle Database SQL Language Reference
- Oracle SQL Developer User Guide

### Books
- "Oracle SQL by Example" by Alice Rischert
- "Mastering Oracle SQL" by Sanjay Mishra

### Practice Platforms
- Oracle Live SQL
- HackerRank SQL challenges
- LeetCode Database problems
- Oracle Cloud Free Tier

---

## Learning Tips

1. **Practice Daily:** Write SQL queries every day
2. **Understand Execution Plans:** Learn to read and optimize
3. **Work with Real Data:** Use sample databases
4. **Learn Oracle-Specific Features:** Window functions, hierarchical queries
5. **Join Communities:** Oracle forums and Stack Overflow

---

## Project Ideas

1. **Database Design Project:** Design and implement a database schema
2. **Reporting System:** Build complex reports with aggregations
3. **Data Migration:** Write scripts to migrate data
4. **Performance Tuning:** Optimize slow queries
5. **ETL Queries:** Build data transformation queries

---

## Assessment Checklist

By the end of 45 hours, you should be able to:

- [ ] Write basic SELECT queries
- [ ] Use joins effectively
- [ ] Perform aggregations and grouping
- [ ] Write subqueries and CTEs
- [ ] Use window functions
- [ ] Modify data (INSERT, UPDATE, DELETE)
- [ ] Create database objects (tables, views, indexes)
- [ ] Optimize query performance
- [ ] Write complex analytical queries
- [ ] Use PL/SQL for procedural logic
- [ ] Understand database administration

---

## Time Allocation Summary

| Module | Hours | Percentage |
|--------|-------|------------|
| SQL Fundamentals | 6 | 13% |
| Data Manipulation | 6 | 13% |
| Advanced Querying | 8 | 18% |
| Data Modification | 4 | 9% |
| Performance and Optimization | 6 | 13% |
| PL/SQL and Administration | 6 | 13% |
| Advanced Topics | 6 | 13% |
| Real-World Applications | 3 | 7% |
| **Total** | **45** | **100%** |

---

## Oracle-Specific Features to Master

- **Analytical Functions:** RANK, DENSE_RANK, LAG, LEAD
- **Hierarchical Queries:** CONNECT BY, START WITH
- **Regular Expressions:** REGEXP functions
- **Flashback Queries:** Query historical data
- **Partitioning:** Table and index partitioning
- **Materialized Views:** Pre-computed aggregations
- **PL/SQL Integration:** Combining SQL with procedural code

---

**Good luck with your Oracle SQL learning journey! 🗄️**

