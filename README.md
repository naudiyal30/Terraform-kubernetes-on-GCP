# Running Kubernetes on Google Cloud Platform using Terraform

## Terraform

Infrastructure is managed using Terraform via the Google Cloud provider, which handles resources such as:

- CloudDNS and compute addresses
- Container clusters
- Networking

## Kubernetes

Cluster components and some cluster-specific infrastructure resources are managed through Kubernetes:

- App deployments, services and ingress
- GCP load balancers (via ingress)
- Cache stateful sets
- Secrets for the app and SSL certificates
- Autoscaling
