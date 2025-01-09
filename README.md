# Additional Resources for 5DATA005W-Data-Engineering Module for Level 5 Data Science students (2024-2025 University of Westminster)

The module is mandatory for Level 5 Data Science students and was taught by me, [Habeeb Balogun](https://www.westminster.ac.uk/about-us/our-people/directory/balogun-habeeb), as the module leader. This module provides a basic understanding of data engineering with hands-on experience in data engineering pipelines and some theory.
 
The compiled list includes courses, blog posts, videos, and textbooks sorted by themes.

## Content
- [Additional Resources for 5DATA005W-Data-Engineering Module for Level 5 Data Science students (2024-2025 University of Westminster)](#additional-resources-for-5data005w-data-engineering-module-for-level-5-data-science-students-2024-2025-university-of-westminster)
  - [Content](#content)
  - [Resources for Beginners](#resources-for-beginners)
    - [Resources for Students Unfamiliar with Cloud Platforms](#resources-for-students-unfamiliar-with-cloud-platforms)
  - [Additional Resources](#additional-resources)
    - [Introduction to Data Engineering (General Resources)](#introduction-to-data-engineering-general-resources)
    - [Big Data and Distributed Systems](#big-data-and-distributed-systems)
    - [Cloud Platforms and Scalable Solutions](#cloud-platforms-and-scalable-solutions)
    - [Data Governance, Ethics, and Bias](#data-governance-ethics-and-bias)
    - [Data Pipelines and Automation](#data-pipelines-and-automation)
  - [Weekly Hands-on](#weekly-hands-on)
  - [Google Colab was used, but you can use any python IDE of your own choice, just make sure you change the directory in the python script to fit your own data location.](#google-colab-was-used-but-you-can-use-any-python-ide-of-your-own-choice-just-make-sure-you-change-the-directory-in-the-python-script-to-fit-your-own-data-location)
  - [Recommended Textbooks for Data Engineering](#recommended-textbooks-for-data-engineering)
---
## Resources for Beginners
- [Beginner’s Guide to Data Engineering](https://www.geeksforgeeks.org/data-engineering-101/) by Geeks.
- [What is Data Engineering and is it right for you?](https://realpython.com/podcasts/rpp/42/) by Real Python.
- [Data Engineering Course for Beginners (FreeCodeCamp YouTube)](https://www.youtube.com/watch?v=PHsC_t0j1dU&t=901s) by FreeCodeCamp.
- [W3Schools: SQL Tutorial](https://www.w3schools.com/sql/) by W3school.
- [Learn Data Engineering](https://learndataengineering.com/): Comprehensive tutorials on ETL, databases, and cloud tools.
- [Data Engineering Roadmap](https://github.com/datastacktv/data-engineer-roadmap): A curated roadmap for aspiring data engineers.
---
### Resources for Students Unfamiliar with Cloud Platforms
- **Introduction to Google Cloud Platform (GCP):**
  - [Google Cloud Free Tier](https://cloud.google.com/free).
  - [Introduction to GCP for Beginners (Video)](https://www.youtube.com/watch?v=kzKFuHk8ovk&list=PLIivdWyY5sqKh1gDR0WpP9iIOY00IE0xL).
- **Introduction to AWS for Data Engineering:**
  - [AWS Free Tier](https://aws.amazon.com/free/).
  - [AWS Fundamentals Specialization (Coursera)](https://www.coursera.org/specializations/aws-fundamentals).
- **Introduction to Apache Spark:**
  - [Apache Spark Quick Start Guide](https://spark.apache.org/docs/latest/quick-start.html).
  - [Databricks Introduction to Spark](https://databricks.com/spark/about).
---
---
## Additional Resources
### Introduction to Data Engineering (General Resources)
- [Data Engineering on GCP Specialization (Coursera)](https://www.coursera.org/specializations/gcp-data-engineering).
- [Building Data Pipelines with Python](https://www.youtube.com/watch?v=Y_vQyMljDsE).
- [Designing Data-Intensive Applications by Martin Kleppmann](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/).
- [ETL in Depth: A Beginner’s Guide](https://aws.amazon.com/what-is/etl/).
- [Database Design and Implementation](https://www.coursera.org/learn/database-management).
---
### Big Data and Distributed Systems
- [Introduction to Big Data](https://www.youtube.com/watch?v=j-0cUmUyb-Y).
- [The Hadoop Ecosystem](https://hadoop.apache.org/): Official Apache Hadoop resources.
- [Understanding Apache Kafka](https://kafka.apache.org/): Kafka documentation and guides.
- [Big Data Specialization by University of California, San Diego](https://www.coursera.org/specializations/big-data).
---
### Cloud Platforms and Scalable Solutions
- [AWS for Data Engineering](https://www.youtube.com/watch?v=6G0bLDIcO7Y).
- [Data Engineering on Azure](https://www.youtube.com/watch?v=sYfy2bQWIKg&list=PL9ooVrP1hQOGpbAJW6fvGa68Yb1C9Ytkt).
- [Google Cloud Data Engineering](https://www.youtube.com/watch?v=ZVgt1-LfWW4&list=PLWXckUXLY7LzOBySwKXb9fqejwpGcnAwi).
- [Kubernetes for Beginners](https://kubernetes.io/docs/tutorials/).
---
### Data Governance, Ethics, and Bias
- [Data Ethics and Responsible Use (DataCamp)](https://www.datacamp.com/blog/introduction-to-data-ethics).
- [Understanding Data Governance](https://cloud.google.com/learn/what-is-data-governance?hl=en).
- [Ethics in AI and Big Data](https://www.unglobalpulse.org/document/building-ethics-into-privacy-frameworks-for-big-data-and-ai/).
---
### Data Pipelines and Automation
- [Building Data Pipelines with Apache Airflow](https://airflow.apache.org/).
- [ETL Frameworks for Python: A Review](https://www.datacamp.com/blog/a-list-of-the-16-best-etl-tools-and-why-to-choose-them).
- [Apache NiFi: Automating Data Workflows](https://nifi.apache.org/).
- [Stream Processing with Apache Flink](https://flink.apache.org/).
- [Best Practices for Data Pipeline Design](https://learn.microsoft.com/en-us/data-engineering/playbook/articles/pipeline-reliability).
---
## Weekly Hands-on
This section contains scripts demonstrating a data engineering pipeline built using MongoDB Atlas (for unstructured data) and SQLite (for structured data). The pipeline covers essential steps such as ingestion, transformation, and storage for both structured datasets like tabular records and unstructured data like JSON or documents.

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
├── Weekly Hands-on/    # Document file providing guide and context, accompanied by python script and data for each week. 
└── README.md            # Project documentation
```

Prerequisites
```
Python 3.8+
MongoDB Atlas account with a free-tier cluster set up.
SQLite (pre-installed with Python).
Google Colab was used, but you can use any Python IDE of your own choice; make sure you change the directory in the Python script to fit your own data location. 
```
---
## Recommended Textbooks for Data Engineering
1. **Fundamentals of Data Engineering: Plan and Build Robust Data Systems** by Joe Reis and Matt Housley  
2. **Designing Data-Intensive Applications** by Martin Kleppmann  
3. **The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling** by Ralph Kimball and Margy Ross  
4. **Cloud Data Management** by Hector Garcia-Molina, Jeffrey D. Ullman, and Jennifer Widom  
5. **Data Engineering with Python** by Paul Crickard  
6. **Building the Data Lakehouse** by Bill Inmon and Mary Levins  
7. **Streaming Systems** by Tyler Akidau, Slava Chernyak, and Reuven Lax  
8. **The Big Data Handbook** by Arvind Sathi  
9. **Data Pipelines Pocket Reference** by James Densmore  
10. **Database Internals** by Alex Petrov  
---
Happy learning!

If this is any useful to you, please star/fork the repo. Thank you!
