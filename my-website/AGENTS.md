# AGENTS.md — AI agent instructions

Purpose
- Help AI coding agents (e.g., Copilot) be immediately productive in this small static website repository.

Quick facts
- Type: Static website (HTML, CSS, images).
- How to run: Open [index.html](index.html) in a browser; there is no build system.
- Key files: [index.html](index.html), [about.html](about.html), [style.css](style.css), [figures/](figures/)

Guidelines for agents
- Minimal edits: Make the smallest, safest change that satisfies the user's request.
- Preserve intent: The CSS contains Japanese comments and a clear visual style; preserve existing comment language and structure unless asked to translate.
- Link, don't embed: When referencing project documentation or behavior, link to files in the repo rather than duplicating their content.
- Visual verification: Because this repo is static, prefer making changes that can be verified by opening the modified HTML in a browser.
- No assumptions: If a requested change may affect layout across pages, ask before wide-reaching edits.

Commit & PR guidance
- Make focused commits with descriptive messages (e.g., "style: adjust header spacing").
- When making non-trivial visual changes, include a short note in the PR description about how to verify (e.g., which pages to open).

Suggested next customizations
- Create a small `/.github/copilot-instructions.md` if you want organization-level defaults.
- Add a formatting/linters skill for CSS (optional).

If you want me to expand this into a `.github/copilot-instructions.md` or add a specific agent skill, tell me which area to focus on.