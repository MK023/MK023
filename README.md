<h1 align="center">Hi, I'm Marco 👋</h1>

<p align="center">
  <strong>Cloud Platform &amp; Security Engineer</strong><br/>
  Production-grade Python · Kubernetes (K3s) · Terraform · AWS · OWASP hardening
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/marco-bellingeri">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-marco--bellingeri-0A66C2?style=flat&logo=linkedin&logoColor=white">
  </a>
  <a href="https://credly.com/users/marco-bellingeri">
    <img alt="Credly" src="https://img.shields.io/badge/Credly-badges-FF6B00?style=flat&logo=credly&logoColor=white">
  </a>
  <a href="mailto:marco.bellingeri@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-marco.bellingeri@gmail.com-D14836?style=flat&logo=gmail&logoColor=white">
  </a>
  <img alt="Open to work" src="https://img.shields.io/badge/Open%20to%20work-remote%2Fhybrid%20Italy-brightgreen?style=flat">
</p>

---

## About me

I design and run cloud-native platforms with **security-by-design**: OWASP Top 10 hardening, infrastructure-as-code, CI/CD with blocking security gates, observability with Prometheus/Grafana/Sentry. I enjoy the boring production problems — graceful shutdown, credential rotation, incident postmortems, real backups — more than the shiny demos.

**Current stack:** Python 3.12 (FastAPI, Falcon, Flask) · Kubernetes (K3s in prod) · Terraform · AWS (Lambda, SQS, SNS, SES, S3, IAM, VPC) · Cloudflare (Tunnel, R2, Zero Trust) · PostgreSQL + PostGIS · Redis · Docker · GitHub Actions · Prometheus/Grafana/Alertmanager · Sentry.

**Production ownership:** Metropolitana Linea C di Roma (400+ video endpoint 24/7), Etihad Airways (network diagnostics), enterprise debt-collection platform (AWS serverless, 100+ REST endpoint).

---

## Featured projects

| Project | One-liner | Stack |
|---|---|---|
| 🔎 **[JobSearch](https://github.com/MK023/JobSearch)** | AI-powered job search platform with CV analysis, gap analysis, cover letters. 1078 test, 11-stage CI, SonarCloud Quality Gate PASS, MCP server for Claude Desktop integration. | FastAPI · Anthropic Claude · PostgreSQL · Render · Sentry |
| 📚 **[MD Vault](https://github.com/MK023/md_vault)** | Self-hosted knowledge base on **K3s in production** with **Terraform** IaC and **Cloudflare Zero Trust** tunnel. | K3s · Terraform · GCP · FastAPI · SQLite FTS5 |
| 🅿️ **[TorinoParking](https://github.com/MK023/TorinoParking)** | Real-time parking availability API with HMAC-SHA256 key hashing, multi-tier rate limiting, threat model docs. | FastAPI · PostgreSQL/PostGIS · Redis · testcontainers |
| 🐇 **[RabbitWatch](https://github.com/MK023/RabbitWatch)** | Self-healing monitoring control-plane: FastAPI health checks + RabbitMQ event bus + automated recovery. | FastAPI · Prometheus · Grafana · Alertmanager · RabbitMQ · MongoDB |
| 🧠 **[HappyKube](https://github.com/MK023/HappyKube)** | AI emotion analysis Telegram bot in production for 2+ years. Clean Architecture, Fernet PII encryption. | Flask · Groq LLaMA · PostgreSQL · Redis · Docker |

---

## Live in production

These are running and reachable right now — same engineering discipline I'd apply at scale, on infrastructure I pay for and operate myself:

- 🌐 **[jobsearches.cc](https://jobsearches.cc)** — JobSearch web UI · [API health](https://api.jobsearches.cc/health)
- 🌐 **[mdvault.site](https://mdvault.site)** — MD Vault on K3s + Cloudflare Tunnel (private knowledge base, auth-walled)
- 🤖 **[@happykube_bot](https://t.me/happykube_bot)** — HappyKube emotion analysis bot on Telegram · [API health](https://happykube.fly.dev/healthz)

Total monthly operating cost across all three: under €20. Cost-engineering as a deliberate design constraint, not an accident.

---

## Currently learning

Preparing **CKA (Certified Kubernetes Administrator)** for Q3 2026 to certify the production K8s experience already deployed in MD Vault. Roadmap continues with **CKS (Kubernetes Security Specialist)** in 2027 to anchor the security side of the Cloud Platform & Security positioning. The path is K8s → in-flight AWS/Azure certs during the next role, not the other way around.

---

## Security &amp; DevSecOps practices I apply

- **Hardening:** OWASP Top 10 audits with documented fixes · brute-force lockout · CSRF Origin validation · session hardening (SameSite strict) · CSP/HSTS · rate limiting (sliding window, multi-tier)
- **Crypto:** AES-256 / Fernet for PII at rest · HMAC-SHA256 for API key hashing · bcrypt with timing-safe comparison · mTLS-ready designs
- **CI/CD gates:** Bandit (SAST) · pip-audit / npm audit (SCA) · CodeQL (deep SAST) · Gitleaks (secret scanning) · SonarCloud (quality gate on new code)
- **Zero-trust:** Cloudflare Tunnel as default ingress · Kubernetes RBAC + PodSecurity · presigned URLs for isolated uploads · least-privilege IAM
- **Reliability:** graceful shutdown on SIGTERM · restart with progressive backoff · credential masking in log rotation · backup CronJobs to R2

---

## Certifications

![AWS Cloud Practitioner](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Cisco Cybersecurity](https://img.shields.io/badge/Cisco-IT%20Specialist%20Cybersecurity-1BA0D7?style=flat&logo=cisco&logoColor=white)
![LPI Linux Essential](https://img.shields.io/badge/LPI-Linux%20Essential-FCC624?style=flat&logo=linux&logoColor=black)
![GitHub Foundations](https://img.shields.io/badge/GitHub-Foundations-181717?style=flat&logo=github&logoColor=white)
![Python PCEP](https://img.shields.io/badge/Python-PCEP%2030--02-3776AB?style=flat&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Python%20Developer-47A248?style=flat&logo=mongodb&logoColor=white)

Verified on [Credly](https://credly.com/users/marco-bellingeri).

---

## Let's talk

Open to **remote / hybrid** roles in **Italy** (Cloud Engineer · DevSecOps · Platform Engineer · Cloud Security). Available for freelance engagements with structured contracts.

- 📨 **Email:** marco.bellingeri@gmail.com
- 💼 **LinkedIn:** [marco-bellingeri](https://www.linkedin.com/in/marco-bellingeri)
- 🏷️ **Badges:** [credly.com/users/marco-bellingeri](https://credly.com/users/marco-bellingeri)
