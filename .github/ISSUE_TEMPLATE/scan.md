---
name: Free eval scan
about: Paste your LLM/agent evaluation script and get a free evalguard report
title: '[SCAN] '
labels: scan
assignees: ''
---

## What does this script evaluate?

(one line — e.g. "RAG answer accuracy on 40 internal cases")

## Paste your script

```python
# paste your eval script here
```

## Which number are you unsure about?

(e.g. "it prints ACCURACY 0.87 — is that meaningful?")

---

**How this works:** a bot runs `evalguard` (pure static AST analysis — your code
is never executed) and posts the findings back here within a few hours.

The free tier is 10 rules. The PRO pack adds 16 more.
No code leaves this repo other than what you paste below.
