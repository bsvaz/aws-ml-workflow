# AWS Machine Learning Workflow for Image Classification

## Overview

This project serves as the capstone for the Machine Learning Fundamentals Nanodegree from Udacity, accessed through the AWS AI & ML Scholarship. It demonstrates proficiency in deploying and monitoring a machine learning workflow for image classification using AWS services like Lambda, Step Functions, SageMaker, and S3.

## Key Features

- **Data Staging with ETL**: Utilizes ETL (Extract, Transform, Load) processes to stage the CIFAR-100 dataset. The data is also stored and accessed via AWS S3.
- **Lambda Functions**: Incorporates three Lambda functions for different stages of the workflow.
- **AWS Step Functions**: Orchestrates the workflow through AWS Step Functions, creating a state machine for the ML process.
- **AWS SageMaker**: Utilizes SageMaker for model training, evaluation, and deployment.
- **AWS S3**: Used for storing datasets, model artifacts, and other essential files.

## Technical Highlights

- **Language**: Python
- **AWS Services**: Lambda, Step Functions, SageMaker, S3

## File Descriptions

- `starter.ipynb`: The main Jupyter Notebook outlining the entire workflow, guiding you through setting up AWS services, data staging, and ML model deployment.
- `Lambda.py`: Contains the code for all three Lambda functions used in the Step Functions.
- `threshold.json`, `serialize.json`, `classification.json`: These JSON files define the invocation settings for each corresponding Lambda function within the Step Functions service.
- `stepfunctions_graph.png`: A graphical representation of the Step Functions workflow.

## Educational Journey

This project is the final milestone in a series of Nanodegrees sponsored by the AWS AI & ML Scholarship, serving as a comprehensive application of the skills and knowledge acquired.

