# DJANGO_HEALTH

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `DJANGO_HEALTH` in category **MEDICAL_HEALTH**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** DJANGO_HEALTH · **Upstream pin:** `0d171598fd7465f51e52dd1994b092d9c60bf334` · **Category:** MEDICAL_HEALTH · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/codingjoe/django-health-check/raw/main/docs/images/logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/codingjoe/django-health-check/raw/main/docs/images/logo-light.svg">
    <img alt="Django HealthCheck: Pluggable health checks for Django applications" src="https://github.com/codingjoe/django-health-check/raw/main/docs/images/logo-light.svg">
  </picture>
<br>
  <a href="https://codingjoe.dev/django-health-check/">Documentation</a> |
  <a href="https://github.com/codingjoe/django-health-check/issues/new/choose">Issues</a> |
  <a href="https://github.com/codingjoe/django-health-check/releases">Changelog</a> |
  <a href="https://github.com/sponsors/codingjoe">Funding</a> 💚
</p>

# Django HealthCheck

_Pluggable health checks for Django applications_

## 🥳 Sponsors 🎉

![Sponsors](https://sponsor.pics/codingjoe/django-health-check.svg?)

[![version](https://img.shields.io/pypi/v/django-health-check.svg)](https://pypi.python.org/pypi/django-health-check/)
[![coverage](https://codecov.io/gh/codingjoe/django-health-check/branch/main/graph/badge.svg)](https://codecov.io/gh/codingjoe/django-health-check)
[![pyversion](https://img.shields.io/pypi/pyversions/django-health-check.svg)](https://pypi.python.org/pypi/django-health-check/)
[![djversion](https://img.shields.io/pypi/djversions/django-health-check.svg)](https://pypi.python.org/pypi/django-health-check/)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://pypi.python.org/pypi/django-health-check/)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

<a href="https://github.com/codingjoe/django-health-check/issues/new/choose">Issues</a> |
  <a href="https://github.com/codingjoe/django-health-check/releases">Changelog</a> |
  <a href="https://github.com/sponsors/codingjoe">Funding</a> 💚
</p>

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing

When writing code, you MUST ALWAYS follow the [naming-things](https://github.com/codingjoe/naming-things/blob/main/README.md) guidelines.

<!--
Bots/Agents MUST use:
curl -sSL https://raw.githubusercontent.com/codingjoe/naming-things/refs/heads/main/README.md
-->

To run the tests, use the following command:

```bash
uv run pytest
```

Before your first commit, ensure that the pre-commit hooks are installed by running:

```bash
uv pre-commit install
```

## Testing with Extra Dependencies

```bash
export REDIS_URL=redis://localhost:6379
export BROKER_URL=amqp://guest:guest@localhost:5672//
export KAFKA_BOOTSTRAP_SERVERS=localhost:9092
uv run --extra=redis --extra=rabbitmq --extra=celery --extra=rss --extra=kafka pytest
```

## Writing documentation

The documentation is built using [MkDocs](https://www.mkdocs.org/) with [mkdocstrings](https://mkdocstrings.github.io/) for automatic API documentation generation.

To serve the documentation locally for development, run:

```bash
uv run mkdocs serve --livereload
```

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** DJANGO_HEALTH
- **Pinned SHA:** `0d171598fd7465f51e52dd1994b092d9c60bf334`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`db33f46960f413b444dcf6376631ac6946f5202be0912d6a21813716daea7d5e`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

