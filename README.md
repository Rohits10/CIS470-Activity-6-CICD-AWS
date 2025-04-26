# CIS470-Activity-6: AWS Lambda CI/CD Pipeline

This project demonstrates automated deployment of an AWS Lambda function using **GitHub Actions** as a CI/CD pipeline.

##  Project Overview 
- **Function Name:** `CIS470-Activity-6`
- **Runtime:** Python 3.12
- **Trigger:** API Gateway (HTTP API)
- **CI/CD:** GitHub Actions automates deployment on every push to the `main` branch.

##  Project Structure 

##  How It Works 
1. On every push to the `main` branch:
   - GitHub Actions triggers the workflow.
   - The `lambda_function.py` is zipped and deployed to AWS Lambda.
2. The Lambda function is exposed via API Gateway.

##  API Gateway Endpoint 
Use this URL to invoke the deployed Lambda function:
https://inhe2adnmk.execute-api.us-east-2.amazonaws.com/default/CIS470-Activity-6


