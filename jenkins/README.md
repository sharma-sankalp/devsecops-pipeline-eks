# Jenkins Pipeline

This directory contains a sample Declarative Jenkins Pipeline used to automate the CI process.

Pipeline stages include:

- Source Checkout
- Maven Build
- Unit Testing
- SonarQube Analysis
- Docker Build
- Trivy Image Scan
- Amazon ECR Push
- Kubernetes Manifest Update

The deployment is completed by ArgoCD using GitOps principles.