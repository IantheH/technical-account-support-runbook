# Technical Account Support Runbook

A practical runbook for managing customer-facing technical issues in a SaaS environment.

This runbook is designed for Customer Success Managers, Technical Account Managers, implementation teams, and support-adjacent roles that need to communicate clearly, triage issues, manage escalations, and help customers stay confident during technical problem-solving.

---

## Template Key

Use the templates in this repo in this order:

1. [Issue Triage Template](template-01-issue-triage.md)  
   Capture the customer issue, business impact, priority level, troubleshooting notes, and next steps.

2. [Escalation Summary Template](template-02-escalation-summary.md)  
   Use when an issue needs support from product, engineering, a vendor, or another internal team.

3. [Post-Resolution Follow-Up Template](template-03-post-resolution-follow-up.md)  
   Use after the issue is resolved to close the loop with the customer, confirm resolution, and document follow-up needs.
---

## Purpose

Technical account support is not just troubleshooting. It is about helping customers feel informed, supported, and confident while issues are being investigated and resolved.

A strong technical support process should:

- clarify the customer’s issue
- understand business impact
- gather the right details
- prioritize the issue appropriately
- communicate clearly with the customer
- coordinate with internal teams
- document resolution steps
- reduce repeat issues over time

---

## Support Intake Framework

When a customer reports an issue, gather the following information:

### Customer Details

- Customer name
- Primary point of contact
- Account owner
- Date reported
- Affected users
- Business impact

### Issue Summary

- What is happening?
- What did the customer expect to happen?
- When did the issue begin?
- Is the issue recurring or one-time?
- Has anything changed recently?
- Which workflow, feature, integration, or user group is affected?

### Supporting Details

- Screenshots
- Error messages
- URLs or record IDs
- Browser/device details
- Steps to reproduce
- Related integrations
- Recent configuration changes

---

## Priority Levels

### P1 — Critical

Customer is unable to use a core business workflow, multiple users are blocked, or there is a major business impact.

Examples:

- platform unavailable
- payment workflow blocked
- major integration failure
- customer-facing process is down
- data access issue affecting operations

### P2 — High

Important workflow is affected, but a workaround may exist.

Examples:

- automation not firing
- reporting issue affecting decision-making
- limited integration issue
- admin or key user blocked

### P3 — Medium

Issue affects a non-critical workflow or a small number of users.

Examples:

- configuration question
- minor workflow issue
- non-urgent reporting request
- template or field update

### P4 — Low

General question, enhancement request, documentation need, or training opportunity.

Examples:

- how-to question
- feature clarification
- documentation request
- future improvement idea

---

## Triage Process

### 1. Acknowledge

Respond quickly and let the customer know the issue has been received.

Example:

> Thanks for flagging this. I’m reviewing the details now and will help determine the next step. I’ll follow up shortly with what I find or what additional information may be needed.

### 2. Clarify

Confirm the issue, scope, and business impact.

Questions:

- Who is affected?
- Is this blocking work?
- Is there a deadline or business event tied to this issue?
- Is there a workaround available?
- Has this happened before?

### 3. Reproduce or Validate

Attempt to confirm the issue using available information.

Check:

- user permissions
- workflow settings
- automation history
- integration status
- recent configuration changes
- data formatting
- system status
- known issues

### 4. Prioritize

Assign a priority level based on impact, urgency, and scope.

### 5. Escalate if Needed

Escalate when:

- the issue cannot be resolved at the account/support level
- engineering or product input is required
- a system defect is suspected
- customer business operations are materially affected
- sensitive data or access concerns are involved

### 6. Communicate

Keep the customer informed with clear, non-technical updates when possible.

### 7. Resolve and Confirm

Once resolved, confirm with the customer that the issue is fixed and the workflow is working as expected.

### 8. Document

Capture the issue, cause, resolution, and any follow-up recommendations.

---

## Customer Communication Principles

Good technical account support requires clear communication.

Use communication that is:

- calm
- specific
- timely
- transparent
- customer-friendly
- free of unnecessary jargon
- focused on next steps

Avoid:

- overpromising
- blaming internal teams
- giving unclear timelines
- using technical language without explanation
- closing an issue before the customer confirms resolution

---

## Escalation Summary Template

Use this when escalating an issue internally.

```text
Customer:
Primary Contact:
Date Reported:
Priority:
Affected Users:
Business Impact:

Issue Summary:
[Briefly describe what is happening.]

Expected Behavior:
[What should happen?]

Actual Behavior:
[What is happening instead?]

Steps to Reproduce:
1.
2.
3.

Troubleshooting Completed:
-
-
-

Supporting Links / Screenshots:
-

Customer Communication Status:
[What has been communicated so far?]

Requested Next Step:
[What is needed from support/product/engineering?]
