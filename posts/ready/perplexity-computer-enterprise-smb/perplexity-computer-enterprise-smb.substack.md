Subject: Slack-first AI agents for SMB ops

Slack can now be your “ops assistant.” Perplexity’s new Computer for Enterprise is an AI agent you can @mention in Slack to produce real deliverables across your tools, not just answers.

## A quick scenario
It’s Friday 4:45pm.
Support tickets are piling up, sales wants Monday call briefs, and ops needs the weekly update.

You drop one objective in Slack:

“@computer triage weekend support tickets by severity, draft customer responses, write escalation briefs, and package everything into a Monday standup doc.”

## What it is (plain English)
Perplexity Computer for Enterprise is a cloud AI agent that breaks a goal into steps, uses different AI models for different parts of the job, and pulls context from connected apps (Slack, email, docs, CRMs, and more) to produce a finished output.

## Top SMB use cases
- Support triage + Monday handoff doc
- Sales call prep briefs (CRM + notes)
- Weekly ops summaries from Slack channels

## How to implement without creating chaos
1) Pick ONE workflow and define “done.”
2) Create a dedicated agent service account (don’t use the founder’s admin).
3) Connect only what that workflow needs (start with Slack + docs).
4) Keep write actions behind approval.
5) Review outputs weekly and tighten templates.

## Risks to take seriously
- Prompt injection (especially if it reads tickets/emails/web content)
- Confident but wrong summaries
- Oversharing if you connect too many apps too quickly

Full post: aibusiness.press

Share this with someone building an AI business