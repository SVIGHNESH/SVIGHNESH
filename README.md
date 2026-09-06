<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:1f6feb,100:58a6ff&height=180&section=header&text=Vighnesh%20Shukla&fontColor=ffffff&fontSize=48&fontAlignY=34&desc=backend%20%C2%B7%20systems%20%C2%B7%20the%20terminal&descAlignY=54&descSize=16" width="100%" alt="Vighnesh Shukla">

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=I+rebuild+the+tools+I+use%2C+from+scratch.;Redis+in+Java.+Git+in+Go.+Tetris+in+C%2B%2B.;Then+I+go+back+to+the+terminal." alt="I rebuild the tools I use, from scratch">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vighnesh0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vighneshshukla00@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://takeuforward.org/profile/SVIGHNESH"><img src="https://img.shields.io/badge/TakeUForward-D71F26?style=for-the-badge&logo=leetcode&logoColor=white" alt="TakeUForward"></a>
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
 runtime   Spring Boot · FastAPI · Node.js · WebSockets
 learning  Linux internals, distributed systems, AI agents
 wants     a backend role where what happens underneath matters
──────────────────────────────────────────────────
```

Backend engineering hooked me the day I noticed the JVM was JIT-compiling, garbage-collecting, and tuning my code without ever asking me.
I wanted to see every layer underneath it, so I started opening them one at a time.

That is why most of what is on this page is rebuilt from scratch.
Not to replace Redis or git, but because reading about how they work and making `redis-cli` connect to a server you wrote yourself are two very different amounts of understanding.

---

### `~$ ls --sort=weight`

> Eight projects, not eighty. Everything else is on the [repositories tab](https://github.com/SVIGHNESH?tab=repositories).

| Project | One line |
|---|---|
| [**jedis**](https://github.com/SVIGHNESH/jedis) `Java` | Redis-compatible key-value store. Real `redis-cli` and `redis-benchmark` connect to it unmodified. Hand-built RESP parser, single-threaded event loop, active expiry. JUnit is the only dependency. |
| [**kit**](https://github.com/SVIGHNESH/KIT) `Go` | Version control that keeps what git got right and drops what it got wrong. No staging area, and every history-changing operation is journaled so `kit undo` never loses work. |
| [**tetris**](https://github.com/SVIGHNESH/tetris) `C++20` | Terminal Tetris where the engine does not know the terminal exists. The same core compiles to WebAssembly in [tetris-web](https://github.com/SVIGHNESH/tetris-web). |
| [**Sealed**](https://github.com/SVIGHNESH/RealTimeChatApplication) `TypeScript` | End-to-end encrypted chat. The relay only ever sees ciphertext: AES-256-GCM keys derived from the invite-link fragment, every envelope signed by a per-device ECDSA key, history kept in the browser. |
| [**gamep2p**](https://github.com/SVIGHNESH/p2p-game) `TypeScript` | 1v1 browser fighting game over WebRTC with rollback netcode. Deterministic fixed-point simulation, input prediction, snapshot ring, desync hashes, and a Playwright suite that plays real online matches. |
| [**watch-party**](https://github.com/SVIGHNESH/watch-party) `Go` | Upload a video once, watch it in sync with 20-50 friends. ffmpeg builds a 3-rendition HLS ladder; a WebSocket hub per room owns playback state, so late joiners snap to the right second. |
| [**OpsCommander**](https://github.com/SVIGHNESH/opscommander) `Python` | Seven agents that detect, diagnose, gate, remediate, and report on cloud incidents, with a human approval in front of anything risky. Every AWS service is mocked, so it runs with zero credentials. |
| [**Pacman Sentry**](https://github.com/SVIGHNESH/pacman-sentry) `QML` | An [Omarchy](https://omarchy.org) bar widget that watches pacman: pending updates, risky packages flagged first, unread Arch news, and the `.pacnew` files you would otherwise forget. |

---

### `~$ cat stack.txt`

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)

---

### `~$ git log --stat`

<!--
  Stats cards: the official github-readme-stats instance returns 503, so these
  use the salesp07 community mirror. If it starts rate-limiting, deploy your own
  fork to Vercel with a PAT_1 token:
  https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance

  Contribution snake: generated by .github/workflows/snake.yml into the `output`
  branch, so it has no third-party host to die on us.
-->

<p align="center">
  <img src="https://github-readme-stats-salesp07.vercel.app/api?username=svighnesh&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9&include_all_commits=true" alt="GitHub stats" height="170">
  <img src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=svighnesh&layout=compact&langs_count=8&hide=html,css,jupyter%20notebook&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=c9d1d9" alt="Most used languages" height="170">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/SVIGHNESH/SVIGHNESH/output/github-snake.svg" alt="Contribution graph" width="98%">
</p>

---

<p align="center">
  <sub><i>Automate anything that can be automated. Then read the source of the thing you automated.</i></sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,60:1f6feb,100:0d1117&height=110&section=footer" width="100%" alt="">
