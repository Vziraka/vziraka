Hi, I'm Ensizziyo 👋

I'm an IT and Cybersecurity student at George Mason University, currently interning as an **Information Systems Security Engineer at SAP NS2**, supporting enterprise cloud infrastructure for U.S. national security customers. I build production-grade security and cloud systems — 10 end-to-end projects spanning AWS, Azure, Kubernetes, Terraform, and AI-powered automation.

---

## 👨‍💻 Project Portfolio

### 🔒 Security & SOC

- 🤖 **[SOC Automation Pipeline – Splunk + n8n + AI](https://github.com/Vziraka/SOC-automation-project)**
  Full SOAR pipeline: Splunk detects suspicious IPs → n8n orchestrates → AbuseIPDB enriches threat intel → ChatGPT generates triage summaries → Slack delivers analyst-ready alerts. Reduces manual triage to near-zero.

- 🏠 **[Azure SOC Homelab](https://github.com/Vziraka/Azure-SOC-HomeLab)**
  Deployed Azure VMs, configured Log Analytics + Microsoft Sentinel, wrote KQL to detect failed logins (Event ID 4625), and built geolocation attack visualization with Watchlists.

- 🛡️ **[Disaster Recovery & Security Posture System](https://github.com/Vziraka/disaster-recovery-system)**
  Cross-region AWS Backup (RDS + S3 → us-west-2), Security Hub (CIS + FSBP benchmarks), and an AI security dashboard: EventBridge triggers Lambda every 6h → Claude Haiku analyzes findings → HTML posture report to S3.

- 🌐 **[AWS VPC Networking Lab](https://github.com/Vziraka/AWS-VPC-Networking-Project)**
  Secure VPC with public/private subnet segmentation, VPC peering, Flow Logs to CloudWatch for ACCEPT/REJECT analysis, and S3 Gateway endpoint with private-only bucket policy.

---

### ☁️ Cloud & Infrastructure

- 🚀 **[Full-Stack CI/CD Pipeline on ECS Fargate](https://github.com/Vziraka/fullstack-cicd-pipeline)**
  4-job GitHub Actions pipeline: Jest → Docker → Trivy CVE scan → OIDC auth to AWS (zero static credentials) → ECR → ECS staging → ECS production with manual approval gate. Deployments auto-generate stakeholder summaries via Claude Haiku. Infrastructure in Terraform.

- ⚙️ **[Serverless AI Document API](https://github.com/Vziraka/serverless-ai-api-)**
  Production REST API: PDF upload → S3 triggers Lambda → Claude Haiku extracts summary + key topics → DynamoDB. Cognito JWT auth, presigned URLs, Secrets Manager rotation, SQS DLQ, 22 unit tests, zero hardcoded credentials.

- 🏗️ **[Production AWS Infrastructure – Terraform Starter Kit](https://github.com/Vziraka/terraform-starter-kit)**
  Modular Terraform: VPC across 2 AZs, NAT gateway, bastion host, 3-tier security groups, least-privilege IAM, encrypted RDS PostgreSQL, versioned S3. Remote state in S3 + DynamoDB locking, separate dev/prod environments.

---

### 🐳 Kubernetes & Observability

- 🧩 **[K8s Microservices Platform](https://github.com/Vziraka/k8s-microservices-)**
  2 Node.js microservices on Kubernetes with nginx ingress routing, HPA autoscaling (2→5 pods), Helm chart for single-command deployment. AI health CronJob: cluster state → Claude Haiku → GREEN/YELLOW/RED Slack report every 5 min.

- 📊 **[Monitoring & Alerting Stack](https://github.com/Vziraka/monitoring-alerting-stack-)**
  Full observability on K8s via Helm: Prometheus (RED/USE metrics), Grafana dashboards, Alertmanager → Slack. AI anomaly detector CronJob queries Prometheus → Claude Haiku classifies severity → alerts only on anomalies. 10 incident runbooks.

---

### 🤖 AI Systems

- 🧠 **AI Agent System** *(private repo)*
  24/7 autonomous infrastructure with 7 specialized agents (Intel, Job Search, Research, Developer, R&D Debate Council, Overnight Employee). Next.js Mission Control dashboard with Kanban, live heartbeats, cost tracking, and approval queue. Claude Sonnet + Gemini Flash with hard security guardrails and $5/day API cap.

---

## 💼 Current Role

**Information Systems Security Engineer Intern @ SAP NS2** *(Mar 2026 – Present)*
Building security operations automation, integrating security tools via APIs, and supporting vulnerability management and compliance monitoring in a FedRAMP-aligned environment.

---

## 📜 Certifications

- 🎯 **CompTIA Security+** — In Progress
- 🛡️ **Google Cybersecurity Professional Certificate** — Coursera
- ☁️ **AWS Educate** — Cloud Computing & Security Labs
- 🔧 **KodeKloud** — Hands-on DevOps Labs (Docker, Kubernetes, CI/CD)

---

## 🤳 Connect

- 🔗 **LinkedIn:** https://www.linkedin.com/in/ensizziyo-ziraka/

---

### 🔍 Interests
- SOC Operations & Detection Engineering
- Cloud Security (AWS & Azure)
- Kubernetes & Container Security
- SIEM, Observability & Security Automation
- DevSecOps & Secure CI/CD
