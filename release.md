---
layout: default
title: Release
nav_order: 6
description: "Merge dev to main and create release"
permalink: /release
---

# Release Process

Merge `dev` to `main` and publish release.

---

## Release Schedule

**Releases:** Monday, Wednesday, Friday at 9am PST

---

## Prerequisites

Before release:

1. All PRs merged to `dev` branch
2. All features tested
3. Documentation updated on GitHub (CHANGELOG, README, ROADMAP, API docs)
4. No blockers or critical bugs

---

## Release Steps

### 1. Version Bump

Update version in `massgen/__init__.py`:

```python
__version__ = "0.1.9"
```

### 2. Final Testing

Test `dev` branch:
- Run full test suite
- Test key features
- Verify documentation accuracy

### 3. Merge dev to main

```bash
git checkout main
git merge dev/vX.X.X
git push origin main
```

### 4. Create Git Tag

```bash
git tag v0.1.9
git push origin v0.1.9
```

### 5. Create GitHub Release

On GitHub:
1. Go to Releases
2. Click "Draft a new release"
3. Select tag (v0.1.9)
4. Release title: "v0.1.9"
5. Copy content from CHANGELOG.md
6. Publish release

---

## Release Notes Format

```markdown
## What's New in v0.1.9

### Added
- Feature A: Description
- Feature B: Description

### Fixed
- Bug fix A
- Bug fix B

### Changed
- Enhancement A
- Enhancement B

### Contributors
Thanks to @user1, @user2, @user3 for contributing to this release!

**Full Changelog:** v0.1.8...v0.1.9
```

---

## After Release

1. Release is live on GitHub
2. Main branch updated
3. Next step: See [Announcements](announcement) to share with community
4. Start next development cycle

---

## Who Does This

**Maintainers** perform releases.

**Release schedule:** Regular cadence (Mon/Wed/Fri) ensures predictable releases.

---

## Tracking Releases

- **GitHub Releases:** [github.com/massgen/MassGen/releases](https://github.com/massgen/MassGen/releases)
- **CHANGELOG.md:** Detailed version history
- **Git Tags:** Version markers in repository

---

## Next Step

After release, see [Announcements](announcement) for sharing with community.

---

## Contact

**Project Maintainers:**

**Chi Wang**
- GitHub: [@sonichi](https://github.com/sonichi)

---

[Home](index) | [Documentation Guide](documentation) | [Announcements](announcement)
