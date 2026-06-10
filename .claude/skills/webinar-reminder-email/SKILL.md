---
name: webinar-reminder-email
description: Write webinar reminder emails for Atom (day-of reminders, day-before/week-before reminders, follow-ups). Use when asked to write any email in a webinar reminder sequence.
---

# Webinar Reminder Email

## Before writing

1. Read the examples in `examples/webinar-reminder-emails/` and match them closely.
2. Gather the facts: webinar title, date/time with timezone, hosts/speakers (names, titles, orgs), what attendees will learn, target roles, and the registration URL. If the user gives a webinar page URL on atomgrants.com, fetch it — it has all of this. Ask only for what you can't find. Never invent details (e.g. don't add an end time if only a start time is published).
3. Confirm where this lands in the sequence (week-before, day-before, day-of) — it changes only the opening line, not the structure.

## Email structure (follow exactly)

```
Hey {{{contact.first_name|there}}},

Just a quick reminder that our webinar on <topic> is <happening today / coming up this Thursday / ...>!

📅 Date: <Weekday, Month D, YYYY>
⏰ Time: <time> Eastern
📍 Location: Zoom (link sent upon registration)

Join <host intro, e.g. "our founder Tomer du Sautoy and Dr. Baron Wolf"> for <one-sentence pitch of the session, including any notable affiliations or backers>.

You'll learn:

* <takeaway 1>

* <takeaway 2>

* <takeaway 3>

Whether you're in <role 1>, <role 2>, or <role 3>, this session will give you <concrete value promise>.

If you haven't signed up yet you can do so here:

Register Now <full registration URL>

See you soon!
The Atom Team
```

## Style notes

- Short and warm — no padding beyond the structure above. One pitch paragraph, exactly three bullets.
- Keep the merge-field syntax verbatim: `{{{contact.first_name|there}}}`.
- Asterisk bullets with a blank line between each, matching the examples.
- The emoji detail block uses 📅 / ⏰ / 📍 in that order.
- Condense the webinar page's "What you'll learn" list down to the three strongest takeaways; pull the audience roles from its "Who should attend" section.

## Output

Create `<Webinar_Name>_Reminder_Emails/` at the repo root. One file per email, prefixed by sequence position (e.g. `01_week_before.md`, `02_day_of.md`).
