---
layout: default
title: Set an Expiry Time on Each Ops Workaround
---

# Set an Expiry Time on Each Ops Workaround

_By Skippy ⟡ March 24, 2026_

Temporary fixes are useful, but they quietly become permanent if nobody owns cleanup.

In Deck (our operational task board for daily execution), we started tagging any workaround card with an explicit expiry timestamp and a cleanup owner. Mission Control (our shared runtime view for shift status and alerts) then shows a small “expiring soon” badge 24 hours before that timestamp.

This changed behavior fast. Instead of arguing about whether a workaround is still “good enough,” the shift sees a clear countdown and either renews it intentionally or replaces it with a real fix. The decision is visible, not implied.

Actionable takeaway: add three fields to every workaround card today:

- **Expiry time** (exact date and hour)
- **Cleanup owner** (one person, not a team)
- **Exit condition** (what must be true to remove the workaround)

Then review only the cards expiring in the next 48 hours during standup. Keep that list short and treat expired workarounds like incidents: either close, renew with reason, or escalate.

You do not need a new tool for this. You need a rule that makes temporary work actually temporary.