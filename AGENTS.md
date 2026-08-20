# Escape documentation guide

- This is the separate documentation repository for Escape. Keep the presentation and technical explanation in one English `README.md`; add real captures under `media/` when available.
- Keep this repository private until the user explicitly asks to change its visibility.
- Describe the implementation you have inspected. Distinguish current behavior, configuration, known limitations, and future work. Never present a deployment as verified without evidence.
- Do not copy application source, private configuration, secrets, manual PDFs, or the application repository's Git history into this repository.
- Check Git status before editing and preserve other work. Stage only the files changed for the requested documentation task.
- The user requests a commit for each completed documentation change. Commit relevant changes with a clear English message, and report the commit and updated file. Push those commits to the configured private origin when available, checking that the destination is still private before pushing.
- Check Markdown links, heading anchors, Mermaid syntax, and Git whitespace errors for documentation changes. No application build is needed unless application code changes.
