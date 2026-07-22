# Architecture Decisions

## Why Jenkins?

Jenkins provides flexible pipeline automation with a rich plugin ecosystem and Pipeline-as-Code capabilities.

---

## Why GitHub?

GitHub acts as the central version control system and triggers Jenkins builds through webhooks.

---

## Why Maven?

Maven manages Java dependencies, builds the application, and executes unit tests consistently.

---

## Why SonarQube?

SonarQube improves code quality by identifying bugs, vulnerabilities, code smells, and technical debt before deployment.

---

## Why Docker?

Docker packages the application into a portable and consistent runtime image.

---

## Why Trivy?

Trivy scans container images for known vulnerabilities before publishing them.

---

## Why Amazon ECR?

Amazon Elastic Container Registry provides secure and scalable container image storage.

---

## Why ArgoCD?

ArgoCD enables GitOps-based deployments where Kubernetes continuously reconciles cluster state with Git.

---

## Why Amazon EKS?

Amazon EKS provides a managed Kubernetes control plane with high availability and AWS integration.

---

## Why Separate Git Repositories?

Separating application code and deployment manifests improves security, auditability, and change management.

---

## Monitoring

Prometheus collects metrics.

Grafana visualizes dashboards.

Loki aggregates application logs.

CloudWatch monitors AWS infrastructure.
