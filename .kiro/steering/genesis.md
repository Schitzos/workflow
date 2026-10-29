# GENESIS Workflow — Steering (ALWAYS ON)

> Auto-injected into every Kiro session in this project.
> **The operating protocol lives in `.genesis/PLAYBOOK.md` — read it first and follow it.**
> It carries the gates, the standing rules, and the "read which file when" map.
> Do not read the whole `.genesis/` docset up front; the PLAYBOOK tells you what to
> read for each phase. Authoritative source: `.genesis/` (the PLAYBOOK routes to it).

## The one rule that cannot wait for a file read
NEVER skip a gate, NEVER push to a protected branch, NEVER commit with a failing
husky guard (lint + type-check + tests + coverage ≥ 80%) or `--no-verify`, and a
task is `Done` only after G3 evidence. Everything else: see `.genesis/PLAYBOOK.md`.
