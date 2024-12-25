# Additional Resources for 5DATA005W-Data-Engineering Module for Level 5 Data Science students (2024-2025 University of Westminster)

The module is mandatory for Level 5 Data Science students and was taught by me, [Habeeb Balogun](https://www.westminster.ac.uk/about-us/our-people/directory/balogun-habeeb), as the module leader.
This module provides a basic understanding of data engineering methods with (mostly) practical tips, hands-on experience in data engineering pipelines, and some theory.
 
The compiled list includes courses, blog posts, videos, and research papers sorted by themes.

## Content

- [Resources for Beginners](##Resources-for-Beginners)
- [Resources for Reading and Writing Research Papers](##Resources-for-Reading-and-Writing-Research-Papers)
- [Additional Resources (Class Content)](##Additional-Resources-(Class-Content))
  - [Introduction to Data Engineering (General Resources)](###Introduction-to-Data-Engineering-(General-Resources))
  - [Big Data and Distributed Systems](###Big-Data-and-Distributed-Systems)
  - [Cloud Platforms and Scalable Solutions](###Cloud-Platforms-and-Scalable-Solutions)
  - [Data Governance, Ethics, and Bias](###Data-Governance,-Ethics,-and-Bias)
  - [Data Pipelines and Automation](###Data-Pipelines-and-Automation)

## Resources for Beginners
- [Beginner’s Guide to Data Engineering](https://medium.com/data-engineering-on-gcp/data-engineering-starter-guide-ae34979a377d) by Harish Kumar.
- [Foundations of Data Engineering: Data Pipelines](https://realpython.com/data-engineering-pipelines/) by Real Python.
- [Python for Data Engineers (FreeCodeCamp YouTube)](https://www.youtube.com/watch?v=5gl3-iA5RZM).
- [W3Schools: SQL Tutorial](https://www.w3schools.com/sql/).
- [Learn Data Engineering](https://learndataengineering.com/): Comprehensive tutorials on ETL, databases, and cloud tools.
- [Data Engineering Roadmap](https://github.com/datastacktv/data-engineer-roadmap): A curated roadmap for aspiring data engineers.

### Resources for Students Unfamiliar with Cloud Platforms
- **Introduction to Google Cloud Platform (GCP):**
  - [Google Cloud Free Tier](https://cloud.google.com/free).
  - [Introduction to GCP for Beginners (Video)](https://www.youtube.com/watch?v=yoIkjG4VoU4).
- **Introduction to AWS for Data Engineering:**
  - [AWS Free Tier](https://aws.amazon.com/free/).
  - [AWS Fundamentals Specialization (Coursera)](https://www.coursera.org/specializations/aws-fundamentals).
- **Introduction to Apache Spark:**
  - [Apache Spark Quick Start Guide](https://spark.apache.org/docs/latest/quick-start.html).
  - [Databricks Introduction to Spark](https://databricks.com/spark/about).

## Resources for Reading and Writing Research Papers
### Reading Papers
- [How to (Seriously) Read a Research Paper?](https://www.science.org/content/article/how-seriously-read-scientific-paper)

### Writing Scientific Papers/Reports
- **Writing an Abstract for Your Research Paper**: https://writing.wisc.edu/handbook/assignments/writing-an-abstract-for-your-research-paper/
- **How to Write an Effective Data Engineering Report**: [To be added – tailored resource].
- **Tips for Writing Technical Papers** by Mark Heard: https://engineering.linkedin.com/blog/2020/tech-writing-tips.

## Additional Resources (Class Content)
### Introduction to Data Engineering (General Resources)
- [Data Engineering on GCP Specialization (Coursera)](https://www.coursera.org/specializations/gcp-data-engineering).
- [Building Data Pipelines with Python](https://realpython.com/data-engineering-pipelines/).
- [Designing Data-Intensive Applications by Martin Kleppmann](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/).
- [ETL in Depth: A Beginner’s Guide](https://aws.amazon.com/what-is/etl/).
- [Database Design and Implementation](https://www.coursera.org/learn/database-management).

### Big Data and Distributed Systems
- [Introduction to Big Data (Coursera)](https://www.coursera.org/learn/intro-to-big-data).
- [The Hadoop Ecosystem](https://hadoop.apache.org/): Official Apache Hadoop resources.
- [Understanding Apache Kafka](https://kafka.apache.org/): Kafka documentation and guides.
- [Big Data Specialization by University of California, San Diego](https://www.coursera.org/specializations/big-data).

### Cloud Platforms and Scalable Solutions
- [AWS for Data Engineering](https://aws.amazon.com/data-engineering/).
- [Data Engineering on Azure](https://azure.microsoft.com/en-us/services/data-engineering/).
- [Google Cloud Data Engineering](https://cloud.google.com/learn/what-is-data-engineering).
- [Kubernetes for Beginners](https://kubernetes.io/docs/tutorials/).

### Data Governance, Ethics, and Bias
- [Data Ethics and Responsible Use](https://www.oreilly.com/library/view/data-ethics-and/9781492040590/).
- [Understanding Data Governance (DataCamp)](https://www.datacamp.com/tutorial/data-governance-introduction).
- [Ethics in AI and Big Data](https://towardsdatascience.com/ethics-in-big-data-52a0f8529147).
- Bender, Emily M., et al. "On the Dangers of Data Mismanagement."
- Gebru, Timnit. "Datasheets for Datasets: A Framework for Ethical Data Use."

### Data Pipelines and Automation
- [Building Data Pipelines with Apache Airflow](https://airflow.apache.org/).
- [ETL Frameworks for Python: A Review](https://towardsdatascience.com/etl-frameworks-in-python-968e88241610).
- [Apache NiFi: Automating Data Workflows](https://nifi.apache.org/).
- [Stream Processing with Apache Flink](https://flink.apache.org/).
- [Best Practices for Data Pipeline Design](https://towardsdatascience.com/best-practices-for-building-data-pipelines-4c5ed8c4e3b7).


### Overview
This repository contains scripts demonstrating a data engineering pipeline built using MongoDB Atlas (for unstructured data) and SQLite (for structured data). The pipeline covers essential steps such as ingestion, transformation, and storage for both structured datasets like tabular records and unstructured data like JSON or documents.

The scripts are designed to be simple and easy to understand for beginners or intermediate data engineers.

Pipeline Features
```
Structured Data Processing (SQLite):

Ingestion: Import structured data from CSV or Excel files.
Transformation: Perform basic operations like cleaning.
Storage: Store transformed data in SQLite, a lightweight and easy-to-use database.
```

Unstructured Data Processing (MongoDB Atlas):
```
Ingestion: Insert unstructured data(Image and text) as BSON and JSON documents into MongoDB Atlas.
Transformation: Use MongoDB's aggregation framework to extract and manipulate nested or hierarchical data.
Storage: MongoDB Atlas serves as the repository for unstructured data, enabling fast retrieval and scalability.
```
```
Folder Structure
├── Weekly_Tutorial_Scripts/    # Python scripts for each pipeline step
└── README.md            # Project documentation
```



Prerequisites
```
Python 3.8+
MongoDB Atlas account with a free-tier cluster set up.
SQLite (pre-installed with Python).
```

