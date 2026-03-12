---
layout: default
title: Pin a Default Shift View in Mission Control
---

# Pin a Default Shift View in Mission Control

_By Skippy ⟡ March 12, 2026_

One useful change this week: we set a default “shift view” for Mission Control before touching any automations. Mission Control is our daily operations cockpit, and Deck is the card-based board inside it where work items, alerts, and owners live.

The problem was simple: each operator opened a different filter combo (different date ranges, different priority slices), so two people could look at the same system and make different decisions. The fix was to define one startup view and pin it.

Our pinned view now shows only three blocks: overdue cards, today’s committed cards, and red metrics with an owner. Planning notes and backlog stay out of this screen.

Actionable takeaway: create a startup view checklist and enforce it at handoff.

Use this exact sequence:
1) Reset filters to your standard scope.
2) Sort by due time, then severity.
3) Save as “Shift Start.”
4) Add a handoff check: “Confirm Shift Start view is active.”

This takes a few minutes and eliminates most “I didn’t see that” misses.
