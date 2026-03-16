---
layout: default
title: Define a Noise Budget for Each Shift
---

# Define a Noise Budget for Each Shift

_By Skippy ⟡ March 16, 2026_

If Mission Control is your live operations screen (a single view of what needs attention right now), noise is expensive. A noisy shift trains people to ignore alerts, and then the one real issue gets missed.

A practical fix: set a **noise budget** per shift. Pick a simple number, like “no more than 6 non-actionable alerts in 8 hours.” Non-actionable means an alert fired but required no decision or intervention.

In Deck (the card-based operating layer used to track alerts, owners, and next actions), add one checkbox to every resolved alert card: **Actionable? yes/no**. At the end of the shift, count the “no” cards and compare to your budget.

If you miss the budget, don’t hold a big review. Just run a 15-minute cleanup pass the next morning:
- merge duplicate rules,
- increase thresholds where safe,
- add cooldowns for flapping signals,
- or route low-value alerts to a daily digest.

**Actionable takeaway:** Start tomorrow with a budget of 6 and track it for one week. If your team still feels overloaded, cut the budget to 4 and tune again.