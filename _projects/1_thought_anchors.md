---
layout: page
title: Thought Anchors for Social Bias
description: Which reasoning steps push extended-thinking LLMs toward stereotypes? Winner, Apart Research hackathon.
year: "2026"
importance: 1
category: research
related_publications: true
---

**Global South AI Safety Hackathon (Apart Research, 2026).** Winner, competing solo: 1 of 3 winning teams out of 217, with a USD 1,000 prize.

**Question.** When an extended-thinking model gives a stereotypical answer about a Latin American scenario, which steps of its chain of thought are responsible?

**Method.** I adapted the _Thought Anchors_ resampling framework. Each reasoning step is resampled, and I measure how much it shifts the final answer. I ran it on Claude Sonnet 4.6, Gemini 2.5 Flash, and Qwen3.7-Plus.

**Output.** A reproducible pipeline, a paper, and an interactive demo, built in about 24 hours.

**Extension.** During BlueDot Impact's Technical AI Safety Project, mentored by Jess Bergs (UK AI Security Institute), I extended it into a workshop paper submitted to GeBNLP @ ACL 2026: 1,708 chunk-level attributions across 3 models, 4 bias categories (gender, classism, racism, xenophobia), and 2 languages. The steps that matter most turn out to be general inference and context recall, not overt stereotype statements.

{% cite mosquera2026thoughtanchors %}
