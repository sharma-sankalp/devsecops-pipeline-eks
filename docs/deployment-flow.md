# Deployment Flow

Developer

↓

GitHub Push

↓

Webhook

↓

Jenkins

↓

Checkout Code

↓

Maven Build

↓

Unit Tests

↓

SonarQube Scan

↓

Docker Build

↓

Trivy Scan

↓

Push Image to Amazon ECR

↓

Update Kubernetes Manifest Repository

↓

Git Commit

↓

ArgoCD Sync

↓

Deploy to Amazon EKS

↓

Application Running
