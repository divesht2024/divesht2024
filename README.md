# Hi, I'm Divesh Tayade 👋

### ☁️ Cloud / DevOps Engineer | AWS • Kubernetes • Terraform • Docker • Jenkins • GitHub Actions • CI/CD • DevSecOps • Prometheus • Grafana

🚀 **AWS Certified Solutions Architect – Associate** and Cloud/DevOps Engineer with **9 months of hands-on experience** at Engiplex Solutions, managing AWS infrastructure, automating CI/CD pipelines, and deploying containerized workloads on EKS/ECS. I build secure, reliable, production-ready cloud environments with Terraform, Kubernetes, and automated security scanning.

📍 Pune, India • ✅ **Available immediately** • 🎯 Open to **DevOps Engineer**, **Cloud Engineer**, and **Cloud Support / Operations Engineer** roles

---

## 💼 Experience

**Junior Cloud Engineer — Engiplex Solutions** *(Remote, Oct 2025 – Jul 2026)*

- ✅ Managed AWS operations across **15+ EC2 instances** and **3 VPCs**: patching, snapshots, Security Group and IAM changes, and target-health checks under least-privilege and change-management procedures
- ✅ Built **Lambda, SNS, SQS, and DynamoDB** automations (scheduled EC2 start/stop), cutting non-production costs by about **25%**
- ✅ Containerized **6+ applications** with Docker (image size reduced by about **40%**) and deployed them on **EKS/ECS** via ECR and Helm; fixed CrashLoopBackOff and ImagePullBackOff issues, cutting recovery time to under **15 minutes**
- ✅ Automated infrastructure with reusable **Terraform** modules (S3 remote state, DynamoDB locking) and maintained **8+ Jenkins and GitHub Actions pipelines** with SonarQube, Trivy, and OWASP checks, cutting deployment time from about 30 to 10 minutes
- ✅ Monitored systems with **CloudWatch, Prometheus, and Grafana** (20+ alarms and dashboards); resolved **30+ incidents** on RHEL/Ubuntu servers and documented **10+ runbooks**

---

## 🚀 Technical Skills

| Category | Skills |
|----------|--------|
| ☁️ **Cloud (AWS)** | EC2, VPC, S3, IAM, EBS, RDS, Route 53, ALB, ASG, Multi-AZ, SNS, SQS, Lambda, API Gateway, ECR, ECS, EKS, DynamoDB, CloudTrail |
| ☸️ **Kubernetes** | Pods, Deployments, ReplicaSets, Services, Ingress, Namespaces, ConfigMaps, Secrets, HPA, Probes, Rolling Updates, Helm, kubectl |
| 🛠️ **Infrastructure as Code** | Terraform — Modules, Variables, Outputs, Remote S3 Backend, DynamoDB State Locking |
| 🔄 **CI/CD** | Jenkins, GitHub Actions — Workflows, Triggers, Secrets, Docker Integration, Terraform Automation |
| 🛡️ **DevSecOps** | SonarQube (static code analysis), Trivy (container & IaC scanning), OWASP, quality gates |
| 🐳 **Containerization** | Docker — Dockerfile, Multi-stage Builds, Docker Compose, Networking, Volumes, ECR Integration |
| 🌍 **Web Servers** | NGINX, Apache HTTP Server, Reverse Proxy, SSL/TLS, Load Balancing |
| 🌐 **Networking** | VPC Design, Public/Private Subnets, Route Tables, IGW, NAT Gateway, Security Groups, NACLs, DNS, HTTP/HTTPS, TCP/IP |
| 📊 **Monitoring & Observability** | Prometheus, Grafana, CloudWatch — Dashboards, Metrics, Alarms, Logs Insights |
| 💻 **Linux & Scripting** | RHEL/Ubuntu, Bash, Python (Boto3), File Permissions, Process Management, Cron Jobs, SSH |
| 🔧 **Version Control** | Git, GitHub |

---

# 📌 Featured Projects

## 🔹 BrewSecOps — Secure Cloud-Native Deployment on AWS & Kubernetes
- ✅ Built an end-to-end **DevSecOps CI/CD pipeline** in Jenkins that runs a SonarQube quality gate, Trivy image scan, Docker build, and Amazon ECR push automatically on every commit
- ✅ Deployed the app on **Amazon EKS** with Helm, Ingress, health probes, resource limits, and HPA for repeatable releases and automatic scaling
- ✅ Implemented **Prometheus and Grafana** dashboards with alerts for 5+ failure scenarios (pod failures, high resource usage, service unavailability)

**Tech:** `Jenkins` `Docker` `Kubernetes` `Amazon EKS` `Helm` `AWS ECR` `AWS ALB` `Cloudflare` `SonarQube` `Trivy` `OWASP Dependency-Check` `Prometheus` `Grafana` `Email Alerts`


---

## 🔹 Production-Grade 3-Tier Architecture on AWS
- ✅ Architected a fault-tolerant 3-tier AWS infrastructure across 2 Availability Zones with isolated public and private subnets for web, application, and database tiers
- ✅ Configured ALB with path-based routing and ASG with dynamic scaling policies, enabling automatic scale-out from 2 to 4 EC2 instances with least-privilege IAM roles and Security Groups per tier
- ✅ Deployed Amazon RDS MySQL in private subnets with Multi-AZ failover, removing the single point of failure
- ✅ Configured CloudWatch alarms on CPU, memory, and request metrics with SNS alerts
- ✅ Deployed and validated a full-stack web application end to end across all three tiers

**Tech:** `EC2` `VPC` `ALB` `Auto Scaling` `RDS` `NAT Gateway` `IAM` `Security Groups` `CloudWatch` `SNS`

---

## 🔹 AWS Infrastructure Automation using Terraform + GitHub Actions
- ✅ Automated provisioning of 10+ AWS resources including VPC, EC2, IAM roles, and Security Groups using Terraform
- ✅ Built 4+ reusable Terraform modules with variables and outputs, enabling consistent one-command deployment across dev and prod environments
- ✅ Configured S3 remote backend with DynamoDB state locking to prevent concurrent state conflicts
- ✅ Integrated a GitHub Actions pipeline that runs Terraform format checks, validation, and plan on every pull request, with automated apply on merge to main

**Tech:** `Terraform` `GitHub Actions` `AWS` `S3` `DynamoDB` `IAM` `VPC`

---

## 🔹 AWS Cost Optimization Toolkit
- ✅ Built serverless automation using Python (Boto3) to detect stale AWS resources — unattached EBS volumes, unused Elastic IPs, and oversized S3 buckets — via Lambda functions triggered by EventBridge schedules
- ✅ Automated scheduled EC2 shutdown and startup using Lambda and EventBridge cron expressions, reducing compute costs during non-business hours
- ✅ Configured SNS notifications for cost alerts, enabling proactive resource cleanup

**Tech:** `Python` `Boto3` `Lambda` `EventBridge` `SNS` `EC2` `EBS` `S3`

---

## 🔹 Serverless Image Processing Pipeline
- ✅ Designed an event-driven serverless pipeline using Python (Boto3) that triggers image processing on S3 upload events via Lambda, eliminating dedicated compute instances
- ✅ Integrated SNS for post-processing notifications and CloudWatch alarms for monitoring and failure alerting

**Tech:** `Python` `Boto3` `Lambda` `S3` `SNS` `CloudWatch`

---

## 📚 Currently Learning

- ☸️ **Advanced Kubernetes** — troubleshooting, scaling, and production practices
- 🛡️ **Advanced DevSecOps** — security automation and CI/CD integration

---

## 🎓 Certifications

- ✅ **AWS Certified Solutions Architect – Associate (SAA-C03)**, 2026 — [Verify on Credly](https://www.credly.com/badges/2d1105d0-847d-4c22-ac10-788e23dbaa9e/public_url)

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/diveshtayade)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/divesht2024)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diveshtayade20@gmail.com)

---

🚀 Building Cloud Infrastructure | Automating CI/CD | Securing Pipelines | Open to DevOps & Cloud Roles
