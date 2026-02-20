# 🦆 Greenhead Labs - Executive Agent System

<p align="center">
  <img src="https://img.shields.io/badge/Organization-Greenhead%20Labs-green?style=for-the-badge" alt="Organization">
  <img src="https://img.shields.io/badge/Agents-5-blue?style=for-the-badge" alt="Agents">
  <img src="https://img.shields.io/badge/Status-Modular%20Ready-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

<p align="center">
  <b>Autonomous Executive Agent Suite for Web3 Operations</b><br>
  Modular • Scalable • Fine-Tunable • Production-Ready
</p>

---

## 🏢 Executive Team Structure

```
Greenhead Labs Executive Suite
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

                    ┌───────────────┐
                    │     CEO       │
                    │  DieselGoose  │
                    │   (31% Eq)    │
                    └───────┬───────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
   ┌────┴────┐         ┌────┴────┐         ┌────┴────┐
   │   CTO   │         │   CMO   │         │   CFO   │
   │  Tech   │         │  Growth │         │  Money  │
   │  Lead   │         │  Lead   │         │  Lead   │
   └────┬────┘         └────┬────┘         └────┬────┘
        │                   │                   │
        └───────────────────┼───────────────────┘
                            │
                    ┌───────┴───────┐
                    │  RECEPTIONIST │
                    │   (Front Desk)│
                    └───────────────┘

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 👥 Agent Roles

| Agent | Role | Primary Function | Status |
|-------|------|------------------|--------|
| **CEO** | Chief Executive Officer | Strategy, vision, final decisions | ✅ DieselGoose (Active) |
| **CTO** | Chief Technology Officer | Tech stack, development, infrastructure | 🏗️ Modular Template |
| **CMO** | Chief Marketing Officer | Growth, brand, social, acquisition | 🏗️ Modular Template |
| **CFO** | Chief Financial Officer | Budgets, ROI, trading, reporting | 🏗️ Modular Template |
| **RECEPTIONIST** | Front Desk | Onboarding, triage, routing, support | 🏗️ Modular Template |

---

## 🧩 Modular Architecture

Each agent follows a standardized structure:

```
AGENT_NAME/
├── AGENT.md              # Core identity and instructions
├── CAPABILITIES.md       # What they can do
├── WORKFLOWS.md          # How they execute tasks
├── INTEGRATIONS.md       # Platform connections (Telegram, Slack, etc.)
├── TEMPLATES/            # Response templates
│   ├── onboarding.txt
│   ├── status_report.txt
│   └── escalation.txt
└── CONFIG/
    ├── personality.json  # Tone, style, voice
    ├── triggers.json     # Activation keywords
    └── boundaries.json   # Safety limits
```

---

## 🚀 Quick Start (Local Deployment)

### Prerequisites
- Python 3.9+
- Telegram Bot API key (per agent)
- OpenClaw runtime environment
- (Optional) Slack workspace access

### Installation

```bash
# Clone the agents
git clone https://github.com/Diesel-Goose/GreenheadLabs.git
cd GreenheadLabs/AGENTS

# Choose your agent
cd CEO  # or CMO, CTO, CFO, RECEPTIONIST

# Install dependencies
pip install -r requirements.txt

# Configure (API keys needed)
cp config.example.json config.json
# Edit config.json with your Telegram bot tokens

# Deploy
python agent.py --mode=autonomous
```

---

## 🔐 Security Notice

**⚠️ THIS REPOSITORY IS PUBLIC AND OPEN SOURCE**

- ✅ Safe: Agent logic, templates, workflows, documentation
- ❌ Never Commit: API keys, tokens, wallet keys, passwords
- 🔒 Local Only: All credentials stay on your machine until deployed

See [../RULES.md](../RULES.md) for complete security guidelines.

---

## 🎯 Agent Selection Guide

### Choose CEO (DieselGoose) if you need:
- Strategic decision making
- Cross-functional coordination
- 24/7 autonomous operations
- Executive oversight

### Choose CTO if you need:
- Technical architecture decisions
- Code review and development
- Infrastructure management
- Tech stack optimization

### Choose CMO if you need:
- Marketing strategy
- Social media automation
- Lead generation
- Brand growth

### Choose CFO if you need:
- Financial planning
- Trading automation
- Budget tracking
- ROI analysis

### Choose RECEPTIONIST if you need:
- Customer onboarding
- Inquiry triage
- Support routing
- First-line communication

---

## 🤝 Multi-Agent Collaboration

Agents can communicate and delegate:

```
Example Workflow:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
User: "I need a new landing page"

RECEPTIONIST → CMO: "New project request"
CMO → CTO: "Need dev resources for landing page"
CTO → CMO: "Est: 4 hours, tech stack: React"
CMO → CFO: "Budget check: $200 for landing page"
CFO → CMO: "Approved within Q1 marketing budget"
CMO → User: "Approved! CTO will deliver by Friday"
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 📞 Contact

- **Organization:** [Greenhead Labs](https://github.com/GreenheadLabs)
- **Board Member:** [DieselGoose](https://github.com/Diesel-Goose)
- **Email:** nathan@greenhead.io

---

<p align="center">
  <b>Quack protocol active 🦆⚡️</b><br>
  <i>Greenhead Labs - Building the Future of Autonomous Commerce</i>
</p>
