# AWS-serverlessWebApplication

Deploying serverless web application on AWS using S3, API Gateway, Lambda, DynamoDB and CloudFront

## Here is the Steps:

### 1. Setting up a DynamoDB: Set up a DynamoDB table to store our data. You'll learn how to define the table schema and perform CRUD operations using Lambda functions.

### 2. Creating Lambda Functions:  Create functions to retrieve data from DynamoDB and insert new data into it and attach role with full access to DynamoDB and Api Gateway.

### 3. Configuring API Gateway:  Set up both GET and POST methods to interact with our DynamoDB database through Lambda.

### 4. Setting up an S3 Bucket:  Create an S3 bucket to host our static web content, including "index.html" and "script.js".

### 5. Implementing Secure Connections with CloudFront: Configure CloudFront to serve our S3 content securely over HTTPS, providing encryption in transit and improving the performance of our application.

