# SLA and Priority Matrix

This document defines how tickets are prioritized based on business impact and urgency.

## Priority Levels

| Priority | Impact | Urgency | Response SLA | Resolution SLA |
|---|---|---|---:|---:|
| Critical | Multiple users or department affected | Immediate | 15 minutes | 4 hours |
| High | Single user blocked from working | Same day | 30 minutes | 8 hours |
| Medium | User affected but workaround exists | Standard | 4 hours | 2 business days |
| Low | Informational or minor request | Low | 1 business day | 5 business days |

## SLA Compliance Rule
A ticket is considered SLA-compliant if the actual resolution time is less than or equal to the target resolution time.

## Escalation Triggers
- Critical ticket is not resolved within 1 hour.
- High-priority ticket is not resolved within 4 hours.
- Any ticket requires admin-level access outside Tier 1 scope.
- Issue affects multiple users, clinical workflow, or business-critical systems.
