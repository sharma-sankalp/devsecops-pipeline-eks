# Deployment Flow

Developer

↓

Push Code to GitHub

↓

GitHub Webhook

↓

Jenkins Pipeline

↓

Checkout Source Code

↓

Maven Build

↓

Unit Tests

↓

SonarQube Analysis

↓

Authenticate using AWS IAM Role

↓

Docker Build

↓

Trivy Image Scan

↓

Push Docker Image to Amazon ECR

↓

Update Kubernetes Manifest Repository

↓

Commit & Push Manifest Changes

↓

ArgoCD Detects Repository Changes

↓

Synchronize Application

↓

Deploy to Amazon EKS

↓

Application Pods Running

↓

Prometheus Collects Metrics

↓

Grafana Visualizes Dashboards

↓

Loki Aggregates Logs

↓

Users Access the Application
