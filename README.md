# Data Modeling with Apache Cassandra

## Project Overview
This project focuses on designing and implementing a data model using Apache Cassandra to support specific analytical queries for a music streaming application.

The project emphasizes query-first data modeling, which is fundamental when working with Cassandra.

---

## Problem Statement
Event data stored in CSV files must be ingested into a Cassandra database in a way that allows efficient querying for predefined analytical questions related to user listening behavior.

---

## Data Architecture
- Input: CSV event data files
- Database: Apache Cassandra
- Modeling approach: One table per query

---

## Queries Supported
1. Retrieve songs played during a specific session
2. Retrieve songs listened to by a specific user
3. Retrieve users who listened to a specific song

Each query is supported by a dedicated table designed for optimal performance.

---

## Technologies Used
- Python
- Apache Cassandra
- CQL (Cassandra Query Language)
- Pandas

---

## How to Run
1. Start a local Cassandra instance
2. Run the ETL script to:
   - Create keyspace and tables
   - Load CSV data
3. Execute validation queries to confirm correct results

---

## Deliverables
- Cassandra keyspace and tables
- ETL pipeline
- Query validation results

---

## Key Concepts
- Query-based data modeling
- Partition keys and clustering columns
- Denormalization in NoSQL databases
