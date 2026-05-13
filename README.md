<div align="center">

<img src="https://img.shields.io/badge/Powered%20by-Vultr-007BFC?style=for-the-badge&logo=vultr&logoColor=white" />
<img src="https://img.shields.io/badge/CNCF-Community%20Event-00AEEF?style=for-the-badge&logo=cncf&logoColor=white" />
<img src="https://img.shields.io/badge/🔒%20Invite%20Only-Event-red?style=for-the-badge" />

<br/><br/>

# ☁️ Cloud Native Day Pune 2026
**In collaboration with Vultr**

<br/>

![Date](https://img.shields.io/badge/📅%20Date-31%20May%202026-0C447C?style=flat-square)
![Time](https://img.shields.io/badge/🕙%20Time-09:30%20AM%20–%2003:00%20PM%20IST-0C447C?style=flat-square)
![Venue](https://img.shields.io/badge/📍%20Venue-JW%20Marriott%20Pune-0C447C?style=flat-square)

<br/>

### 🚀 [REGISTER HERE →](https://forms.gle/XfaczLoLoEu71AT78)

> **Invite-only event.** Confirmations sent by **20 May 2026**.

</div>

---

## 📋 Table of Contents

- [About the Event](#-about-the-event)
- [Agenda](#️-agenda)
- [Pre-Workshop Setup](#️-pre-workshop-setup)
- [OpenClaw Setup](#-openclaw-setup)
- [Project Structure](#-project-structure)
- [Troubleshooting](#️-troubleshooting)
- [Code of Conduct](#-code-of-conduct)
- [Important Links](#-important-links)

---

## 🌟 About the Event

**Cloud Native Day Pune 2026** is Pune's flagship full-day cloud-native conference, organised by Cloud Native Pune (CNCF Community Group) in collaboration with **Vultr**.

Bringing together developers, SREs, platform engineers, and cloud enthusiasts for technical talks, hands-on workshops, and real-world cloud-native stories.

**Topics:** Kubernetes · Platform Engineering · Observability · AI + Cloud Native · Security · CNCF Ecosystem

> [!IMPORTANT]
> This is an **invite-only** event. Submit the registration form → team reviews → confirmation by **20 May 2026**. Only confirmed attendees receive entry details.

---

## 🗓️ Agenda

| Time | Session |
|:---|:---|
| `09:30 AM` | Doors open & check-in |
| `10:00 AM` | Does Security Have a Place in the Cloud Native Galaxy? |
| `11:00 AM` | Observability for AI |
| `TBA` | Deploying OpenClaw on Vultr — Hands-on Workshop |
| `TBA` | Lightning Sessions |
| `03:00 PM` | Networking & Closing |

> Agenda will be updated as confirmations come in. Watch the [event page](https://ocgroups.dev/cncf/group/p5hsakp/event/xavkwq6).

---

## ⚙️ Pre-Workshop Setup

> [!WARNING]
> Complete all steps **before 31 May**. No time for installations on the day.
> Arrive at 09:30 AM if you need help from mentors.

### Required Accounts

| Platform | Link | Required |
|:---|:---|:---:|
| GitHub | [github.com](https://github.com) | ✅ |
| Vultr | [vultr.com](https://www.vultr.com) | ✅ |
| Docker Hub | [hub.docker.com](https://hub.docker.com) | Optional |

### Required Software

| Tool | Version | Link |
|:---|:---|:---|
| Node.js | v22.14+ (v24 recommended) | [nodejs.org](https://nodejs.org) |
| Git | Latest | [git-scm.com](https://git-scm.com) |
| Docker Desktop | v24+ | [docker.com](https://www.docker.com/products/docker-desktop) |
| VS Code | Latest | [code.visualstudio.com](https://code.visualstudio.com) |

**VS Code Extensions:** `Docker` · `YAML` · `Kubernetes`

### System Requirements

| | Minimum |
|:---|:---|
| RAM | 8 GB |
| Free Storage | 10 GB+ |
| Internet | Stable |
| Battery | Fully charged |

> **Windows users:** WSL2 recommended. See [docs.openclaw.ai/platforms/windows](https://docs.openclaw.ai/platforms/windows)

---

## 🚀 OpenClaw Setup

Complete all steps before arriving.

**1. Verify Node.js & Docker**
```bash
node --version        # v22.14.0 or above
npm --version         # 10.x or above
docker --version      # 24.x or above
docker run hello-world
git --version
```

**2. Install OpenClaw**
```bash
# macOS / Linux
curl -fsSL https://openclaw.ai/install.sh | bash

# Windows (PowerShell)
iwr -useb https://openclaw.ai/install.ps1 | iex
```

**3. Run onboarding**
```bash
openclaw onboard --install-daemon
```

**4. Verify gateway**
```bash
openclaw gateway status
# Expected: Gateway listening on port 18789
```

**5. Open dashboard**
```bash
openclaw dashboard
# Opens in browser — if it loads, you're ready ✅
```

---

## 📁 Project Structure

```
cloud-native-day-pune-2026/
├── openclaw/       # OpenClaw configs
├── docker/         # Dockerfiles
├── deployment/     # Deployment manifests
├── kubernetes/     # K8s configs
└── notes/          # Workshop notes
```

---

## 🛠️ Troubleshooting

| Issue | Action |
|:---|:---|
| Installation error | Arrive at 09:30 AM — mentors available |
| Node.js issues | [docs.openclaw.ai/install/node](https://docs.openclaw.ai/install/node) |
| Windows issues | [docs.openclaw.ai/platforms/windows](https://docs.openclaw.ai/platforms/windows) |

---

## 🤝 Code of Conduct

All participants must maintain a welcoming, inclusive, and respectful environment.

- Be respectful to speakers and fellow participants
- Follow mentor instructions
- Keep devices on silent
- Do not share credentials or run unauthorized tools

> Harassment or disruptive behaviour will not be tolerated.

---

## 🔗 Important Links

| Resource | Link |
|:---|:---|
| 📋 Register | [forms.gle/XfaczLoLoEu71AT78](https://forms.gle/XfaczLoLoEu71AT78) |
| 📅 Event Page | [ocgroups.dev/cncf/.../event/xavkwq6](https://ocgroups.dev/cncf/group/p5hsakp/event/xavkwq6) |
| ☁️ Vultr × OpenClaw | [vultr.com/marketplace/apps/openclaw](https://www.vultr.com/marketplace/apps/openclaw/#getting-started) |
| 📖 OpenClaw Docs | [docs.openclaw.ai](https://docs.openclaw.ai/start/getting-started) |

---

<div align="center">

Organised by **Cloud Native Pune** · Powered by **Vultr**

<img src="https://img.shields.io/badge/Powered%20by-Vultr-007BFC?style=for-the-badge&logo=vultr&logoColor=white"/>

</div>
