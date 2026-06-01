<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Ensizziyo Ziraka — Mission Control" />

<img src="./assets/divider.svg" width="100%" alt="" />

</div>

### `~/ whoami`

Information Systems Security Engineer Intern **@ SAP NS2**, working in a FedRAMP-aligned environment on security-operations automation and cloud compliance. IT & Cybersecurity student at **George Mason University**.

I design and ship **production-grade cloud, security, and Kubernetes systems** — end-to-end, entirely in code, with AI woven into the operations layer. What's below isn't a list of tutorials. It's one connected platform: the stack a real engineering team runs on.

<div align="center">

#### ◤ ARSENAL ◢

![AWS](https://img.shields.io/badge/AWS-0B1020?style=flat-square&logo=amazonaws&logoColor=22D3EE)
![Azure](https://img.shields.io/badge/Azure-0B1020?style=flat-square&logo=microsoftazure&logoColor=22D3EE)
![Terraform](https://img.shields.io/badge/Terraform-0B1020?style=flat-square&logo=terraform&logoColor=22D3EE)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0B1020?style=flat-square&logo=kubernetes&logoColor=22D3EE)
![Docker](https://img.shields.io/badge/Docker-0B1020?style=flat-square&logo=docker&logoColor=22D3EE)
![Helm](https://img.shields.io/badge/Helm-0B1020?style=flat-square&logo=helm&logoColor=22D3EE)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0B1020?style=flat-square&logo=githubactions&logoColor=22D3EE)
![Prometheus](https://img.shields.io/badge/Prometheus-0B1020?style=flat-square&logo=prometheus&logoColor=22D3EE)
![Grafana](https://img.shields.io/badge/Grafana-0B1020?style=flat-square&logo=grafana&logoColor=22D3EE)
![Splunk](https://img.shields.io/badge/Splunk-0B1020?style=flat-square&logo=splunk&logoColor=22D3EE)
![Trivy](https://img.shields.io/badge/Trivy-0B1020?style=flat-square&logo=trivy&logoColor=22D3EE)
![Claude](https://img.shields.io/badge/Claude-0B1020?style=flat-square&logo=anthropic&logoColor=E879F9)
![Python](https://img.shields.io/badge/Python-0B1020?style=flat-square&logo=python&logoColor=22D3EE)
![Node.js](https://img.shields.io/badge/Node.js-0B1020?style=flat-square&logo=nodedotjs&logoColor=22D3EE)
![Bash](https://img.shields.io/badge/Bash-0B1020?style=flat-square&logo=gnubash&logoColor=22D3EE)

#### ◤ TELEMETRY ◢

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Vziraka&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0B1020&title_color=22D3EE&icon_color=E879F9&text_color=9FB3C8&ring_color=E879F9" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vziraka&layout=compact&hide_border=true&bg_color=0B1020&title_color=22D3EE&text_color=9FB3C8&langs_count=8" alt="top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vziraka&hide_border=true&background=0B1020&ring=22D3EE&fire=E879F9&currStreakLabel=22D3EE&sideLabels=9FB3C8&dates=5A7CA8&stroke=1C2C4A&sideNums=E6F6FF&currStreakNum=E6F6FF&dayLabels=9FB3C8&currStreakNum=E6F6FF" alt="streak" />

<img src="./assets/divider.svg" width="100%" alt="" />

</div>

## ▚ 01 · CLOUD & PLATFORM ENGINEERING

▸ **[Full-Stack CI/CD Pipeline → ECS Fargate](https://github.com/Vziraka/fullstack-cicd-pipeline)** — 4-job GitHub Actions pipeline: Jest → multi-stage Docker → Trivy CVE gate → **OIDC to AWS (zero static keys)** → ECR → ECS staging → prod behind a manual approval gate. Every deploy auto-writes a stakeholder summary via Claude. All infra in Terraform.

▸ **[Serverless AI Document API](https://github.com/Vziraka/serverless-ai-api-)** — PDF → presigned S3 upload (the Lambda never touches the bytes) → Claude extracts summary + topics → DynamoDB. Cognito JWT auth, Secrets Manager rotation, SQS DLQ, 22 unit tests, zero hardcoded credentials.

▸ **[Terraform Starter Kit — Secure 3-Tier AWS](https://github.com/Vziraka/terraform-starter-kit)** — Modular Terraform: 2-AZ VPC, bastion, defense-in-depth security groups, least-privilege IAM, encrypted RDS, versioned S3. Remote state in S3 + DynamoDB locking, isolated dev/prod.

▸ **[AI Cost-Optimization Dashboard](https://github.com/Vziraka/cost-optimization-dashboard)** — Weekly EventBridge → Lambda pulls Cost Explorer spend → DynamoDB trends → Claude flags >20% week-over-week jumps and posts the top 3 savings to Slack `#finops`.

## ▚ 02 · KUBERNETES & OBSERVABILITY

▸ **[K8s Microservices Platform](https://github.com/Vziraka/k8s-microservices-)** — 2 Node.js services, nginx ingress, HPA autoscaling 2→5 pods, one-command Helm chart. An AI health CronJob reads cluster state via read-only RBAC → Claude → GREEN/YELLOW/RED to Slack every 5 min.

▸ **[Monitoring & Alerting Stack](https://github.com/Vziraka/monitoring-alerting-stack-)** — Full observability via kube-prometheus-stack: Prometheus RED metrics, Grafana, Alertmanager → Slack with runbook links. An AI anomaly CronJob classifies severity so it only pings when something's actually wrong. 10 incident runbooks.

## ▚ 03 · SECURITY OPERATIONS & RESILIENCE

▸ **[SOC Automation Pipeline — Splunk + n8n + AI](https://github.com/Vziraka/SOC-automation-project)** — End-to-end SOAR: Splunk detects → n8n orchestrates → AbuseIPDB enriches → AI writes analyst-ready triage → Slack. Manual triage driven to near-zero.

▸ **[Azure SOC Homelab](https://github.com/Vziraka/Azure-SOC-HomeLab)** — Microsoft Sentinel + Log Analytics, KQL detections for failed logons (Event ID 4625), geo-mapped attack visualization via Watchlists.

▸ **[Disaster Recovery & Security Posture](https://github.com/Vziraka/disaster-recovery-system)** — Cross-region AWS Backup (RDS + S3 → us-west-2), Security Hub (CIS + FSBP), and a Lambda that turns findings into a plain-English posture report every 6h.

## ▚ 04 · AUTONOMOUS AI SYSTEMS

▸ **AI Agent System** *(private)* — 24/7 autonomous infrastructure: specialized agents (Intel, Research, Developer, R&D Debate Council) behind a Next.js Mission Control with live heartbeats, cost tracking, and an approval queue. Hard security guardrails and a daily API spend cap.

<div align="center"><img src="./assets/divider.svg" width="100%" alt="" /></div>

## ▚ CURRENT ROLE

**Information Systems Security Engineer Intern · SAP NS2**
Security-operations automation, security-tool integration via APIs, and vulnerability-management & compliance monitoring in a FedRAMP-aligned environment.

## ▚ CERTIFICATIONS & TRAINING

![Security+](https://img.shields.io/badge/CompTIA%20Security%2B-In%20Progress-0B1020?style=flat-square&logo=comptia&logoColor=E879F9&labelColor=0B1020)
![Google Cybersecurity](https://img.shields.io/badge/Google%20Cybersecurity-Certified-0B1020?style=flat-square&logo=google&logoColor=22D3EE&labelColor=0B1020)
![AWS Educate](https://img.shields.io/badge/AWS%20Educate-Cloud%20%26%20Security-0B1020?style=flat-square&logo=amazonaws&logoColor=22D3EE&labelColor=0B1020)
![KodeKloud](https://img.shields.io/badge/KodeKloud-DevOps%20Labs-0B1020?style=flat-square&logo=kubernetes&logoColor=22D3EE&labelColor=0B1020)

## ▚ CONNECT

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1020?style=for-the-badge&logo=linkedin&logoColor=22D3EE)](https://www.linkedin.com/in/ensizziyo-ziraka/)

<div align="center"><sub><code>SOC & Detection Engineering · Cloud Security (AWS/Azure) · Kubernetes Security · DevSecOps · Security Automation</code></sub></div>
