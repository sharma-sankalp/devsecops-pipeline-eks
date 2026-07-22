# ArgoCD

ArgoCD continuously monitors the Kubernetes manifest repository.

Whenever Jenkins updates the deployment manifests with a new image tag, ArgoCD automatically synchronizes the desired state with the Amazon EKS cluster.

This demonstrates a GitOps-based Continuous Delivery workflow.