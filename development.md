---
layout: default
title: Development
nav_order: 4
description: "Development pipeline from issue to release"
permalink: /development
---

# Development Guide

Follow the development pipeline to contribute code.

---

## Development Pipeline

### 1. Browse/Claim Issues

Browse [GitHub Issues](https://github.com/massgen/MassGen/issues)

**Find issues with labels:**
- `bug` - Something broken
- `feature` - New feature
- `enhancement` - Improvement
- `research` - Research tasks

**Claim an issue:**
1. Find open, unassigned issue
2. Comment: "I would like to work on this"
3. Wait for assignment (1-2 days)
4. Do not start before assignment

---

### 2. Fork, Clone, Setup Branch

**Fork and Clone:**
```bash
# Fork on GitHub first, then:
git clone https://github.com/YOUR-USERNAME/MassGen.git
cd MassGen
git remote add upstream https://github.com/massgen/MassGen.git
```


**Create Branch:**
```bash
git fetch upstream
git checkout -b feature/your-feature-name
```

---

### 3. Implement and Test

**Write code:**
- Implement the feature or fix
- Follow code quality standards (Black, isort, flake8, pylint, mypy)
- Add docstrings

**Write tests:**
```python
# Unit test example
def test_feature():
    result = your_function()
    assert result == expected
```

**Run tests:**
```bash
pytest                    # Run all tests
pytest --cov=massgen     # With coverage
```

**Run quality checks:**
```bash
black massgen tests      # Format
isort massgen tests      # Sort imports
flake8 massgen tests     # Lint
mypy massgen             # Type check
```

**Commit:**
```bash
git add .
git commit -m "feat: add new feature"
# Use: feat, fix, docs, test, refactor
```

---

### 4. Submit PR

**Push to your fork:**
```bash
git push origin feature/your-feature-name
```

**Create Pull Request on GitHub:**
- Target branch: `dev/vX.X.X` (or `main` if dev doesn't exist)
- Fill out PR description
- Link to issue: "Closes #123"

**PR Checklist:**
- [ ] All tests pass
- [ ] Pre-commit hooks pass
- [ ] Code documented
- [ ] CHANGELOG.md updated (if needed)

---

### 5. Review and Merge to dev

**Review process:**
1. Automated checks run (CI)
2. Maintainers review 
3. Address feedback
4. Approval and merge to `dev` branch

**After merge:**
- Your code is in the development branch
- Will be tested before release

---

### 7. Merge dev to main (Release)

**Release schedule:** Monday, Wednesday, Friday at 9am PST

**Process:**
1. All changes in `dev` branch tested
2. Documentation updated
3. `dev` merged to `main`
4. GitHub release created
5. Version tagged

---


## Code Quality Standards

**Pre-commit hooks run:**
- **Black** - Code formatting
- **isort** - Import sorting
- **flake8** - Linting
- **pylint** - Advanced linting
- **mypy** - Type checking
- **bandit** - Security scanning

---


## Contact

**Development Track:**

**Nick Crispino**
- Discord: nickcrispino


**Danrui**
- Discord: danrui2020


---
