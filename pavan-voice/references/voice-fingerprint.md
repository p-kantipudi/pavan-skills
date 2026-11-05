# Pavan's voice fingerprint

Measured on 2026-11-05 from Pavan's own Microsoft 365 messages. The rule files quote short phrases from his real messages as examples (some name internal systems); the longer samples are synthetic. Keep this skill in a private repo, or scrub those quotes before publishing it.

## Corpus

| Source | Items | Words | Dates |
| --- | --- | --- | --- |
| Teams chat messages he sent (DMs, group, meeting chats, channel replies) | 98 | about 1,070 | Jun, Jul, Sep, Oct, Nov 2026 |
| Emails he typed himself | 13 | about 390 | Jun to Oct 2026 |

Left out: code and PowerShell snippets, bare links, pasted secrets, meeting accepts, Planner and SharePoint notifications, phish reports, quoted text from other people.

Caveat: this is a small sample. Treat the numbers as directional and re-measure with a larger pull before tightening the checker.

## Chat

| Measure | Value |
| --- | --- |
| Median words per message | 9.5 |
| Mean words per message | 10.9 |
| 75th / 90th percentile words | 14 / 22 |
| Starts lowercase | 73% |
| Ends with "?" | 21% |
| Ends with "." | 6% |
| No end mark | 70% |
| Has "!" | 1 of 98 |
| ":)" | 3 of 98 |
| Standalone "i" lowercase vs "I" | 27 vs 14 |
| "u" vs "you" | 8 vs 22 |
| "i am" / "I'm" | 10 / 0 |
| "I will" / "I'll" | present / 0 |
| "I think" | 0 |
| Hedges used | "i thought" 2, "i guess" 1, "I am assuming", "I would say", "hoping", "Looks like" |
| Call asks | "call?" / "quick call?" 4, "do u have a min?" 1, "u available?" 1 |
| Acks | "ok" 8, "aah ok" 2, "yes" 3, "will do", "Got it, thanks" |

## Email

| Measure | Value |
| --- | --- |
| Median body words (no greeting, no sign-off) | 29 |
| Range | 4 to 55 |
| Mean sentence length | 10.3 words |
| Opens with "Hi [Name]," | 8 of 13 |
| Closes "Thanks," + "Pavan" | 6 of 13 (every email with a greeting but two short ones) |
| Closes "Thank you," | 0 |
| Emails with a "?" | 3 of 13, one each |
| Ask form | "Could we ...?", "Did ... ?" |
| Em dashes | 0 |

## Not yet measured

Docs, exec, spoken, and blog have no Pavan data yet. Their register files keep general writing rules from the skill's original author and are marked as uncalibrated.
