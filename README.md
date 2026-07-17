# Seed Vault

A starter Obsidian vault built around the [PARA Model](https://fortelabs.com/blog/para/), a framework for sorting everything you capture into four categories: Projects, Areas, Resources, and Archive. This vault comes with suggested folders and templates optimised for use as a work-related vault, but the structure doesn't enforce that use case keeping you free to adapt to our own needs.

---

## Folder Structure

```
Seed Vault/
├── 1 Projects/                     # Active work with a defined outcome
│   └── Onboarding/
├── 2 Areas of focus/               # Ongoing responsibilities with no end date
│   └── Hiring/
│       └── Candidates/
├── 3 Resources and curiosities/    # Reference material and supporting files
│   ├── Attachments/
│   ├── Definitions/
│   ├── People/
│   ├── Prompts/
│   ├── Saved articles/
│   ├── List of opportunities.md
│   ├── List of questions.md
│   └── List of reminders.md
├── 4 Archive/                      # Completed or inactive items
├── Notes/                          # Periodic notes
│   ├── Daily/
│   ├── Weekly/
│   ├── Monthly/
│   ├── Quarterly/
│   ├── Yearly/
│   └── Zettelkasten/
├── Templates/                      # All Templater templates
├── Inbox.md                        # Your landing pad, process regularly
└── Scratch.md                      # A throwaway scratchpad
```

---

## Templates

All templates use [Templater](https://github.com/SilentVoid13/Templater) and include YAML frontmatter with `saved_date` and `updated_date` fields for tracking.

| Template | Purpose |
|---|---|
| **Daily Note** | Agenda, task rollup via Tasks plugin, and a space for notes |
| **Week in Review** | Weekly summary with done/not-done task queries and links to daily notes |
| **Month in Review** | Monthly summary with weekly note links and task rollups |
| **Quarterly Review** | Structured reflection with what went well / to improve / to continue |
| **Year in Review** | Annual summary linked to quarterly notes |
| **Zettelkasten Template** | Atomic note with blockquote for the core idea and source links |
| **Note** | General-purpose note |
| **MOC** | Map of Content with auto-generated backlinks, tag queries, and text references |
| **Definition** | Personal glossary entry |
| **Extract** | Pull a passage out of another note, maintaining the source link |
| **Person** | Contact note with org metadata fields (role, team, department, etc.), biography, and auto-generated references via Dataview |
| **Saved Article** | Clipped article with URL, author, and publisher fields |

Periodic notes (Weekly, Monthly, Quarterly, Yearly) auto-file themselves into the correct subfolder under `Notes/` when created.

---

## Plugins Included

| Plugin | Purpose |
|---|---|
| [Templater](https://github.com/SilentVoid13/Templater) | Powers all templates with dynamic dates and scripting |
| [Dataview](https://github.com/blacksmithgu/obsidian-dataview) | Query your notes like a database |
| [Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks) | Track and query tasks across your vault |
| [Periodic Notes](https://github.com/liamcain/obsidian-periodic-notes) | Create daily, weekly, monthly, quarterly, and yearly notes |
| [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) | Calendar sidebar view for navigating periodic notes |
| [Natural Language Dates](https://github.com/argenos/nldates-obsidian) | Type dates in plain English |
| [Advanced URI](https://github.com/Vinzent03/obsidian-advanced-uri) | Deep-link into your vault from external apps |
| [Smart Typography](https://github.com/mgmeyers/obsidian-smart-typography) | Auto-converts quotes and dashes to typographically correct characters |
| [Tag Wrangler](https://github.com/pjeby/tag-wrangler) | Rename, merge, and manage tags |
| [Change Case](https://github.com/dbrockman/obsidian-change-case) | Quickly transform text case |

---

## Getting Started

1. Download `seed-vault.zip` from this repository
2. Unzip it to wherever you keep your vaults
3. Open Obsidian → **Open folder as vault** → select the unzipped folder
4. Obsidian will prompt you to trust community plugins; click **Trust and enable**
5. Start in `Inbox.md` and go from there

---

## Customizing

- **Daily Note** includes a placeholder comment for an AI briefer link — replace or remove it
- **Person** template includes org-specific fields (role, team, department, division), trim these if using this for personal rather than work contacts
- **Quarterly Review** queries three list files in `3 Resources and curiosities/`:
  - **List of opportunities** — open opportunities; completed ones move to the Closed section
  - **List of questions** — open questions you're tracking over time
  - **List of reminders** — standing reminders that don't fit neatly as tasks

  All three are tagged `ignore` so they can be easily excluded from searches.

---

## Credits

Organizational structure based on the [PARA Model](https://fortelabs.com/blog/para/) by Tiago Forte.
