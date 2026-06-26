# AWS Cloud Resume Challenge

This is my implementation of the Cloud Resume Challenge in AWS. The Cloud Resume Challenge is a multi-step project designed to build and demonstrate the foundational skills required to pursue a career in Cloud Computing. The project was created by Forrest Brazeal.

## Architecture

![Architecture Diagram]({1B565F8F-6706-417D-BA09-19DCC8231341}.png)

*   **Frontend**: Hosted in an S3 bucket and served through CloudFront for secure, low-latency delivery.
*   **DNS & Domain**: Managed via Route 53 to point to the CloudFront distribution.
*   **Backend API**: An API Gateway triggers a Lambda function to handle logic.
*   **Database**: Amazon DynamoDB is used to store and retrieve the visitor count.

## Key Skills Demonstrated
*   **Infrastructure as Code (IaC)**: Provisioning resources using [Insert your tool, e.g., SAM, Terraform, or CDK].
*   **CI/CD Pipeline**: Automating code deployment using GitHub Actions, ensuring that updates to the repository are automatically pushed to the production environment.
*   **Serverless Computing**: Utilizing Lambda and API Gateway for a scalable, event-driven backend.
