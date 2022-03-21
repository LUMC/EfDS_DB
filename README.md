# Essentials for Data Science

Materials for Essentials for Data Sciences course: relational databases, SQL and relational objects.

## Prerequisites

- This course is Python-based and uses Python packages:
    - [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) for the database access and the SQL language.
    - [pandas](https://pandas.pydata.org/) for data access and presentation.
- The materials are developed and tested in:
    - Python >=3.7
    - Jupyter notebook
    - [Google Colaboratory](https://colab.research.google.com/).

## Goals

- Understand general database concepts.
- Understand relational databases design (data model, types and representaions of relationships, normal forms).
- Practice SQL language (`SELECT` queries of growing complexity, table `JOIN` operations, data content and table structure modification commands).
- Work with Object Relational Mapper (use data from a relational database in an object-oriented code).

## Day 1/4

### Primary concepts

- [Database, database models and DataBase Management Systems](database.md)
- [Database related terms](database_related_terms.md)

### Relational databases concepts

- [Relation/table](table.md)
- [Keys, primary keys, prime attributes](keys.md)
- [Database design anomalies](design_anomalies.md)
- [Database normalisation](database_normalisation.md)
- [Types of relationships](relationships_types.md)
- [Column data types](data_types.md)
- [Advantages/disadvantages of relational databases](reldb_adv_disadv.md)

### Practicing SQL

- Downloading and connecting to the example database: [Lecture](connect_to_database.ipynb)
- Querying and selecting data (`SELECT`, `LIMIT`, `AS`, `ORDER`, `DISTINCT`, `WHERE`, `IN`, `BETWEEN`, `LIKE`): [Lecture](SQL/SELECT_basic.ipynb), [Exercises](SQL/SELECT_basic.exercises.ipynb)

## Day 2/4

### Practicing SQL

- Grouping and summarising (`GROUP BY`, `HAVING`, `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP_CONCAT`): [Lecture](SQL/SELECT_groups.ipynb), [Exercises](SQL/SELECT_groups.exercises.ipynb)
- Modification statements (`UPDATE`, `INSERT`, `DELETE`): [Lecture](SQL/UPDATE_INSERT_DELETE.ipynb), [Exercises](SQL/UPDATE_INSERT_DELETE.exercises.ipynb)
- Data definition language (`CREATE TABLE`, `DROP TABLE`): [Lecture](SQL/CREATE_TABLE.ipynb)
- Joining tables 1 (`INNER JOIN`, `LEFT JOIN`, `CREATE TEMP TABLE`): [Lecture](SQL/JOIN_basic.ipynb), [Exercises](SQL/JOIN_basic.exercises.ipynb)
- Joining tables 2 (`UNION`, `EXCEPT`, `INTERSECT`, self joins, `CROSS JOIN`, subqueries, `EXIST`): [Lecture](SQL/JOIN_adv.ipynb), [Exercises](SQL/JOIN_adv.exercises.ipynb)

## Day 3/4

### Learning Object Relational Mapper

- Building object-oriented interface to a database: [Practical](orm_practice.ipynb)   
    (This is one long session but it cannot be easily split into smaller parts without major code repetitions.)

## Day 4/4

- [A practical `git` command line usage session](git.md)

## Additional resources

- [Databases general overview](https://en.wikipedia.org/wiki/Outline_of_databases)
- [SQLite tutorial](https://www.sqlitetutorial.net/)
- [w3schools SQL Tutorial](https://www.w3schools.com/sql/default.asp)
- [Diagram editor](https://www.diagrameditor.com/)

