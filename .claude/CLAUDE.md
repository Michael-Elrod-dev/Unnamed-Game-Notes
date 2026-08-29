# CLAUDE.md

Guidance for any AI assistant working in this vault. Applies to every session.

## What this vault is

Design notes for an in-development indie game. These notes are the blueprint the team builds from and the source of truth for what the game is.

Several people work in this vault and all of them work through AI. Anything written here will be read months later by someone who was not in the conversation that produced it.

## Canon and speculation

Highest priority rules in this file.

- Never invent design decisions. If the game does not have an answer yet, it does not get one written down.
- If a detail is unspecified and a note needs it, ask. Do not fill the gap and keep going.
- Open questions get recorded as open. Mark them with **Open:** or a TODO line.
- Anything you suggest is a proposal and gets labeled as one. Proposals never get rewritten into settled language.
- Before building on an earlier note, check how it was marked. Do not treat a past proposal as a decision.
- Numbers, names, and mechanics are decisions. Placeholder values get marked as placeholders.

An unanswered question in the notes is fine. A confident wrong answer is not.

## Writing standards

These apply to notes and to chat responses. The canon rules above apply to notes.

Banned:

- Em dashes
- Semicolons
- Colons inside a sentence
- Emoji, decorative symbols, ASCII art
- Narrative or essay voice
- "Not x, but y" and "rather than" constructions
- Preamble announcing what a section covers before covering it
- Filler adjectives such as robust, seamless, powerful, comprehensive, deeply
- Closing summaries that repeat what was just said

Allowed:

- Colons in frontmatter, list labels, and table headers
- A colon introducing a list

Tone is concise and direct. Assume the reader has context.

Wrong register:

> The combat system is designed to be a fast paced, deeply engaging experience that rewards player skill rather than raw stats, creating moments of genuine tension.

Same content, correct register:

> Combat is fast. Skill matters more than stats.

## Obsidian formatting

Formatting exists to make a note faster to read. That is the only test.

- Use headings, lists, tables, and callouts where they help someone skimming.
- Use `[[wikilinks]]` when a note genuinely references another concept. Do not add links to grow the graph.
- Do not decorate. If a formatting choice is not saving the reader time, remove it.
- Images and reference art are welcome. Embed them where they explain something.

## Conventions

Thin on purpose. The vault is new and its patterns have not emerged yet.

- Match the patterns already present in the vault. Read a neighboring note before writing a new one.
- Do not invent conventions for naming, tagging, linking, or frontmatter.
- If a note needs a pattern that does not exist yet, ask first.

Settled conventions get added below as the team makes them.

- **Links.** Shortest form. Write `[[Combat]]`, never the full vault path. Add an alias only when the display text should differ from the filename, as in `[[05-Jotenheim|Jotenheim]]`. Obsidian is configured to generate this format automatically.
- **Entity notes.** Units, structures, enemies, bosses, and locations use the matching template in `99-Templates`. One entity per note.
- **Markers.** Unresolved items get **Open:**. Suggestions that no one has agreed to get **Proposal:**. Neither is ever silently promoted into plain text.
- **No manual index notes.** The file explorer and backlinks handle navigation. `Game Overview` is the only hub.
- **No tags and no frontmatter.** Decided against both.

## Scope

- Do not reorganize, rename, or move existing notes unless asked.
- Do not create top level folders without asking.
- Edit the note in question. Leave its neighbors alone.
- Do not rewrite another person's note to match your phrasing.

## Maintenance

When the team settles a convention or a rule, add it here. An out of date CLAUDE.md is worse than a short one.
