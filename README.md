# Creator Desk (Flip the Switch)

Support team of Switch agents for a creator program: FAQ answers with citations, submission logging, escalation to a human manager, and a weekly insight report.

Track: Best Business Workflow. Built on the official Switch `support-desk` template.

## Repo layout

- `creator-desk.template.yaml` — greeter, policy, analyst across intake + escalations
- `docs/` — fake AuraLabs Creator Circle FAQ, rules, deadlines, payouts (RAG via file read)

## Day plan

1. Nov 4 — Switch Console quickstart, instantiate template, connect Discord, drop docs into agent directories
2. Nov 5 — Tune greeter, submissions document, escalation flow (see SETUP.md)
3. Nov 6 — Policy + analyst report, optional Slack, 30 questions in demo-test-questions.md
4. Nov 7 — README polish, 3 min demo, blog / #HowISwitch, submit by 11:59 PM IST

## Demo script

1. Creator asks how payouts work → greeter cites `docs/payouts.md`
2. Creator submits a video link → row appended to submissions document
3. Creator disputes a rejected payout → escalated to policy + manager
4. Manager asks for this week's report → analyst posts top questions and a docs gap

## Spec

Full build spec: Flip the Switch canvas (Creator Desk). Switch docs: https://docs.switchagents.ai/
