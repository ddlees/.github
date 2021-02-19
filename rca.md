---
name: Root Cause Analysis
about: A postmortem for a disruption of services
title: "[RCA] Enter your RCA title here"
labels: Epic, RCA
assignees: ''

---

# RCA - <title of incident>
(Action Items associated w/ Epic)

### Date(s)

## Summary
<!-- Provide a brief 1-2 sentence summary of the incident -->
<!-- e.g. - <Feature/Service> was unavailable for <duration> due to <cause> -->

## Impact
<!-- What was the impact to clients, revenue, business value, etc.? -->

## Root Causes
<!-- An explanation of the circumstances in which this incident happened. Use the 5 Whys (https://en.wikipedia.org/wiki/5_Whys) technique to understand the contributing factors -->

## Trigger
<!-- If known, describe what ultimately triggered the incident -->

## Resolution
<!-- In 100 words or less, describe how the incident was resolved -->

## Detection
<!-- How did we find out about this incident? Were there monitoring alerts in place? Did a client tell us? etc. -->

# Lessons Learned

### What went well
<!-- What systems or processes were in place that helped resolve this incident? -->

### What went wrong
<!-- What were the contributing factors that led to an escalation beyond our normal error budget and incident response process? -->

### Where we got lucky
<!-- This section is really for near misses -->
<!-- e.g., “The goat teleporter was available for emergency use with other animals despite lack of certification.” -->

# Supporting Information
<!-- Useful information, links, logs, screenshots, graphs, chat logs, etc. -->

# Timeline
<!-- A “screenplay” of the incident; use the info from relevant issues to start filling in the postmortem timeline, then supplement with other relevant entries, such as any Box notes used during triage to collect information. -->

| Time  | Description |
| ----- | ----------- |
| 00:00 | **INCIDENT BEGINS**  |
| 00:00 | **INCIDENT REPORTED**  |
| 00:00 | **INCIDENT REPORTED**  |
| 00:00 | **INCIDENT ENDS**   |
| 00:00 | **INCIDENT CLOSED**  |

# Action Items
Action items created in response to this postmortem RCA should be added to this Epic, [using the appropriate template](./postmortem-action-item.md) and labeled with the correct **type**:
- _mitigate_: These action items help mitigate the impact of this outage in the future.  e.g, updating a playbook with instructions for responding to the root cause more quickly in the future.
- _prevent_: This action item will contribute to preventing the root cause of the issue in the future.
- _process_: These action items reflect changes in process that help us avoid the outage in the future.
