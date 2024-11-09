# Text2SQL using Amazon Bedrock forked from https://github.com/kevmyung/text-to-sql-bedrock/tree/main

# Text-to-SQL Bedrock

This repository contains multiple labs focused on implementing Text-to-SQL using various tools and techniques. Below are the details for each lab included in this repository.

## Lab 1: Text-to-SQL with S3 and Athena

In this lab, you'll learn how to set up and use Amazon S3 and Athena to query data using SQL.

### Files
- `lab1_text2sql_s3_athena/`
  - `1.basic-athena.ipynb`: Jupyter notebook to set up the S3 and Athena.
  - `2.advanced-athena.ipynb`: Jupyter notebook to run SQL queries on data stored in S3 using Athena.

## Lab 2: Text-to-SQL Implementation (Chain & Agent & Function Calling)

This lab focuses on implementing Text-to-SQL functionality with different approaches.

### Files
- `lab2_text2sql_implementation/`
  - `1.chain_agent_sample.ipynb`: Sample notebook demonstrating chain & agent.
  - `2.function_calling_sample.ipynb`: Sample notebook demonstrating function calling.

## Lab 3: Text-to-SQL Schema Preparation

This lab involves preparing the schema documents for Text-to-SQL applications.

![schema_prep](./images/text2sql/schema-prep-1.png)

### Files
- `lab3_text2sql_schema_preparation/`
  - `1.sample_queries.ipynb`: Jupyter notebook for preparing the sample query documents.
  - `2.detailed_schema.ipynb`: Jupyter notebook for preparing the detailed schema documents.

## Lab 4: Text-to-SQL Application (Function Calling)

In this lab, you will create a Text-to-SQL application.

![text2sql_app](./images/text2sql/text2sql_app.png)

### Files
- `lab4_text2sql_app/`
  - `1.setup-streamlit.ipynb`: Jupyter notebook for developing the Text-to-SQL application.
  - `demo-app.py` : Sample Application (main)
  - `src/...` : Custom libraries for Text2SQL app.

## Lab 5: Workflow Composition using LangGraph

In this lab, you will build a cyclic workflow using LangGraph

![langgraph](./images/text2sql/langgraph.png)

### Files
- `lab5_text2sql_langgraph/`
  - `1.text2sql_langgraph.ipynb`: Jupyter notebook for developing the Text-to-SQL workflow using LangGraph.



## Setup Instructions

Refer to `SETUP.md` for instructions on how to set up the environment and dependencies for running the labs.
- `cloudformation/`: Directory containing CloudFormation templates for setting up resources.

