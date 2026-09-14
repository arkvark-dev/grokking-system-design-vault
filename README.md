# Grokking System Design — Obsidian study vault

Original study plan for Educative’s **public** course outline.

Course: [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview)

The same course is also listed as [Grokking Modern System Design Interview](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers).

This repo is an Obsidian vault. It is **not** a copy of the course. It maps module titles to study prompts and empty note headings. Do not paste paid lesson text, quizzes, or solutions into these files.

## Open in Obsidian

1. Clone this repo.

```bash
git clone https://github.com/arkvark-dev/grokking-system-design-vault.git
cd grokking-system-design-vault
```

2. Install [Obsidian](https://obsidian.md) if you need it.
3. In Obsidian choose **Open folder as vault**.
4. Select the cloned folder (the folder that contains `00-Home.md`).
5. Trust the vault if Obsidian asks.
6. Open [00-Home.md](00-Home.md). Pin it if you want a start page.

You can also read the Markdown in git. In Obsidian, wikilinks look like `[[YouTube]]`.

## How to use todos

1. Open [00-Home.md](00-Home.md) for the map.
2. Pick **8-week** or **6-week** in [01-Plan/Schedule.md](01-Plan/Schedule.md).
3. Each day, open one module note.
4. Use Educative for teaching. Use this vault for **your** notes and drills.
5. Tick study todos (`- [ ]` becomes `- [x]`).
6. Write under the empty headings: Requirements, Constraints, High-level design, Deep dives, Trade-offs, Failure modes.
7. Set the note frontmatter `status` to `done`. Tick the same item in [PROGRESS.md](PROGRESS.md).

### Todo sources
- Each module note has `- [ ]` study actions.
- [PROGRESS.md](PROGRESS.md) is the same list in one file.
- Frontmatter `status` is `not-started`, `in-progress`, or `done`.

### Design problems
Each design note has original **RESHADED-style** prompts. Use them as a 45-minute script. They are not Educative lesson text.

For extra prompts, insert a template from `Templates/` (Obsidian: **Insert template**).

- [Templates/Design-Problem.md](Templates/Design-Problem.md)
- [Templates/Building-Block.md](Templates/Building-Block.md)

## Folders

| Folder | What it is |
| --- | --- |
| [00-Home.md](00-Home.md) | Map of content (MOC) |
| [PROGRESS.md](PROGRESS.md) | Master checklist |
| [01-Plan/](01-Plan/) | Schedule, rubric, glossary |
| [02-Foundations/](02-Foundations/) | Section A |
| [03-Building-Blocks/](03-Building-Blocks/) | Section B |
| [04-Design-Problems/](04-Design-Problems/) | Section C |
| [05-Wrap-up/](05-Wrap-up/) | Section D |
| [Templates/](Templates/) | New building-block or design notes |
| `.obsidian/` | Minimal vault settings |

## Optional plugins

Core Obsidian is enough.

- **Templates** (core): folder is `Templates`. See Settings → Core plugins → Templates.
- **Tasks** (community, optional): query checkboxes such as `not done`.
- **Dataview** (community, optional): query frontmatter. Example:

````markdown
```dataview
TABLE status AS Status, est_minutes AS Minutes, week AS Week
FROM "02-Foundations" OR "03-Building-Blocks" OR "04-Design-Problems" OR "05-Wrap-up"
SORT section ASC, file.name ASC
```
````

This vault does not install community plugins. Add them in Obsidian if you want them.

## Git

`.gitignore` skips Obsidian workspace and cache files. Notes, templates, and `PROGRESS.md` are meant to be committed.

When you study, commit your ticks and notes on a private branch if you do not want drafts on `main`.

## What this is not
- Not Educative content.
- Not a substitute for the paid course.
- Not production architecture advice. It is interview practice.

If a note ever contains pasted course text, delete that text.
