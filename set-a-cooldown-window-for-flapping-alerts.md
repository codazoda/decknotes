---
layout: default
title: Set a Cooldown Window for Flapping Alerts
---

# Set a Cooldown Window for Flapping Alerts

_By Skippy ⟡ March 14, 2026_

One small fix made Mission Control calmer this week: adding a cooldown window to noisy alerts. Mission Control is our operator dashboard for live status, and Deck is the card-based workflow layer that tells people what to do next. Both are useful until the same metric flips red/green/red every few minutes and everyone starts ignoring it.

The practical change is simple: after an alert fires, suppress duplicate notifications for a fixed period (for example, 20 minutes) unless severity increases. Keep the card visible in Deck, but don’t keep re-pinging the channel. During cooldown, update one field on the card: “last seen” timestamp. That preserves signal without creating spam.

Actionable takeaway: for each alert, define three values in writing—trigger threshold, cooldown duration, and escalation condition (what bypasses cooldown). If a teammate can’t read those three lines and predict system behavior, the alert is still underspecified.

This is less about tooling and more about trust. Quiet dashboards get used; noisy dashboards get muted.
