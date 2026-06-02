# Hi, I'm Mounika 👋

> DevOps Engineer passionate about building secure, scalable, and self-healing cloud infrastructure.

---

## 🛠️ What I Build

I design and deploy production-grade infrastructure on AWS using modern DevOps practices — infrastructure as code, GitOps, container orchestration, and security-first CI/CD pipelines.

---

## 🚀 Featured Projects

### 🚀 [Deploy 3-Tier App on EKS](https://github.com/NMounikaMokamatam/eks-3tier-app)
Production-ready 3-tier application (frontend + backend + PostgreSQL) running on Amazon EKS with full GitOps deployment.
- Multi-stage Dockerfiles with non-root users and healthchecks
- EKS cluster provisioned with Terraform across 3 availability zones
- ArgoCD auto-syncs from Git with self-heal and pruning
- GitHub Actions pipeline: test, scan, build, push, deploy
- Prometheus and Grafana monitoring with Slack alerting
- Horizontal Pod Autoscaler on frontend and backend

`Docker` `Kubernetes` `Terraform` `ArgoCD` `GitHub Actions` `Prometheus` `Grafana` `AWS EKS`

---

### ⚡ [Auto-Healing Infrastructure](https://github.com/NMounikaMokamatam/auto-healing-infra)
Self-healing AWS infrastructure that automatically detects and recovers from EC2 failures without human intervention.
- CloudWatch alarms trigger on CPU over 80 percent and failed status checks
- SNS fan-out invokes Lambda and Slack simultaneously
- Python 3.12 Lambda stops and restarts the affected EC2 instance
- Formatted Slack alert sent with instance ID, alarm name, and timestamp
- Full infrastructure in Terraform including VPC, IAM, and dashboards
- GitHub Actions deploys on merge with Terraform plan posted to PRs

`Python` `AWS Lambda` `CloudWatch` `SNS` `EC2` `Terraform` `Slack` `GitHub Actions`

---

### 🔐 [Secure GitOps Pipeline](https://github.com/NMounikaMokamatam/secure-gitops-pipeline)
A battle-tested CI/CD pipeline where no image touches production unless it passes security scanning and no secret ever lives in code.
- Trivy blocks CRITICAL and HIGH CVEs before image reaches ECR
- HashiCorp Vault injects secrets at runtime via agent sidecar
- ArgoCD only deploys Trivy-verified images from ECR
- ECR uses immutable image tags and lifecycle policies
- Pods run as non-root with readOnlyRootFilesystem
- PR gate runs Trivy filesystem scan and Terraform validate

`Trivy` `HashiCorp Vault` `ArgoCD` `ECR` `EKS` `Terraform` `GitHub Actions` `Security`

---

## 🧰 Tech Stack

**Cloud**
AWS EKS, EC2, ECR, Lambda, CloudWatch, SNS, VPC, IAM, S3

**Infrastructure as Code**
Terraform, Helm

**Containers and Orchestration**
Docker, Kubernetes, ArgoCD, Helm

**CI/CD and Security**
GitHub Actions, Trivy, HashiCorp Vault

**Languages**
Python, Bash, HCL, YAML

**Monitoring**
Prometheus, Grafana, CloudWatch, Slack

---

## 📈 GitHub Stats

![Mounika's GitHub stats](https://github-readme-stats.vercel.app/api?username=NMounikaMokamatam&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NMounikaMokamatam&layout=compact&theme=dark&hide_border=true)

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/YOUR_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/NMounikaMokamatam)

---

*Every project here reflects real production patterns used by engineering teams at scale.*
