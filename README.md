<h1 align="center">Hi there 👋, I'm Oleksii Odarchuk</h1>
<h3 align="center">aka iShawyha | Backend Developer (Go) from Ukraine 🇺🇦</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?color=00ffcc&center=true&vCenter=true&width=580&height=55&lines=Backend+Developer+(Go);Creator+of+rombik+and+the+Piton+language;Compilers,+tree-sitter,+WebAssembly;AI+orchestration:+MCP,+RAG,+pgvector;1st+place+at+BEST+Hackathon+2026+%F0%9F%8F%86;I+use+Arch+btw+%F0%9F%90%A7;Ukrainian+folk+dancer+%F0%9F%92%83" />
</p>

<p align="center">
  <a href="https://ishawyha.dev"><img src="https://img.shields.io/badge/Portfolio-ishawyha.dev-00ffcc?style=for-the-badge&logo=firefoxbrowser&logoColor=white" /></a>
  <a href="https://rombik.app"><img src="https://img.shields.io/badge/rombik.app-be123c?style=for-the-badge&logo=diagramsdotnet&logoColor=white" /></a>
</p>

---

### 👨‍💻 About Me

- <img src="https://img.shields.io/endpoint?url=https://wakapi.dev/api/compat/shields/v1/iShawyha/interval:today&label=Coding%20Activity%20-%20Today&color=1E90FF">
- <img src="https://img.shields.io/endpoint?url=https://wakapi.dev/api/compat/shields/v1/iShawyha/interval:30_days&label=Coding%20Activity%20-%20Last%2030%20Days&color=8A2BE2">
- 💼 Backend Developer (Go) at **SkyService** — Go microservices, an AI orchestrator and a RAG platform in production
- 🧑‍🎓 Student at [Taras Shevchenko National University of Kyiv](https://knu.ua/), Faculty of Information Technology
- 🔷 Creator of [**rombik**](https://rombik.app) — code in 10 languages → a DSTU 19.701-90 flowchart
- 🐍 Author of [**Piton**](https://piton.ishawyha.dev) — a Ukrainian programming language with its own interpreter
- 🏆 1st place at BEST Hackathon 2026 · 3rd at Mate Hackathon 2026 · personally invited to DOU Day 2026
- 🐧 Daily Linux user (`I use Arch btw`)
- 💃 Ukrainian folk dancer, and I write for the theatre

---

### 🚀 What I'm Building

Feed [**rombik**](https://rombik.app) a function in any of 10 languages:

```go
func Fib(n int) int {
	a, b := 0, 1
	for i := 0; i < n; i++ {
		a, b = b, a+b
	}
	return a
}
```

…and get back a flowchart or a structogram, drawn to the standard — the images below came straight out of `rombik render`:

<p align="center">
  <img src="assets/demo-flowchart.svg" height="340" alt="Flowchart generated from the Go function above, per DSTU 19.701-90" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/demo-structogram.svg" height="300" alt="Nassi–Shneiderman structogram generated from the same function" />
</p>
<p align="center"><sub>flowchart · ДСТУ 19.701-90&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;structogram · Nassi–Shneiderman</sub></p>

| Project | What it is | Stack |
|---|---|---|
| 🔷 [**rombik**](https://rombik.app)<br><img src="https://img.shields.io/github/stars/OlexiyOdarchuk/rombik?style=flat-square&color=00ffcc&labelColor=16161E&logo=github" /> | Commercial micro-SaaS. A compiler pipeline (parser → IR → layout → render) on tree-sitter turns code in **10 languages** into flowcharts and Nassi–Shneiderman structograms, pixel-for-pixel to DSTU 19.701-90 / ISO 5807. Web editor, 8 export formats, public API, CLI and an MCP server. | `Go` `Gin` `tree-sitter` `PostgreSQL` |
| 🐍 [**Piton**](https://github.com/OlexiyOdarchuk/piton)<br><img src="https://img.shields.io/github/stars/OlexiyOdarchuk/piton?style=flat-square&color=00ffcc&labelColor=16161E&logo=github" /> <img src="https://img.shields.io/github/v/release/OlexiyOdarchuk/piton?style=flat-square&color=8A2BE2&labelColor=16161E" /> | My own programming language — Ukrainian transliterated syntax, written from scratch in Go without yacc/bison: recursive-descent parser, tree-walking evaluator, Turing-complete. Compiled to **WebAssembly via TinyGo** (~220 KB) — [try it in the browser](https://piton.ishawyha.dev). | `Go` `TinyGo` `WebAssembly` `D2` |
| 🏦 [**go-monobank-sdk**](https://github.com/OlexiyOdarchuk/go-monobank-sdk)<br><img src="https://img.shields.io/github/stars/OlexiyOdarchuk/go-monobank-sdk?style=flat-square&color=00ffcc&labelColor=16161E&logo=github" /> <img src="https://img.shields.io/github/v/release/OlexiyOdarchuk/go-monobank-sdk?style=flat-square&color=8A2BE2&labelColor=16161E" /> | Go SDK covering **all five public monobank APIs** — personal, corporate, business, acquiring and installment purchases. ECDSA webhook verification with key rotation, typed money/currency/MCC, and a fake monobank server for tests. | `Go` `ECDSA` `OpenTelemetry` |
| ⚡ [**SHMiner**](https://github.com/OlexiyOdarchuk/Student-Hryvnia-Miner)<br><img src="https://img.shields.io/github/stars/OlexiyOdarchuk/Student-Hryvnia-Miner?style=flat-square&color=00ffcc&labelColor=16161E&logo=github" /> <img src="https://img.shields.io/github/v/release/OlexiyOdarchuk/Student-Hryvnia-Miner?style=flat-square&color=8A2BE2&labelColor=16161E" /> | Cross-platform desktop miner. Rewrote SHA-256 from JS to Go with a goroutine worker pool — **1000× the hashrate** of the official client on identical hardware. | `Go` `Wails` `Svelte` `WebSockets` |
| 🎟 [**monokasa**](https://github.com/OlexiyOdarchuk/monokasa)<br><img src="https://img.shields.io/github/stars/OlexiyOdarchuk/monokasa?style=flat-square&color=00ffcc&labelColor=16161E&logo=github" /> | Self-hosted ticketing in one container: a Telegram bot with an in-chat seat map, a customer site, a SvelteKit admin panel with a drag-and-drop hall editor, and a QR scanner for the door. Payments go straight to your own monobank jar — no platform fee, no middleman. Runs on my own SDK. | `Go` `SvelteKit` `SQLite` `PDF + QR` |

<details>
  <summary>📂 Read more...</summary>

### 🧠 What I'm Using

🔹 **Main focus:**
**Go** for backend, compilers and CLI tooling — plus **Svelte (TypeScript)** when a project needs a face.

🔹 **Confident with:**
- `Go` — microservices, goroutines, tree-sitter, TinyGo/WebAssembly
- `PostgreSQL` + `pgvector` — semantic memory, hybrid search, schema-per-tenant isolation
- `Docker` — isolated sandboxes, egress-allowlist proxies, container lifecycle
- `Python` — Telegram bots (`aiogram`), scraping and automation
- `Svelte` + `TypeScript` + `Tailwind` — web editors and dashboards

🔹 **Also in the toolbox:**
- `C` — hot numerical kernels where Go isn't enough
- `MCP`, `RAG`, Anthropic API — AI orchestration and agent infrastructure
- `Redis`, `ClickHouse` — caching and real-time analytics
- `Typst`, `D2` — documents and diagrams as code

🔹 **Everyday tools:**
- `Arch Linux` as my main development OS
- `Zed` and `VSCode` as code editors
- `Claude Code` as a daily driver

---

### 🏆 Wins & Hackathons

- **🥇 1st place — BEST Hackathon 2026.** Lead backend & sensor fusion: reconstructing a UAV's trajectory **without GPS** from IMU and barometer logs, in Go + C.
- **🥉 3rd place — Mate Hackathon 2026.** A Go backend built from scratch in **7 hours** for an AI MarTech tool — beating teams with 5+ years of experience.
- **🔐 Security research → job offer.** Found and responsibly reported a critical flaw in a college blockchain system: the backend never validated transaction amounts, allowing arbitrary negative transfers.
- **🎟 DOU Day 2026** — a personal invitation from the organisers, while still a student.

---

### 📊 Coding Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=OlexiyOdarchuk&theme=tokyonight" width="740" alt="Profile overview and contributions over the last year" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=OlexiyOdarchuk&theme=tokyonight&hide_border=true&background=16161E&ring=82AAFF&fire=89DDFF&currStreakLabel=82AAFF" alt="Commit streak" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=OlexiyOdarchuk&theme=tokyonight" width="365" alt="Top languages by repository" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=OlexiyOdarchuk&theme=tokyonight" width="365" alt="Top languages by commit" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=OlexiyOdarchuk&theme=tokyonight" width="365" alt="Stars, commits, pull requests and issues" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=OlexiyOdarchuk&theme=tokyonight&utcOffset=3" width="365" alt="Commits by hour of day" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=OlexiyOdarchuk&theme=tokyo-night&hide_border=true&bg_color=16161E&color=82AAFF&line=89DDFF&point=ECEFF4&area=true" alt="Contribution activity graph" />
</p>

---

### 📫 Contact me

[![Portfolio](https://img.shields.io/badge/ishawyha.dev-00ffcc?style=for-the-badge&logo=firefoxbrowser&logoColor=black)](https://ishawyha.dev)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/NeShawyha)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:me@ishawyha.dev)

Open to commercial work: backend and APIs, Telegram bots, web apps, automation and parsing.

</details>

---

### ☕ Support My Work

If you like what I do, consider supporting me:

[![Monobank](https://img.shields.io/badge/MonoBank-000000?style=for-the-badge)](https://send.monobank.ua/jar/23E3WYNesG)

---

> 💡 *"From the compiler to the deploy — I own what I build."*
