# OctoAcme — Process Templates & Accountability Checklists

Use these lightweight templates to improve clarity and reduce handoff or escalation ambiguity across the lifecycle.

## Lightweight RACI Matrix Template

Use at initiation and refine during planning.

| Workstream / Decision | Project Manager (PM) | Product Manager (PdM) | Developers | UX Designer | DevOps / Platform | Data Analyst | Support Lead |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Problem framing & scope | A | R | C | C | I | C | C |
| Backlog prioritization | C | A/R | C | C | I | C | C |
| UX and accessibility definition | I | C | C | A/R | I | I | C |
| Implementation and code quality | I | I | A/R | C | C | I | I |
| CI/CD and deployment readiness | C | I | C | I | A/R | I | C |
| Success metric instrumentation | I | C | C | I | I | A/R | I |
| Release comms and support readiness | A | C | I | I | C | C | R |

Legend: R = Responsible, A = Accountable, C = Consulted, I = Informed.

## Dependency & Escalation Checklist

Use during planning and weekly execution reviews.

- [ ] Dependency owner named for each external dependency
- [ ] Needed-by date and impact level documented
- [ ] Fallback path documented if dependency slips
- [ ] Escalation trigger defined (for example, blocked > 2 business days)
- [ ] Escalation path confirmed (Team -> PM -> PdM/Platform -> Sponsor)
- [ ] Communication owner assigned for each escalation step
- [ ] Decision captured in the decision log when trade-offs are made

## Release Readiness Checklist (Cross-functional)

Use before release approval to confirm owner coverage.

- [ ] PM owner confirms timeline, approvals, and stakeholder notification plan
- [ ] PdM owner confirms scope, acceptance criteria, and known trade-offs
- [ ] Developer owner confirms final validation, migrations, and smoke checks
- [ ] DevOps / Platform owner confirms monitoring, alerting, and rollback steps
- [ ] Data Analyst owner confirms instrumentation and post-release dashboard checks
- [ ] Support Lead owner confirms support brief, FAQ updates, and escalation contacts
- [ ] Communication owner confirms release note publication and audience messaging

## Handoff & Decision Log Template

Use when ownership changes or major decisions are made.

### Handoff Note
- Date:
- From role/person:
- To role/person:
- Context:
- Open risks/dependencies:
- Required follow-up by date:
- Links to artifacts:

### Decision Log Entry
- Decision ID:
- Date:
- Decision owner:
- Decision summary:
- Options considered:
- Rationale:
- Impacted milestones/teams:
- Follow-up actions (owner + due date):
