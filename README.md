### Hi there 👋

I'm **Senri** — full-stack developer at [Protonoro](https://protonoro.com/), focused on **web platforms**, **real-time systems**, and **observability**.

I design and ship production tooling: from parsing pipelines and SIEM backends to React portals and Docker/Kubernetes deployments. Currently co-building products at [@PROTONORO-LTD](https://github.com/PROTONORO-LTD).

<p>
  <a href="https://protonoro.com/"><img alt="Website" src="https://img.shields.io/badge/Website-protonoro.com-7c3aed?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="mailto:aid128638caides@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-me-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/PROTONORO-LTD"><img alt="Org" src="https://img.shields.io/badge/Org-PROTONORO--LTD-0969da?style=flat-square&logo=github&logoColor=white"></a>
</p>

---

### What I build

#### [thread-sync](https://github.com/Davitushka/thread-sync) — production-grade SIEM

Open-source security analytics platform for microservice environments.

- **Rust parser** — HTTP ingest, Kafka pipeline, PII redaction, normalization (&lt;5ms p99 parse)
- **React SOC portal** — analyst suite, real-time updates, case management UI
- **Data plane** — ClickHouse storage, Redis state, Sigma-based detection engine
- **Observability** — Grafana dashboards, Prometheus metrics, Vector aggregation
- **Deploy** — Docker Compose for local/prod-like stacks, Kubernetes manifests
- **Scale targets** — 10k → 50k EPS, critical alerts ≤ 30s from event

#### Protonoro Timer — full-stack productivity app

- Full-stack timer product at **@PROTONORO-LTD** (frontend + backend)
- Built for daily focus workflows and team productivity
- Commercial codebase — showcased here, not open-sourced

---

### Architecture (thread-sync)

```mermaid
flowchart LR
  apps[Apps_and_agents] --> vector[Vector]
  vector --> kafka[Kafka_Redpanda]
  kafka --> parser[Rust_parser]
  parser --> clickhouse[ClickHouse]
  parser --> detection[Detection_engine]
  clickhouse --> portal[SIEM_portal]
  clickhouse --> grafana[Grafana]
  detection --> portal
```

**Components:** `rust-parser` · `siem-portal` · `detection-engine-rs` · `case-management-rs` · `vector` · `deploy/docker` · `deploy/k8s`

---

### Tech stack

**Languages**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_9-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)

**Data and messaging**

![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Ops and observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)

---

<details>
<summary><b>Stats and activity</b></summary>
<br>

<p align="center">
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Davitushka&theme=tokyonight&hide_border=true" alt="streak" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Davitushka&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="langs" />
</p>

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/pin/?username=Davitushka&repo=thread-sync&theme=tokyonight&hide_border=true" alt="thread-sync" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Davitushka&theme=tokyo-night&hide_border=true" alt="graph" />
</p>

</details>

---

**Open to collaboration** — reach out via [protonoro.com](https://protonoro.com/) or [email](mailto:aid128638caides@gmail.com).
