# AI Access & Roles — Sagittarius

**Status:** Parked research candidate  
**Last updated:** 2026-10-12  
**Owner:** Daniel (wildwrld86)  
**Companion file:** [GB_HANDOFF.md](GB_HANDOFF.md)

This file exists so SuperGrok, Grok Bots (GB), free-tier Grok, ChatGPT, and other agents can see clear boundaries without guessing.  
**Repository visibility is not authorization to act.**

---

## Current standing rules (apply to all AIs)

- Treat this repository as **parked**. Do not begin autonomous development, installation, paid API use, deployment, or infrastructure changes.
- Do not invent a use case or treat the project as active.
- Preserve upstream attribution (https://github.com/undeadindustries/sagittarius), README, and license.
- Prefer a disposable / isolated environment for any future evaluation.
- Keep upstream updates separate from any custom work (use a dedicated branch).
- No secrets, API keys, or credentials belong in this repo.
- When in doubt, wait for explicit activation from Daniel with a bounded task and cost limit.

---

## Tool / agent roles

| Agent / Tool              | Access level          | Allowed actions                                      | Forbidden / restricted                          |
|---------------------------|-----------------------|------------------------------------------------------|-------------------------------------------------|
| **Grok Bot (GB)**         | Read + research       | Read code, docs, and this file; propose small tests when activated | Autonomous coding, installs, deploys, spending |
| **SuperGrok**             | Read + research       | Analysis, documentation drafts, planning             | Direct pushes without review, paid usage beyond limits |
| **Free-tier Grok**        | Read                  | Answer questions about the public repo               | Writes, tool use that modifies anything         |
| **ChatGPT**               | Read (if shared)      | Analysis and suggestions only                        | Writes, execution, or assuming ownership        |
| **Other agents / bots**   | None by default       | —                                                    | Any action until explicitly granted             |

Multiple Grok Bots exist. Until named and scoped here, treat every GB the same: research only, wait for activation.

---

## When a task is activated

1. Confirm the intended use case with Daniel.
2. Inspect current upstream changes.
3. Propose a small, bounded test with an explicit cost limit.
4. Document the plan and any changes on a dedicated branch.
5. Update this file (or GB_HANDOFF.md) with the new scope and expiry.

---

## How to update this note

- Prefer editing this file directly on GitHub or via a connected agent.
- Commit message style: `docs: update AI_ACCESS.md — <short reason>`
- Keep the table and standing rules current whenever access or roles change.

---

## Notes

- GB is short for **Grok Bot**.
- SuperGrok subscription status may change; free-tier and repo-based docs remain the reliable source of truth.
- This file does not replace normal GitHub permissions or branch protection. It is coordination guidance only.
