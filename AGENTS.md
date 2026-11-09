# ShopBoard — Agent Instructions

## Stack
- Build tool: Vite (vanilla template)
- Languages: HTML, CSS (plain JavaScript only when explicitly asked)
- No frameworks, no CSS libraries, no new npm packages without asking

## Rules
- Semantic HTML first: use header, nav, main, section, article, footer before div
- Every input has a label, linked with for/id
- Mobile-first: base styles for small screens, then min-width media queries
- No !important
- Explain every change: what changed, why it changed, and which rule it follows

## Workflow
- Keep changes small and focused on one task
- Do not touch files unrelated to the task
- Before saying "done", run `npm run check` and `npm run build` and confirm there are no errors
