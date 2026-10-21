<h1 align="center">Hi, I'm Mohammed 👋</h1>

<p align="center">
  Software Engineering student at Concordia University (Co-op), building on AWS and working on cloud, DevOps and backend.<br>
  FinOps Intern at Intact Financial Corporation, Montreal.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammed-el-ouaabani-808014384"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mohammed.elouaabani@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## 💫 About me

I like cloud systems that are secure by default, cheap to run and easy to deploy: private subnets, least-privilege IAM, everything in Terraform, and every pull request gated by tests. I also build with AI coding agents every day, which is what led me to start Prusik, a safety layer for them.

Open to Summer 2027 internships in cloud, DevOps and backend development in Montreal.

---

## 🧗 Currently building

### [Prusik](https://github.com/momoElbn/prusik): a safety layer for AI coding agents

> *Slides when you climb. Grips when you fall.*

AI coding agents now get the keys to real systems, and once in a while one does something that can't be undone. Prusik sits between the agent and production. An AI model grades every command in context, known-safe commands skip the AI, and anything dangerous is held: it takes a snapshot, asks a human to approve, and keeps an undo ready.

- **Status:** open source (Apache-2.0) and in active development, with the first release (v0.1) planned
- **Planned for v0.1:** Claude Code hook, local AI grading through Ollama, snapshots, terminal approval and `prusik undo`
- **Follow along:** [repository](https://github.com/momoElbn/prusik)
<!-- Once the site is live, use this line instead:
- **Follow along:** [website](WEBSITE_URL_HERE) · [repository](https://github.com/momoElbn/prusik)
-->

---

## 🚀 Projects

- **[PayloadWatch](https://github.com/momoElbn/PayloadWatch)**: cloud-native API observability platform that catches silent failures uptime monitors miss, by validating live responses against user-defined JSON contracts. Spring Boot polling engine with Cognito JWT auth, deployed on AWS behind an HTTPS ALB (Route 53, ACM) over ECS Fargate Spot in 2 AZs, with RDS in isolated subnets. GitHub Actions ships every release (Docker build, ECR push, ECS deploy) with CloudWatch logs and metrics.
- **Flash Sale Engine**: high-concurrency flash-sale transaction engine built with atomic SQL transactions to prevent race conditions. In local k6 load tests: zero overselling at 300 concurrent users, 0.64 ms average latency, 9,300 req/s peak, and a 99.58% success rate across 140,000+ transactions at 1,000 concurrent users. Node.js, Express, PostgreSQL.

---

## 💼 Experience

**FinOps Intern, Intact Financial Corporation** (Sept. 2026 to present, Montreal)

- Gave procurement its first AI usage and spend visibility against contract commitments for 3,500+ unique Copilot and Devin users, with forecasts projecting 71% savings on overage fees
- Built a serverless pipeline (EventBridge, Step Functions, Lambda) into KMS-encrypted RDS that processes 12,800+ rows per upload in about 6 seconds
- Kept the data subnets private and saved about $900 a year in NAT Gateway cost by fetching FX rates from a Lambda outside the VPC
- Automated Terraform deployments with GitHub Actions, gating every PR on 352+ unit and E2E tests and 90% coverage

---

## 💻 Tech stack

### ☁️ Cloud and DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🖥️ Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🔧 Backend and frontend

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🤖 GenAI and LLMs

![LLM-as-Judge](https://img.shields.io/badge/LLM--as--Judge-8B5CF6?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-A78BFA?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111827?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Model Evaluation](https://img.shields.io/badge/Model_Evals-0F766E?style=for-the-badge)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-F59E0B?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-6D28D9?style=for-the-badge)

### 🧪 Testing and tools

![k6](https://img.shields.io/badge/Grafana_k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

**AWS services I've worked with:** Lambda, Step Functions, EventBridge, S3, API Gateway, RDS, VPC, IAM, KMS, Secrets Manager, CloudTrail, CloudWatch, SNS, AWS Backup, ECS Fargate, ALB

---

## 🏆 Certifications and awards

- **AWS Certified Solutions Architect, Associate (SAA-C03)**: in progress, expected November 2026
- **AWS Certified Cloud Practitioner (CLF-C02)** (March 2026)
- **1st Place, Interac Track**, @Hack Cybersecurity CTF Hackathon (March 2026)

---

## 🎓 Education

**Concordia University**, Bachelor of Engineering in Software Engineering (Co-op), expected 2029
