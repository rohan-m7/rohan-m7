<!-- ==========================================================================
  SETUP — delete this comment block once done
  1. Create a new PUBLIC repo named EXACTLY your GitHub username
     (github.com/<username>/<username>). GitHub renders its README.md
     at the top of your profile page.
  2. Replace every {{PLACEHOLDER}} below.
  3. Pin the triage-agent repo (Profile → "Customize your pins").
     One real repo pinned beats six tutorial repos. Unpin everything else.
========================================================================== -->

<div align="center">

# Hey, I'm Rohan 👋

### Platform engineer building AI agents for infrastructure

**4 years running production Kubernetes, storage, and cross-cloud DNS at NetApp & Infoblox —<br/>now building the agents that do that job.**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]({{LINKEDIN_URL}})
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rohan.m.rohan7@gmail.com)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)]({{X_URL}})

🟢 **Open to founding / early engineer roles — AI agents · platform · infra** &nbsp;·&nbsp; Bangalore / Remote

</div>

---

## 🔨 Building now

### [k8s-triage-agent](https://github.com/{{GITHUB_USERNAME}}/{{TRIAGE_REPO_NAME}})

**An LLM agent that does first-pass Kubernetes incident triage the way an SRE actually would.**

Given a firing alert, the agent investigates the cluster through read-only tools (kubectl, log retrieval) in a ReAct loop, checks its hypothesis against a runbook corpus via RAG, and produces a structured root-cause report — with a human-in-the-loop gate before anything is acted on. MongoDB gives it memory across incidents, so it recognizes repeat offenders.

The part I care most about is the **eval harness**: 15+ scripted failure scenarios (CrashLoopBackOff, OOMKills, DNS breakage, PVC binding issues…) scored on root-cause accuracy and cost-per-triage. An agent you can't measure is a demo, not a tool.

`Python` · `LLM tool use / ReAct` · `RAG` · `MongoDB` · `Kubernetes` · `evals`

> **Why this project:** I spent years doing exactly this triage by hand on production NAS-on-Kubernetes systems at NetApp. This automates the first twenty minutes of every incident — the part everyone hates.

### 🔭 Up next — TrendScout

Daily outlier detection across ~40 YouTube channels: flags videos breaking out relative to each channel's baseline view-velocity. Shares ~70% of its architecture with the triage agent — same agent loop, different tools.

<!-- ==========================================================================
## 🌱 Open source

Uncomment this section the day your first PR is merged — merged upstream PRs
are the single strongest signal on this entire page. Format:

- [signoz#1234](PR_LINK) — one-line description of the fix (+59/−8, merged)
========================================================================== -->

## 💼 Where I've been

**Software Engineer 2 — NetApp** · Bangalore · *Dec 2024 – May 2026*
Production escalation triage and root-cause analysis on Kubernetes/NAS storage infrastructure (GCP). Delivered SLA-driven hotfixes on live customer systems. Built an internal LLM-powered log analyser (hackathon project → adopted by the team) that meaningfully cut initial debugging time. <!-- add a defensible number here if you have one -->

**Software Engineer — Infoblox** · Bangalore · *Jan 2022 – Dec 2024*
Go/gRPC microservices for cross-cloud DNS (AWS Route 53 + Azure DNS) on the Universal DDI platform. Built a cloud write-proxy service for resource lifecycle operations; replaced a licensed third-party tool with a Go service on Lambda + RDS, saving ~$25K/yr.

## 🧰 Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Infrastructure**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

**Data & APIs**

![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**AI** — LLM agents & tool use · RAG · eval design

## 📜 Certifications

- Certified Kubernetes Application Developer (CKAD) <!-- confirm this is the exact cert name on your certificate -->
- Deep Learning Specialization — DeepLearning.AI

<!-- ==========================================================================
## 📺 Elsewhere

I run **CoreShift** — a documentary-style channel on AI economics: how the
money behind AI actually flows. Latest: *The AI Bill Comes Due*.

→ Uncomment + link ONLY once the first video is live. A linked channel with
  zero uploads reads worse than no mention at all.
========================================================================== -->

<!-- ==========================================================================
GITHUB STATS — enable only after you have ~3 active public repos.
On a sparse account these cards hurt more than they help.

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username={{GITHUB_USERNAME}}&show_icons=true&rank_icon=github&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username={{GITHUB_USERNAME}}&layout=compact&hide_border=true" />
</div>
========================================================================== -->

---

<div align="center">
<sub>Fastest way to reach me: <a href="mailto:rohan.m.rohan7@gmail.com">rohan.m.rohan7@gmail.com</a> — I reply fast to anything with “agent” or “Kubernetes” in it.</sub>
</div>
