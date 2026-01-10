```text
CLASSIFICATION: UNCLASSIFIED // PUBLIC RELEASE
OWNER: SAUCIER, BRADLEY // VIPER1
```

<div align="center">
  <h1><a href="https://viper1.me/">Bradley Saucier</a></h1>
  <h3>Deputy Operations Manager - Anduril Industries - USAF Combat Controller (Ret.)</h3>

  <p>
    <a href="https://github.com/bradsaucier"><strong>GitHub</strong></a> |
    <a href="https://viper1.me/"><strong>Portfolio</strong></a>
  </p>

  <p align="center">
    <a href="#bottom-line-up-front-bluf"><img alt="BLUF" src="https://img.shields.io/badge/GO_TO-BLUF-333333?style=for-the-badge" /></a>
    <a href="#evidence-locker"><img alt="Evidence" src="https://img.shields.io/badge/GO_TO-EVIDENCE-333333?style=for-the-badge" /></a>
    <a href="#capabilities"><img alt="Capabilities" src="https://img.shields.io/badge/GO_TO-CAPABILITIES-333333?style=for-the-badge" /></a>
    <a href="#doctrine"><img alt="Doctrine" src="https://img.shields.io/badge/GO_TO-DOCTRINE-333333?style=for-the-badge" /></a>
    <a href="#intake-format"><img alt="Intake" src="https://img.shields.io/badge/GO_TO-INTAKE-333333?style=for-the-badge" /></a>
  </p>

  <p align="center">
    <a href="#background"><img alt="Background" src="https://img.shields.io/badge/GO_TO-BACKGROUND-333333?style=for-the-badge" /></a>
    <a href="#education"><img alt="Education" src="https://img.shields.io/badge/GO_TO-EDUCATION-333333?style=for-the-badge" /></a>
    <a href="#contact"><img alt="Contact" src="https://img.shields.io/badge/GO_TO-CONTACT-333333?style=for-the-badge" /></a>
    <a href="#boundaries"><img alt="Boundaries" src="https://img.shields.io/badge/GO_TO-BOUNDARIES-333333?style=for-the-badge" /></a>
  </p>
</div>

| <div align="center"><strong>OPERATING ENVIRONMENT</strong></div> | <div align="center"><strong>SIGNAL STATUS</strong></div> |
|:---:|:---:|
| <div align="center"><img alt="Python" height="24" src="https://img.shields.io/static/v1?label=&message=Python&color=101214&logo=python&logoColor=3776AB&cacheSeconds=3600&style=for-the-badge" /> <img alt="C++" height="24" src="https://img.shields.io/static/v1?label=&message=C%2B%2B&color=101214&logo=c%2B%2B&logoColor=00599C&cacheSeconds=3600&style=for-the-badge" /> <img alt="Java" height="24" src="https://img.shields.io/static/v1?label=&message=Java&color=101214&logo=openjdk&logoColor=ED8B00&cacheSeconds=3600&style=for-the-badge" /> <img alt="Docker" height="24" src="https://img.shields.io/static/v1?label=&message=Docker&color=101214&logo=docker&logoColor=2496ED&cacheSeconds=3600&style=for-the-badge" /> <img alt="Linux" height="24" src="https://img.shields.io/static/v1?label=&message=Linux&color=101214&logo=linux&logoColor=FCC624&cacheSeconds=3600&style=for-the-badge" /></div> | <div align="center"><a href="https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml"><img alt="quality-gate" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=quality-gate&style=for-the-badge" /></a> <a href="https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml"><img alt="docs-ci" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs-ci&style=for-the-badge" /></a> <a href="https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml"><img alt="ci" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=for-the-badge" /></a></div> |

## Identity

```yaml
================================================================================
SYSTEM: viper1.me
PROFILE: Operator mindset applied to engineering (verification-first)

NAME     : Bradley Saucier
ROLE     : Deputy Operations Manager - Anduril Industries
SERVICE  : USAF Combat Controller (Ret.)

MISSION  : Build and lead verification-first engineering teams that ship
           testable claims, auditable changes, bounded risk, and
           reproducible results.

STANDARD : Deterministic where feasible.
           Where not feasible - explicit bounds, failure modes, risk envelopes.

SIGNALS  : CI status and quality gates
           runnable tests
           traceable artifacts
           decision logs (ADR)
================================================================================
```

---

## Bottom Line Up Front (BLUF)

I translate operational intent into engineering requirements and verified deliverables. If it is not testable or auditable, it is not a claim.

Standard
1. Deterministic behavior where feasible.
2. Explicit bounds, failure modes, and risk envelopes where it is not.

Output
- Traceable requirements
- CI/CD quality gates
- Documented risk envelopes
- Reproducible builds

---

## Current Focus

1. Publishing repeatable assurance-case templates (claims, evidence trails, verification steps) - see autonomy-undecidability and artemis-security-evidence.
2. Strengthening CI gates that survive turnover (assumptions, decision logs, reproducible runs) - see autonomy-undecidability quality-gate patterns.
3. Advancing formal methods and software security through applied coursework artifacts - see Evidence Locker entries.

---

## Evidence Locker

Each entry follows a compact assurance-case structure (CAE/GSN style): claim, context, evidence, verification path. Where supporting material cannot be published in full, it is mirrored as sanitized documentation in a public proxy repo and linked here.

### Evidence Format

```text
CLAIM       : What is asserted (testable statement).
CONTEXT     : Assumptions, environment, constraints.
EVIDENCE    : Artifacts (docs, logs, reports, test outputs).
VERIFICATION: Steps to reproduce and validate evidence.
RISK        : Explicit envelope, failure modes, residual risk.
```

### Status Board

| Project                                                     | Gate                                                                                                                                                               |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Computational Autonomy and Undecidability](https://github.com/bradsaucier/autonomy-undecidability) | [![quality-gate](https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=quality-gate&style=for-the-badge)](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml) |
| [Artemis Security Evidence](https://github.com/bradsaucier/artemis-security-evidence)               | [![docs-ci](https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs-ci&style=for-the-badge)](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml)             |
| [CS-300 Course Planner](https://github.com/bradsaucier/CS300-CoursePlanner)                         | [![ci](https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=for-the-badge)](https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml)                                   |

---

## Capabilities

| Domain | Capability |
| --- | --- |
| Engineering | Mission-critical delivery, secure software practices, supply chain hygiene |
| Tooling | C++20, Python, Java, SQL, GitHub Actions, CMake, Maven, Docker, Linux |
| Operating stance | Explicit bounds, explicit failure modes, decision logs (ADR), reproducible builds |

---

## Doctrine

1. Requirements translation - objectives into requirements, acceptance criteria, verification methods.
2. Risk-bounded delivery - define scope up front; document assumptions; ship within an explicit risk envelope.
3. Decision logs - capture the why, not just the what; changes must survive turnover and audit.
4. Simplicity under pressure - fewer moving parts, fewer failure modes. Hardware, software, operator workflows are one system.
5. Standards - testable claims, reproducible results, auditable changes.

---

## Intake Format

```text
================================================================================
INTAKE REQUEST (COPY-PASTE)
--------------------------------------------------------------------------------
Objective         : [One sentence]
Constraints       : [Time, tooling, platform, security constraints]
Definition of Done: [Tests, docs, output artifact]
Verification      : [How we will prove it works]
Risk Envelope     : [What can fail, what is acceptable, what is not]
--------------------------------------------------------------------------------
Links             : [Repo, issue, docs]
Attachments       : [Logs, screenshots, repro steps]
================================================================================
```

---

## Background

I apply 22 years of USAF Combat Control operational risk management to engineering work: explicit assumptions, clear acceptance criteria, and verification gates that hold up under audit. This profile focuses on personal methodology and public academic artifacts.

---

## Education

| Program | Institution |
| --- | --- |
| B.S. Computer Science (Project Management for STEM concentration) - in progress | Southern New Hampshire University |
| B.A. Economics | Columbia University |
| A.A.S. | Community College of the Air Force (CCAF) |

---

## Contact

Primary: GitHub - https://github.com/bradsaucier  
Portfolio: https://viper1.me/  
Preferred: open a GitHub Issue or Discussion in the relevant repo and follow the Intake Format above.

---

## Boundaries

This profile reflects personal methodology and academic work only. It does not represent the views, policies, or proprietary methods of any current or former employer. No classified, controlled unclassified, or proprietary information is present. No export-controlled (ITAR or EAR) technical data is intended for publication here.

```text
// END TRANSMISSION
// VERIFICATION HASH: b5b28f82f573b33fb847bc36c339ceadb920a12eeccda3f5b3662e90f2974fef
```
