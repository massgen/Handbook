---
layout: default
title: Documentation
nav_order: 7
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
## [v0.1.x] - 202X-XX-XX

### Added
- New feature description

### Fixed
- Bug fix description

### Changed
- Enhancement description

### Documentations, Configurations and Resources
- All updated markdown files, `.yaml` config files and other resources (e.g. updated files for massgen website)

### Technical Details
- **Major Focus**: Current version focus on waht features
- **Contributors**: Contributors for current version
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

**Note:** Developers write API documentation during development (see [Development Guide](development), step 4).

**Verify completeness of:**
- Function/class docstrings
- Configuration options
- Usage examples
- Integration guides

**Ensure quality:**
- Documentation is clear and accurate
- Examples are tested and working
- All new features are documented

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

**Henry**
- **Discord:** henry_weiqi

---

[Back to Home](index) | [Previous: Development Guide](development) | [Next: Release Guide](release)