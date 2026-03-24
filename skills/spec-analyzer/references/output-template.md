# Output Template

Analysis results follow this format.

## Template

```markdown
# Spec Analysis: {spec title}

> **Source**: {spec file path}
> **Date**: {spec date}
> **Module**: {spec module name}
> **Analyzed at**: {current datetime}

---

## DO

### Data Layer
- [ ] {Specific task: create migration / model / factory / seeder}
- [ ] {Include file path, e.g.: `modules/Core/app/Models/Xxx.php`}

### Backend Logic
- [ ] {Service / Controller / FormRequest / Command}
- [ ] {Trait / Observer / Scope / Policy}

### API Routes
- [ ] {Route definition with HTTP method + path}

### Frontend
- [ ] {View / Component / JS integration}

### Integration & Modifications
- [ ] {Existing files to modify, with description of changes}

### Other
- [ ] {Scheduled tasks, config, dependency installation, etc.}

---

## DON'T

### Explicit Exclusions (from "Out of Scope" sections)
- {Excluded item} — Source: §{section number} {section name}

### Constraints & Limitations (from "Caveats" etc.)
- {Constraint} — Source: §{section number} {section name}

### Anti-patterns (from "Excluded Approaches" etc.)
- {Approach to avoid and reason} — Source: §{section number} {section name}

---

## Verification Metrics (Test Cases)

### {Functional Area 1} (e.g.: CRUD Operations)

| # | Test Scenario | Expected Result | Priority |
|---|--------------|-----------------|----------|
| 1 | {Specific operation description} | {Expected behavior/return value} | P0/P1/P2 |
| 2 | ... | ... | ... |

### {Functional Area 2} (e.g.: Permission Filtering)

| # | Test Scenario | Expected Result | Priority |
|---|--------------|-----------------|----------|
| 1 | ... | ... | ... |

### {Functional Area N}

| # | Test Scenario | Expected Result | Priority |
|---|--------------|-----------------|----------|
| 1 | ... | ... | ... |

---

## Summary

| Category | Count |
|----------|-------|
| DO items | {X} |
| DON'T items | {Y} |
| Test cases | {Z} |
| P0 critical tests | {N} |

### Risk Areas
- {Functional areas with the highest density of DON'T constraints}

### Suggested Implementation Order
1. {Items with fewest dependencies and most dependents first}
2. ...

### Items Needing Clarification
- {Ambiguous or missing parts in the spec that need confirmation from spec author}
```

## Usage Notes

- DO subcategories (Data Layer, Backend, API, Frontend, etc.) should be added/removed based on actual spec content; omit empty categories
- Each DON'T item must reference its source section for traceability
- Verification is grouped by functional area, not by spec section
- Priority definitions: P0 = must pass before release, P1 = important but can defer, P2 = nice-to-have
- Items needing clarification are listed at the end, noting who should confirm
