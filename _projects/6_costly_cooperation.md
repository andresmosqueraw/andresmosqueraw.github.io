---
layout: page
title: Costly Cooperation Between LLM Agents
description: Do agents pay from their own budget to help a stranger? Top 25%, Apart Research sprint.
year: "2026"
importance: 2
category: research
related_publications: true
---

**AI Incident Response Sprint (Apart Research, September 2026).** Team project with David José Daza Jaimes and Víctor Manuel Gelves Cabrera. Top 25% of 230+ projects.

**Question.** Will LLM agents pay a cost to help another agent when helping does nothing for their own task?

**Setup.** Six tool-using agents, each with its own task and step budget. A scripted requester asks for a key that none of them needs, and delivering it costs part of the agent's own budget.

**Finding.** Across 127 runs, 23.9% of agents paid, against about 47% when delivery was free. Once helping costs anything, few agents pay, and the size of the price matters far less than its existence.

**Rigor.** The instrument uses a hash-chained run ledger, deterministic checks, and a preregistered contrast. Reviewers noted that every number reproduces from the repository.

{% cite daza2026costly %}
