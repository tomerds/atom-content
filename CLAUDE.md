# Atom Content Repo

This repo is for writing Atom's written content: blogs, webinar posts, newsletters, investor memos, webinar reminder emails, and similar.

## How this repo works

- **Skills** live in `.claude/skills/`, one per content type. When asked to write a piece of content, use the matching skill.
- **Examples** live in `examples/`, organized by content type. These are approved, high-quality past pieces. Skills reference them as the ground truth for voice, structure, and length - when writing, read the relevant examples first.
- **Playbooks** live in `playbooks/`, organized by channel (e.g. `playbooks/linkedin/`). A playbook is the distilled *rules* for a channel: voice, structure, hooks, formatting, do's and don'ts. Where a channel has a playbook, its skill reads the playbook first, then the examples. The playbook is the rules; the examples are the proof.
- **References** live in `references/`, organized by channel (e.g. `references/linkedin/`). These are external, web-sourced craft guidance (general best practices, not Atom-specific). A skill may read its references alongside the playbook. The playbook is Atom's house voice and wins on any conflict; references back it up and never override it. Keep sources cited so they stay auditable.
- **Generated content** goes in its own folder at the repo root, named in `Title_Case_With_Underscores` (e.g. `Grant_Deadlines_Blog/`). These folders are gitignored by design - only the scaffolding (skills, examples, docs) is version controlled.

## Conventions

- One folder per content piece at the repo root. Keep drafts, final copy, and any supporting notes for a piece together in its folder.
- Write final copy as Markdown unless the skill says otherwise.
- Don't invent facts about Atom, customers, or metrics - pull from the examples, or ask.

## Style rules (apply to ALL copy, every content type)

- **Never use em dashes (—).** Not in titles, body copy, subject lines, or bullets. Rewrite the sentence instead: use a comma, a period, a colon, or parentheses. This applies to every skill in this repo even if the skill doesn't repeat it.

## About Atom

Atom (atomgrants.com) is a grants platform. Audience for most content: research administrators and university research offices. Investor memos target investors instead - different voice, see that skill.
