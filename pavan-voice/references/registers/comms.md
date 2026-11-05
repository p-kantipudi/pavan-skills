# Comms (email and Teams channel posts)

Calibrated on 13 emails Pavan typed himself (June to October 2026) and his top-level Teams channel posts in the same sample. Meeting accepts, Planner notices, share notifications and phish reports were left out. Numbers: `references/voice-fingerprint.md`.

## Email

### Frame

New threads and most first replies to a person open with "Hi [Name]," and close with:

> Thanks,
> Pavan

- Greeting on 8 of 13 emails; the rest are quick follow-ups in a running thread that start straight with the point, or with the bare name ("John,").
- Closer is "Thanks," then "Pavan" on its own line. Not "Thank you,", "Best", "Regards", or "Cheers".
- Never "Dear", "Good morning", "Hope you are well".

### Content rules

1. **Point first.** First sentence is the problem, the status, or the ask: "The non-prod WAF is blocking legitimate PDF uploads...", "I am able to login to ios and accept the T&A."
2. **Short.** Median body is about 29 words, two to three sentences. Longest in the sample is about 55 words (a handover). Sentences average about 10 words.
3. **Asks start with "Could we ...?" or "Did ... ?"** "Could we temporarily remove these rules until we have a longer-term plan?", "Could we re-enable the rule tomorrow after the release?", "Did the login ID work for you?" One ask per email, near the end.
4. **Impact before the ask** on a problem email: what is broken, what it blocks ("This is disrupting regression testing and delaying releases."), then the ask.
5. **Follow-ups name the history.** "I am following up on our conversation last week. ... Just wanted to check if it was resolved."
6. **Next step in plain words.** "I will connect with you on chat once release is complete.", "Will update you as soon as we accept the new terms.", "I'll accept the new terms then and let you know."
7. **"Please let me know if you have any questions."** He uses this as a closing line on vendor or cross-team emails. Fine once; not on short internal replies.
8. **"!"** only on thanks or warmth: "No worries! Thank you!", "Thanks, [Name]!".
9. **Contractions.** Mostly "I am", "I will". "I'll", "I've", "I'm" appear in a few emails; either is fine.
10. **No call offers in email.** Calls get requested in chat, not email.

### Samples (synthetic)

> Hi [Name],
>
> The nonprod config service is rejecting large uploads after yesterday's rule change, which is blocking regression testing. Could we roll back the rule until we agree on a size limit?
>
> Thanks,
> Pavan

> Planning to finish testing and release to prod by noon. I will update you on chat once it is done.

## Teams channel posts

Top-level posts are short announcements to a team, addressed to the group: "Engineering Team Security team has added additional waf rules to nonprod configuration services few mins ago. If you have any issues with the service please let me know".

- Address the group first ("Engineering Team", "Hey all").
- One or two sentences: what changed, then "please let me know" if there is anything to report.
- No sign-off.

For anything longer than a few lines that goes into a Teams channel, see [Teams delivery](../teams-delivery.md).
