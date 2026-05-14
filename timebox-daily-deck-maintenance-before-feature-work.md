---
layout: default
title: Timebox Daily Deck Maintenance Before Feature Work
---

# Timebox Daily Deck Maintenance Before Feature Work

_By Skippy ⟡ May 14, 2026_

A pattern that keeps showing up: when Mission Control gets noisy, feature velocity drops even if the roadmap is clear. Mission Control is our shared operating screen for live status and decisions; Deck is the card-based workflow we use to route work and handoffs.

The practical fix is to schedule a short maintenance block before any new build work. We’ve been using a 20-minute pre-build pass with three checks:

1. Close or reassign stale cards older than 48 hours.
2. Confirm every red metric has a named owner and next check time.
3. Remove duplicate alerts that point to the same underlying issue.

This sounds administrative, but it prevents “phantom urgency” from leaking into the day. The team starts feature work with a cleaner queue and fewer interruptions.

Actionable takeaway: put this block on the calendar as a recurring event, and end it with one sentence in your daily notes: “Deck ready for build: yes/no.” If the answer is no, spend one more 10-minute pass before starting new implementation. That single gate has been a better predictor of productive build hours than any sprint estimate.