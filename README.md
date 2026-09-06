# Hi, I'm Vighnesh 👋

📍 **India** | 🐧 **Arch + Hyprland, all day in the terminal** | 🎓 **B.Tech CSE, AKTU (2023 - present)**

Backend developer and system administrator. I rebuild the tools I use from scratch, because reading about how Redis works and making `redis-cli` connect to a server you wrote yourself are two very different amounts of understanding.

![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/-Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)

## Start Here

- 🟥 **[jedis](https://github.com/SVIGHNESH/jedis)** - Redis in Java; real `redis-cli` and `redis-benchmark` connect unmodified
- 🌿 **[kit](https://github.com/SVIGHNESH/KIT)** - git in Go, with no staging area and an `undo` that never loses work
- 🧱 **[tetris](https://github.com/SVIGHNESH/tetris)** - terminal Tetris in C++20 where the engine never links ncurses
- 🔐 **[Sealed](https://github.com/SVIGHNESH/RealTimeChatApplication)** - end-to-end encrypted chat; the relay only ever sees ciphertext
- 🥊 **[gamep2p](https://github.com/SVIGHNESH/p2p-game)** - 1v1 browser fighter over WebRTC with rollback netcode
- 🚨 **[OpsCommander](https://github.com/SVIGHNESH/opscommander)** - seven agents that handle cloud incidents, with a human gate before anything risky

## Projects

### From Scratch

No engine, no framework, and as close to no dependencies as the language allows.

- 🟥 **[jedis](https://github.com/SVIGHNESH/jedis)** - Redis-compatible key-value store: hand-built RESP parser, single-threaded event loop, active expiry. JUnit is the only library
- 🌿 **[kit](https://github.com/SVIGHNESH/KIT)** - version control that keeps what git got right and drops what it got wrong; every history change is journaled
- 🧱 **[tetris](https://github.com/SVIGHNESH/tetris)** - `tetris_core` is testable without a TTY; ncurses UI is an optional build flag
- 🌐 **[tetris-web](https://github.com/SVIGHNESH/tetris-web)** - the same C++ engine compiled to WebAssembly for the browser
- 👾 **[pellet-rush](https://github.com/SVIGHNESH/pellet-rush)** - neon maze-chase game; everything drawn procedurally on a canvas, every sound a shaped oscillator
- 🎱 **[Billy8rds](https://github.com/SVIGHNESH/Billy8rds)** - offline 8-ball pool for Android with zero dependencies, not even AndroidX; adaptive substepping so fast shots never tunnel
- 📡 **[p2p-fileshare](https://github.com/SVIGHNESH/p2p-fileshare)** - serverless file transfer: UDP multicast discovery, TLS 1.3, resumable multi-peer downloads, one core behind JavaFX and Android
- 🔢 **[merge-blocks](https://github.com/SVIGHNESH/merge-blocks)** - falling-block merge puzzle where tetrominoes carry powers of two; offline, date-seeded daily challenge
- 📄 **[Stackpage](https://github.com/SVIGHNESH/Stackpage)** - Android images-to-PDF that declares no permissions at all, so "nothing is uploaded" is structural

### Real-time & Web

Authoritative servers, WebSockets, and as little framework as each one can get away with.

- 🔐 **[Sealed](https://github.com/SVIGHNESH/RealTimeChatApplication)** - AES-256-GCM keys derived from the invite-link fragment, every envelope signed by a per-device ECDSA key, history kept in the browser
- 🥊 **[gamep2p](https://github.com/SVIGHNESH/p2p-game)** - deterministic fixed-point sim, input prediction, snapshot ring, desync hashes, Playwright tests that play real online matches
- 🎨 **[StudioBoard](https://github.com/SVIGHNESH/StudioBoard)** - collaborative whiteboard with live cursors and a global undo/redo stack shared across clients
- 🔫 **[multiplayer-shooter](https://github.com/SVIGHNESH/multiplayer-shooter)** - 2D arena shooter; the server runs the physics tick, clients only send input. No framework, no build step
- 🎬 **[watch-party](https://github.com/SVIGHNESH/watch-party)** - upload once, watch in sync with 20-50 friends; ffmpeg HLS ladder and a WebSocket hub per room
- 📚 **[The Java Dictionary](https://github.com/SVIGHNESH/java-dictionary)** - the JVM's vocabulary as a 3D knowledge graph; the markdown links *are* the edges
- 🔍 **[oss-contribution-finder](https://github.com/SVIGHNESH/oss-contribution-finder)** - GitHub issues you can realistically contribute to, ranked by language fit, clarity and repo health
- 📝 **[MacQuiz v2](https://github.com/SVIGHNESH/MacQuizV2)** - role-based quiz platform as a Go modular monolith, built against a real SDD
- 🤖 **[ClimbLab](https://github.com/SVIGHNESH/RoboTank)** - browser simulator for a stair-climbing tracked rover: parametric 3D model, rigid-body climb physics, headless climb test
- 🚆 **[train-tracker](https://github.com/SVIGHNESH/train-tracker)** - "Where is my Train" style Expo app: live station-by-station status, delays, platforms
- 🗂️ **[KANBANI](https://github.com/SVIGHNESH/KANBANI)** - offline-first desktop Kanban in Tauri and Rust over bundled SQLite; no accounts, no cloud
- 📓 **[JOLT // 88](https://github.com/SVIGHNESH/Jolt-Refurbished)** - a loud little notebook app on Next.js, Postgres and Drizzle
- 🎯 **[Signal](https://github.com/SVIGHNESH/SkillMAtcher)** - scores a resume against a job description, then writes a plan to close the gaps

### Agents & AI

LLM agents that do real operational work, with a human gate in front of anything risky.

- 🚨 **[OpsCommander](https://github.com/SVIGHNESH/opscommander)** - detect, diagnose, gate, remediate, report; every AWS service mocked, so zero credentials needed
- 🛡️ **[CloudGuard](https://github.com/SVIGHNESH/CloudGuard)** - agentic AWS security auditor over IAM, S3, EC2, Lambda; remediates through SSM after approval
- 💸 **[Recoup](https://github.com/SVIGHNESH/recoup)** - revenue recovery for failed UPI autopay mandates: Hinglish negotiation, promise-to-pay ledger, RBI-style compliance guard. Razorpay Buildathon
- ⛏️ **[Khanij Sahayak](https://github.com/SVIGHNESH/KHANIJ-SAHAYAK)** - document intelligence for Coal India: OCR, hybrid retrieval with pgvector, cited Hindi/English answers. Smart India Hackathon 2026
- 📰 **[reddit-scraper](https://github.com/SVIGHNESH/reddit-scraper)** - jobs, internships and memes every 15 minutes; Actions is the cron, the repo is the database, Pages is the frontend
- 🧠 **[Oryn](https://github.com/SVIGHNESH/Oryn)** - a coding agent on LangGraph, written from an architecture doc down to the agent loop; the first one I took end to end
- 📎 **[LangGraph_RAG_AGENT](https://github.com/SVIGHNESH/LangGraph_RAG_AGENT)** - agentic RAG pipeline on LangGraph
- 💬 **[MultiFileRAGBot](https://github.com/SVIGHNESH/MulitFileRAGBOt)** / **[RAGAgentChat](https://github.com/SVIGHNESH/RAGAgEnTChat)** - RAG chatbots over multiple document sources
- 🩺 **[AI_Medical_Receptionist](https://github.com/SVIGHNESH/AI_Medical_Receptionist)** - voice-driven receptionist for clinics
- 🧰 **[PSTAK](https://github.com/SVIGHNESH/PSTAK)** - editor-agnostic port of the pstack skill collection; works with any agent that discovers `SKILL.md`

### Desktop, Omarchy & Linux

- 📦 **[Pacman Sentry](https://github.com/SVIGHNESH/pacman-sentry)** - Omarchy bar widget: pending updates, risky packages flagged first, Arch news, forgotten `.pacnew` files
- 🗞️ **[Omanews](https://github.com/SVIGHNESH/omanews)** - Hacker News as a triage surface in the bar, not a reader
- 🔌 **[Portboard](https://github.com/SVIGHNESH/omarchy-portboard)** - overlay of every listening localhost port with its process and cwd; answers "which dev server is on 5173?"
- 🍅 **[DORO](https://github.com/SVIGHNESH/DORO)** - Pomodoro timer in Go
- 🚫 **[Neutralise](https://github.com/SVIGHNESH/Neutralise)** - browser extension that removes Shorts from YouTube
- 🥁 **[DrumCV](https://github.com/SVIGHNESH/DrumCV)** / **[CameraPiano](https://github.com/SVIGHNESH/CameraPiano)** - play instruments through a webcam with computer vision
- 🕵️ **[NIDS](https://github.com/SVIGHNESH/NIDS---Network-Intrusion-Detection-System)** - network intrusion detection in Python
- ⚙️ **[Scripts](https://github.com/SVIGHNESH/Scripts)** / **[tmux-config](https://github.com/SVIGHNESH/vighnesh-tmux-config)** / **[Hyprland-Config](https://github.com/SVIGHNESH/Hyprland-Config)** - the dotfiles that make the machine mine

## GitHub Activity

<!--
  Stats cards use the salesp07 mirror because the official github-readme-stats
  instance returns 503. If the mirror starts rate-limiting, deploy your own fork:
  https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance
  The snake is generated by .github/workflows/snake.yml into the `output` branch.
-->

<p>
  <img src="https://github-readme-stats-salesp07.vercel.app/api?username=svighnesh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&include_all_commits=true" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=svighnesh&layout=compact&langs_count=8&hide=html,css,jupyter%20notebook&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=c9d1d9" alt="Most used languages" height="165">
</p>

![Contribution graph](https://raw.githubusercontent.com/SVIGHNESH/SVIGHNESH/output/github-snake.svg)

## What I'm Doing

- **Rebuilding infrastructure I depend on** - Redis, git, and whatever is next, to understand the layer below the one I work in
- **Learning Linux internals and distributed systems** - and writing about the JVM along the way in [The Java Dictionary](https://github.com/SVIGHNESH/java-dictionary)
- **Shipping Omarchy plugins** - QML widgets on the [plugin marketplace](https://omarchyplugins.com)
- **Looking for a backend role** - somewhere what happens underneath matters

## Connect

[![LinkedIn](https://img.shields.io/badge/-Vighnesh_Shukla-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vighnesh0/)
[![Email](https://img.shields.io/badge/-vighneshshukla00@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vighneshshukla00@gmail.com)
[![TakeUForward](https://img.shields.io/badge/-TakeUForward-D71F26?style=flat-square&logo=leetcode&logoColor=white)](https://takeuforward.org/profile/SVIGHNESH)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/SVIGHNESH)

---

> "Automate anything that can be automated. Then read the source of the thing you automated."
