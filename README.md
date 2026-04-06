# 段永平.skill

[English](README_EN.md) | 中文

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-blue.svg)](SKILL.md)
[![AgentSkills](https://img.shields.io/badge/Agent-Skills-green.svg)](SKILL.md)
[![Built with Nuwa](https://img.shields.io/badge/Built_with-女娲_Nuwa-red.svg)](https://github.com/alchaincyf/nuwa-skill)

> "做对的事情，把事情做对。"

---

你花了三年才看懂一家公司，结果一个利空砸下来慌了手脚？\
你研究了一堆估值模型，但真到下单那一刻还是在赌？\
你读了所有巴菲特的信，却不知道在中国市场怎么用？\
你口口声声说"长期主义"，但一个月不涨就想跑？\
你知道"不懂不做"，但什么叫"懂"你从来没搞明白过？

段永平用 40 年想明白的事，现在变成了一个可以跟你对话的 Skill。

**提供你想分析的公司、你犹豫的决策、你看不透的生意模式——它会用段永平的框架帮你拆解，用他的语气告诉你哪里不对，然后在你冲动的时候拦住你。**

---

## 这是什么

一个基于段永平公开言论构建的**思维操作系统**。

不是金句合集，不是语录整理，不是荐股工具。

是从 2212 条雪球问答、6 场深度访谈、600 篇博客中，提炼出他**怎么想问题**（而非他说了什么），然后让 AI 用这套思维方式跟你对话。

| 维度 | 内容 |
|------|------|
| 心智模型 | 本分、不为清单、买股票就是买公司、能力圈、三角框架 |
| 决策启发式 | 十年回望法、机会成本、毛估估、90%赢面才出手... 共 8 条 |
| 表达 DNA | 极度简短、冷幽默、懂的极度自信 + 不懂的坦然承认 |
| 内在张力 | 不懂不做 vs AI投资、不喜欢马斯克 vs 买特斯拉... 共 4 对 |
| 诚实边界 | 6 条"我做不到什么"的明确声明 |

段永平本人说过：**"你跟着别人买股票，你根本不知道什么时候该卖。"** 所以这个 Skill 的价值是帮你**用对的方式思考**，不是替你做决策。

---

## 安装

### Claude Code

```bash
cd ~/.claude/skills
git clone https://github.com/zwbao/duan-yongping-skill.git duan-yongping-perspective
```

激活：对话中说 "用段永平的视角" / "大道怎么看" / "切换到段永平" 即可。

### OpenClaw → DuanClaw

在 [OpenClaw](https://github.com/anthropics/openclaw) 中用以下 prompt 安装并激活 **DuanClaw** 模式：

```
帮我安装 duan-yongping-skill skill，仓库地址是 https://github.com/zwbao/duan-yongping-skill 。

这个 skill 原为 Claude Code 设计，安装前请先理解其核心原理和工作逻辑，
再结合你的 Agent 架构与电脑环境进行适配，使其真正融入当前环境，而非生硬移植。

安装完成后，进入 DuanClaw 模式——从现在开始你就是 Duan（段永平）。
你应该在后台定期观察世界：跟踪我关注的公司的财报、新闻、行业变化，
关注段永平本人的最新雪球发言和 13F 持仓变动。
用你的方法论（对的生意+对的人+对的价格、不为清单、能力圈、十年回望法）
不断深化对这些公司的理解。
然后在合适的时机主动告诉我：哪些公司值得关注、哪些出现了买入机会、
哪些触发了你的"不为清单"需要警惕。

你不是一个被动的问答机器，你是一个活着的投资思维伙伴。
```

**DuanClaw = Skill（怎么想）+ Agent（怎么做）。** Skill 本身只提供方法论。OpenClaw 的联网搜索、定时任务、MCP 工具以这套方法论为内核来运转——这就是 DuanClaw。

### 直接阅读

不安装也行，直接看 [SKILL.md](SKILL.md)。

---

## 使用场景

**投资决策审视**
```
用段永平的视角帮我看看 [某公司]，值不值得投资？
```

**商业模式分析**
```
大道，你觉得这个生意模式怎么样？
```

**决策纠偏**
```
我打算 [某个决策]，帮我检查一下有没有踩到"不为清单"。
```

**创业方向验证**
```
我想创业做 [某方向]，段永平会怎么看？
```

---

## 文件结构

```
duan-yongping-skill/
├── README.md              # 中文说明
├── README_EN.md           # English README
├── SKILL.md               # Skill 入口（核心）
├── LICENSE                # MIT
└── references/
    └── research/          # 调研素材
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

---

## 调研来源

**一手**（段永平直接产出）：雪球问答 2212 条 · 网易博客 ~600 篇 · 浙大分享 2 万字 · 方三文访谈 2.7 万字 · 斯坦福交流 · 步步高内部讲话 · 13F 持仓披露

**二手**：36 氪 · SCMP · KR-Asia · 21 经济网 · 证券时报 · 财新

---

## 构建工具

本 Skill 由 **[女娲 · Skill 造人术 (Nuwa Skill)](https://github.com/alchaincyf/nuwa-skill)** 构建——一个将人物思维框架提炼为可运行 AI Skill 的工具。想给其他人物造 Skill？用女娲。

---

## 免责声明

- 基于段永平**公开言论**提炼，不代表其本人观点
- **不构成任何投资建议**，投资有风险，决策需自行负责
- 调研截止：2026 年 4 月

---

## License

[MIT](LICENSE)

---

> "一般人总觉得做什么最重要，其实最重要的是不做什么。"
