<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=7c3aed&height=220&section=header&text=Hi%2C%20I'm%20Senri&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-stack%20developer%20%40%20Protonoro&descSize=18&descAlignY=58&descAlign=55" width="100%" alt="Header banner" />

<a href="https://davitushka.github.io/"><img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=A855F7&center=true&vCenter=true&width=520&lines=Rust+parsers+%26+real-time+pipelines;React+SOC+portals;.NET+services+%40+Protonoro;ClickHouse+%C2%B7+Kafka+%C2%B7+Grafana" alt="What I build" /></a>

<br>

<a href="https://davitushka.github.io/"><img src="https://img.shields.io/badge/%F0%9F%9A%80%20Live%20Portfolio-davitushka.github.io-7c3aed?style=for-the-badge&labelColor=000000" alt="Live Portfolio" /></a>
<a href="https://davitushka.github.io/#playground"><img src="https://img.shields.io/badge/Live%20log%20parser-demo-22d3ee?style=for-the-badge&labelColor=000000" alt="Log parser demo" /></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Davitushka&label=Profile%20views&color=7c3aed&style=for-the-badge" alt="Profile views" />
<img src="https://img.shields.io/github/commit-activity/m/Davitushka?color=7c3aed&label=Commits%20this%20month&style=for-the-badge&logo=git" alt="Commits this month" />
<img src="https://img.shields.io/badge/Public%20repos-2-7c3aed?style=for-the-badge&logo=github" alt="Public repos" />

</div>

---

### About me

👋 I'm **Senri** — full-stack developer at **[Protonoro](https://protonoro.com/)** (he/him).

🔭 I build **web platforms**, **real-time systems**, and **observability** tooling.

🚀 Focus: **Rust** parsers · **React** portals · **.NET** services · **ClickHouse** / **Kafka** data planes.

🔨 **[thread-sync](https://github.com/Davitushka/thread-sync)** — my open-source SIEM (code on GitHub, portfolio modal has **tabbed code snippets** from the repo).

⏱ **[Protonoro Timer](https://protonoro.com/)** — productivity app I build (commercial, source is private).

🧪 **[Live portfolio](https://davitushka.github.io/)** — RU/EN site with **interactive SIEM pipeline map** and live log parser demo.

📫 **protonoro.com** · **aid128638caides@gmail.com**

<details>
<summary><b>🇷🇺 Обо мне (RU)</b></summary>

<br>

👋 Я **Senri** — full-stack разработчик в **[Protonoro](https://protonoro.com/)**.

🔭 Делаю веб-платформы, real-time системы и observability-инструменты.

🚀 Стек: **Rust** · **React** · **.NET** · **ClickHouse** / **Kafka**.

🔨 **[thread-sync](https://github.com/Davitushka/thread-sync)** — моя open-source SIEM, в модалке на портфолио — **вкладки с кодом** из репозитория.

⏱ **[Protonoro Timer](https://protonoro.com/)** — таймер продуктивности (коммерческий, исходники закрыты).

🧪 **[Портфолио](https://davitushka.github.io/)** — RU/EN, **интерактивная карта SIEM-пайплайна** и live-демо парсера логов.

</details>

---

> Sections below work like tabs — click to expand. Full experience: **[live portfolio](https://davitushka.github.io/)** (RU/EN switcher on site).

<details open>
<summary><b>🛠 Technology stack</b></summary>

<br>

<div align="center">

<img src="https://skillicons.dev/icons?i=rust,typescript,react,dotnet,python,docker,kubernetes,postgres,redis,kafka,grafana,prometheus,bash,powershell,vite,tauri&perline=8" alt="Tech stack icons" />

</div>

</details>

<details>
<summary><b>🚀 Projects and architecture</b></summary>

<br>

#### [thread-sync](https://github.com/Davitushka/thread-sync)

SIEM I built from scratch — Rust parser, React SOC portal, ClickHouse, Kafka, Grafana, Docker/K8s.

- 10k → 50k EPS · alerts ≤ 30s · parse &lt;5ms p99
- Portfolio: click card → **tabbed code preview** (`detect_format`, `parse`, `handle_parse`)
- About tab: **interactive pipeline map** — click nodes to see what each layer does

#### Protonoro Timer

Full-stack productivity app at **[Protonoro](https://protonoro.com/)** — commercial, source is private.

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

<details>
<summary><b>📊 Stats and activity</b></summary>

<br>

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Davitushka&show_icons=true&theme=tokyonight&hide_border=false&border_color=7c3aed&icon_color=7c3aed&title_color=7c3aed&text_color=c9d1d9&bg_color=0d1117" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Davitushka&layout=compact&theme=tokyonight&hide_border=false&border_color=7c3aed&title_color=7c3aed&text_color=c9d1d9&bg_color=0d1117&langs_count=8" alt="Top languages" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Davitushka&theme=tokyonight&hide_border=false&border=7c3aed&ring=7c3aed&fire=7c3aed&currStreakLabel=7c3aed&sideLabels=7c3aed&dates=7c3aed&sideNums=ffffff" alt="GitHub streak" />

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Davitushka&theme=tokyo-night&hide_border=true&color=7c3aed&line=7c3aed&point=ffffff&area=true" alt="Contribution graph" />

</div>

</details>

---

<div align="center">

**Thanks for stopping by — open to collaboration**

<br>

<a href="https://davitushka.github.io/"><img src="https://img.shields.io/badge/Portfolio-davitushka.github.io-7c3aed?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=000000" alt="Portfolio"></a>
<a href="https://davitushka.github.io/#playground"><img src="https://img.shields.io/badge/Log%20parser-demo-22d3ee?style=for-the-badge&labelColor=000000" alt="Demo"></a>
<a href="https://protonoro.com/"><img src="https://img.shields.io/badge/Website-protonoro.com-7c3aed?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=000000" alt="Website"></a>
<a href="mailto:aid128638caides@gmail.com"><img src="https://img.shields.io/badge/Email-me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>
