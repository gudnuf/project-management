# Cashu Project Management

> Strategic initiatives and cross-repository coordination for the Cashu ecosystem

## 🎯 Purpose

This repository serves as the central hub for:
- Strategic initiative tracking
- Cross-repository coordination
- Ecosystem health monitoring
- Long-term roadmap planning

**Important**: This repo contains NO CODE - only project management issues and documentation.

## 📊 How It Works

### We Track Goals, Not Code
Instead of cluttering implementation repos with project management issues, we:
1. Create all initiative/epic/task issues HERE
2. Link to actual PRs/issues in implementation repos
3. Keep implementation repos focused on code

### Issue Types

| Label | Purpose | Example |
|-------|---------|----------|
| `initiative` | Big picture goals | "Enable onchain Bitcoin payments" |
| `epic` | Major feature sets | "Implement Bitcoin backend for all libraries" |
| `task` | Concrete work items | "Research Bitcoin Core RPC requirements" |
| `signal` | Ecosystem metrics | "Track CDK version adoption" |

## 🏗️ Structure

```
project-management/
├── initiatives/           # Strategic goal documentation
│   ├── onchain.md
│   ├── offline.md
│   └── scaling.md
├── signals/              # Ecosystem metrics we track
│   ├── mint-versions.md
│   └── wallet-adoption.md
└── .github/
    ├── ISSUE_TEMPLATE/   # Templates for different issue types
    └── workflows/        # Automation scripts
```

## 🎯 Active Initiatives

### [Onchain Bitcoin Payments](initiatives/onchain.md) - 15% Ready
Enable users to send and receive onchain Bitcoin through Cashu

**Current Blockers:**
- NUT-26 specification approval
- Production Bitcoin backend implementation
- Wallet UI patterns for confirmations

**Tracking**: [Issue #1](#)

---

### [Offline Payment Support](initiatives/offline.md) - 40% Ready
Allow users to receive ecash while offline

**Current Blockers:**
- P2PK implementation in wallets
- Sync UX patterns
- Network partition testing

**Tracking**: [Issue #2](#)

---

### [1000 Active Mints](initiatives/scaling.md) - 5% Ready
Scale ecosystem to 1000+ production mints

**Current Blockers:**
- One-click deployment solution
- Monitoring infrastructure
- Operator documentation

**Tracking**: [Issue #3](#)

## 📋 Using This Repo

### For Project Managers

1. **Create initiatives** for big goals using the initiative template
2. **Track signals** to monitor ecosystem health
3. **Break down work** into epics and tasks
4. **Link to implementation** - reference PRs/issues in other repos

### For Developers

1. **Check active tasks** to find work that needs doing
2. **Update status** on tasks you're working on
3. **Link your PRs** to relevant tasks here
4. **Report blockers** so PMs can help unblock

### For Mint Operators & Users

1. **Watch initiatives** to see what's coming
2. **Comment on issues** with feedback and requirements
3. **Track readiness** to know when features are production-ready

## 🏷️ Label Structure

### Goal Labels
- `goal:onchain` - Related to onchain payments
- `goal:offline` - Related to offline capability
- `goal:scaling` - Related to ecosystem growth
- `goal:ux` - Related to user experience

### Status Labels
- `status:blocked` - Waiting on something
- `status:active` - Being worked on
- `status:ready` - Ready to implement
- `status:needs-owner` - Needs someone to drive

### Priority Labels
- `P0` - Drop everything
- `P1` - This sprint
- `P2` - Next sprint
- `P3` - Backlog

## 🔄 Weekly Process

### Monday: Review & Plan
- Update initiative readiness scores
- Identify new blockers
- Plan week's priorities

### Friday: Summarize & Communicate
- Post weekly update
- Celebrate completed work
- Share with community

## 🔗 Quick Links

### Core Repos
- [nuts](https://github.com/cashubtc/nuts) - Specifications
- [cdk](https://github.com/cashubtc/cdk) - Rust implementation
- [cashu-ts](https://github.com/cashubtc/cashu-ts) - TypeScript
- [nutshell](https://github.com/cashubtc/nutshell) - Python

### Communication
- Matrix: #cashu:matrix.org
- Telegram: @CashuBTC
- GitHub Discussions: [Here](#)

## 🤖 For AI Agents

This repo is designed to be AI-friendly:
- Structured issue templates with consistent fields
- Machine-readable status tracking
- Clear linking between issues and external PRs
- Weekly summaries in predictable format

Query our GraphQL API to get current status of any initiative.

---

*Remember: This repo is for coordination only. Actual code changes happen in implementation repositories.*