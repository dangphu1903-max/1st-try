# AGENTS.md — Assistant guidance for this repository

Purpose: Provide minimal, actionable instructions so AI coding agents can be immediately productive in this repository.

Repository snapshot
- Single Python script: [hello-world.py](hello-world.py)

Quick run
```
python3 hello-world.py
```

Agent guidance (concise)
- **Scope:** Limit changes to files relevant to the user's request. Ask before adding new top-level files.
- **Verify:** Run the quick-run command above when verifying behavior; report output and errors back to the user.
- **Testing:** There are no tests. Propose adding tests before large refactors.
- **Conventions:** Use idiomatic Python; keep changes minimal and reversible.
- **Docs:** Link to repository docs instead of copying them. If none exist, summarize and link to created files.

Suggested next customizations
- Add a `.github/copilot-instructions.md` or expand `AGENTS.md` if you want organization-level rules.
- Add `README.md` and a `requirements.txt` if the project grows.

If anything here is unclear or you want more specific agent behavior (e.g., strict linting, testing rules, or CI steps), tell me and I will update this file.
