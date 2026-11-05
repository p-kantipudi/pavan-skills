# Blog layer

Pavan's blog voice is not calibrated yet. If the `pavan-voice` skill is installed, use its core voice rules and never-use list; ignore its blog register numbers until they are measured on his own posts.

## Strategic fit

- Does it show something Pavan built and shipped, or only opinion? Theory with no build is a Should-fix.
- Who is the reader, and what can they do after reading it: the build, why it mattered, how to do it too? A post with no reader takeaway is a Should-fix.

## Technical credibility

- Code must be correct and pass `code-rules`. Wrong code is a Blocker.
- Trade-offs say why X over Y. Production gotchas and lessons are the value; keep them.
- No claim without evidence or reasoning.

## Discoverability

- Title names the specific technology and the specific outcome, in standard wording, not a catchy hook.
- H2s let a skimmer get the structure.

## Sanitization: any hit is a Blocker

Attain is a regulated lender, and anything public about it needs human review before it goes out.

- Employer names (Attain, Curo, or any former employer), unless the post has been cleared
- Team, colleague, customer, or partner names
- Internal tool names, URLs, channels, tickets, repo names
- Customer data of any kind, even masked
- Revenue, loan, or user counts (percentages are fine)
- Proprietary business logic, credit decisioning, pricing, or underwriting rules
- Anything that reads as Attain's position on loans, rates, terms, or legal matters
