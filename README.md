<div align="center">

<img src="https://img.shields.io/badge/Cloud%20Native%20Day-2026-0078FF?style=for-the-badge&logo=cloudflare&logoColor=white" />
<img src="https://img.shields.io/badge/Powered%20by-Vultr-007BFC?style=for-the-badge&logo=vultr&logoColor=white" />
<img src="https://img.shields.io/badge/OpenClaw-Workshop-FF6B35?style=for-the-badge&logo=openapiinitiative&logoColor=white" />

<br/><br/>

# ☁️ Cloud Native Day 2026
## Vultr × OpenClaw Workshop

**Deploying & Exploring OpenClaw on Vultr Marketplace**

<br/>

[![Date](https://img.shields.io/badge/📅%20Date-22nd%20May%202026-blue?style=flat-square)](.)
[![Duration](https://img.shields.io/badge/⏱%20Duration-1%20Hour-green?style=flat-square)](.)
[![Format](https://img.shields.io/badge/🎯%20Format-Hands--on%20%2B%20Guided-orange?style=flat-square)](.)
[![Community](https://img.shields.io/badge/🏙️%20Community-Cloud%20Native%20Pune-purple?style=flat-square)](.)

<br/>

> *A hands-on workshop for developers ready to explore cloud-native deployments — from zero to live in one hour.*

</div>

---

## 📋 Table of Contents

**For Volunteers & Speakers**
- [🎤 Volunteer Responsibilities](#-volunteer-responsibilities)
- [📣 Promotion Checklist](#-promotion-checklist)
- [📦 GitHub Repo Checklist](#-github-repo-checklist)

**For Participants**
- [🌟 About the Workshop](#-about-the-workshop)
- [🎯 What You'll Learn](#-what-youll-learn)
- [⚙️ Pre-Workshop Setup](#️-pre-workshop-setup)
  - [Required Accounts](#-required-accounts)
  - [Required Software](#-required-software)
  - [System Requirements](#-system-requirements)
- [🚀 OpenClaw Setup](#-openclaw-setup)
- [🗓️ Workshop Flow](#️-workshop-flow)
- [📁 Project Structure](#-project-structure)
- [🔐 Security Best Practices](#-security-best-practices)
- [🛠️ Troubleshooting](#️-troubleshooting)
- [🤝 Code of Conduct](#-code-of-conduct)
- [🔗 Important Links](#-important-links)

---

# 🎤 FOR VOLUNTEERS & SPEAKERS

> [!NOTE]
> This section is for **workshop organizers, speakers, and volunteers only.**  
> If you're a participant, skip to [About the Workshop](#-about-the-workshop) below.

---

## 🎤 Volunteer Responsibilities

As a volunteer for Cloud Native Day 2026, your two main responsibilities are:

### 1. 📣 Promotion & Outreach
- Promote the workshop on **LinkedIn** and other developer communities
- Drive registrations to the **OpenClaw landing page**
- Encourage developers in the Cloud Native Pune & Docker Hub Pune groups to join
- Use the hashtag **#CloudNativeDay2026** in all posts

### 2. 📦 GitHub Repository Maintenance
- Keep this repo updated with pre-workshop setup instructions
- Ensure all installation commands are tested and working
- Add resources, references, and troubleshooting steps as needed
- Keep the README clean, welcoming, and easy to follow

---

## 📣 Promotion Checklist

Use this checklist before the event:

- [ ] Post on LinkedIn about the workshop (tag OpenClaw & Vultr if possible)
- [ ] Share the OpenClaw landing page link: `https://www.vultr.com/marketplace/apps/openclaw/#getting-started`
- [ ] Post in Cloud Native Pune community channels
- [ ] Post in Docker Hub Pune community channels
- [ ] Remind participants 3 days before to complete pre-setup
- [ ] Remind participants 1 day before with venue/time details
- [ ] Pin the GitHub repo link in all community channels

**Sample LinkedIn Post:**
```
🚀 Excited to be volunteering at Cloud Native Day 2026!

Join us on 22nd May for a hands-on workshop on deploying OpenClaw 
on Vultr Marketplace — from zero to live cloud deployment in just 1 hour!

🔧 What you'll build: A live OpenClaw deployment on Vultr
👥 Who it's for: Developers curious about cloud-native workflows
📍 Format: Hands-on + Guided session

Complete your setup before arriving 👇
[GitHub Repo Link]

#CloudNativeDay2026 #CloudNative #OpenClaw #Vultr #Pune #DevCommunity
```

---

## 📦 GitHub Repo Checklist

Before the event, ensure this repo contains:

- [ ] Updated README with setup instructions (this file)
- [ ] All installation commands tested on Windows, macOS & Linux
- [ ] Troubleshooting steps for common errors
- [ ] Folder structure created (`openclaw/`, `docker/`, `deployment/`, etc.)
- [ ] Workshop references and important links verified and working
- [ ] Code of conduct visible to participants

---

---

# 👥 FOR PARTICIPANTS

---

## 🌟 About the Workshop

This workshop helps participants **deploy and explore OpenClaw** using the Vultr Marketplace.  
Whether you're new to cloud-native or expanding your skills, this guided session takes you from **setup to live deployment** in under an hour.

<table>
<tr>
<td>🏗️ <strong>Deploy</strong></td>
<td>OpenClaw on Vultr Marketplace from scratch</td>
</tr>
<tr>
<td>🔧 <strong>Configure</strong></td>
<td>A production-ready cloud environment</td>
</tr>
<tr>
<td>🧭 <strong>Explore</strong></td>
<td>The OpenClaw dashboard and AI gateway ecosystem</td>
</tr>
<tr>
<td>🤝 <strong>Connect</strong></td>
<td>With the Cloud Native Pune community</td>
</tr>
</table>

---

## 🎯 What You'll Learn

By the end of this session, you will be able to:

- ✅ Deploy OpenClaw via Vultr Marketplace
- ✅ Understand the OpenClaw ecosystem and dashboard
- ✅ Configure a development-ready cloud environment
- ✅ Apply cloud-native deployment best practices
- ✅ Work with containers and cloud deployment concepts
- ✅ Engage with the open-source community

---

## ⚙️ Pre-Workshop Setup

> [!WARNING]
> **Please complete ALL setup steps BEFORE arriving at the venue.**  
> This ensures you can follow along during the hands-on session without delays.

---

### 📂 Required Accounts

Create accounts on the following platforms before the event:

| Platform | Link | Required |
|:---|:---|:---:|
| 🐙 GitHub | [github.com](https://github.com) | ✅ Mandatory |
| ☁️ Vultr | [vultr.com](https://www.vultr.com) | ✅ Mandatory |
| 🐳 Docker Hub | [hub.docker.com](https://hub.docker.com) | ⚡ Optional |

---

### 💻 Required Software

#### 1. 🟢 Node.js (v24 recommended, v22.14+ supported)

> OpenClaw requires Node.js. This is the most important dependency.

Download → [nodejs.org](https://nodejs.org)

```bash
# Check your Node version:
node --version
# Expected: v22.14.0 or above (v24.x recommended)

npm --version
# Expected: 10.x or above
```

> 💡 Need help installing Node? See [docs.openclaw.ai/install/node](https://docs.openclaw.ai/install/node)

---

#### 2. 🔀 Git

Download → [git-scm.com](https://git-scm.com)

```bash
# Verify installation:
git --version
# Expected: git version 2.x.x
```

---

#### 3. 🐳 Docker Desktop

Download → [docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

```bash
# Verify installation:
docker --version
# Expected: Docker version 24.x.x or above

# Test Docker is running:
docker run hello-world
# Expected: "Hello from Docker!" message
```

---

#### 4. 🖥️ VS Code

Download → [code.visualstudio.com](https://code.visualstudio.com)

**Recommended Extensions:**

| Extension | Purpose |
|:---|:---|
| 🐳 Docker | Container management & visualization |
| 📄 YAML | Config file syntax support |
| ☸️ Kubernetes | K8s manifest support |
| 🤖 GitHub Copilot | AI code assistance *(optional)* |

---

### 🖥️ System Requirements

| Requirement | Minimum |
|:---|:---|
| 💾 RAM | 8 GB |
| 💿 Free Storage | 10 GB+ |
| 🌐 Internet | Stable broadband connection |
| 🔋 Battery | Fully charged before arriving |
| 🌍 Browser | Latest Chrome / Firefox / Edge |

> **Windows users:** Both native Windows and WSL2 are supported. WSL2 is more stable and recommended. See [docs.openclaw.ai/platforms/windows](https://docs.openclaw.ai/platforms/windows)

---

## 🚀 OpenClaw Setup

Follow these steps to install and verify OpenClaw before the workshop.

### Step 1 — Install OpenClaw

**macOS / Linux:**
```bash
curl -fsSL https://openclaw.ai/install.sh | bash
```

**Windows (PowerShell):**
```powershell
iwr -useb https://openclaw.ai/install.ps1 | iex
```

> Other install methods (Docker, Nix, npm): [docs.openclaw.ai/install](https://docs.openclaw.ai/install)

---

### Step 2 — Run Onboarding

```bash
openclaw onboard --install-daemon
```

> The wizard walks you through choosing a model provider, setting an API key, and configuring the Gateway. Takes about 2 minutes.

---

### Step 3 — Verify the Gateway is Running

```bash
openclaw gateway status
# Expected: Gateway listening on port 18789
```

---

### Step 4 — Open the Dashboard

```bash
openclaw dashboard
# This opens the Control UI in your browser.
# If it loads, everything is working! ✅
```

---

### Step 5 — Send Your First Message

Type a message in the Control UI chat — you should get an AI reply. You're ready for the workshop! 🎉

---

### Vultr Marketplace Deployment (During Workshop)

During the session, participants will:

1. 🌐 Access the [Vultr Marketplace — OpenClaw](https://www.vultr.com/marketplace/apps/openclaw/#getting-started)
2. 🚀 Deploy the OpenClaw image on a Vultr instance
3. ⚙️ Configure the server instance
4. 📊 Complete onboarding and access the dashboard
5. 🔍 Explore the deployment architecture with the mentor

---

## 🗓️ Workshop Flow

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🟦  INTRODUCTION         ~10 min
                           Cloud-native concepts
                           OpenClaw overview · Vultr intro
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
           ↓
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🟧  HANDS-ON DEPLOYMENT  ~25 min
                           Deploy OpenClaw on Vultr
                           Environment config · Dashboard
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
           ↓
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🟩  GUIDED EXPLORATION   ~15 min
                           Project walkthrough
                           Usage examples · Best practices
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
           ↓
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  🟪  Q&A + NETWORKING     ~10 min
                           Open discussion · Community
                           Troubleshooting assistance
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 📁 Project Structure

```
cloud-native-day/
│
├── 📂 openclaw/          # OpenClaw configs and setup files
├── 📂 docker/            # Dockerfiles and compose files
├── 📂 deployment/        # Cloud deployment manifests
├── 📂 kubernetes/        # K8s configs (optional advanced)
└── 📂 notes/             # Your personal workshop notes
```

---

## 🔐 Security Best Practices

> [!CAUTION]
> Follow these practices throughout the workshop and beyond.

- 🔒 Never expose deployments publicly without authentication
- 🔑 Use strong passwords and manage API keys securely
- 🚫 Do not share credentials or screenshots containing tokens/keys
- 🛡️ Follow responsible cloud security practices at all times
- 👁️ Avoid running unauthorized scripts or tools on shared environments

---

## 🛠️ Troubleshooting

Having setup issues? Here's how to get help:

| Situation | Action |
|:---|:---|
| 🐛 Installation error | Arrive early — mentors assist before the session starts |
| 📋 Need debugging help | Keep your logs/screenshots ready to share |
| ❓ Node.js issues | Check [docs.openclaw.ai/install/node](https://docs.openclaw.ai/install/node) |
| 🪟 Windows issues | Check [docs.openclaw.ai/platforms/windows](https://docs.openclaw.ai/platforms/windows) |
| ❓ General questions | Reach out to mentors or workshop volunteers on-site |

---

## 🤝 Code of Conduct

All participants are expected to maintain a **welcoming, inclusive, and respectful** environment.

| ✅ Do | ❌ Don't |
|:---|:---|
| Be respectful to everyone | Harass or discriminate |
| Participate actively | Disrupt the session |
| Help fellow participants | Share others' credentials |
| Keep devices on silent | Run unauthorized tools |
| Follow mentor instructions | Expose credentials publicly |

> **Harassment, discrimination, or disruptive behavior will not be tolerated.**

---

## 🔗 Important Links

| 🔖 Resource | 🌐 URL |
|:---|:---|
| Vultr Marketplace — OpenClaw | [vultr.com/marketplace/apps/openclaw](https://www.vultr.com/marketplace/apps/openclaw/#getting-started) |
| OpenClaw Documentation | [docs.openclaw.ai/start/getting-started](https://docs.openclaw.ai/start/getting-started) |
| OpenClaw Install Guide | [docs.openclaw.ai/install](https://docs.openclaw.ai/install) |
| OpenClaw Windows Setup | [docs.openclaw.ai/platforms/windows](https://docs.openclaw.ai/platforms/windows) |
| Full Docs Index | [docs.openclaw.ai/llms.txt](https://docs.openclaw.ai/llms.txt) |

---

## 🌐 Community

Cloud Native Day is about more than just tech — it's about **building a strong developer community!**

- 🤝 Connect with fellow developers at the event
- 📢 Share your learnings on LinkedIn with **#CloudNativeDay2026**
- 🌱 Contribute to open-source projects
- 🚀 Keep exploring cloud-native technologies

---

<div align="center">

<br/>

**Cloud Native Pune &nbsp;×&nbsp; Docker Hub Pune**

<img src="https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/For-Developers-0078FF?style=for-the-badge&logo=github&logoColor=white" />

<br/><br/>

*Happy Learning &nbsp;🚀*

</div>
