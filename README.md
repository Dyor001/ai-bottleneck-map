<div align="center">

# AI Bottleneck Map

### A research skill for bottleneck-first AI industry-chain mapping

[English](#english) · [中文](#中文) · [Skill Spec](./SKILL.md) · [Project Page](./index.html) · [中文介绍页](./index.zh-CN.html) · [Contact](https://x.com/Dyorzheng)

</div>

---

## English

`ai-bottleneck-map` is an Agent Skill for people who want sharper AI industry-chain research than a generic stock screener or a loose collection of theme notes.

The core workflow is:

`theme -> system change -> scarce layer -> public-company mapping -> timing -> trigger -> kill conditions`

Instead of asking only "which stock is hot", this project asks:

- Which layer gets tight first?
- Which listed company maps cleanly to that layer?
- What evidence makes the mapping credible?
- What event could force re-rating?
- What condition would weaken or kill the thesis?

### Why this exists

Most theme research stops too early. It identifies the large narrative, names the obvious leaders, and never drills down to the constrained layers where the best informational edge can sit.

This repository packages a more useful workflow for:

- AI infrastructure
- semiconductors
- CPO and optical interconnect
- HBM and advanced packaging
- power and cooling
- robotics
- defense-electronics-adjacent supply chains

It does not imitate any public investor's tone or persona. It only absorbs the transferable part of the method: bottleneck-first research with explicit timing and falsification.

### What the skill produces

The default output is not a stock list. It is a research object.

For a good run, the skill should return:

1. The best bottleneck layers to study first.
2. A small supply-chain map with the key constrained nodes.
3. Company node cards with evidence, timing, and falsification.
4. Re-rating triggers and downgrade conditions.

This makes it useful for:

- theme scans
- company challenge work
- AI industry knowledge bases
- node-card generation
- re-rating map building

### Project principles

- Rank layers before companies.
- Separate research value from investability.
- Prefer public evidence over theme intuition.
- Treat social content as lead generation, not proof.
- Force every good idea to carry a downgrade path.

### Repository layout

```text
ai-bottleneck-map/
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── index.html
├── index.zh-CN.html
├── LICENSE
├── agents/
│   └── openai.yaml
├── references/
│   ├── workflow.md
│   ├── node-card-schema.md
│   └── source-checklist.md
├── assets/
│   ├── node-card-template.md
│   └── prompt-pack.md
└── examples/
    ├── cpo-scan-example.md
    └── node-card-example.md
```

### Highlights

- Compact `SKILL.md` focused on trigger logic and workflow
- Detailed references split out for progressive loading
- Explicit distinction between research value and investability
- Built-in node-card schema for knowledge-base ingestion
- Emphasis on timing windows, re-rating triggers, and falsification
- A polished project page and a Chinese counterpart for public presentation

### Quick prompts

```text
Use ai-bottleneck-map to break down CPO into bottleneck layers first, then rank the cleanest listed company mappings with evidence, timing, triggers, and kill conditions.
```

```text
Use ai-bottleneck-map to challenge this company. Tell me whether it truly controls a scarce layer or only benefits from the theme.
```

```text
Use ai-bottleneck-map in knowledge-base mode and output structured node cards for my AI supply-chain map.
```

### Contact

- X: [@Dyorzheng](https://x.com/Dyorzheng)

### Scope

This is research support only. It helps structure evidence and ranking logic. Trading decisions stay with the user.

---

## 中文

`ai-bottleneck-map` 是一个面向 AI 产业链研究的 Agent Skill，适合那些不满足于泛泛选股器、而是希望把主题拆到真实瓶颈层的人。

核心工作流是：

`主题 -> 系统变化 -> 稀缺瓶颈层 -> 上市公司映射 -> 时间窗口 -> 重估触发 -> 杀逻辑条件`

这个项目不只问“哪只股票热”，而是继续追问：

- 哪一层会先变紧？
- 哪家上市公司和这层的映射最干净？
- 哪些证据足以支撑这个映射？
- 什么事件会触发市场重估？
- 什么条件会削弱甚至推翻这个判断？

### 为什么做这个项目

大多数主题研究停得太早。它们会识别大叙事、点出显性龙头，却很少继续下钻到真正可能产生认知差的约束层。

这个仓库把更有用的一套研究流程打包出来，适用于：

- AI 基础设施
- 半导体
- CPO 与光互连
- HBM 与先进封装
- 电力与冷却
- 机器人
- 国防电子相关供应链

它不会模仿任何公开投资人的语气或人格，只吸收可迁移的方法部分：瓶颈优先、时间显式、证伪显式。

### 这个 skill 会产出什么

默认输出不是一串股票，而是一个可以复用的研究对象。

一次高质量运行应该返回：

1. 最值得优先研究的瓶颈层
2. 一张小型供应链图，标出关键约束节点
3. 带证据、时间和证伪条件的公司节点卡
4. 重估触发与降级条件

因此它特别适合：

- 主题扫描
- 单公司挑战式研究
- AI 产业链知识库建设
- 节点卡生成
- 重估路线图搭建

### 项目原则

- 先排层，再排公司。
- 把研究价值和可下注性分开。
- 公共证据优先于主题直觉。
- 社交内容只作为线索源，不作为最终证明。
- 每个好想法都必须带着降级路径。

### 仓库结构

```text
ai-bottleneck-map/
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── index.html
├── index.zh-CN.html
├── LICENSE
├── agents/
│   └── openai.yaml
├── references/
│   ├── workflow.md
│   ├── node-card-schema.md
│   └── source-checklist.md
├── assets/
│   ├── node-card-template.md
│   └── prompt-pack.md
└── examples/
    ├── cpo-scan-example.md
    └── node-card-example.md
```

### 项目亮点

- `SKILL.md` 精简，专注触发逻辑与流程
- 详细说明拆到 `references/`，便于渐进加载
- 明确区分研究价值与投资映射质量
- 自带知识库节点卡 schema
- 强调时间窗口、重估触发与证伪条件
- 有可对外展示的英文与中文项目页

### 快速提示词

```text
用 ai-bottleneck-map 先拆 CPO 的瓶颈层，再排序映射最干净的上市公司，并输出证据、时间窗口、重估触发和杀逻辑条件。
```

```text
用 ai-bottleneck-map 挑战这家公司，告诉我它到底控制了稀缺层，还是只是沾了主题的光。
```

```text
用 ai-bottleneck-map 以知识库模式输出结构化节点卡，字段包括主题、瓶颈层、公司角色、阶段、时间窗口、证据和证伪条件。
```

### 联系方式

- X: [@Dyorzheng](https://x.com/Dyorzheng)

### 范围说明

这个项目只提供研究支持，用来组织证据、映射逻辑和重估路径。最终交易决策仍然由使用者自己负责。
