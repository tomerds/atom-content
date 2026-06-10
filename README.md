# Atom Content

Claude Code workspace for writing Atom's content - blogs, webinar posts, newsletters, investor memos, webinar reminder emails.

## Structure

```
.claude/skills/   One skill per content type (blog, newsletter, etc.)
examples/         Approved past pieces, organized by type - the source of truth for voice and structure
<Piece_Name>/     Generated content, one folder per piece (gitignored)
```

## Usage

Open Claude Code in this folder and ask for what you need, e.g. "write a blog post about X" - the matching skill loads the right examples and conventions.

Only scaffolding (skills, examples, docs) is committed. Generated content folders are ignored automatically via a whitelist `.gitignore`.

## Adding examples

Drop approved pieces into the matching `examples/<type>/` folder as Markdown (or the original format) and commit. Skills always read examples before writing.
