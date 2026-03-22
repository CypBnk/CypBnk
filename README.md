# Hi there, I'm Marc Holländer 👋

## About Me

Senior Security Architect at **Deutsche Telekom MMS** based in Berlin, Germany. With 15+ years of enterprise IT experience, I specialize in designing and implementing secure, scalable Microsoft cloud solutions. My focus areas include Microsoft 365, Azure, Identity & Access Management, and Cloud Security. I'm an advocate for open-source tooling, infrastructure automation, and privacy-first technologies.

---

- 🔭 I'm currently working on **Zero Trust security assessments, Conditional Access baselines, and AI-powered security tooling for enterprise environments**

- 🌱 I'm currently learning **Cyber Risk Modeling (CRML/FAIR), AI-driven security workflows, and MCP (Model Context Protocol) integrations**

- 👯 I'm looking to collaborate on **open-source Microsoft 365 & Azure security projects**

- 🤝 I'm looking for help with **building community-driven security baselines and expanding open-source cloud security tooling**

- 💬 Ask me about **Microsoft 365, Azure, Cloud Security, Conditional Access, Zero Trust, PowerShell automation, and enterprise identity management**

- 📫 How to reach me: &nbsp; [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marc-holl%C3%A4nder-279307152/) &nbsp; [![Xing](https://img.shields.io/badge/-Xing-006567?style=flat&logo=xing&logoColor=white)](https://www.xing.com/profile/Marc_Hollaender)

---

## 🚀 Project Highlights

### 🔐 [ConditionalAccessBaseline](https://github.com/CypBnk/ConditionalAccessBaseline)

A simplified, Zero Trust security baseline for Microsoft Entra Conditional Access policies. Based on the Microsoft CA framework by Claus Jespersen, streamlined for easier understanding and deployment.

- **Persona-based policy structure** — Global, Admins, Internals, Guests, Service Accounts, Agents
- **30+ pre-configured policies** — MFA enforcement, legacy auth blocking, device compliance, phishing-resistant MFA for admins
- **One-click bulk import** via IntuneManagement tool with automatic dependency resolution
- **GDPR-aware** — Country whitelisting, continuous access evaluation, session controls

`JSON` · `PowerShell` · `Microsoft Entra ID` · `Intune`

---

### 🎬 [expert-review-system](https://github.com/CypBnk/expert-review-system)

AI-Powered Media Recommendation Engine that analyzes professional reviews from IMDb, Steam, and Metacritic to generate personalized compatibility scores.

- **BERT-based sentiment analysis** using the nlptown multilingual model
- **20+ theme detection** — character development, plot twists, atmosphere, and more
- **Smart review filtering** — deduplication, spam detection, length validation
- **Privacy-first** — all data stored locally, no external tracking
- **Docker-ready** with multi-stage builds and Gunicorn WSGI

`Python` · `Flask` · `PyTorch` · `HuggingFace Transformers` · `Docker` · `JavaScript`

---

### 🎙️ [whisper-transcription-toolkit](https://github.com/CypBnk/whisper-transcription-toolkit)

Comprehensive Python toolkit for transcribing German audio and video files using OpenAI Whisper with GPU acceleration support.

- **Dual processing modes** — Direct video transcription or MP3 conversion pipeline
- **GPU-accelerated** — ~2.8x real-time speed on RTX 3090 via CUDA
- **Batch processing** with smart file management and folder structure preservation
- **Multiple output formats** — TXT (timestamped), SRT (subtitles), JSON (metadata)
- **German language optimized** — pre-configured with umlaut handling

`Python` · `OpenAI Whisper` · `PyTorch/CUDA` · `FFmpeg` · `PowerShell`

---

### 🤖 [CoPilot-instruction-generator-system](https://github.com/CypBnk/CoPilot-instruction-generator-system)

Multi-agent orchestration system for GitHub Copilot that auto-detects your tech stack and generates a complete, production-ready `.github/` instruction set in one pass.

- **Seven specialist agents** — stack detection, scaffolding, instruction writing, validation, and more
- **Three-gate validation** — structural, behavioral, and provenance checks before delivery
- **Stack-adaptive output** — different projects get tailored agents and instructions
- **Security by default** — hardened `security.instructions.md` always generated

`Markdown` · `GitHub Copilot Agent Mode` · `Claude Haiku 4.5` · `GPT-5 mini`

---

### 📊 [Magenta_Cost-of-Breach](https://codeberg.org/MaHo_CB/Magenta_Cost-of-Breach)

Interactive breach cost calculator based on the IBM Cost of Data Breach Report 2024. Estimates financial impact by industry, country, company size, and attack vector.

- **12 industries, 11 countries, 12 attack vectors** — granular cost modeling
- **8 mitigation strategies** — AI & Automation, MFA/Zero Trust, Threat Hunting, and more
- **GDPR compliance module** — EU regulatory fine calculations
- **Zero-cost architecture** — runs entirely on Azure Static Web Apps free tier

`JavaScript` · `Python` · `Azure Functions` · `Azure Static Web Apps` · `Vite`

---

### 🛡️ [Scripts-and-Tools](https://github.com/CypBnk/Scripts-and-Tools)

A comprehensive collection of automation and utility scripts for Microsoft 365 and Entra ID administration.

- **Intune MDM Management** — stale device cleanup, broken enrollment repair, Autopilot-safe deletion
- **SecurityGroupUsage Module** — discovers where Entra security groups are used across all workloads (CA policies, Intune, licensing, Exchange, role assignments)
- **Generates 9 output artifacts** — JSON, Markdown, HTML reports, and 6 CSV exports with decision matrix

`PowerShell` · `Microsoft Graph API` · `Entra ID` · `Intune`

---

### Notable Forks & Contributions

| Project | What | Why |
|---------|------|-----|
| [zerotrustassessment](https://github.com/CypBnk/zerotrustassessment) | Microsoft Zero Trust tenant audit module | Custom `Magenta365_Changes` for Deutsche Telekom environments |
| [Magenta_crml](https://github.com/CypBnk/Magenta_crml) | Cyber Risk Modeling Language (CRML) | Declarative risk-as-code — FAIR Monte Carlo, Bayesian models |
| [lokka-MCP-Streamable](https://github.com/CypBnk/lokka-MCP-Streamable) | MCP for Microsoft 365 | Model Context Protocol integration with Microsoft Graph |
| [M365Documentation](https://github.com/CypBnk/M365Documentation) | Automatic M365 documentation | Simplifies tenant documentation for admins |
| [PiHoleBlocklist](https://github.com/CypBnk/PiHoleBlocklist) | Custom Pi-hole blocklist | 580 domains — focused on unofficial game mod sites & suspicious downloads |

---

## 🛠️ Languages & Tools

![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Azure](https://img.shields.io/badge/-Microsoft%20Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/-Microsoft%20365-D83B01?style=flat&logo=microsoft&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=CypBnk&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" />
</p>
<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CypBnk&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</p>
<p>
  <img src="https://streak-stats.demolab.com?user=CypBnk&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

---

## 📈 Contribution Timeline

<p>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=CypBnk&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" />
</p>

<!--
  🐍 Snake Animation — uncomment after running the generate-snake.yml GitHub Action:-->

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CypBnk/CypBnk/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CypBnk/CypBnk/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/CypBnk/CypBnk/output/github-contribution-grid-snake.svg" />
  </picture>


---

## 🔗 Find me also on

[![Codeberg](https://img.shields.io/badge/-Codeberg-2185D0?style=flat&logo=codeberg&logoColor=white)](https://codeberg.org/MaHo_CB)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marc-holl%C3%A4nder-279307152/)
[![Xing](https://img.shields.io/badge/-Xing-006567?style=flat&logo=xing&logoColor=white)](https://www.xing.com/profile/Marc_Hollaender)
