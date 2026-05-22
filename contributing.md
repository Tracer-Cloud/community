# Contributor & PR Guidelines

These guidelines are intended to keep collaboration, reviews, and discussions organized as the project grows.

---

## Issue Claiming

- Please claim or discuss an issue before starting significant work.
- Avoid starting work on issues already assigned to someone else unless coordinated first.
- Issues inactive for 2+ days may be reassigned to keep progress moving.

---

## PR Scope

- Keep PRs focused and reasonably scoped to a single issue or change area.
- Large PRs touching unrelated systems are significantly harder to review and validate.
- Follow-up improvements are usually better handled in separate PRs.

---

## PR Descriptions

PR descriptions should clearly explain both the implementation and reasoning behind the change.

**Please include:**

- What changed
- Why the previous behaviour was incorrect or insufficient
- Why the new behaviour is more correct (not only "working")
- What scenarios or edge cases are improved
- What was validated locally

**Recommended additions when relevant:**

- Tests executed
- Screenshots
- Logs
- Reproduction steps
- Demo videos
- Before/after behaviour or validation output

---

## Tagging / Mentions

- Avoid excessive tagging or mentioning multiple unrelated people/issues.
- Only tag reviewers or contributors directly related to the PR.
- Keep review threads focused and easy to follow.

---

## Validation

- Behavioural, orchestration, workflow, or UI-related changes should generally include validation material.
- Screenshots, logs, traces, or short demo videos are often the fastest way to clarify behaviour changes.
- Validation artifacts are best included directly in the PR description.

---

## Review Feedback

- Address review feedback before opening multiple follow-up PRs in the same area.
- Avoid stacking several overlapping PRs without resolving earlier review comments first.
- If requirements or implementation direction become unclear, clarify before continuing.

---

## PR Lifecycle

PRs may remain open if:

- Review feedback is still pending
- Additional validation is required
- Implementation details are still under discussion
- The scope of the change is evolving

PRs may be closed if:

- They remain inactive for an extended period
- The implementation diverges significantly from the issue scope
- Substantial regressions are introduced
- Required follow-up changes are not addressed
- Overlapping work is already being handled elsewhere

---

## Discussion Quality

- Avoid spam comments, unnecessary noise, or repeated pings in review threads.
- Keep discussions respectful, constructive, and technical.
- Use the appropriate channels for questions, implementation discussions, and research-related topics.

---

## General Expectations

- Prioritize correctness, maintainability, and clarity over rushing changes.
- Small, well-tested, well-explained PRs are generally reviewed faster and more effectively.
- Contributor quality matters more than contributor volume.
