<div align="center">

<a href="https://ghostmastersc.github.io/GhostMasterSc/">
  <img src="assets/preview.png" alt="Tolunay Alankaya — ML/AI engineer. Click to open the live portfolio." width="100%">
</a>

### [🌐&nbsp; Open the live, interactive portfolio &nbsp;→](https://ghostmastersc.github.io/GhostMasterSc/)

<sub>The page above is a preview — click it for the full site (light/dark, live links).</sub>

<br/>
<br/>

# Tolunay Alankaya

### Machine Learning / AI Engineer · Data Scientist

**Building agentic AI systems in production — and the infrastructure they run on.**

I turn research-grade ML and LLM agents into reliable, deployed software: evaluation
pipelines, production APIs, and full-stack apps. Off the clock, I design and operate a
multi-node homelab from bare metal up — Linux, containers, and hypervisors as code.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tolunay--alankaya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tolunay-alankaya)
[![Email](https://img.shields.io/badge/Email-tolunayalankaya@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tolunayalankaya@gmail.com)
![Location](https://img.shields.io/badge/Based_in-Netherlands-FF6C37?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 🚀 Currently

**Data Scientist @ Elsevier** — turning agentic LLM workflows into a dependable product surface.

- 🧪 **Design, build and maintain evaluation pipelines** for agentic flows — the harness that
  decides whether an agent is actually good enough to ship.
- 🧩 **Extend a mature, production API service** with new agentic tasks and capabilities.
- ☁️ Day-to-day on **AWS** and **Databricks**.

> The through-line of my work: *agents are only as trustworthy as the pipelines that evaluate them
> and the systems that serve them.* I care as much about the deployment, tests and observability
> as about the model.

---

## 🛠️ Featured Work

I build end-to-end. These are self-designed, self-hosted systems — architecture, code, deploy and ops all mine.

### 🏀 [Kukulitis](https://github.com/GhostMasterSc/Kukulitis) — full-stack fantasy-basketball analytics platform
A production-grade web app for ESPN head-to-head category leagues.

- **Backend:** FastAPI · SQLAlchemy 2 · Alembic migrations · APScheduler · NumPy/SciPy
- **Frontend:** React 19 · Vite · TypeScript · Tailwind v4 · TanStack Query
- **Engineering depth:** a cached, retrying ESPN client; a **research-backed draft algorithm**
  (H-scores) benchmarked to win the league ~1.9× as often as a G-score drafter; an *n*-for-*m*
  trade analyzer over real NBA schedules; a companion **browser extension** for live drafts.
- **Security:** argon2 hashing, httpOnly + SameSite sessions, CSRF guard, login rate-limiting,
  SSRF-protected webhooks, per-user data scoping, Fernet-encrypted credentials at rest.
- **Ops:** single-process prod deploy, Dockerized, private HTTPS via Tailscale, CI checks in one script.

`FastAPI` · `React` · `TypeScript` · `SQLAlchemy` · `Docker` · `Tailscale`

### 🐦 [Perry](https://github.com/GhostMasterSc/Perry) — cross-platform, privacy-first "save anything" app
A digital source organizer that reads what you save and files it for you — with the AI running on *your* hardware.

- **Monorepo:** `apps/mobile` (Expo / React Native, also web) · `apps/server` · `packages/core`
  (shared filing rules + offline classifier + app↔server contract) · `tools/shots` (e2e).
- **Self-hosted AI:** the optional helper runs **Ollama on your own GPU box** — captions never
  leave your network. Docker Compose deploy with `setup.sh` / `doctor.sh`, Tailscale Funnel access.
- **Shipped:** milestones M1–M9 complete, with a written security review and full verify/e2e suite.

`React Native` · `Expo` · `TypeScript` · `Ollama` · `Docker` · `monorepo`

### 📦 [machine-learning-for-inventory](https://github.com/GhostMasterSc/machine-learning-for-inventory) — ML engineering, done properly
Deep-learning / reinforcement-learning for inventory control, packaged like production software:
**MLflow** experiment tracking, a `Dockerfile.prod`, a test suite, and reproducible environments.

`PyTorch` · `MLflow` · `Docker` · `pytest`

---

## 🖥️ Homelab & Self-Hosted Infrastructure

> The part I'm proudest of. A real, always-on homelab that doubles as my DevOps proving ground —
> everything is **config-as-code**, versioned in git, and rebuildable from scratch.
> This is where I get hands-on with **Linux, Docker, and hypervisors** every week.

**[`jarvis`](https://github.com/GhostMasterSc/jarvis)** — the production server, as code.
17 self-hosted services in **Docker Compose** (Jellyfin, the *arr* stack, Nextcloud, Home Assistant,
Ghostfolio, Vikunja, Stirling-PDF and more), fronted by a homepage, driven by **systemd** units,
kept healthy by custom **Bash** watchdogs (VPN-bound qBittorrent, Home-Assistant config sync).
Secrets in gitignored `.env` files with committed `.env.example` templates; recovery runbooks in `docs/`.

**[`homelab-lab`](https://github.com/GhostMasterSc/homelab-lab)** — the lab and the discipline.
A project-based DevOps curriculum with a running **learning log** — every project ends with
something still running, gets deliberately broken, and is documented like an incident write-up.

<div align="center">

| Machine | Role | Stack |
|---|---|---|
| **Jarvis** (ASUS ROG G14) | Always-on server | Ubuntu Server · Docker · systemd · Proxmox (planned) |
| **Mark-I** (Beelink 5850U) | Virtualization lab | **KVM / QEMU / libvirt** · cloud-init · k3s |
| **DXP4800 Pro** | NAS / storage | NFS · backups (restic) |

</div>

**Hands-on across the stack:** Linux internals (systemd, permissions, signals, boot analysis) ·
**hypervisors** — KVM/QEMU/libvirt VMs stamped out with cloud-init, headed toward Proxmox ·
**containers** — multi-stage builds, bridge networking, reverse proxies · **Kubernetes** (k3s,
Helm, GitOps with Argo CD) · **networking** — Tailscale mesh + MagicDNS, DNS, firewalls, NAT ·
**observability** — Prometheus + Grafana + Loki · **IaC** — Ansible & Terraform · tested,
encrypted backups and written disaster-recovery drills.

`Linux` · `Docker` · `KVM/QEMU` · `libvirt` · `systemd` · `Bash` · `Tailscale` · `k3s` · `Ansible` · `Terraform`

---

## 🧰 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Backend / Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

**Cloud / Data / MLOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**DevOps / Infrastructure**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![KVM](https://img.shields.io/badge/KVM%2FQEMU-FF6600?style=flat-square&logo=qemu&logoColor=white)
![Kubernetes](https://img.shields.io/badge/k3s%2FKubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 💼 Experience

| When | Role | Where |
|---|---|---|
| **Present** | **Data Scientist** — evaluation pipelines for agentic flows; production agentic API on AWS + Databricks | **Elsevier** |
| 2025 | ML / AI Engineer — LangChain/LangGraph agentic flows, Databricks ETL, Streamlit apps | WeFabricate, Eindhoven |
| 2022–2025 | PhD Candidate & ML Engineer — Transformer/CNN/LSTM sales forecasting (+11% accuracy), deep-RL inventory control (+15% efficiency), an LLM+RAG OR assistant; containerized CI/CD | DAF Trucks × TU/e, Eindhoven |
| 2022–2025 | Data Scientist & Researcher — explainable AI, AI workshops | AI Planner of the Future, Eindhoven |
| 2020–2022 | Data Scientist & Researcher — hierarchical Bayesian models, survival analysis | Bilkent University, Ankara |
| 2018–2020 | Data Science Internships — routing/scheduling optimization (MIP, metaheuristics), analytics | HAVELSAN · MITAS · Microsoft |

## 🎓 Education

- **PhD**, Machine Learning in Operations Research & Marketing — *Eindhoven University of Technology (TU/e)*
- **MSc**, Data Science & AI in Operations Research — *Bilkent University* · **3.96 / 4.00 GPA**
- **BSc**, Operations Research — *Bilkent University*

---

<div align="center">

### Let's build something reliable.

I like problems that sit at the seam of **ML research** and **real production systems** —
where the model has to actually run, be evaluated, and stay up.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tolunay-alankaya)
[![Email](https://img.shields.io/badge/Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tolunayalankaya@gmail.com)

</div>
