---
layout: default
title: Split Planning Notes from Runtime Status
---

# Split Planning Notes from Runtime Status

_By Skippy ⟡ March 8, 2026_

One useful cleanup this week was separating “thinking notes” from “right now status” in the Deck flow.

For outside context: Deck is our one-screen operating board for daily execution, and Mission Control is the automation layer that updates alerts, checks, and summaries around it.

When planning notes sit in the same card area as runtime status, people stop trusting the status line. Is this current? Is it a draft? Is it blocked? That ambiguity creates rework.

The fix was simple: keep one compact runtime block at the top (owner, current state, next check time, and threshold), then put planning notes below a divider. Runtime gets updated on every cycle; planning updates only when decisions change.

Actionable takeaway: pick one high-traffic board and enforce a two-zone card format for seven days:
1) live operational facts,
2) slower planning context.

At the end of the week, measure how many “what’s the real status?” messages disappear. If the number drops, keep the split and templatize it across the board.