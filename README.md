# Serverless Registration Web Application

A serverless web application for handling user registration using AWS managed services. The project demonstrates how a frontend application can interact with a serverless backend and store registration data without managing traditional servers.

## Technologies Used

* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* Amazon S3
* AWS IAM

## Architecture Overview

The application uses a serverless architecture where the frontend is hosted on Amazon S3. User registration requests are sent through Amazon API Gateway to AWS Lambda, which processes the request and stores the registration data in Amazon DynamoDB.

IAM is used to manage permissions between the AWS services.

> Architecture diagram will be added to this section.

## AWS Services

* **Amazon S3** — Static frontend hosting
* **Amazon API Gateway** — Handles application API requests
* **AWS Lambda** — Processes registration requests
* **Amazon DynamoDB** — Stores registration data
* **AWS IAM** — Manages permissions and access


## Application Workflow

1. The user accesses the frontend hosted on Amazon S3.
2. The user submits the registration form.
3. The request is sent to Amazon API Gateway.
4. API Gateway invokes the AWS Lambda function.
5. Lambda processes the registration request.
6. Registration data is stored in Amazon DynamoDB.
7. IAM permissions control access between the required AWS services.



## Key Implementation Areas

* Built a serverless application using AWS managed services.
* Configured API Gateway and Lambda for API-driven backend processing.
* Used DynamoDB for storing registration data.
* Hosted the static frontend using Amazon S3.
* Configured IAM permissions for AWS service interaction.
* Practiced integrating multiple AWS services into a serverless workflow.

## Key Learnings

This project provided practical experience with serverless application architecture, API-driven workflows, AWS service integration, database storage, S3 hosting, and IAM-based access control.

## Project Flow

**S3 → API Gateway → Lambda → DynamoDB**

**IAM → Access and permissions across AWS services**
