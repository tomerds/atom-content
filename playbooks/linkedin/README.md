# LinkedIn Playbook

This folder is the source of truth for how Atom writes LinkedIn content. It was
built over the past year with Stanley as the main AI ghostwriter, and it captures
the voice, structure, hooks, formatting, and do/don't rules that make a post sound
like us.

**The `linkedin-post` skill reads everything in this folder before writing.** When
you ask Claude to write a LinkedIn post, it pulls context from here to follow these
guidelines.

## What's here

- **`playbook.md`** — the complete playbook (13 parts: foundational philosophy,
  style rules, post structure, content themes, the editing process, templates,
  reference lists, example posts, revision case studies, calendar, metrics, quick
  reference, appendix). This is the canonical source of truth.

Add more Markdown files here if a topic grows big enough to warrant its own file;
the skill reads everything in this folder.

This is distinct from `examples/linkedin-posts/`, which holds approved *finished
posts*. The playbook is the **rules**; the examples are **proof**. The skill reads
both.

## Style note

The repo-wide rule still applies: **no em dashes anywhere.** See the root
`CLAUDE.md`.
