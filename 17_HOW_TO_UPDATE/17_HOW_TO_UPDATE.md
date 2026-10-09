# How to Update — DJANGO_HEALTH

**Project:** `DJANGO_HEALTH`
**Category:** MEDICAL_HEALTH
**Domain:** medical health and clinical systems
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
DJANGO_HEALTH --version
DJANGO_HEALTH check-update
```

### Applying Updates
```bash
pip install --upgrade DJANGO_HEALTH
```

### Rolling Back
```bash
pip install DJANGO_HEALTH==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
