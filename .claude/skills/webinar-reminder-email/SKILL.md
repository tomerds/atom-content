---
name: webinar-reminder-email
description: Write webinar reminder emails for Atom (registration confirmations, day-before/day-of reminders, follow-ups with the recording). Use when asked to write any email in a webinar sequence.
---

# Webinar Reminder Email

## Before writing

1. Read every example in `examples/webinar-reminder-emails/` — match the voice, length, and structure. The examples are the source of truth. Reminder emails are short; resist padding.
2. Confirm before drafting: webinar title, date/time (with timezone), join link placeholder, speakers, and which email in the sequence this is (confirmation, day-before, day-of, follow-up). Ask for anything missing.

## Process

1. Create a folder at the repo root: `<Webinar_Name>_Reminder_Emails/`. If writing a sequence, put each email in its own file (`01_confirmation.md`, `02_day_before.md`, ...).
2. For each email include: 2–3 subject line options, preview text, and the body. Use `{{placeholders}}` for merge fields (first name, join link) rather than made-up values.

<!-- TODO: This skill is a scaffold. Refine once approved examples land in examples/webinar-reminder-emails/. -->
