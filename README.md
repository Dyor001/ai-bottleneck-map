# AI Bottleneck Map

`ai-bottleneck-map` is an Agent Skill for turning broad AI narratives into bottleneck maps, company node cards, and re-rating paths.

This project is built for people who do not want another generic AI stock screener. The goal is narrower and sharper:

`start from a technology expansion path -> find the hard-to-scale layer -> map the cleanest listed companies -> define timing, triggers, and kill conditions`

Instead of asking "which stock is hot", this skill asks:

- Which layer gets tight first?
- Which company maps cleanly to that layer?
- What proof makes the mapping credible?
- What would make the thesis weaker or wrong?

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

It does not imitate any public investor's tone or persona. It only absorbs the transferable part of the method: bottleneck-first research.

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

## Repository layout

```text
ai-bottleneck-map/
├── SKILL.md
├── README.md
├── index.html
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

## Scope

This is research support only. It helps structure evidence and ranking logic. Trading decisions stay with the user.
