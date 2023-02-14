# README: DevOps coding challenge
# Overview:
This project contains infrastructure code for deploying a backend and frontend application on an Amazon Web Services (AWS) Elastic Kubernetes Service (EKS) cluster using Terraform. The project includes the necessary scripts and configurations for automating the deployment and scaling of the application.

# Directory Structure:
- backend/: This directory contains the source code files for the backend application.
- frontend/: This directory contains the source code files for the frontend application.
- terraform/: This directory contains the Terraform files and configurations for creating and managing the EKS cluster in AWS.
- backup/: This directory contains backup files and configurations for the infrastructure.
- runtime: This file contains the script and configurations for automating the Terraform deployment.
# Automated Deployment:
The runtime contains a script that automates the Terraform deployment process. The script creates the EKS cluster, deploys the ingress controller and storage class, and deploys the Conduit demo app in the cluster.
>Subdomain:
Currently, work is ongoing to make the subdomain work with the application. Further updates will be added to this README as this progresses.
# Usage:
To use this infrastructure code, follow these steps:
- Clone the repository to your local machine.
- Run the runtime script to deploy the infrastructure using Terraform.
- Access the application at the URL provided by the script upon completion of the deployment.


# Contact:
For any questions or comments, please contact the project maintainer at hemanthmandadi@gmail.com.
