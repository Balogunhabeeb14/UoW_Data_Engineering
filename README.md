Overview
This repository contains scripts demonstrating a data engineering pipeline built using MongoDB Atlas (for unstructured data) and SQLite (for structured data). The pipeline covers essential steps such as ingestion, transformation, and storage for both structured datasets like tabular records and unstructured data like JSON or documents.

The scripts are designed to be simple and easy to understand for beginners or intermediate data engineers.

Pipeline Features
Structured Data Processing (SQLite):

Ingestion: Import structured data from CSV or Excel files.
Transformation: Perform basic operations like cleaning.
Storage: Store transformed data in SQLite, a lightweight and easy-to-use database.


Unstructured Data Processing (MongoDB Atlas):

Ingestion: Insert unstructured data(Image and text) as BSON and JSON documents into MongoDB Atlas.
Transformation: Use MongoDB's aggregation framework to extract and manipulate nested or hierarchical data.
Storage: MongoDB Atlas serves as the repository for unstructured data, enabling fast retrieval and scalability.

'''
Folder Structure
├── data/                       # Raw data files (CSV, JSON, etc.)
├── Weekly_Tutorial_Scripts/    # Python scripts for each pipeline step
└── README.md            # Project documentation
'''



Prerequisites
Python 3.8+
MongoDB Atlas account with a free-tier cluster set up.
SQLite (pre-installed with Python).
