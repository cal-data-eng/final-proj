# Data 101 Final Project: Database Systems Comparison

## Overview
This project explores and compares relational and non-relational database systems using a moderately sized dataset. Remember, this project is _optional_. It will be largely self-directed, and will be much more open-ended that prior assignments.

This project must be completed in groups of **two or three** students in DATA 101. You can be in any section.

### Tasks
In this project you will:

* Pick a dataset to work with
* Design a relational schema for your teams chosen dataset
* Load this dataset into both Postgres, and a non-relational DB
* Write queries to explore this data set (some EDA)
* Practice with DATA 101 topics (entity resolution, imputation, etc)
* Compare query performance between two different types of databases
* Write your findings in a report.

_Note:_ A lot of time will be spent on the first few parts of the assignment––setting up your data. While you can accomplish some of your work on DataHub, we are expecting that most will setup a locally working Postgres instance and install other tools as needed.

Practicing the rest of your engineering and debugging skills is also one of the goals of this project.

##  Grading and Deadlines

### Checkpoint

### Final Report

## (1) Pick Your Dataset

We _recommend_ that you choose one of the following datasets to explore for this project.

* **Yelp:** https://www.yelp.com/dataset
* **Open Library:** https://openlibrary.org/developers/dumps
* **Wikipedia:** https://dumps.wikimedia.org/

### Your Own Dataset

This final project will allow you to bring your own dataset, but it must meet the following requirements:

* Have a mix of structured and semi-structured data
* Have more than 1,000,000 total "rows"
* Contain at least 4 distinct tables or types of objects
* There must be some kind of "foreign" key

## (2) Pick Your Non-Relational DB

## (3) Setup and Install Your Tools

## (4) Schema Design, Data Loading & Cleaning

* use DDL / DML
* Show a (basic) ERD
* Explain your schema
* Identify your PKs and FKs

## (5) Data & System Analysis

* Write 2 "complex" queries to run in each tool
* Query Performance Comparison
  A. Index Optimization
  B. Using %timeit, `time`, comparing to NoSQL
* Statistical Analysis
* Outlier Detection


* "ergonomics"
* pickup the best tool for the job
## (6) Semi-Structured Non-Relational Analysis

* Try to write one of the above SQL queries against a NoSQL DB
  * (You can mix Python, etc)
* Could you have done any of this in Postgres?

## (7) Reporting and Wrap Up


---

## Project Structure

The final project contains this starter setup. You may adapt it as needed, but please make sure you

```
.
├── README.md           # Project documentation
├── RUBRIC.md           # Grading criteria
├── checkpoint.ipynb    # Initial data exploration and schema design
├── final-project.ipynb # Main analysis and results
├── data/               # Data directory (excluded from git)
├── examples/           # Some (maybe) useful code examples
```

**Warning:** It can be tricky to work with large files and git / GitHub. We've set up a `.gitignore` to exclude many common large files, and **everything** inside `data/`.

---
