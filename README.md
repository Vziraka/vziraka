<div align="center">

![](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3200&pause=900&color=00E5FF&center=true&vCenter=true&width=820&lines=Information+Systems+Security+Engineer+%40+SAP+NS2;I+build+production-grade+cloud+%26+security+systems;AWS+%E2%80%A2+Azure+%E2%80%A2+Kubernetes+%E2%80%A2+AI-driven+automation;Systems%2C+not+side+projects.)

</div>

---

### `whoami`

Information Systems Security Engineer Intern **@ SAP NS2**, working in a FedRAMP-aligned environment on security-operations automation and cloud compliance. IT & Cybersecurity student at **George Mason University**.

I design and ship **production-grade cloud, security, and Kubernetes systems** — end-to-end, entirely in code, with AI woven into the operations layer. Below isn't a list of tutorials. It's one connected platform: the stack a real engineering team runs on.

<div align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=65A637)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=trivy&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Vziraka&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0D1117" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vziraka&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vziraka&theme=tokyonight&hide_border=true&background=0D1117" />

<img src="https://github-profile-trophy.vercel.app/?username=Vziraka&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=8" />

</div>

---

## ☁️ Cloud & Platform Engineering

- 🚀 **[Full-Stack CI/CD Pipeline → ECS Fargate](https://github.com/Vziraka/fullstack-cicd-pipeline)** — 4-job GitHub Actions pipeline: Jest → multi-stage Docker → Trivy CVE gate → **OIDC to AWS (zero static keys)** → ECR → ECS staging → prod behind a manual approval gate. Every deploy auto-writes a stakeholder summary via Claude. All infra in Terraform.
- ⚙️ **[Serverless AI Document API](https://github.com/Vziraka/serverless-ai-api-)** — PDF → presigned S3 upload (Lambda never touches the bytes) → Claude extracts summary + topics → DynamoDB. Cognito JWT auth, Secrets Manager rotation, SQS DLQ, 22 unit tests, zero hardcoded credentials.
- 🏗️ **[Terraform Starter Kit — Secure 3-Tier AWS](https://github.com/Vziraka/terraform-starter-kit)** — Modular Terraform: 2-AZ VPC, bastion, defense-in-depth security groups, least-privilege IAM, encrypted RDS, versioned S3. Remote state in S3 + DynamoDB locking, isolated dev/prod.
- 💸 **[AI Cost-Optimization Dashboard](https://github.com/Vziraka/cost-optimization-dashboard)** — Weekly EventBridge → Lambda pulls Cost Explorer spend → DynamoDB trends → Claude flags >20% WoW jumps and posts the top 3 savings to Slack #finops.

## 🐳 Kubernetes & Observability

- 🧩 **[K8s Microservices Platform](https://github.com/Vziraka/k8s-microservices-)** — 2 Node.js services, nginx ingress, HPA autoscaling 2→5 pods, one-command Helm chart. AI health CronJob reads cluster state via read-only RBAC → Claude → GREEN/YELLOW/RED to Slack every 5 min.
- 📊 **[Monitoring & Alerting Stack](https://github.com/Vziraka/monitoring-alerting-stack-)** — Full observability via kube-prometheus-stack: Prometheus RED metrics, Grafana, Alertmanager → Slack with runbook links. AI anomaly CronJob classifies severity so it only pings when something's actually wrong. 10 incident runbooks.

## 🔐 Security Operations & Resilience

- 🤖 **[SOC Automation Pipeline — Splunk + n8n + AI](https://github.com/Vziraka/SOC-automation-project)** — End-to-end SOAR: Splunk detects → n8n orchestrates → AbuseIPDB enriches → AI writes analyst-ready triage → Slack. Manual triage driven to near-zero.
- 🏠 **[Azure SOC Homelab](https://github.com/Vziraka/Azure-SOC-HomeLab)** — Microsoft Sentinel + Log Analytics, KQL detections for failed logons (4625), geo-mapped attack visualization via Watchlists.
- 🛡️ **[Disaster Recovery & Security Posture](https://github.com/Vziraka/disaster-recovery-system)** — Cross-region AWS Backup (RDS + S3 → us-west-2), Security Hub (CIS + FSBP), and a Lambda that turns findings into a plain-English posture report every 6h.

## 🤖 Autonomous AI Systems

- 🧠 **AI Agent System** *(private)* — 24/7 autonomous infrastructure: specialized agents (Intel, Research, Developer, R&D Debate Council) behind a Next.js Mission Control with live heartbeats, cost tracking, and an approval queue. Hard security guardrails and a daily API spend cap.

---

## 💼 Current Role

**Information Systems Security Engineer Intern · SAP NS2**
Security-operations automation, security-tool integration via APIs, and vulnerability-management & compliance monitoring in a FedRAMP-aligned environment.

## 📜 Certifications & Training

![Security+](https://img.shields.io/badge/CompTIA%20Security%2B-In%20Progress-FF0000?style=flat-square&logo=comptia&logoColor=white)
![Google](https://img.shields.io/badge/Google%20Cybersecurity-Certified-4285F4?style=flat-square&logo=google&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20Educate-Cloud%20%26%20Security-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![KodeKloud](https://img.shields.io/badge/KodeKloud-DevOps%20Labs-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ensizziyo-ziraka/)

<div align="center"><sub>SOC & Detection Engineering · Cloud Security (AWS/Azure) · Kubernetes Security · DevSecOps · Security Automation</sub></div>
