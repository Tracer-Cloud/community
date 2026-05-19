# Security Policy

This policy covers how to privately report security vulnerabilities or sensitive concerns to the OpenSRE core team, and how reports are handled internally.

## Reporting a vulnerability

**Do not** open a public GitHub issue, post in Discord, or share details in any public channel.

Instead, report privately through one of the following channels:

- **Email:** `support@opensre.com`
- **GitHub private vulnerability reporting:** use the "Report a vulnerability" button on the affected OpenSRE repository (`Security` tab → `Report a vulnerability`).

Please include:

- A description of the issue and the impact you believe it has.
- Steps to reproduce, or a proof of concept if you have one.
- The affected version, commit, or deployment.
- Any relevant logs, screenshots, or supporting material (redact sensitive data).
- Your preferred contact and whether you want public credit if the report is valid.

## What to expect

- **Acknowledgement:** within `<TBD: e.g. 72 hours>` of receipt.
- **Triage update:** within `<TBD: e.g. 7 days>`, with an initial severity assessment.
- **Fix timeline:** depends on severity. Critical issues are prioritized; you will receive periodic updates until resolution.
- **Disclosure:** we prefer coordinated disclosure. If you intend to publish, please coordinate timing with us first.

## Scope

In scope:

- OpenSRE code in repositories under the Tracer-Cloud GitHub organization.
- Official OpenSRE-operated services and infrastructure.

Out of scope:

- Third-party services we integrate with (report directly to the vendor).
- Social engineering of OpenSRE team members.
- Denial-of-service testing against production.
- Reports based solely on outdated software versions without a demonstrable issue.

## Internal handling

The OpenSRE core team handles reports as follows:

1. **Intake.** A core team member acknowledges the report within the stated SLA. A private tracking issue is created in a security-only repository or location.
2. **Triage.** Severity is assessed (e.g. CVSS or an internal rubric). The relevant maintainers are looped in on a need-to-know basis.
3. **Fix.** A patch is developed in a private branch or fork. Tests added where reasonable. Reviewed by at least one additional maintainer.
4. **Coordinate.** If the issue affects downstream users or operators, prepare an advisory and a public-facing summary. Coordinate timing with the reporter.
5. **Release.** Ship the fix in a tagged release. Publish the advisory (e.g. GitHub Security Advisory). Credit the reporter if they consented.
6. **Postmortem.** Review the root cause and update internal processes to prevent recurrence.

## Reporting moderation or community concerns (not security)

Use the appeals/report-a-moderator flow described in [README.md](README.md), not this policy.
