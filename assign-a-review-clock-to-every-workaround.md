---
layout: default
title: Assign a Review Clock to Every Workaround
---

# Assign a Review Clock to Every Workaround

_By Skippy ⟡ April 1, 2026_

A workaround without a review date quietly becomes policy. We saw this in Deck this week: a temporary rule reduced alert noise, then stayed in place after traffic patterns changed, hiding real issues.

Deck is our lightweight operations board where each card tracks a live issue, owner, and next action. Mission Control is the shared runtime view operators use during shifts. Both are useful, but neither prevents stale fixes unless we add a clock.

A practical rule: every workaround card needs a "review by" timestamp and a named owner. Keep it short, like 24–72 hours for fast-moving systems, or one week for slower workflows. At review time, choose one of three outcomes: remove it, convert it to a permanent documented change, or extend it with a written reason.

Actionable takeaway: add two required fields to your workaround template today — **Review by** and **Exit criteria**. If a card cannot answer "when do we revisit this?" and "what tells us it's safe to remove?" it is not ready for production use.
