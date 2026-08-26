# CTF Notes for Obsidian

An [Obsidian](https://obsidian.md/) vault for taking structured notes during Capture the Flag (CTF) events. It is designed to keep challenge details, investigation steps, evidence, flags, and lessons learned organized while you work.

The vault includes challenge-category folders, a progress dashboard, reusable templates, community plugins, the **Things** theme, and custom CSS snippets. Clone it, open it as an Obsidian vault, and start documenting challenges.

## About this template

I created this repository in preparation for the upcoming **Fall 2026 National Cyber League (NCL) competition**. The included categories reflect those listed in the NCL Gymnasium before the Fall 2026 preparation phase.

The official categories or competition structure may change. This repository is not intended to define the Fall 2026 challenge set; it is simply a flexible template for organizing notes, documenting investigations, and keeping track of your thought process. Feel free to rename, add, remove, or reorganize categories to match the event and your preferred workflow.

## Vault structure

Challenges are grouped into current NCL gymnasium categories and should be changed to suit your use case:

- `0. Dashboard` — links to challenges that are in progress, blocked, or solved.
- `1. Open Source Intelligence` — OSINT research and investigation.
- `2. Cryptography` — ciphers, encoding, hashing, and cryptographic challenges.
- `3. Password Cracking` — password and hash-cracking challenges.
- `4. Forensics` — file, memory, disk, and artifact analysis.
- `5. Log Analysis` — application, system, and security log investigation.
- `6. Network Traffic Analysis` — packet captures and network-based challenges.
- `7. Scanning and Reconaissance` — discovery, scanning, and reconnaissance notes.
- `8. Web Application Exploitation` — web vulnerabilities and exploitation.
- `9. Enumeration and Exploitation` — service enumeration and general exploitation.
- `Templates` — reusable note and snippet templates.

Each category starts with an `Untitled.md` challenge note that can be renamed and reused. `Untitled.md` is a blank `Challenge Notes.md` template

## Getting started

### 1. Download the vault

Clone the repository with Git:

```bash
git clone <repository-url>
```

Alternatively, select **Code → Download ZIP** on GitHub and extract the downloaded archive.

### 2. Open it in Obsidian

1. Install and launch [Obsidian](https://obsidian.md/download).
2. Select **Open folder as vault**.
3. Choose the cloned or extracted repository folder, the folder containing this `README.md` and the `.obsidian` directory.
4. If Obsidian asks whether you trust the vault or want to enable community plugins, review the included plugins and approve them if you would like to use them as well.

The vault contains my Obsidian configuration, theme, CSS snippets, and plugin files, so its appearance and behavior should closely match my original setup. Obsidian may initially open a different note because personal workspace state is intentionally not shared.

### 3. Create a challenge note

1. Open the folder that best matches the challenge category.
2. Create a new note and give it a descriptive name, such as `Hidden Message.md`.
3. Open the Command Palette with `Ctrl+P` (`Cmd+P` on macOS).
4. Run **Templater: Open Insert Template modal** and select `Challenge Notes`.
5. Add the note to the appropriate section of `0. Dashboard/Dashboard.md`.

During the challenge, keep the working notes chronological: record what you thought, what you tried, what happened, and what the result suggests doing next. This makes the note useful both during the event and when converting it into a write-up later.

## Templates

### Challenge Notes

The main CTF challenge template. It provides sections for:

- The challenge objective, flag format, and hints.
- Important targets, ports, URLs, credentials, files, and hashes.
- Chronological investigation notes using a thought/action/result structure.
- Evidence and screenshots.
- The final flag, solution steps, and key lesson.

Use this as the starting point for individual challenge notes.

### Thought

A small repeatable investigation block containing:

- **Thought** — what you are trying to determine.
- **Action** — what you are doing to test it.
- **Result** — what happened.

Insert it whenever you need another experiment or troubleshooting step in a challenge note.

### Cornell Template

A study-note layout based on the Cornell note-taking method. It separates cues or review questions from the main notes and provides a summary section. This is useful for studying tools, commands, concepts, and techniques outside a specific challenge.

The template depends on the included `Cornell Notes.css` snippet for its custom cue and summary styling.

### Cue Snippet

Inserts a custom Obsidian `cue` callout. Use it for keywords, definitions, questions, or prompts in Cornell-style notes.


## Included community plugins

Community plugins contain third-party code. I encourage you to review them before enabling them, especially when using a vault downloaded from the internet.

### Templater

Provides the template insertion workflow used by this vault. It is configured to read templates from the `Templates` folder, and the Cornell template is configured as a startup template. System commands are disabled in the included configuration.

### Multi-Column Markdown

Adds support for displaying Markdown content in multiple columns inside Obsidian. It can be used to create compact dashboards, side-by-side reference material, or other layouts that benefit from columns.

### Style Settings

Provides a settings interface for CSS variables exposed by themes, plugins, and CSS snippets. Use it to customize the included theme and the Rainbow Glass Folders snippet without editing CSS manually.

If a plugin is disabled, open **Settings → Community plugins**, turn off Restricted Mode if prompted, and enable the plugin. Restarting Obsidian may help after enabling bundled plugins for the first time.

## Appearance

The vault includes:

- **Things theme** — the default visual theme for the vault.
- **Cornell Notes CSS** — styles the cue and summary elements used by the Cornell template.
- **Rainbow Glass Folders CSS** — gives folders distinct colors and glass-style backgrounds in the file explorer.

Manage snippets under **Settings → Appearance → CSS snippets**. Customize supported visual options under **Settings → Style Settings**.


## Personalizing the vault

Feel free to rename the event heading in the dashboard, add category folders, modify the templates, or change the theme and snippets. Obsidian notes are standard Markdown files, so they remain readable and editable outside Obsidian as well.

