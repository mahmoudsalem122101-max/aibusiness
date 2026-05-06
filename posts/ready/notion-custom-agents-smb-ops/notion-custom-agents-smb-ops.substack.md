Subject: Notion agents that run your ops

Notion just turned “our Notion is where we work” into “our Notion does the work.” The new **Custom Agents** can sit in the background and handle recurring, multi-step busywork across your tools, like routing requests, drafting weekly updates, and answering the same Slack questions all day.

## A quick scenario
It’s 8:12am. A client pings your team in Slack: “Can we change the delivery date?” Someone asks, “What’s the policy again?” Another person DMs you for an exception. Meanwhile, a sales rep needs the latest price sheet. By noon you have seven parallel threads, two different answers, and zero updated documentation.

A **Custom Agent** can answer the policy question (with the source link), create a tracked request in Notion, tag the owner, and post a clean status update back to Slack.

## What it is (plain English)
Custom Agents are AI “teammates” you configure to do a job repeatedly, not just chat once.

Think: job description + allowed tools + triggers + logs.

## Top SMB use cases
- Request router: Slack request → Notion database item → assign owner → ask 1 clarifying question → post tracking link back
- Weekly ops report: pull statuses → summarize blockers → post to Slack on schedule
- SOP/policy Q&A: answer repeat questions and cite the Notion source page every time
- Lightweight sales enablement: find the latest doc and draft a reply (you approve)

## Pricing (real numbers)
Notion’s pricing page lists Custom Agents as: “Free to try, then **$10 per 1,000 monthly Notion credits**.”

Notion’s announcement also notes a free beta window before credits kick in.

## A safe pilot checklist
1) Pick ONE workflow with a clear before/after (routing or reporting)
2) Create a dedicated agent space in Notion (edit only where it must write)
3) Limit Slack exposure (start with one channel, ideally @mention only)
4) Turn on usage alerts and auto-pause
5) Add approvals for anything external/customer-facing
6) Review run logs daily for the first week

## Risks to take seriously
- Prompt injection (content tries to manipulate the agent)
- Confidently wrong answers if your SOPs are messy
- Cost creep from always-on behavior
- Permission drift over time

If your team already lives in Notion and Slack, this is worth a 7-day controlled test.

Share this with someone building an AI business
