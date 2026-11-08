<h1 align="center">Hi, I'm Mohammed 👋</h1>

<p align="center">
  Software Engineering student at Concordia University (Co-op), working on cloud, distributed systems and backend.<br>
  FinOps Intern at Intact Financial Corporation, Montreal.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammed-el-ouaabani-808014384"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mohammed.elouaabani@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

I like systems that are secure by default, cheap to run and easy to deploy, and I like proving they work by breaking them on purpose. Open to **Summer 2027 internships** in cloud, DevOps and backend development in Montreal.

---

## ⭐ Featured: [Quorum](https://github.com/momoElbn/quorum)

**A Raft-replicated key-value store with a Kubernetes operator that keeps it available through crashes, scaling and upgrades.**

Go · hashicorp/raft · Kubernetes operator (kubebuilder) · Helm · Argo CD (GitOps) · Prometheus + Grafana · GitHub Actions → GHCR

- **0 acknowledged writes lost** across 86 leader kills (SIGKILL) and 517,000+ acknowledged writes at 100 writes/s
- **~2 s median failover**, and a readiness fix that cut repeat outages after an election from 4–6 per run to 1
- **Safe scaling 3 → 5 → 3 under load:** the operator removes members from Raft before deleting pods, so a follower crash afterwards cost 0–1 failed writes, versus a ~6 s outage with naive scaling

[Repository](https://github.com/momoElbn/quorum) · [Design decisions](https://github.com/momoElbn/quorum/blob/main/docs/decisions.md) · [GitOps repo](https://github.com/momoElbn/quorum-gitops)

---

## 🚀 Other projects

- **[PayloadWatch](https://github.com/momoElbn/PayloadWatch)**: my first hands-on step into AWS solutions architecture. An API monitor that validates live responses against JSON contracts, built to practice a production-style AWS design: HTTPS ALB (Route 53, ACM) in front of ECS Fargate Spot across 2 AZs, RDS in isolated subnets, Cognito JWT auth, and a GitHub Actions pipeline to ECR and ECS with CloudWatch logs and metrics. Spring Boot.
- **Flash Sale Engine**: high-concurrency checkout using atomic SQL transactions. In k6 load tests: zero overselling at 300 concurrent users, 9,300 req/s peak and a 99.58% success rate over 140,000+ transactions at 1,000 users. Node.js, Express, PostgreSQL.

---

## 💼 Experience

**FinOps Intern, Intact Financial Corporation** (Sept. 2026 to Dec. 2026, Montreal)

- Cut ETL cost by∼95% to $18/mo (∼$4K/yr saved) by merging 5 GitHub Actions workflows and 2 always-on
Airflow DAGs into one serverless event-driven pipeline (EventBridge cron, dbt on ECS Fargate) that unifies 8 cloud,
AI, and SaaS sources, ends 3-month-stale Entra ID data, and onboards new ones as a single task definition.
- Built an internal FastAPI/React showback tool on the pipeline that gave all Intact teams visibility into
MongoDB/HashiCorp spend before chargeback, presented to VPs, SVPs, and Directors.
- Made releases safe and failures visible by gating PRs on 352+ unit/E2E tests and 90% coverage, shipping
images to ECR with probe-verified rollbacks, running a 3-stage Terraform CI with comment-triggered apply, plus
CloudWatch failure/freshness alarms with SNS alerts.
- Made a sluggish internal LLM usage dashboard (tracking 11,000+ employees) seamless by speeding up 11
production API endpoints a median 3.1x (up to 14.9x) with caching, SQL indexing, and query rewrites.

---

## 💻 Tech stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
<br>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 🏆 Certifications and awards

- **AWS Certified Solutions Architect, Associate (SAA-C03)** (October 2026)
- **AWS Certified Cloud Practitioner (CLF-C02)** (March 2026)
- **1st Place, Interac Track**, @Hack Cybersecurity CTF Hackathon (March 2026)

## 🎓 Education

**Concordia University**, Bachelor of Engineering in Software Engineering (Co-op), expected 2029
