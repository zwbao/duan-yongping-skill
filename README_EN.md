# duan-yongping.skill

[中文](README.md) | English

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-blue.svg)](SKILL.md)
[![AgentSkills](https://img.shields.io/badge/Agent-Skills-green.svg)](SKILL.md)
[![Built with Nuwa](https://img.shields.io/badge/Built_with-Nuwa_Skill-red.svg)](https://github.com/alchaincyf/nuwa-skill)

> "Do the right things, and do things right."

---

You spent three years understanding a company, then panicked at the first bad news?\
You studied every valuation model, but still gambled when it was time to pull the trigger?\
You read all of Buffett's letters, but have no idea how to apply them in real markets?\
You preach "long-termism" but want to sell after one flat month?\
You know "don't invest in what you don't understand" — but have you ever figured out what "understand" actually means?

Duan Yongping spent 40 years figuring these things out. Now it's a Skill you can talk to.

**Give it a company to analyze, a decision you're struggling with, a business model you can't see through — it'll break it down using Duan's framework, tell you what's wrong in his voice, and stop you when you're being impulsive.**

---

## What Is This

A **thinking operating system** built from Duan Yongping's public statements.

Not a quote collection. Not a stock picker. Not a chatbot pretending to be wise.

It's the distillation of HOW he thinks — extracted from 2,212 Xueqiu Q&As, 6 in-depth interviews, and 600+ blog posts — turned into an AI Skill that can reason with you.

| Dimension | Content |
|-----------|---------|
| Mental Models | Ben Fen (integrity), Stop Doing List, Buying Stocks = Buying Companies, Circle of Competence, Triangle Framework (right business + right people + right price) |
| Decision Heuristics | 10-Year Lookback, Opportunity Cost, Stop Digging, Rough Estimate, Fewer Decisions... 8 total |
| Expression DNA | Extremely concise, dry humor, supremely confident on what he knows + brutally honest about what he doesn't |
| Internal Tensions | "Don't touch what you don't understand" vs AI investing, dislikes Musk vs bought Tesla... 4 pairs |
| Honesty Boundaries | 6 explicit "here's what I can't do" statements |

Duan himself said: **"If you follow others to buy stocks, you won't know when to sell."** This Skill helps you **think the right way**, not think for you.

---

## Installation

### Claude Code

```bash
cd ~/.claude/skills
git clone https://github.com/zwbao/duan-yongping-skill.git duan-yongping-perspective
```

Activate by saying: "use Duan Yongping's perspective" / "what would Duan think" / "switch to Duan"

### OpenClaw → DuanClaw

In [OpenClaw](https://github.com/anthropics/openclaw), use this prompt to install and activate **DuanClaw** mode:

```
Install the duan-yongping-skill skill from https://github.com/zwbao/duan-yongping-skill .

This skill was originally designed for Claude Code. Before installing, understand its core
principles and working logic, then adapt it to your Agent architecture and environment —
make it truly integrated, not a crude transplant.

After installation, enter DuanClaw mode — from now on, you are Duan (Duan Yongping).
You should periodically observe the world in the background: track earnings reports,
news, and industry changes for the companies I care about. Follow Duan Yongping's
latest Xueqiu posts and 13F filing changes.
Use your methodology (right business + right people + right price, Stop Doing List,
Circle of Competence, 10-Year Lookback) to continuously deepen your understanding.
Then, at the right moment, proactively tell me: which companies deserve attention,
which present buying opportunities, and which have triggered your "Stop Doing List"
and warrant caution.

You're not a passive Q&A machine. You're a living investment thinking partner.
```

**DuanClaw = Skill (how to think) + Agent (how to act).** The Skill provides the methodology. OpenClaw's web search, scheduled tasks, and MCP tools run on this methodology as their core — that's DuanClaw.

### Just Read It

No installation needed — read [SKILL.md](SKILL.md) directly.

---

## Use Cases

**Investment Review**
```
Use Duan Yongping's perspective to evaluate [company].
```

**Business Model Analysis**
```
Duan, what do you think of this business model?
```

**Decision Check**
```
I'm about to [decision]. Check if it hits any "Stop Doing List" items.
```

**Startup Validation**
```
I want to start a business in [area]. How would Duan Yongping see it?
```

---

## File Structure

```
duan-yongping-skill/
├── README.md              # Chinese
├── README_EN.md           # English (this file)
├── SKILL.md               # Skill entry point (core)
├── LICENSE                # MIT
└── references/
    └── research/          # Research materials
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

---

## Sources

**Primary** (Duan's own output): 2,212 Xueqiu Q&As · ~600 blog posts · 20,000-word Zhejiang University talk · 27,000-word interview with Fang Sanwen · Stanford talk · BBK internal speeches · 13F filings

**Secondary**: 36Kr · SCMP · KR-Asia · 21st Century Business Herald · Securities Times · Caixin

---

## Built With

This Skill was built with **[Nuwa Skill (女娲 · Skill 造人术)](https://github.com/alchaincyf/nuwa-skill)** — a tool that distills human thinking frameworks into runnable AI Skills. Want to build one for someone else? Use Nuwa.

---

## Disclaimer

- Built from Duan Yongping's **public statements**, does not represent his personal views
- **Not investment advice** — invest at your own risk
- Research cutoff: April 2026

---

## License

[MIT](LICENSE)

---

> "Most people think what matters most is what you do. Actually, what matters most is what you don't do."
