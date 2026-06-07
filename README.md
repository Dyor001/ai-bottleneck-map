<div align="center">

# AI Bottleneck Map

### A research skill for turning AI narratives into bottleneck layers, node cards, and re-rating maps

[English](./README.md) · [中文](./README.zh-CN.md) · [Project Page](./index.html) · [中文介绍页](./index.zh-CN.html) · [Skill Spec](./SKILL.md) · [Examples](./examples/cpo-scan-example.md) · [Contact](https://x.com/Dyorzheng)

</div>

`ai-bottleneck-map` is an Agent Skill for people who want sharper AI industry-chain research than a generic stock screener or a loose collection of theme notes.

The core workflow is:

`theme -> system change -> scarce layer -> public-company mapping -> timing -> trigger -> kill conditions`

Instead of asking only "which stock is hot", this project asks:

- Which layer gets tight first?
- Which listed company maps cleanly to that layer?
- What evidence makes the mapping credible?
- What event could force re-rating?
- What condition would weaken or kill the thesis?

## Why this exists

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

## What the skill produces

The default output is not a stock list. It is a research object.

For a good run, the skill should return:

1. The best bottleneck layers to study first.
2. A small supply-chain map with the key constrained nodes.
3. Company node cards with evidence, timing, and falsification.
4. Re-rating triggers and downgrade conditions.

That makes it useful for:

- theme scans
- company challenge work
- AI industry knowledge bases
- node-card generation
- re-rating map building

## Project principles

- Rank layers before companies.
- Separate research value from investability.
- Prefer public evidence over theme intuition.
- Treat social content as lead generation, not proof.
- Force every good idea to carry a downgrade path.

## Repository layout

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

## Highlights

- Compact `SKILL.md` focused on trigger logic and workflow.
- Detailed references split out for progressive loading.
- Explicit distinction between research value and investability.
- Built-in node-card schema for knowledge-base ingestion.
- Emphasis on timing windows, re-rating triggers, and falsification.
- A clean landing page you can show publicly.

## Showcase files

- `index.html`: polished English landing page for local viewing or GitHub Pages
- `index.zh-CN.html`: polished Chinese landing page
- `README.md`: public repository overview in English
- `README.zh-CN.md`: public repository overview in Chinese
- `SKILL.md`: the actual skill trigger and behavior contract
- `examples/`: small examples for scans and node-card output
- `references/`: the deeper workflow, schema, and source-check guidance

## Quick prompts

```text
Use ai-bottleneck-map to break down CPO into bottleneck layers first, then rank the cleanest listed company mappings with evidence, timing, triggers, and kill conditions.
```

```text
Use ai-bottleneck-map to challenge this company. Tell me whether it truly controls a scarce layer or only benefits from the theme.
```

```text
Use ai-bottleneck-map in knowledge-base mode and output structured node cards for my AI supply-chain map.
```

## Public page

Open `index.html` to view the standalone project page locally. It is intended to be suitable for GitHub Pages or for simple repository showcase use.

## Contact

If you want to discuss the method, suggest improvements, or follow the project, reach out here:

- X: [@Dyorzheng](https://x.com/Dyorzheng)

## Scope

This is research support only. It helps structure evidence and ranking logic. Trading decisions stay with the user.
