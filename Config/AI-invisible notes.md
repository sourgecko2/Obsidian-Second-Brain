---
date: "2026-09-08"
---
# Making a note AI-invisible

- **Move it to `Private.noindex/`.** That is the whole mechanism. Covers Copilot, Claude Code, any agent reading `AGENTS.md`, and macOS Spotlight.
- **It doesn't hide the filename.** Siri can still find a note by name and read it out if asked. Contents aren't indexed, so it can't find them by what's inside — tested Sept 2026.
- **It isn't encryption.** Every layer is a cooperating system honouring a request. Anything that genuinely must not be read belongs outside the vault.
