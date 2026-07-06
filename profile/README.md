
<h1 align="center">Pandemonium</h1>
<p align="center">
  <img src="./assets/pandemonium-banner.png" alt="Pandemonium - The capital of organized chaos">
</p>

<h3 align="center">Automate modern survival. Protect modern living. For time, and all time.</h3>

<br>

<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" height="25" alt="">
</p>

## ⚡ What is this?

<img align="right" width="220" src="./assets/pandemonium-logo.png" alt="Pandemonium logo">

Pandemonium is a modular operating layer for life automation.

A daemon sits at the center.  
Modules orbit it.  
Signals enter.  
Decisions leave.

The system watches schedules, routes, receipts, browser sessions, Discord bridges,
operator surfaces, and the tiny operational details that usually rot into a pile
of scripts named `final-final-real-this-time.js`.

The rule is simple:

**Modules own their domain. The daemon owns the room.**

<br clear="right">

---

## 🕯 Current Vibe

<details open>
<summary>The city is awake</summary>

- One daemon supervises many feature modules.
- Modules advertise APIs, capabilities, status, logs, and hosted sites.
- Cross-module calls go through registered daemon APIs.
- Internet requests are brokered by central Networking.
- Browser/CDP access is daemon-owned and leased.
- The Web UI, TUI, Discord bots, and module sites all expose different windows into the same system.
- Warm daemon restarts preserve expensive modules whenever possible.
- The future mobile collector will add opt-in phone-side signals without becoming the brain.

</details>

<br>

---

## 🧩 Districts

| District | Owns | Mood |
|:---:|:---|:---|
| **Calendar** | Schedule truth, event lookup, time windows | Boring on purpose |
| **Email** | Scoped Gmail search, messages, attachments | Evidence vault |
| **Finance** | Receipts, providers, labels, reconciliation | Money chaos containment |
| **Public Transport** | Routes, favorites, Discord transit UX | Movement layer |
| **Work** | Shift interpretation, commute intent, workpage | Personal policy engine |
| **Yapbridge** | Discord ↔ ChatGPT sync | The yapping conduit |
| **Networking** | HTTP, headers, limits, browser leases | The gatekeeper |
| **Daemon** | Supervision, API registry, auth, TUI/Web UI | The quiet authority |

<br>

---

## 🖥 Surfaces

Pandemonium is meant to be operated from wherever the signal appears.

| Surface | Purpose |
|:---:|:---|
| **Web UI** | Browser dashboard for status, logs, shell calls, and live control |
| **TUI** | Terminal control for SSH, recovery, and low-friction operations |
| **Discord** | Human-facing buttons, prompts, confirmations, and alerts |
| **Module Sites** | Feature dashboards like Work and Finance |
| **Future Mobile Collector** | Opt-in phone-side context, receipts, lightweight signals, and sensor-adjacent data |

The mobile collector is not the brain.  
It is another witness.

<br>

---

## 🔐 Design Rules

<details open>
<summary>How the chaos stays organized</summary>

- Feature code lives under `src/modules/<module>/`.
- Module tests live with the module.
- Modules do not import each other.
- Cross-module behavior goes through the daemon API broker.
- Secrets belong to the module that uses them.
- Shared runtime code stays generic and boring.
- Hosted web pages are module-owned sites.
- The daemon discovers, supervises, authenticates, and brokers.
- Restarts should be targeted because module startup is expensive.
- If something is dangerous, it should at least be observable.

</details>

<br>

---

## 🛠 Built For

<div align="center">

| Local Reality | Remote Control | Future Signals |
|:---:|:---:|:---:|
| Discord bots | Web UI | Mobile collector |
| Calendar events | TUI | Device-side context |
| Receipts | Module APIs | More data streams |
| Transit plans | Warm deploys | Better automation |
| Browser sessions | Scoped auth | Less manual panic |

</div>

<br>

---

## 📚 For Agents

If you are an agent entering the city, read before touching things.

| Document | Why |
|:---|:---|
| [Agent Operations Handbook](https://github.com/helpless-kitten/Pandemonium/blob/master/docs/agent-operations-handbook.md) | How to work, test, deploy, and avoid breaking production |
| [Agent Coordination](https://github.com/helpless-kitten/Pandemonium/blob/master/docs/agent-coordination.md) | How multiple agents avoid collisions |
| [Module Protocol](https://github.com/helpless-kitten/Pandemonium/blob/master/docs/module-protocol.md) | API discovery, capabilities, status, and consumes |
| [Daemon Modules](https://github.com/helpless-kitten/Pandemonium/blob/master/docs/daemon-modules.md) | Module descriptors, lifecycle, reloads, and supervision |

The daemon is the authority.  
The module boundary is not decorative.

<br>

---

## 🏛 Repository

<div align="center">

  <a href="https://github.com/helpless-kitten/Pandemonium">
    <img src="https://img.shields.io/badge/Open%20the%20Core-Pandemonium-ff4fb8?style=for-the-badge">
  </a>

</div>

<br>

<div align="center">
  <a href="https://github.com/helpless-kitten/Pandemonium">
    <img src="./assets/pandemonium-logo.png" width="180" alt="Pandemonium logo">
  </a>
</div>

<br>

---

## 🖤 Operating Principle

Pandemonium is what happens when automation stops being a pile of scripts and
starts becoming a governed system.

Small modules.  Explicit contracts.  Scoped secrets.  Visible state.  No silent cross-talk.

<div align="center">
  <img style="margin: 10px" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" height="25" alt="">
</div>

<div align="center">
  <sub>One system. All your chaos. Perfectly orchestrated.</sub>
</div>
