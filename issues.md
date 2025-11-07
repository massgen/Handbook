---
layout: default
title: Issues
nav_order: 3
description: "Bug reports, case studies, and feature proposals"
permalink: /issues
---

# GitHub Issues Guide

GitHub Issues track three types of contributions: case studies, features, and bugs.

**Issues Page:** [github.com/massgen/MassGen/issues](https://github.com/massgen/MassGen/issues)

---

## Issue Types

### 1. Case Study Issues

Document real-world usage of MassGen.

**Create issue:** [github.com/massgen/MassGen/issues/new](https://github.com/massgen/MassGen/issues/new)

**Labels to use:**
- `research` - For research-oriented case studies
- `enhancement` - For case studies that suggest improvements
- `self-improvement` - If tied to self-improvement goal

**What to include:**
- Prompt - The task/prompt to test
- Config file - Which agents, hyperparameters
- Cmd - Command to run
- Current behavior - What happens now
- Expected behavior - What should happen
- How this ties to goals - Connection to self-improvement

See [Case Studies Guide](case-studies) for detailed workflow.

---

### 2. Feature Issues

Propose new features (usually from research meetings).

**Create issue:** [github.com/massgen/MassGen/issues/new](https://github.com/massgen/MassGen/issues/new)

**Labels to use:**
- `feature` - For new feature requests
- `enhancement` - For improvements to existing features
- Additional domain labels: `memory`, `filesystem`, `interoperability`, `self-improvement`

---

### 3. Bug Issues

Report problems that need fixing.

**Create issue:** [github.com/massgen/MassGen/issues/new](https://github.com/massgen/MassGen/issues/new)

**Label:** `bug`

**What to include:**
- Steps to reproduce
- Expected vs actual behavior
- Environment (Python version, OS, MassGen version)
- Error messages
- Configuration file (remove API keys)

---

## Browse Issues

**Main page:** [github.com/massgen/MassGen/issues](https://github.com/massgen/MassGen/issues)

**Filter by label:**
- `bug` - Something isn't working
- `feature` - Feature requests
- `enhancement` - New feature or request
- `documentation` - Improvements or additions to documentation
- `research` - Research-oriented tasks
- `memory` - Memory functionality
- `filesystem` - File system related
- `interoperability` - Integration with other agent frameworks
- `self-improvement` - Internal improvements

**Search examples:**
```
is:issue label:bug is:open
is:issue label:feature
is:issue label:research
is:issue "memory system"
```

---

## Claim an Issue

1. Find an open, unassigned issue
2. Comment: "I would like to work on this"
3. Wait for assignment 
4. Once assigned, create your branch and start work

**Do not start before assignment.**

---

## Contact

**Development Track:**
- Nick: nickcrispino ([@ncrispino](https://github.com/ncrispino))
- Danrui: danrui2020 ([@qidanrui](https://github.com/qidanrui))

**Case Studies Track:**
- Nick: nickcrispino ([@ncrispino](https://github.com/ncrispino))
- Yu: crinvo ([@a5507203](https://github.com/a5507203))

---

[Home](index) | [Development Guide](development)
