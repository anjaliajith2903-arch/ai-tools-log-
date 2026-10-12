# Which AI tool is best for which part of the sales cycle?

*A hands-on test of ChatGPT, Claude and Gemini on three everyday sales tasks. By Anjali Ajith, October 2026.*

## Why I did this

In my [Instinct notes](instinct.md) I found that AI assistants are pitched as helpers for the admin around selling: researching prospects, writing follow-ups and keeping records. I wanted to test whether the everyday tools most people already have can actually do those jobs, and which one does each job best.

## How I tested

- **3 tasks**, each one a real step in the sales cycle:
  1. Prospect research before a call
  2. Follow-up email after the call
  3. Turning messy call notes into a CRM record
- **3 tools:** ChatGPT, Claude and Gemini (free web versions)
- **Same prompt, word for word**, in each tool, so the only difference is the tool
- **Scenario:** I play a sales rep selling a marketing analytics tool to Medtronic Ireland. The contact (Sarah Byrne) and the call are made up for the test.
- I scored each answer from 1 to 3 stars on what matters to a sales rep

---

## Task 1: Prospect research

**Prompt**
```
I'm a sales rep about to call Medtronic Ireland to sell them a marketing analytics tool. In under 200 words: what they do, who I should speak to (job titles), 2 likely business problems, and 2 opening questions for the call. List your sources.
```

| | ChatGPT | Claude | Gemini |
|---|---|---|---|
| Accuracy and sources | ⭐⭐⭐ | ⭐⭐ | ⭐ |
| Up to date | ⭐⭐ | ⭐⭐⭐ | ⭐ |
| Opening questions | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| Honesty about uncertainty | ⭐⭐⭐ | ⭐ | ⭐⭐ |

**What I noticed**
- **ChatGPT** used the most trustworthy sources (Medtronic's annual report and Irish report) and clearly labelled its business problems as *"hypotheses to validate"*. It also gave a smart tip: check whether buying decisions are made locally or globally.
- **Claude** found recent news (a new Galway software hub, the MiniMed split, tariff pressure), which made its opening questions the most specific, e.g. *"With the MiniMed separation, how are you re-baselining marketing performance?"* But it stated those problems as facts, and some sources were news sites and a German trading blog, so the figures need checking.
- **Gemini** gave the most generic answer. It could have described almost any medtech company, and one of its two sources was a recruitment agency page.

**Lesson:** AI can produce a solid call-prep brief in about a minute, but a rep must still check the facts before quoting them to a customer.

---

## Task 2: Follow-up email

**Prompt**
```
I just had a 20-minute sales call with Sarah Byrne, Head of Marketing Operations at Medtronic Ireland. I sell a marketing analytics tool. My call notes: they struggle to link campaign data to sales results; reports take her team 2 days each month; she liked our dashboard demo; she needs to check budget with her director, Mark; next step is a demo for Mark in 2 weeks. Write a short follow-up email (under 150 words) that thanks her, recaps her problems, and proposes 2 time slots for the demo with Mark. Professional but warm, Irish/UK spelling.
```

| | ChatGPT | Claude | Gemini |
|---|---|---|---|
| Sounds human | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| Complete (subject, recap, time slots) | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| Accuracy | ⭐⭐⭐ | ⭐⭐⭐ | ⭐ |

**What I noticed**
- **ChatGPT** wrote a correct, polite email but forgot a subject line, and phrases like *"clear opportunities to streamline reporting"* sound like AI.
- **Claude** wrote the email most like a real rep's: a subject line, the two problems as bullet points (easy for Sarah to forward to Mark), and human phrasing like *"give that time back to your team"*.
- **Gemini** had the clearest recap, but made a real mistake: it put the meeting times in **"IST"**. Irish clocks go back on 25 October 2026, so on 27 October Ireland is on GMT, and many readers would take "IST" to mean India Standard Time. It also pushed for *"budget alignment"* before Sarah had even spoken to Mark.

**Lesson:** AI drafts a good follow-up in seconds, but a rep must check dates, time zones and tone before sending.

---

## Task 3: Call notes to CRM record

The notes were deliberately messy, with traps: an unsure budget, a "maybe" date, and an unconfirmed personal detail.

**Prompt**
```
Turn my messy call notes into a clean CRM record with these fields: Contact name, Job title, Company, Deal stage, Estimated deal value, Pain points, Competitors mentioned, Decision maker, Next step, Next step date, Risk level (Low/Med/High) with reason. If something isn't in the notes, write "Unknown" - don't guess.

Notes: call w/ sarah byrne medtronic IE, head mktg ops. 20 min. reporting takes 2 days/mo, cant link campaigns to sales. liked dashboard demo!! they use tableau a bit but nobody likes it. budget prob 15-20k/yr? not sure. needs mark (director) sign off. demo for mark in 2 wks, maybe tue 27th. she's leaving on mat leave in dec??
```

| | Claude | ChatGPT | Gemini |
|---|---|---|---|
| Followed "don't guess" | ⭐⭐⭐ | ⭐ | ⭐ |
| Kept uncertainty | ⭐⭐⭐ | ⭐⭐ | ⭐ |
| Privacy awareness | ⭐⭐⭐ | ⭐ | ⭐ |

**What I noticed**
- **Claude** followed the rules best: deal stage "Unknown", budget "unconfirmed, currency not stated", date "tentative". It also advised keeping the maternity-leave detail out of a shared CRM (personal and health details are sensitive under GDPR) and suggested writing *"Contact may be unavailable from December"* instead.
- **ChatGPT** was tidy and added a useful follow-up checklist, but it guessed the deal stage ("Demo / Evaluation"), assumed the budget was in euros, and wrote the maternity leave straight into the record.
- **Gemini** said it was *"based strictly on your call notes"* but guessed the most: it invented the deal stage and currency, turned *"maybe tue 27th"* into a fixed date and *"mat leave in dec??"* into a fact.

**Lesson:** AI saves real time on CRM admin, but it fills gaps with confident guesses. Wrong data in a CRM spreads to forecasts and handovers, so a rep must check every field.

---

## Overall results

| Sales task | Best tool | Why |
|---|---|---|
| Prospect research | ChatGPT (facts) / Claude (conversation starters) | ChatGPT had the most reliable sources; Claude had the most specific, up-to-date angles |
| Follow-up email | Claude | Most human, complete and accurate |
| CRM record | Claude | Only tool that didn't guess, and it flagged a privacy risk |

## What can be automated in sales, and what can't

| Step | Automate with AI? | Human still needed for |
|---|---|---|
| Prospect research | Mostly yes | Checking facts and figures before using them |
| Follow-up emails | Yes, as a first draft | Dates, time zones, tone, not over-promising |
| CRM updates | Partly | Checking every field, keeping personal details out |

## My takeaway
What surprised me most was how confidently the tools guessed. Even when I wrote "don't guess", two of them invented a deal stage and a currency, and one turned "maybe" into a fixed date. The biggest time savings were in follow-up emails and call prep, where each tool gave me a usable first draft in seconds.

In a sales or marketing ops role, I would use AI to draft research briefs, follow-ups and CRM notes, then spend my time checking facts, dates and privacy. That way AI does the repetitive work and I make sure the data the team relies on is right.