<h1 align="center">Logan Velier</h1>
<h3 align="center">Software Engineer &nbsp;·&nbsp; Backend, DevOps & Security &nbsp;·&nbsp; Wisconsin</h3>

<p align="center">
  <a href="https://linkedin.com/in/logan-velier"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:loganv308@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://velier.dev"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8+PHBhdGggZD0iTTIgMTJoMjAiLz48cGF0aCBkPSJNMTIgMmExNS4zIDE1LjMgMCAwIDEgNCAxMCAxNS4zIDE1LjMgMCAwIDEtNCAxMCAxNS4zIDE1LjMgMCAwIDEtNC0xMCAxNS4zIDE1LjMgMCAwIDEgNC0xMHoiLz48L3N2Zz4=" alt="Portfolio"/></a>
</p>

---

### 👋 About

- 🏢 Software Engineer at **Acuity Insurance**, building document composition systems — **OpenText Exstream**, XML pipelines, and **GitLab CI/CD** automation
- 🏠 Run **AntonLabs**, a self-hosted homelab where most of my side projects live (Proxmox, Docker, Nginx, Tailscale, VLAN-segmented UniFi network)
- 🛡️ Moving toward **cybersecurity** — starting an M.S. in Cybersecurity & Information Assurance at WGU, and practicing in the lab with Wazuh, Sysmon, and an Active Directory attack/defense environment
- 🧱 I like building things end-to-end: data ingestion → database → API → UI → container → deployed

---

### 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[LogStream](https://github.com/Loganv308/Forge-modules)** | Self-hosted log aggregation platform with live streaming and drop-in client libraries for Python (async), TypeScript, and Java (Maven) | React · TypeScript · Express · PostgreSQL · WebSockets |
| **MediaFlow** | Media transcoding pipeline that scans a NAS, re-encodes video with NVENC GPU acceleration, and shows live job progress | Java · Spring Boot · FFmpeg · PostgreSQL · React |
| **ChatPipeline** | Fault-tolerant Twitch chat ingestion — collector buffers to SQLite (WAL) so ingestion survives database outages, sync process drains to Postgres | Python · asyncio · SQLite · PostgreSQL · Docker |
| **AntonLabs Wiki** | Wiki that renders Obsidian-flavored markdown, with vault import, drag-and-drop ordering, and attachments; shipped as a single container | React · Vite · Express · PostgreSQL · GitHub Actions |
| **TwitchAnalyticsBot** | Chat analytics dashboard backed by a tuned PostgreSQL instance (materialized views, pool caps, config tuning) | Python · TypeScript · Express · PostgreSQL |
| **[PgPort](https://github.com/Loganv308/PgPort)** | Browser-based SQL console for PostgreSQL with a read-only safety model, server-side paging, a schema browser, and streaming CSV/JSON/XML exports | C# · ASP.NET Core 8 · Npgsql · Docker |

---

### 🛡️ Homelab & Security

```text
AntonLabs
├── Proxmox ─────────── LXC / VMs for services and databases
├── UniFi ───────────── VLAN segmentation, DMZ zone
├── Nginx ───────────── reverse proxy for self-hosted apps
├── Tailscale + PiHole ─ remote access & DNS
├── Wazuh + Sysmon ──── endpoint monitoring / SIEM
└── AD Lab ──────────── tiered admin model, GPO hardening, Kerberoasting practice
```

---

### 🛠 Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Backend & Frontend**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![XML](https://img.shields.io/badge/XML_Pipelines-005A9C?style=flat&logo=xml&logoColor=white)

**DevOps & Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

**Security**
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat&logo=wazuh&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat&logo=windows&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat&logo=tailscale&logoColor=white)
![Pi-hole](https://img.shields.io/badge/Pi--hole-96060C?style=flat&logo=pihole&logoColor=white)

---

### 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Loganv308&show_icons=true&hide_border=true&theme=transparent" alt="GitHub stats"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Loganv308&layout=compact&hide_border=true&theme=transparent" alt="Top languages"/>
</p>

<p align="center">
  <a href="https://github.com/Loganv308?tab=repositories"><b>Browse all repositories →</b></a>
</p>
