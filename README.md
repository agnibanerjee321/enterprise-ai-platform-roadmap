# Enterprise AI Platform Engineering Roadmap

This repository documents my 6-month hands-on roadmap to become a strong Platform Engineer / Cloud Architect with AI infrastructure capability.

## Goal

Build a production-style enterprise platform covering:

- Linux and networking foundations
- Azure landing zone
- Infrastructure as Code with Terraform and Bicep
- Secure CI/CD with GitHub Actions
- Docker and Kubernetes
- GitOps
- DevSecOps and Policy as Code
- Observability and SRE
- AI-powered operations platform
- Internal developer platform concepts

## Final Architecture Vision

The final platform will include:

```text
Azure Landing Zone
   |
   +-- Hub-Spoke Networking
   +-- IAM / RBAC
   +-- Key Vault
   +-- Azure Policy
   +-- Monitoring
   |
   v
AKS Kubernetes Platform
   |
   +-- Secure Application Deployments
   +-- Ingress
   +-- TLS
   +-- GitOps
   +-- Policy as Code
   +-- Observability
   |
   v
AI-Powered Operations Layer
   |
   +-- RAG over documentation and runbooks
   +-- Incident explanation assistant
   +-- Platform troubleshooting assistant
   +-- Self-service developer workflows
