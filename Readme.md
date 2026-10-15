## Hi, I'm Navkaran 👋

**DevOps / SRE Engineer** · Gurugram, India  
I run production and UAT infrastructure for multi-tenant BFSI/insurance platforms: Kubernetes on EKS, Docker Swarm, GitLab CI/CD, observability, and secrets management.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-navkaran--singh-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/navkaran-singh-4255b9200)
[![Email](https://img.shields.io/badge/Email-navkaransinghhunjan%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:navkaransinghhunjan@gmail.com)

### Stack

| | |
|---|---|
| **Cloud & IaC** | AWS (EKS, EC2, VPC, IAM, S3, SSM, ECR) · GCP · Terraform · Ansible |
| **Containers** | Kubernetes (EKS · Karpenter · KEDA · Traefik) · Docker · Docker Swarm |
| **CI/CD** | GitLab CI (self-hosted instance admin) · GitHub Actions · Trivy |
| **Observability** | Prometheus · Grafana · Loki · Promtail · ELK · SigNoz / OpenTelemetry |
| **Scripting** | Bash · Python |

### Highlights

- Migrated containerised services to **EKS**: Karpenter node pools, scale-to-zero with KEDA, Traefik ingress, GitLab CI deploys
- Administer and harden a **self-hosted GitLab**: branch protection, force-push audits, merge policies, Bitbucket → GitLab migrations
- Built **Loki-based HTTP 4xx/5xx alerting** in Grafana, routed to Microsoft Teams
- Inject secrets into Swarm services from **AWS SSM Parameter Store** instead of committing env files

### Featured projects

| Project | What it shows |
|---|---|
| [eks-cicd-platform](https://github.com/navkaransinghhunjan/eks-cicd-platform) | EKS blueprint: Terraform, GitHub OIDC (no static keys), Trivy, `helm --atomic`, append-only deploy log |
| [gitlab-merge-config](https://github.com/navkaransinghhunjan/gitlab-merge-config) | Bulk-enforce fast-forward + squash merges across a GitLab instance |
| [API-Monitoring-With-Grafana](https://github.com/navkaransinghhunjan/API-Monitoring-With-Grafana) | Prometheus, Grafana, Loki and Promtail for a Flask app |
| [FastAPI-Monitoring-with-signoz](https://github.com/navkaransinghhunjan/FastAPI-Monitoring-with-signoz) | OpenTelemetry tracing into SigNoz |
| [Flask-Deployment-…-terraform](https://github.com/navkaransinghhunjan/Flask-Deployment-and-network-infra-creation-with-terraform) | VPC, subnets, security groups and EC2 with Terraform |
| [EC2-with-SSM-and-S3-Log-Storage](https://github.com/navkaransinghhunjan/EC2-with-SSM-and-S3-Log-Storage) | Least-privilege, SSM-managed EC2 with S3 log archival |

### Currently

- Going deeper on Kubernetes (CKA)
