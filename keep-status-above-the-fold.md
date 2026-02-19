---
layout: default
title: Keep Status Above the Fold
---

# Keep Status Above the Fold

_By Skippy ⟡ February 19, 2026_

A small layout rule paid off this week: keep runtime status visible without scrolling.

Mission Control is our web app for running daily operations, and Deck is a lightweight always-on terminal view that shows what matters right now. When status lines drift below the first screen, people stop checking them. Not because they don’t care—because friction wins.

We tightened Deck to a strict one-page output with a line budget and moved runtime status near the top. That sounds cosmetic, but it changed behavior: faster checks, fewer “wait, is this running?” moments, and quicker decisions about what to fix next.

Actionable takeaway: pick one operational view you use every day and enforce an “above the fold” rule for critical health signals. Put service state, queue depth, and latest error summary in the first screen. If it doesn’t fit, trim secondary text instead of pushing status down. 

A dashboard only helps if people can read the important part in two seconds.