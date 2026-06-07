# SPEC: <section name>   (e.g. Hero, Pricing, Footer)

> The orchestrator fills this in. The runner opens Antigravity (model = **Gemini 3.5 Flash**)
> and says: "Implement specs/<this-file>.md", then reports "done".
> (For Mode A, the same content goes into a `gemini -p` prompt.)

## Goal
One sentence: what this section is and the one job it must do.

## Locked design (do NOT improvise)
- **Aesthetic:** <e.g. high-end editorial / minimalist / brutalist>
- **Fonts:** heading = <font>, body = <font>
- **Colors (use ONLY these):** bg `#xxxxxx` · text `#xxxxxx` · accent `#xxxxxx` · muted `#xxxxxx`
- **Spacing scale:** <e.g. 4 / 8 / 16 / 32 / 64 px>
- **Radius / shadow:** <tokens>
- **Motion:** <easing + what animates, or "none">

## Build
- **Files to create/edit:** `<exact/path/file.ext>`
- **Framework:** <Next.js / plain HTML / etc.>
- **Content:** <copy, links, data — be specific, no lorem ipsum>
- **Responsive:** must work on a small laptop + mobile.

## Bans (reject if present)
- ❌ Bootstrap blue `#007bff` or any color outside the palette above
- ❌ Inline `onmouseover` / inline event handlers
- ❌ Templated "hero + 3 cards + footer" filler
- ❌ Placeholder comments / `// rest of code` / TODO stubs
- ❌ Lorem ipsum (use the real copy above)

## Acceptance checklist
- [ ] Uses only the locked fonts + palette
- [ ] Hover / focus / active states present
- [ ] Responsive verified
- [ ] Complete code, no placeholders
