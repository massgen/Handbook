---
layout: default
title: Documentation
nav_order: 5
description: "Update documentation before release"
permalink: /documentation
---

# Documentation Guide

Update documentation on GitHub before each release.

---

## When to Update

After PRs merge to `dev` branch and before merging `dev` to `main` for release.

**Timeline:** Before Monday, Wednesday, Friday 9am PST releases

---

## Files to Update

### CHANGELOG.md

List all changes for the version:

```markdown
## [v0.1.9] - 2025-11-XX

### Added
- New feature description

### Fixed
- Bug fix description

### Changed
- Enhancement description
```

**Include:**
- Feature additions
- Bug fixes
- Breaking changes
- Contributors

---

### README.md

Update if:
- New features need documentation
- Installation steps changed
- Examples need updates
- Project description changed

---

### ROADMAP.md

Update to reflect:
- Completed features (move from planned to done)
- New planned features
- Updated priorities
- Timeline changes

---

### API Documentation

Update feature-related docs:
- Function/class docstrings
- Configuration options
- Usage examples
- Integration guides

---

## Who Updates

**Maintainers** update documentation before release.

**Contributors** can help by:
- Including docs in PRs
- Suggesting CHANGELOG entries
- Reporting doc issues

---

## Documentation Standards

**Be Clear:**
- Use simple language
- Provide examples
- Explain why, not just what

**Be Complete:**
- Document all new features
- Update all affected sections
- Include breaking changes

**Be Accurate:**
- Test examples
- Verify commands
- Check links

---

## After Documentation Update

1. Documentation updated on GitHub
2. Ready for release

**Next step:** See [Release Process](release) to merge `dev` to `main` and publish release.

---

## Contact

