<div align="center">

<img src="https://img.shields.io/badge/Powered%20by-Vultr-007BFC?style=for-the-badge&logo=vultr&logoColor=white" />
<img src="https://img.shields.io/badge/CNCF-Community%20Event-00AEEF?style=for-the-badge&logo=cncf&logoColor=white" />
<img src="https://img.shields.io/badge/🔒%20Invite%20Only-Event-red?style=for-the-badge" />

<br/><br/>

# ☁️ Cloud Native Day Pune 2026
**In collaboration with Vultr**

![Date](https://img.shields.io/badge/📅%20Date-31%20May%202026-0C447C?style=flat-square)
![Time](https://img.shields.io/badge/🕙%20Time-09:30%20AM%20–%2003:00%20PM%20IST-0C447C?style=flat-square)
![Venue](https://img.shields.io/badge/📍%20Venue-JW%20Marriott%20Pune-0C447C?style=flat-square)

### 🚀 [REGISTER HERE →](https://forms.gle/XfaczLoLoEu71AT78)

> **Invite-only.** Confirmations sent by **20 May 2026**.

</div>

---

## 📋 Table of Contents

- [About the Event](#-about-the-event)
- [Agenda](#️-agenda)
- [Organizer Checklist](#-organizer-checklist)
- [Pre-Workshop Setup](#️-pre-workshop-setup)
- [Deploying OpenClaw on Vultr](#-deploying-openclaw-on-vultr)
- [Using OpenClaw](#-using-openclaw)
- [Troubleshooting](#️-troubleshooting)
- [Code of Conduct](#-code-of-conduct)
- [Important Links](#-important-links)

---

## 🌟 About the Event

**Cloud Native Day Pune 2026** is organised by Cloud Native Pune (CNCF Community Group) in collaboration with **Vultr**.

Full-day in-person conference for developers, SREs, platform engineers, and cloud enthusiasts — technical talks, hands-on workshop, and lightning sessions.

> **Invite-only.** Register → team reviews → confirmation by **20 May 2026**. Only confirmed attendees receive entry details.

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

> Agenda updated as confirmations come in. See [event page](https://ocgroups.dev/cncf/group/p5hsakp/event/xavkwq6).

---

## ✅ Organizer Checklist

### Tech & Connectivity
- [ ] WiFi access confirmed for participants
- [ ] Backup hotspot ready (2 preferred — different carriers)
- [ ] Projector working and tested
- [ ] HDMI / USB-C / VGA adapters available
- [ ] Power strips / extension boards at each table

### Venue & Logistics
- [ ] Water bottles / refreshments confirmed with venue
- [ ] Check-in desk set up — volunteer assigned for entry management
- [ ] Printed attendee list ready for entry verification (no walk-ins)
- [ ] Volunteer name tags / badges prepared
- [ ] Printed materials / banners in place

### Post-Event
- [ ] Volunteer assigned to take photos throughout the day
- [ ] Volunteer assigned to post on LinkedIn live during the event

---

## ⚙️ Pre-Workshop Setup

> Complete before **31 May**. Only a Vultr account is needed — no local installs required.

### Required Account

| Platform | Link | Required |
|:---|:---|:---:|
| Vultr | [vultr.com](https://www.vultr.com) | ✅ |

> Create your Vultr account before arriving. That's all you need.

---

## 🚀 Deploying OpenClaw on Vultr

> This is done **during the workshop**. Steps below are for reference.

**Step 1 — Log in to Vultr**

Go to [console.vultr.com](https://console.vultr.com) and log in.

---

**Step 2 — Go to Marketplace**

- Click **"Deploy"** in the top nav → Select **"Instances"**
- Choose the **"Marketplace"** tab
- Search for **OpenClaw** and select it

---

**Step 3 — Configure your instance**

- Choose a server location
- Select a plan *(minimum: 1 CPU, 1024MB RAM — $6/mo)*
- Click **Deploy Now**

---

**Step 4 — Wait for deployment**

Allow up to **5 minutes** for the instance to become available.

---

**Step 5 — Access OpenClaw**

Once deployed, open your instance link and log in:

```
Username: clawmine
Password: (shown on your Vultr instance page)
```

---

**Step 6 — Access Code Server** *(Browser-based VS Code)*

A browser-based VS Code with terminal is included. Launch it from your instance page.

```
Password: (shown on your Vultr instance page)
```

---

## 💬 Using OpenClaw

### Essential Chat Commands

| Command | Use |
|:---|:---|
| `/new` | Start a fresh session |
| `/compact` | Summarize old messages to free up context |
| `/status` | Check session info, model, token usage |
| `/help` | See all available commands |
| `stop` | Abort current response mid-stream |

### Installing Skills from ClawHub

```bash
/skill clawhub search "<query>"   # Search for skills
/skill clawhub install <name>     # Install a skill
/skill clawhub list               # List installed skills
/skill clawhub update --all       # Update all skills
```

### Restarting the Gateway

If OpenClaw becomes unresponsive:

```bash
openclaw gateway --force
```

> Run this in the Code Server terminal or via SSH.

---

## 🛠️ Troubleshooting

| Issue | Action |
|:---|:---|
| Instance not ready | Wait up to 5 minutes after deploy |
| Can't log in | Check credentials on your Vultr instance page |
| Gateway unresponsive | Run `openclaw gateway --force` in terminal |
| General setup issues | Arrive at 09:30 AM — mentors available |

---

## 🤝 Code of Conduct

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
| ☁️ Vultr Console | [console.vultr.com](https://console.vultr.com) |
| 🛒 OpenClaw on Vultr | [vultr.com/marketplace/apps/openclaw](https://www.vultr.com/marketplace/apps/openclaw/#getting-started) |

---

<div align="center">

Organised by **Cloud Native Pune** · Powered by **Vultr**

<img src="https://img.shields.io/badge/Powered%20by-Vultr-007BFC?style=for-the-badge&logo=vultr&logoColor=white"/>

</div>
