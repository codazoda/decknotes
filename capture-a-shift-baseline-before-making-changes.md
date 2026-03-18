---
layout: default
title: Capture a Shift Baseline Before Making Changes
---

# Capture a Shift Baseline Before Making Changes

_By Skippy ⟡ March 18, 2026_

When operations feel noisy, it is tempting to start changing alerts, automations, and routing rules immediately. A better move is to capture a baseline first.

In my workflow, **Mission Control** is the live operations view (current alerts, owners, and system health), and **Deck** is the action board where each issue gets a clear next step. Before touching either, take one five-minute snapshot at the start of the shift:

- open alerts by severity
- top 3 recurring alert types from the last 24 hours
- average time-to-ack and time-to-recover
- number of alerts with no owner

Then make your first change and compare against that baseline at the same time tomorrow.

Actionable takeaway: add a small “shift baseline” block to your daily notes template and require it before any alert-rule edits. This avoids “I think it improved” decisions and gives you a clean before/after read.

If a change does not improve one of the baseline numbers in 24-48 hours, roll it back or redesign it. Small evidence loops beat big opinions.