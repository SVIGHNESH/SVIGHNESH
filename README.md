<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:1f6feb,100:58a6ff&height=180&section=header&text=Vighnesh%20Shukla&fontColor=ffffff&fontSize=48&fontAlignY=34&desc=backend%20%C2%B7%20systems%20%C2%B7%20the%20terminal&descAlignY=54&descSize=16" width="100%" alt="Vighnesh Shukla">

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=I+rebuild+the+tools+I+use%2C+from+scratch.;Redis+in+Java.+Git+in+Go.+Tetris+in+C%2B%2B.;Then+I+go+back+to+the+terminal." alt="I rebuild the tools I use, from scratch">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vighnesh0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vighneshshukla00@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://takeuforward.org/profile/SVIGHNESH"><img src="https://img.shields.io/badge/TakeUForward-D71F26?style=for-the-badge&logo=leetcode&logoColor=white" alt="TakeUForward"></a>
  <img src="https://komarev.com/ghpvc/?username=svighnesh&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile views">
</p>

---

### `~$ whoami`

```console
vighnesh@arch
──────────────────────────────────────────────────
 role      Backend Developer / System Administrator
 studying  B.Tech CSE, AKTU  ·  2023 - present
 os        Arch Linux + Hyprland
 shell     bash + tmux, all day
 writes    Java  ·  Go  ·  TypeScript  ·  Python  ·  C++
 runtime   Spring Boot · FastAPI · Node.js · Socket.IO
 learning  Linux internals, distributed systems, AI agents
 wants     a backend role where what happens underneath matters
──────────────────────────────────────────────────
```

I got hooked on backend engineering the first time I really understood what the JVM was doing underneath me.
The idea that my code was being JIT-compiled, garbage-collected, and tuned by a runtime I had never looked at made me want to open every layer below it.

So now I rebuild things.
Not to replace them, but because reading a Redis internals post and writing a working RESP parser are two completely different amounts of understanding.

---

### `~$ ls from-scratch/`

> The rule for this shelf: **no engine, no framework, and as close to no dependencies as the language allows.**

| Project | What it is | Why it was hard |
|---|---|---|
| [**jedis**](https://github.com/SVIGHNESH/jedis) `Java` | A Redis-compatible key-value store. Real `redis-cli` and `redis-benchmark` connect to it unmodified. | Hand-built RESP parser, single-threaded event loop owning the whole keyspace, and active expiry cycles. JUnit is the only library in the repo. |
| [**kit**](https://github.com/SVIGHNESH/KIT) `Go` | A version control system that keeps what git got right and drops what it got wrong. | No staging area, one job per command, and every history-changing operation journaled so `kit undo` and `kit redo` never silently lose work. |
| [**tetris**](https://github.com/SVIGHNESH/tetris) `C++20` | A terminal Tetris where the engine does not know the terminal exists. | `tetris_core` never links ncurses, so the entire game is testable without a TTY. Catch2 suite, CMake, UI is an optional build flag. |
| [**Billy8rds**](https://github.com/SVIGHNESH/Billy8rds) `Kotlin` | Offline 8-ball pool for Android that stays smooth on decade-old phones. | Zero dependencies, not even AndroidX. Custom `SurfaceView` loop with adaptive substepping so fast shots never tunnel through rails, and zero allocations on the frame path. |
| [**p2p-fileshare**](https://github.com/SVIGHNESH/p2p-fileshare) `Java` | Cross-platform peer-to-peer file transfer with no server in the middle. | UDP multicast peer discovery, TLS 1.3 on the wire, and parallel multi-peer downloads that resume. One shared core behind both JavaFX and Android. |

---

### `~$ ls agents/`

| Project | What it is |
|---|---|
| [**OpsCommander**](https://github.com/SVIGHNESH/opscommander) `Python` | Seven specialised agents that detect, diagnose, gate, remediate, and report on cloud incidents, with a human in the loop before anything risky runs. Every AWS service is mocked locally, so it works with zero credentials and zero config. |
| [**CloudGuard**](https://github.com/SVIGHNESH/CloudGuard) `Python` | An agentic AWS security and compliance auditor. Scans IAM, S3, EC2, Lambda and security groups, reasons about findings with Bedrock, scores severity, and can remediate through SSM after approval. |
| [**reddit-scraper**](https://github.com/SVIGHNESH/reddit-scraper) `Python` | Jobs, internships and memes pulled off Reddit every 15 minutes. There is no server and nothing to pay for: Actions is the cron, the repo is the database, Pages is the frontend, and Telegram is the alert channel. |
| [**Oryn**](https://github.com/SVIGHNESH/Oryn) `Python` | A coding agent on LangGraph, written from an architecture document down to the agent loop. It was the first one I took end to end, and the reason the rest of this list exists. |
| [**LangGraph_RAG_AGENT**](https://github.com/SVIGHNESH/LangGraph_RAG_AGENT) `Python` | An agentic RAG pipeline built on LangGraph. |

---

### `~$ ls web/`

| Project | What it is |
|---|---|
| [**StudioBoard**](https://github.com/SVIGHNESH/StudioBoard) `TypeScript` | Real-time collaborative whiteboard with live cursors, presence, a global undo/redo stack shared across clients, client-side image downscaling, and PNG export. |
| [**multiplayer-shooter**](https://github.com/SVIGHNESH/multiplayer-shooter) `JavaScript` | A 2D arena shooter in the browser with a room-code invite system. The server is authoritative: it runs the physics tick and clients only send input, which keeps the game cheat-resistant and desync-free. No framework and no build step. |
| [**The Java Dictionary**](https://github.com/SVIGHNESH/java-dictionary) `TypeScript` | The vocabulary of Java and the JVM as an interactive 3D knowledge graph. There is no `nodes.json`: the markdown links between entries *are* the edges, so the graph can never drift out of date with the writing. |
| [**MacQuiz v2**](https://github.com/SVIGHNESH/MacQuizV2) `Go` | A role-based quiz platform rebuilt as a modular monolith, designed against a real SDD with a documented data model, permission matrix, and $0-hosting deployment plan. |

<details>
<summary><b>~$ ls experiments/</b></summary>

<br>

- [**MultiFileRAGBot**](https://github.com/SVIGHNESH/MulitFileRAGBOt) and [**RAGAgentChat**](https://github.com/SVIGHNESH/RAGAgEnTChat) - RAG chatbots over multiple document sources
- [**AI_Medical_Receptionist**](https://github.com/SVIGHNESH/AI_Medical_Receptionist) - voice-driven receptionist for clinics
- [**NIDS**](https://github.com/SVIGHNESH/NIDS---Network-Intrusion-Detection-System) - network intrusion detection in Python
- [**DrumCV**](https://github.com/SVIGHNESH/DrumCV) and [**CameraPiano**](https://github.com/SVIGHNESH/CameraPiano) - play instruments through a webcam using computer vision
- [**Signal**](https://github.com/SVIGHNESH/SkillMAtcher) - scores a resume against a job description, then writes a plan to close the missing skills. SvelteKit and FastAPI
- [**KANBANI**](https://github.com/SVIGHNESH/KANBANI) - offline-first Kanban board for the desktop. Tauri and Rust over bundled SQLite, no accounts and no cloud
- [**JOLT // 88**](https://github.com/SVIGHNESH/Jolt-Refurbished) - a loud little notebook app. Next.js 14 on Postgres with Drizzle, Auth.js and Upstash rate limiting
- [**DORO**](https://github.com/SVIGHNESH/DORO) - Pomodoro timer in Go
- [**Neutralise**](https://github.com/SVIGHNESH/Neutralise) - browser extension that removes Shorts from YouTube
- [**Scripts**](https://github.com/SVIGHNESH/Scripts), [**tmux-config**](https://github.com/SVIGHNESH/vighnesh-tmux-config), [**Hyprland-Config**](https://github.com/SVIGHNESH/Hyprland-Config) - the dotfiles that make the machine mine

</details>

---

### `~$ cat stack.txt`

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend and real-time**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data and infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### `~$ git log --stat`

<!--
  Stats cards run on a community mirror of github-readme-stats, because the
  official instance (github-readme-stats.vercel.app) is currently returning
  503 DEPLOYMENT_PAUSED. If this mirror ever dies too, swap the host for one of:
      github-readme-stats-salesp07.vercel.app     (verified working)
      github-readme-stats-sigma-five.vercel.app   (works, but caps top-langs at 5)
  The permanent fix is to deploy your own fork to Vercel and point these at it:
      https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance
  Note: github-profile-trophy.vercel.app is dead (402 Payment Required), which is
  why there is no trophy row here.
-->

<p align="center">
  <img src="https://github-readme-stats-one-gules.vercel.app/api?username=svighnesh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&include_all_commits=true" alt="GitHub stats" height="170">
  <img src="https://github-readme-stats-one-gules.vercel.app/api/top-langs/?username=svighnesh&layout=compact&langs_count=8&hide=html,css,jupyter%20notebook&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=c9d1d9" alt="Most used languages" height="170">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=svighnesh&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="Contribution streak" height="170">
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=svighnesh&theme=react-dark&bg_color=0D1117&color=c9d1d9&line=58A6FF&point=ffffff&hide_border=true&area=true" alt="Contribution activity" width="98%">
</p>

---

<p align="center">
  <sub><i>Automate anything that can be automated. Then read the source of the thing you automated.</i></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,60:1f6feb,100:0d1117&height=110&section=footer" width="100%" alt="">
