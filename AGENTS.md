This is an Obsidian vault: Read this before touching anything.
## Ground rules
- **Markdown only.** Never introduce a format that breaks on mobile Obsidian.
- **Never edit `Config/copilot/`.** Plugin-managed: conversations, skills, memory.
- **Ask before deleting or renaming any note.** Renames break wikilinks silently.
- **Don't reformat a note you were only asked to read.** No tidying frontmatter, re-wrapping prose, or "fixing" heading levels as a side effect.
- **Prefer editing in place** with a script that reads the file, not by re-typing its contents from earlier output.
## Folders
| Folder             | Holds                                                              | New files here?                                 |
| ------------------ | ------------------------------------------------------------------ | ----------------------------------------------- |
| `Notes/`           | Real notes — sermon notes, topic notes, reference                  | Yes — this is the default for new notes         |
| `Daily Notes/`     | One note per day, `YYYY-MM-DD.md`                                  | Only via the daily note command                 |
| `Pinboard/`        | Standing pages that stay open: goals, plans, `Captures.md`         | Only when it's a page you return to repeatedly  |
| `Attachments/`     | Images and files embedded in notes                                 | Auto — Obsidian puts them here                  |
| `Attachments/Ink/` | Handwritten pages exported from Noteful as PDF                     | Via the share-sheet Shortcut                    |
| `Sketches/`        | Excalidraw drawings                                                | Via Excalidraw (`cmd+D`)                        |
| `Canvases/`        | Obsidian canvases                                                  | Via the Canvas command                          |
| `Templates/`       | QuickAdd templates                                                 | Rarely                                          |
| `Config/`          | Vault documentation — shortcuts, formatting, palette, system rules | When documenting the system itself              |

`Config/` and `Templates/` are in Obsidian's Excluded Files list, so they are down-ranked in search and hidden from graph view. That is deliberate.

This may change but discrepancies are to be reported.

## Frontmatter
Every note opens with YAML. Only three properties are in use:

```yaml
---
date: "2026-09-02"    # typed as a date property
tags:
  - tagname
due: 2026-09-15       # typed as a date property; optional
---
```

- `date` and `due` are both **date-typed** properties (see `.obsidian/types.json`) — write them as bare `YYYY-MM-DD`, never as prose dates.
- Don't invent new properties without asking. If a note needs status or priority, raise it rather than adding a field that only one note uses.

## Tag vocabulary
The whole vocabulary, deliberately small:

- `daily` — daily notes
- `pinboard` — standing Pinboard pages
- `competency/` — nested-tags for competency levels in studies
- `competency/low` — low competency (need to study this!)
- `competency/medium` — medium competency
- `competency/high` — high competency

Other tags may and will appear based on needs.

Do not add tags outside this list without asking. A tag that appears once is noise.

## Templates
Templates are applied by **QuickAdd**, not by the core Templates plugin (which is off) and not by Templater. That means the placeholder syntax is QuickAdd's:

- `{{DATE:YYYY-MM-DD}}` — formatted date
- `{{VALUE}}` — captured input
- `{{NAME}}` — file name

Templater syntax (`<% tp.date.now() %>`) will not work here. Neither will Dataview queries — Dataview is not installed.

QuickAdd choices currently wired to commands:

| Choice | Type | Target | Hotkey |
|---|---|---|---|
| New Note | Template | `Templates/Template Note.md` | `cmd+N` |
| New pin | Template | `Pinboard/` | — |
| New capture | Capture | appends to `Pinboard/Captures.md` under a `## <date>` heading | `cmd+shift+K` |

## Tasks
Open commitments live as markdown checkboxes inside notes — mostly in `Pinboard/Main Goals.md` and `Pinboard/Post exams stuff.md`, plus the Goals section of each daily note. There is no task plugin.

The single roll-up view is a saved core search: `task-todo:""`.

## Links
- Wikilinks, not markdown links, for anything inside the vault: `[[Main Goals]]`.
- Link to a heading with `[[Note#Heading]]`, to a block with `[[Note#^blockid]]`.
- Daily notes usually open with a short list of that day's main notes, so the day is
 one click from its context. Keep that section if it's present.
- Embeds use `![[file]]`. Images live in `Attachments/`.

## Writing style in notes
Match what's already in the vault: sentence-case headings, bullets over paragraphs for study notes, prose for diary entries. LaTeX with `$...$` inline and `$$...$$` for display — maths shows up often and belongs in real LaTeX, not unicode approximations. `Config/Formatting Guide.md` is the reference for available syntax; `Config/Useful latex.md` for maths.