# Changelog

## 1.0.0 — 2026-06-07
- Initial release of the **gemini-subagents** skill.
- Manager/worker pattern: orchestrator agent directs, Gemini workers generate.
- **Mode A** — headless Gemini CLI workers (`gemini-3-flash-preview`, `gemini-2.5-flash`, `gemini-2.5-pro`).
- **Mode B** — Antigravity handoff for Gemini 3.5 Flash on consumer accounts.
- Verified model IDs + the `gemini-3.5-flash` `ModelNotFoundError` gotcha documented.
- Spec template for the section-by-section build loop.
