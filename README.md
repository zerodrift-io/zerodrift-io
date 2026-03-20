# ZeroDrift

### AI Crews & Automation — Zero Error. Zero Drift.

Building autonomous AI organizations: specialized agent crews
that operate with precision so humans focus on what matters.

## Stack

OpenClaw · Groq Llama 3.3 70B · Docker · Python · M365 Graph API · Telegram · Azure

## Projects

| Project | Description | Status |
|---|---|---|
| [0dr1ft](https://github.com/zerodrift-io/cave-bot) | AI automation platform (built on OpenClaw) | Active |

## Architecture

```
zerodrift-io/
├── zerodrift-io        # This repo — org documentation
└── cave-bot (0dr1ft)   # AI automation platform
    ├── 0dr1ft.mjs      # Custom entry point
    ├── OpenClaw core   # Upstream engine (unmodified)
    └── Azure infra     # Deployment (0dr1ft-* prefix)
```

## Principles

- **GitHub is the source of truth** — all decisions documented in issues/PRs
- **Zero drift from upstream** — OpenClaw core stays unmodified, custom layer on top
- **Infrastructure as Code** — Azure resources managed via Bicep, prefixed `0dr1ft-*`
- **Documentation first** — every change is traceable

## Paris, France — Open to collaborations
