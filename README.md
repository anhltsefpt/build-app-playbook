# Playbook Collection

Reusable decision playbooks for solo indie app development. Each playbook is a self-contained HTML file — open in browser, follow the steps.

## Playbooks (in pipeline order)

| # | Playbook | Purpose | Input | Output |
|---|----------|---------|-------|--------|
| 1 | [Astro MCP Research](astro-mcp-research-playbook.html) | Score & kill app ideas using App Store keyword data | Raw app idea | GO / CONDITIONAL / KILL with score |
| 2 | [Feature Validation](feature-validation-playbook.html) | 5-step gate: core value, core loop, accessories, surface area, retention hook | One feature/app idea | BUILD / RESHAPE / KILL |
| 3 | [App Selection](app-selection-playbook.html) | Pick which validated app to build next | Ideas that passed Playbook 1 & 2 | Ranked top 3 + sprint decision |
| 4 | [App Store Screenshots](app-store-screenshot-playbook.html) | Generate App Store listing screenshots | Built app + codebase | 5 App Store-ready screenshots (1290x2796) |
| 5 | [Mobile UI Cloning](mobile-ui-cloning-playbook.html) | Clone competitor UI into React Native code via Claude Code | PRD + competitor screenshots | Full UI codebase, validated against user stories |

## Pipeline

```
Ideas → [1] Kill Filter → [2] Feature Gate → [3] Pick Winner → Sprint Build
                                                                    ↓
                                                          [5] Clone UI → [4] Screenshots → App Store
```

## Core Philosophy

- Always copy proven revenue apps. Never invent.
- Differentiate through fixing verified user pain, not adding features.
- Missing features in competitors = users don't need it.
- Kill fast, dive deep on survivors.

## How to Use

Open any `.html` file in a browser. Each playbook contains step-by-step instructions, AI prompt templates, scoring systems, and decision criteria.
