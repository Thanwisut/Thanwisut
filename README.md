[README.md](https://github.com/user-attachments/files/30075238/README.md)
<div align="center">

# Hi, I'm Thanwisut 👋

### High school student building in cybersecurity, AI, and web development

I'm currently focused on becoming a strong cybersecurity engineer while combining AI with security automation — learning by shipping real tools, not just reading about them.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://thanwisut.vercel.app/thanwisut)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Thanwisut)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thanwisut2551@gmail.com)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@thanwisutsiamsec)

</div>

---

## 🧭 About Me

I'm a student from Thailand with a genuine interest in how systems break and how to build them more securely. My interests sit at the intersection of **cybersecurity, web development, and AI** — I like understanding a system well enough to attack it, and well enough to defend it.

Outside of security work, I build web apps, write automation tooling, and create content to share what I'm learning.

- 🔐 Interested in: Cybersecurity, Web Security, AI, Programming, Linux, Networking, Automation, Open Source
- 🎯 Currently working toward: becoming a strong cybersecurity engineer, blending AI with security automation
- 🌱 I'm still early in this journey — everything below reflects real, in-progress work, not a finished resume

---

## 🛠️ Skills

<table>
<tr>
<td valign="top" width="50%">

**Programming**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td valign="top" width="50%">

**Database**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**DevOps / Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**Cybersecurity Tooling**
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>Full recon / offensive-security toolkit</b></summary>
<br>

`Nuclei` · `sqlmap` · `John the Ripper` · `Gobuster` · `ffuf` · `Amass` · `Subfinder` · `httpx` · `Naabu` · OWASP Top 10 methodology

</details>

---

## 🚀 Featured Projects

### 🔴 [REDPILOT](https://github.com/Thanwisut/RedPilot)
**AI-powered autonomous penetration testing framework**

REDPILOT is my biggest project so far — an attempt to see how far LLM-driven agents can go in automating real penetration-testing workflows, from reconnaissance through reporting. I built it because a lot of the repetitive parts of pentesting (recon, enumeration, first-pass triage) are exactly the kind of work an agent can help with, if it's given the right tools and enough human oversight to stay safe and accountable.

It's built around a terminal-first philosophy — a rich TUI (built with [Ink](https://github.com/vadimdemedes/ink), React for CLIs) acts as the operator's command center, while a Python/FastAPI backend orchestrates agents and tools over a typed WebSocket contract.

**Highlights:**
- 🤖 LLM-driven agents that autonomously execute pentesting tasks, with multi-provider support (OpenRouter, Gemini, OpenAI-compatible)
- 🔬 Task orchestration across multiple coordinated agents, visualized as a live task graph
- 🛠️ Sandboxed execution layer for real security tools (subfinder, nmap, nuclei, and more)
- ✅ Human-in-the-loop approval for sensitive operations — nothing destructive runs unattended
- 📝 Structured, auditable markdown reports

`TypeScript` `Python` `Ink/React` `FastAPI` `WebSockets`

---

### 🎓 [SiamSec](https://siam-sec.vexr.dev)
**Cybersecurity learning platform**

A platform built to make learning ethical hacking, web security, and Linux more structured and hands-on — built with the kind of resource I wished existed when I was starting out. It offers guided learning paths and premium content behind authentication, with a markdown-based content editor on the backend.

`Next.js` `Supabase` `Authentication` `Markdown CMS`

---

### 💼 [Digital Identity Card](https://thanwisut.vercel.app/thanwisut)
**Personal portfolio / digital business card**

A modern, minimal personal site that works as a digital identity card — built to look sharp on both desktop and mobile, with a focus on clean motion and responsive layout over heavy visual noise.

`Next.js` `TailwindCSS` `Responsive Design`

---

### 🏢 Company Landing Page
**Cybersecurity services landing page**

A professional landing page built for a cybersecurity-focused brand — service showcase, clean modern UI, fully responsive.

`Next.js` `TailwindCSS`

---

### 🧪 Other / Learning Projects

<details>
<summary>Offensive-security research repos</summary>
<br>

A few smaller repositories (`Spam`, `S7IAM-PHISH`, `nglspam-lnwper`) built while studying offensive security concepts — social engineering mechanics, phishing infrastructure, and how these attacks are actually built, purely for educational and defensive-research purposes. Understanding how these techniques work is part of learning how to defend against them.

</details>

---

## 📚 Currently Learning

`AI Agents` · `MCP` · `LLMs` · `Prompt Engineering` · `Malware Analysis` · `Web Security` · `Cloud Security` · `Active Directory` · `API Security` · `Reverse Engineering`

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Thanwisut&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Thanwisut&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Thanwisut&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Thanwisut&theme=tokyo-night&hide_border=true" alt="Contribution Graph" width="90%"/>

</div>

---

## 📫 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Thanwisut)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thanwisut2551@gmail.com)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@thanwisutsiamsec)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](#)

</div>

<div align="center">
<sub>Always learning, always building — feel free to reach out.</sub>
</div>
