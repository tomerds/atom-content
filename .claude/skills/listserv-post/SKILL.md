---
name: listserv-post
description: Write posts for research administration community listservs (RESADM-L and the NORDP Forum) promoting an Atom webinar or sharing a resource. Use when asked to write a listserv post, listserv announcement, or "message to the listserv".
---

# Listserv Post

## Before writing

1. Read the examples in `examples/listserv-posts/` and match their voice and structure.
2. Gather the facts (webinar title, date/time with timezone, speakers, registration URL, key topics). If there's an atomgrants.com webinar page, fetch it. Never invent details.
3. Remember the repo-wide style rules in CLAUDE.md, especially: no em dashes anywhere in the copy.

## Always produce TWO emails, one per community

Never write a single cross-posted email. Each community gets its own email, sent separately:

| Community | Address | Audience slant |
|---|---|---|
| RESADM-L | resadm-l@lists.healthresearch.org | Research administrators: pre-award, sponsored programs, compliance, grants management |
| NORDP Forum | NORDPForum@hub.nordp.org | Research development professionals: proposal development, strategic funding initiatives, institutional research strategy |

The two emails share the same skeleton and facts but differ in the audience sentence (and anywhere else relevance framing appears). Tailor "who this is most useful for" to each community's day-to-day work; don't just swap the list name.

## Voice

A listserv post is Tomer personally messaging colleagues, not Atom marketing to prospects:

- First person, warm, conversational ("I wanted to share...", "I think will be relevant to a lot of folks on this list").
- **Always include a founder disclosure** when promoting something Atom hosts: name the affiliation plainly and note the session is substance, not a product pitch.
- No hard sell, no marketing superlatives, no emoji blocks. Lead with why it's relevant to the list's work.
- Sign off as Tomer personally: name, Atom (atomgrants.com), tomer@atomgrants.com.

## Structure (each email)

```
Subject options: 2 plain, informative subject lines (date + topic, no clickbait)

Hi all,

<1 sentence: sharing a free webinar/resource relevant to this list>

<1 paragraph: who's speaking (names, titles, orgs) and what they'll cover, framed
around the ideas rather than the event>

**<Full webinar title>**
<Weekday, Month D, YYYY>
<Time> Eastern, on Zoom

<1 sentence: who it's most useful for, tailored to THIS community>

You can register here: <URL>

<Founder disclosure + "happy to answer questions" + recording note if registrants
get the recording (confirm before promising)>

Hope to see some of you there!

Tomer du Sautoy
Atom (atomgrants.com)
tomer@atomgrants.com
```

## Style notes

- No em dashes, ever (repo rule). Rewrite with commas, periods, colons, or parentheses.
- Keep it plain-text friendly: most listservs strip rich formatting, so don't rely on bold or links rendering. Bare URLs, minimal markdown.
- Shorter than the marketing email: one content paragraph, one audience sentence. Colleagues skim.

## Output

Save both inside the relevant content folder at the repo root (e.g. alongside that webinar's reminder emails):
- `listserv_post_resadm.md`
- `listserv_post_nordp.md`

If asked to draft in Gmail, create two separate drafts, one per address. Never put both lists on one email.
