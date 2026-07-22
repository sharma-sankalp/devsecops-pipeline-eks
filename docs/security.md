# Security

The pipeline incorporates multiple security controls.

## Source Code

- Branch protection
- Pull requests
- Code reviews

## Build

- Jenkins credentials
- Secret masking
- Pipeline as Code

## Code Quality

- SonarQube analysis
- Quality Gates

## Containers

- Docker image scanning using Trivy
- Minimal base images

## AWS

- IAM Least Privilege
- Security Groups
- Private Subnets

## Kubernetes

- RBAC
- Namespaces
- Secrets
- Network Policies

## GitOps

ArgoCD continuously reconciles desired and actual cluster state.
