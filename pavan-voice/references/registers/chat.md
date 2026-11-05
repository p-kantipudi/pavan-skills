# Chat (Teams DMs, group and meeting chats, channel replies)

Calibrated on 98 of Pavan's own Teams chat messages (about 1,070 words) sampled from June, July, September, October and November 2026. Code snippets, bare links and pasted secrets were left out. Numbers: `references/voice-fingerprint.md`.

## Scope and before you draft

- Covers DMs, group chats, meeting chats, and replies inside a channel thread. Email and top-level channel posts are comms.
- You need who it is for (1:1, group, or a senior person) and the message you are answering. If either is missing, ask in one short question before drafting. If you have both, draft. Never invent a promise, time, or reason the user did not give.
- Mirror the thread: its casing, length, and tone.
- A single message over 30 words is rare for him (under 5%). If the content needs more, split it into 2 or 3 short messages or switch to comms.

## Rules

1. **Size.** Median message is about 9 words; 3 in 4 are 14 words or fewer. One thought per message. A reply is often a burst of 2 or 3 short lines, each adding one fact.
2. **Bare answers are normal.** "yes", "ok", "will do", "only in grafana", "this is prod though", "the pdf document". Do not restate the question.
3. **Drop the subject when it is obvious.** "generated new key", "will check again", "Trying to create a pat token, not sure if i have access". This is his habit; keep it.
4. **Casing.** About 73% of messages start lowercase. Standalone "i" is lowercase about two times in three ("i am exploring more as we speak"); capital "I" shows up more at the start of longer, more formal messages ("I have created a epic for this..."). Either is fine in chat. Never lowercase "i" in email or docs.
5. **"u" for "you".** Used in about 1 of 4 places ("do u have a min?", "did u get them from aws?", "u available?"). Mostly in short questions to one person. Use "you" in anything longer or to someone senior.
6. **End marks.** About 70% of messages have no end mark. About 1 in 5 ends with "?". A closing period is rare (6%). No "!" except on thanks ("that works. Thank you!"), about 1 message in 100.
7. **Asks.** Short and direct: "can you ...", "did u ...", "do you know ...?", "is it ok to ...". One question per message. To confirm, he states the belief and tags it: "..., correct?", "isn't it the case?", "i thought we changed to master".
8. **Calls are fine.** He asks for a call when it is faster: "call?", "quick call?", "do u have a min?", "u available?". These are whole messages on their own. Use one when the user wants to talk live; do not add one to a written answer.
9. **Hedges he uses.** "i thought ...", "i guess ...", "I am assuming ...", "I would say 3-4 days", "hoping ...", "Looks like ...". He does not open with "I think".
10. **Acknowledgements.** "ok", "Ok", "aah ok", "aah ok. Makes sense", "Got it, thanks", "will do", "yes". "thanks" and "thank you" both appear; keep them short.
11. **Mentions.** Name first when pulling someone in: "[Name] do you have any Airflow docs you can share...?", "[Name], i am trying to use gcx login to Grafana."
12. **Light threads.** ":)" glued to the word before it ("lost the internet connection on my first aab:)", "I dont need a flight though:)"). Use only when the thread is personal or light. No "lol", no emoji.
13. **Contractions.** He writes "i am", "I have", "I will" in full; "I'm", "I'll" do not appear in chat. "dont" and "its" without apostrophes are common slips; do not add them deliberately, but do not "correct" a draft into formal English either.
14. **Formatting.** Plain text. A link goes in its own message. Technical names stay as he types them (scoring.api, tiger.business.api, nonprod, prod).

## Samples (synthetic, matching his measured shape)

Reply to "did the deploy fix it?":

> not yet
> still seeing errors in grafana for scoring.api

Starting a thread:

> do u have a min?

Status in a group chat:

> The db connection is set to master and we are resetting iis to fix the problem

Confirming a belief:

> but the new build would need the new cert, correct?
