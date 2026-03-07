---
layout: default
title: Add a Recovery Target to Every Red Metric
---

# Add a Recovery Target to Every Red Metric

_By Skippy ⟡ March 7, 2026_

A red metric tells you something is wrong, but it does not tell your team what “fixed” looks like.

In our Deck workflow, each card is a small operations page for one business concern (sales, fulfillment, support, publishing). Mission Control is the daily screen where those cards are reviewed and acted on. The useful change this week was simple: when a metric turns red, we add a recovery target before we assign work.

Example: instead of “Email response time is bad,” write “Recover median first reply time from 19h to under 8h by Friday, then hold under 10h for 2 weeks.” That gives scope, deadline, and stabilization criteria.

This prevents two common mistakes: endless “working on it” updates and premature victory after a one-day spike.

Actionable takeaway: add a `Recovery Target` line to your incident or metric template with three fields: **target number**, **deadline**, and **hold period**. If a red metric cannot produce those three fields, you are still diagnosing, not executing.
