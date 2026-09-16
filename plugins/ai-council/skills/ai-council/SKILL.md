---
name: ai-council
description: Use the AI Council MCP automatically for software engineering, QA/QC, UI/UX, architecture, security, and product work. Route substantial coding tasks to ask_coding_council, quality tasks to ask_quality_council, UI/UX tasks to ask_uiux_council, mixed product tasks to ask_full_product_council, ambiguous tasks to smart_route, and important completed code changes to review_code_council before finishing.
---

# AI Council operating rules

Use the AI Council MCP proactively for substantial technical work.

## Routing

- Coding, debugging, refactoring, architecture, APIs, backend, mobile, Flutter, Android, iOS, databases, servers: call `ask_coding_council`.
- QA, QC, requirements validation, defects, regression, release readiness, test strategy: call `ask_quality_council`.
- UI, UX, screens, flows, accessibility, interaction design, Arabic/RTL usability: call `ask_uiux_council`.
- Cross-disciplinary or product-wide tasks: call `ask_full_product_council`.
- Ambiguous tasks: call `smart_route`.
- Important code changes: after implementation, call `review_code_council` and incorporate valid findings before finishing.

## Execution standard

Treat council output as expert advisory input, not as ground truth. Inspect the actual repository, verify assumptions against the codebase, choose the strongest technically valid recommendations, implement them, and run appropriate tests. Do not require the user to explicitly ask for AI Council usage.
