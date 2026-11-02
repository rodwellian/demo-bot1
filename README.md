# demo-bot1



A flowstore project. The spec is markdown with YAML frontmatter:

- `agent.md` — identity, languages, entry flow; body is the system prompt template if any
- `flows/<id>.md` — one flow per file: routing in frontmatter, instructions and scripts in the body
- `guardrails.md`, `knowledge/` — rules, FAQ, glossary, tables
- `variables.yaml`, `business-goals.yaml`, `capabilities/` — machine-facing declarations
- `tests/` — cases, personas, rubrics, golds

See FILE-MODEL.md in the flowstore repo for the layout.
