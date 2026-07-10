<h1 align="center">Ciao, I'm Marco 👋</h1>

<p align="center">
  <strong>Cloud Platform &amp; Security Engineer</strong><br/>
  I make cloud infrastructure boring. On purpose.
</p>

<p align="center">
  <a href="https://marcobellingeri.dev">
    <img alt="Website" src="https://img.shields.io/badge/marcobellingeri.dev-live-FF5A1F?style=flat&logo=astro&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/marco-bellingeri">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-marco--bellingeri-0A66C2?style=flat&logo=linkedin&logoColor=white">
  </a>
  <a href="https://credly.com/users/marco-bellingeri">
    <img alt="Credly" src="https://img.shields.io/badge/Credly-verified%20badges-FF6B00?style=flat&logo=credly&logoColor=white">
  </a>
  <a href="mailto:mkdevpy@proton.me">
    <img alt="Email" src="https://img.shields.io/badge/Email-mkdevpy@proton.me-6D4AFF?style=flat&logo=protonmail&logoColor=white">
  </a>
  <img alt="Open to work" src="https://img.shields.io/badge/Open%20to%20work-remote%2Fhybrid%20Italy-brightgreen?style=flat">
</p>

---

### `$ whoami`

I build and run cloud-native platforms with **security-by-design** — and I genuinely enjoy the boring production problems (graceful shutdowns, credential rotation, real backups, postmortems) more than the shiny demos. Shiny demos don't page you at 3am. Boring infrastructure doesn't either.

- 🔭 Just shipped: **[marcobellingeri.dev](https://marcobellingeri.dev)** — a site that *audits itself*. The Security section reads its own response headers live, and the A+ grade in the hero isn't a claim: it links to a [Mozilla Observatory scan](https://developer.mozilla.org/en-US/observatory/analyze?host=marcobellingeri.dev) you can re-run right now.
- 🖥️ There's a hidden CRT terminal on it. `⌘K` is one way in. There's another.
- 📚 Preparing **CKA** (Q3 2026), then CKS — certifying the Kubernetes I already run in production, not the other way around.
- 🏗️ Past production ownership: Rome Metro Line C (400+ video endpoints, 24/7), Etihad Airways network diagnostics, enterprise debt-collection platform on AWS serverless.

### 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black" alt="Supabase" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=vscodium&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion" />
</p>

### 📦 Things I've built

| | Project | The point | Alive? |
|---|---|---|---|
| 🌐 | **[marcobellingeri.dev](https://github.com/MK023/marcobellingeri.dev)** | My site audits itself: CSP by hash (no `unsafe-inline`), live security headers, deploy gated by tests that run on the *built* output. Astro 7 · Cloudflare Workers · Supabase RAG. | **[Live](https://marcobellingeri.dev)** |
| 🔎 | **[JobSearch](https://github.com/MK023/JobSearch)** | AI job-search platform: CV analysis, gap analysis, cover letters. 1078 tests, 11-stage CI, SonarCloud gate, MCP server for Claude. FastAPI · Claude API · PostgreSQL. | **[Live](https://jobsearches.cc)** |
| 🅿️ | **[TorinoParking](https://github.com/MK023/TorinoParking)** | Turin parking availability, hardened like it matters: HMAC-SHA256 API keys, multi-tier rate limiting, a written threat model. Native iOS app on the way. FastAPI · PostGIS · Redis. | iOS app in progress |
| 🐇 | **[RabbitWatch](https://github.com/MK023/RabbitWatch)** | Self-healing monitoring control plane: health checks, RabbitMQ event bus, automated recovery. Prometheus · Grafana · Alertmanager · MongoDB. | — |
| 🧠 | **[HappyKube](https://github.com/MK023/HappyKube)** | Emotion-analysis Telegram bot with **2+ years of production runtime**. Clean Architecture, Fernet PII encryption. Flask · Groq LLaMA · Redis. | — |
| 🪟 | **[Vetreria Monferrina](https://github.com/MK023/vetreriamonferrina.com)** | Real client work: a local glazier's website. Astro · Sanity CMS · Lighthouse 100s, WCAG 2.1 AA. | **[Live](https://vetreriamonferrina.com)** |

### 📜 Certifications

![AWS Cloud Practitioner](https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Cisco Cybersecurity](https://img.shields.io/badge/Cisco-IT%20Specialist%20Cybersecurity-1BA0D7?style=flat&logo=cisco&logoColor=white)
![LPI Linux Essential](https://img.shields.io/badge/LPI-Linux%20Essential-FCC624?style=flat&logo=linux&logoColor=black)
![GitHub Foundations](https://img.shields.io/badge/GitHub-Foundations-181717?style=flat&logo=github&logoColor=white)
![Python PCEP](https://img.shields.io/badge/Python-PCEP%2030--02-3776AB?style=flat&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Python%20Developer-47A248?style=flat&logo=mongodb&logoColor=white)

All verifiable on [Credly](https://credly.com/users/marco-bellingeri) — badges you can click are worth more than badges you can claim.

---

<p align="center">
  <code>guest@bellingeri:~$ exit</code><br/>
  <sub>© Marco Bellingeri — tutti i diritti, nessun bug in produzione (si spera).</sub>
</p>
