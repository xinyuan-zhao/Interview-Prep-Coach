# Interview Prep Coach Agent Skills

Two standalone, evidence-based interview-preparation skills:

- [`interview-prep-coach-en`](interview-prep-coach-en/) — natural English experience for English-speaking users.
- [`interview-prep-coach-zh`](interview-prep-coach-zh/) — natural Chinese coaching, including English-language interview support.

Both versions follow the same methodology:

> Resume + JD → Role Analysis → Evidence Mapping → Core Story Bank → Likely Questions → Critical Answers → Mock Interview → Cheat Sheet → Debrief

## Design Principles

- Prove fit with real evidence rather than generic question lists.
- Emphasize Problem → Action → Result → Value.
- Never fabricate experience, ownership, tools, titles, metrics, or impact.
- Support the complete workflow and individual modules.
- Keep core behavior in `SKILL.md`; load detailed methodology and scoring from `references/` only when needed.

## Repository Structure

```text
Interview-Prep-Coach/
├── README.md
├── interview-prep-coach-en/
│   ├── SKILL.md
│   ├── README.md
│   ├── agents/
│   │   └── openai.yaml
│   └── references/
│       ├── interview-methodology.md
│       └── mock-interview-rubric.md
└── interview-prep-coach-zh/
    ├── SKILL.md
    ├── README.md
    ├── agents/
    │   └── openai.yaml
    └── references/
        ├── interview-methodology.md
        └── mock-interview-rubric.md
```

## Install One Version

Zip either language folder by itself and upload/install it as an Agent Skill. Each folder is independently functional and does not reference the other version.

See the README inside each language folder for beginner-friendly usage instructions.
