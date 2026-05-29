# First Contribution / Getting Started

Welcome to OpenSRE

This document is intended to help new contributors understand how the project and review process work before opening their first PR.

The goal is not to add unnecessary rules, but to reduce confusion and make collaboration smoother for everyone.

---

## Before You Start

Please take a few minutes to read:

- [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- [`rules.md`](./rules.md)
- Existing PRs and review comments
- Relevant issue discussions

A lot of common mistakes can be avoided just by understanding the existing project flow first.

---

## Picking an Issue

If this is your first contribution, please start with:

- `good first issue` labeled issues
- Small bug fixes
- Documentation improvements
- Focused test fixes
- Small tooling improvements

**Avoid starting with:**

- Large refactors
- Broad architectural changes
- Multi-system PRs
- Huge feature additions

Large changes are significantly harder to review and validate for first-time contributors.

---

## Claiming an Issue

Before starting work:

- Comment on the issue first
- Wait for confirmation or assignment if needed
- Avoid working on issues already assigned to someone else

If an assigned issue stays inactive for 2+ days, it may be reassigned to keep work moving.

---

## First PR Expectations

Please focus on getting your first PR merged successfully before opening multiple additional PRs.

This helps contributors:

- Better understand the project flow
- Understand review expectations
- Avoid overlapping or conflicting work

One PR should generally focus on one issue or one clearly scoped concern.

**Please avoid:**

- Combining many unrelated issues into one PR
- Opening many PRs simultaneously as a first-time contributor
- Mass tagging multiple people/issues for visibility

Quality and clarity matter more than PR volume.

---

## Before Opening a PR

Before opening a PR, make sure you:

- Understand the issue scope
- Read related files and tests
- Run local checks
- Understand why the current behaviour is incorrect
- Understand why your solution is more correct

> A working fix is not always a correct fix.

---

## Writing a Good PR Description

A strong PR description should explain:

- What changed
- Why the previous behaviour was incorrect
- Why the new behaviour is more correct
- What scenarios are improved
- What was tested locally

**When relevant, include:**

- Logs
- Screenshots
- Reproduction steps
- Validation output
- Demo videos
- Before/after behaviour

This makes reviews significantly faster and easier.

---

## Reviews & Feedback

Review feedback is part of the contribution process.

**Please:**

- Respond to feedback constructively
- Clarify requirements when unsure
- Update the PR before opening more follow-up PRs in the same area

Sometimes a PR may stay open for a while because:

- More validation is needed
- Discussions are ongoing
- The implementation direction is still evolving

Sometimes PRs may also be closed if:

- The scope changes significantly
- The implementation introduces regressions
- The work overlaps with another PR
- The PR becomes inactive

This is a normal part of maintaining a growing open-source project.

---

## Communication & Discussion

Please keep discussions respectful, constructive, technical, and organized.

**Avoid:**

- Spam comments
- Repeated pings
- Unnecessary review noise
- Pressuring reviewers for immediate responses

Use the appropriate Discord channels for questions and discussions:

- `#contribute` → Contribution help and guidance
- `#review-me` → PR reviews and feedback
- `#general` → General OpenSRE discussions
- `#research-dse-bench` → Research and benchmarking discussions
- `#server-faq` → Common questions
- `#resources` → Learning materials

---

## Final Advice

The fastest way to grow in OpenSRE is:

- Smaller focused PRs
- Good communication
- Strong testing
- Thoughtful review participation

Maintainers care much more about consistency, collaboration quality, and engineering judgement than raw PR count.

Thanks for contributing. 
