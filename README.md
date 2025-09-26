# Demo GitOps Application

This is a sample application demonstrating GitOps principles with ArgoCD.

## Architecture
- **Application**: Simple Nginx web server
- **Deployment**: 2 replicas for high availability
- **Service**: ClusterIP for internal communication
- **Ingress**: External access configuration

## GitOps Workflow
1. Code changes committed to this repository
2. ArgoCD detects changes automatically
3. ArgoCD syncs changes to Kubernetes cluster
4. Application updates without manual intervention

## Environments
- **Development**: This branch (main)
- **Staging**: staging branch (planned)
- **Production**: production branch (planned)
