AWS Lambda Project
This project serves as an introduction to AWS cloud computing and the deployment of serverless applications using AWS Lambda. The primary objectives were to gain familiarity with AWS services and explore cloud-based development practices.

Getting Started
AWS Account Setup:

Create an AWS account to access a variety of cloud services.
Integrate AWS Explorer with Visual Studio Code for seamless AWS resource management.
AWS CLI Configuration:

Generate and configure AWS Access Keys for programmatic access.
Install and configure the AWS Command Line Interface (CLI) to interact with AWS services.
Docker and SAM Installation:

Install Docker for containerization, allowing consistent development and deployment environments.
Set up AWS Serverless Application Model (SAM) for local testing and deployment.
Lambda Function Development
Creating Lambda Functions:

Leverage AWS Lambda functions for executing code in a serverless environment.
Simultaneously commit code to the cloud, ensuring scalability and efficiency.
Function Deployment:

Develop specific Lambda functions using sample data for targeted functionality.
Commit and deploy functions to AWS Lambda, providing real-world application scenarios.

Project Structure
- airtravel.csv          # Sample data for Lambda function testing
- functions/             # Directory containing Lambda function code
  - lamda-first.js       # Lambda function source code
  - node_modules/        # Dependencies required for Lambda function
- .serverless/           # Serverless Framework artifacts and configurations
- serverless.yml         # Serverless Framework configuration file

Deployment
Use the Serverless Framework to deploy your AWS Lambda functions. Execute the following command:

serverless deploy --stage dev --aws-profile Your_AWS_Profile

Replace Your_AWS_Profile with the AWS CLI profile configured for this project.

Conclusion
This project provides a foundation for cloud-native development using AWS Lambda and related services. Explore and expand upon the existing codebase to build scalable and efficient serverless applications.
