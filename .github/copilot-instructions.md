<!-- Generated: concise Copilot instructions for this repository -->
# Copilot instructions — ahmed-moustafa-homepage

Purpose
- Provide focused, actionable guidance for AI coding agents working in this repository.

Repository snapshot
- This repository currently contains only `README.md` (a small homepage repo placeholder).
- Owner: `drahmos`; repository: `ahmed-moustafa-homepage`; default branch: `main`.

High-level guidance (what you may assume)
- There is no build system, framework, or test harness present. Do not add opinions about frameworks or package managers without asking the repo owner first.
- Treat changes as proposals: create clear, minimal diffs and ask for explicit approval before adding large scaffolding (CI, frameworks, directories).

What to ask the user before you act
- If a task requires adding a site framework (e.g., React, Next.js, SSG) ask which stack they prefer.
- If a task needs CI or deployment, ask which provider (GitHub Pages, Netlify, Vercel, GitHub Actions) and whether secrets/tokens are available.

When making edits
- Keep changes small and transparent. Use branch names like `feat/<short-desc>` or `fix/<short-desc>` and reference the repo/owner in PR descriptions.
- If you add files, update `README.md` to document them.

Concrete examples (safe, minimal changes an agent can propose)
- Add a single `index.html` at repo root with a simple static homepage and update `README.md` to document it.
- Propose a `docs/` or `src/` folder only after confirmation; add a brief README inside that folder explaining its purpose.
- When proposing CI, present a minimal `workflow` YAML and explain required secrets; do not commit secrets.

Developer workflows & checks (commands to run locally)
- Inspect repository state: `git status` and `git rev-parse --abbrev-ref HEAD`.
- Create a feature branch: `git checkout -b feat/add-homepage`.
- Commit with a concise message and push: `git add . && git commit -m "feat: add homepage" && git push --set-upstream origin feat/add-homepage`.

Patterns & conventions discovered in this repo
- There are currently no project-specific coding patterns or build/test conventions to follow. Prefer to ask before introducing conventions.

Integration points
- No external integrations are present. If you add integrations (analytics, CI, hosting), document them in `README.md` and in the PR description.

Safety and review
- Always explain why a change is needed and provide a short rollback plan (files added/modified).
- Avoid adding secrets or credentials. If a change requires secrets, list them in the PR and request manual setup by the owner.

If anything is unclear
- Prompt the repository owner for clarification. Example questions are: which framework to use, preferred CI provider, or whether the repo should remain minimal.

End
<!-- End generated instructions -->