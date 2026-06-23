<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=7c3aed&height=220&section=header&text=Hi%2C%20I'm%20Senri&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-stack%20developer%20%40%20Protonoro&descSize=18&descAlignY=58&descAlign=55" width="100%" alt="Header banner" />

<br>

<img src="https://komarev.com/ghpvc/?username=Davitushka&label=Profile%20views&color=7c3aed&style=for-the-badge" alt="Profile views" />
<img src="https://img.shields.io/github/commit-activity/m/Davitushka?color=7c3aed&label=Commits%20this%20month&style=for-the-badge&logo=git" alt="Commits this month" />
<img src="https://img.shields.io/badge/Public%20repos-2-7c3aed?style=for-the-badge&logo=github" alt="Public repos" />

</div>

---

### About me

👋 I'm **Senri** — full-stack developer at **[Protonoro](https://protonoro.com/)** (he/him).

🔭 Building **web platforms**, **real-time systems**, and **observability** tooling.

🚀 Focus: **Rust** parsers · **React** portals · **.NET** services · **ClickHouse** / **Kafka** data planes.

🏢 Co-building [@PROTONORO-LTD](https://github.com/PROTONORO-LTD) — [Protonoro Timer](https://github.com/PROTONORO-LTD) & **[thread-sync](https://github.com/Davitushka/thread-sync)** (open-source SIEM).

📫 **protonoro.com** · **aid128638caides@gmail.com**

---

### Technology stack

<div align="center">

<img src="https://skillicons.dev/icons?i=rust,typescript,react,dotnet,python,docker,kubernetes,postgres,redis,kafka,grafana,prometheus,bash,powershell,vite,tauri&perline=8" alt="Tech stack icons" />

</div>

<br>

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Davitushka&show_icons=true&theme=tokyonight&hide_border=false&border_color=7c3aed&icon_color=7c3aed&title_color=7c3aed&text_color=c9d1d9&bg_color=0d1117" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Davitushka&layout=compact&theme=tokyonight&hide_border=false&border_color=7c3aed&title_color=7c3aed&text_color=c9d1d9&bg_color=0d1117&langs_count=8" alt="Top languages" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Davitushka&theme=tokyonight&hide_border=false&border=7c3aed&ring=7c3aed&fire=7c3aed&currStreakLabel=7c3aed&sideLabels=7c3aed&dates=7c3aed&sideNums=ffffff" alt="GitHub streak" />

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Davitushka&theme=tokyo-night&hide_border=true&color=7c3aed&line=7c3aed&point=ffffff&area=true" alt="Contribution graph" />

</div>

---

<details>
<summary><b>Projects and architecture</b></summary>

<br>

#### [thread-sync](https://github.com/Davitushka/thread-sync)

Production-grade SIEM — Rust parser, React SOC portal, ClickHouse, Kafka, Grafana, Docker/K8s.

- 10k → 50k EPS · alerts ≤ 30s · parse &lt;5ms p99

#### Protonoro Timer

Full-stack productivity app @ **PROTONORO-LTD** (commercial, not open-sourced).

<br>

```mermaid
flowchart LR
  apps[Apps] --> vector[Vector]
  vector --> kafka[Kafka]
  kafka --> parser[Rust_parser]
  parser --> clickhouse[ClickHouse]
  parser --> detection[Detection]
  clickhouse --> portal[Portal]
  clickhouse --> grafana[Grafana]
```

</details>

---

<div align="center">

**Thanks for stopping by — open to collaboration**

<br>

<a href="https://protonoro.com/"><img src="https://img.shields.io/badge/Website-protonoro.com-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
<a href="mailto:aid128638caides@gmail.com"><img src="https://img.shields.io/badge/Email-me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/PROTONORO-LTD"><img src="https://img.shields.io/badge/Org-PROTONORO--LTD-0969da?style=for-the-badge&logo=github&logoColor=white" alt="Org"></a>

</div>
