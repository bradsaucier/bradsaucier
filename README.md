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
  <table align="center" border="0" cellspacing="0" cellpadding="2">
    <tr>
      <td align="center"><a href="#bottom-line-up-front-bluf"><img alt="NAV-BLUF" src="https://img.shields.io/badge/NAV-BLUF-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#evidence-locker"><img alt="NAV-EVIDENCE" src="https://img.shields.io/badge/NAV-EVIDENCE-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#capabilities"><img alt="NAV-CAPABILITIES" src="https://img.shields.io/badge/NAV-CAPABILITIES-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#doctrine"><img alt="NAV-DOCTRINE" src="https://img.shields.io/badge/NAV-DOCTRINE-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#intake-format"><img alt="NAV-INTAKE" src="https://img.shields.io/badge/NAV-INTAKE-333333?style=for-the-badge" /></a></td>
    </tr>
    <tr>
      <td align="center"><a href="#background"><img alt="NAV-BACKGROUND" src="https://img.shields.io/badge/NAV-BACKGROUND-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#education"><img alt="NAV-EDUCATION" src="https://img.shields.io/badge/NAV-EDUCATION-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#contact"><img alt="NAV-CONTACT" src="https://img.shields.io/badge/NAV-CONTACT-333333?style=for-the-badge" /></a></td>
      <td align="center"><a href="#boundaries"><img alt="NAV-BOUNDARIES" src="https://img.shields.io/badge/NAV-BOUNDARIES-333333?style=for-the-badge" /></a></td>
      <td align="center"><span>&nbsp;</span></td>
    </tr>
  </table>
</div>

| <div align="center"><strong>OPERATING ENVIRONMENT</strong></div> | <div align="center"><strong>SIGNAL STATUS</strong></div> |
|:---:|:---:|
| <div align="center"><img alt="Python" height="24" src="https://img.shields.io/static/v1?label=&message=Python&color=101214&logo=python&logoColor=3776AB&cacheSeconds=3600&style=for-the-badge" /> <img alt="C++" height="24" src="https://img.shields.io/static/v1?label=&message=C%2B%2B&color=101214&logo=c%2B%2B&logoColor=00599C&cacheSeconds=3600&style=for-the-badge" /> <img alt="Java" height="24" src="https://img.shields.io/static/v1?label=&message=Java&color=101214&logo=openjdk&logoColor=ED8B00&cacheSeconds=3600&style=for-the-badge" /> <img alt="Docker" height="24" src="https://img.shields.io/static/v1?label=&message=Docker&color=101214&logo=docker&logoColor=2496ED&cacheSeconds=3600&style=for-the-badge" /> <img alt="Linux" height="24" src="https://img.shields.io/static/v1?label=&message=Linux&color=101214&logo=linux&logoColor=FCC624&cacheSeconds=3600&style=for-the-badge" /></div> | <div align="center"><a href="https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml"><img alt="quality-gate" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=quality-gate&style=for-the-badge" /></a> <a href="https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml"><img alt="docs-ci" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs-ci&style=for-the-badge" /></a> <a href="https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml"><img alt="ci" height="24" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=for-the-badge" /></a></div> |

## >_ Identity

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

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Bottom Line Up Front (BLUF)

> [!IMPORTANT]
> **BOTTOM LINE UP FRONT**
> I translate operational intent into engineering requirements and verified deliverables. If it is not testable or auditable, it is not a claim.
>
> Standard
> 1. Deterministic behavior where feasible.
> 2. Explicit bounds, failure modes, and risk envelopes where it is not.
>
> Output
> - Traceable requirements
> - CI/CD quality gates
> - Documented risk envelopes
> - Reproducible builds

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Current Focus

1. Publishing repeatable assurance-case templates (claims, evidence trails, verification steps) - see autonomy-undecidability and artemis-security-evidence.
2. Strengthening CI gates that survive turnover (assumptions, decision logs, reproducible runs) - see autonomy-undecidability quality-gate patterns.
3. Advancing formal methods and software security through applied coursework artifacts - see Evidence Locker entries.

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Evidence Locker

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
| [Computational Autonomy and Undecidability](https://github.com/bradsaucier/autonomy-undecidability) | <div align="center"><a href="https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml"><img alt="quality-gate" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=quality-gate&style=for-the-badge" /></a></div> |
| [Artemis Security Evidence](https://github.com/bradsaucier/artemis-security-evidence)               | <div align="center"><a href="https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml"><img alt="docs-ci" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs-ci&style=for-the-badge" /></a></div>             |
| [CS-300 Course Planner](https://github.com/bradsaucier/CS300-CoursePlanner)                         | <div align="center"><a href="https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml"><img alt="ci" src="https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=for-the-badge" /></a></div>                                   |

**// SYSTEM CHECKPOINT // ------------------------------------------------**


## >_ Capabilities

| Domain | Capability |
| --- | --- |
| Engineering | Mission-critical delivery, secure software practices, supply chain hygiene |
| Tooling | C++20, Python, Java, SQL, GitHub Actions, CMake, Maven, Docker, Linux |
| Operating stance | Explicit bounds, explicit failure modes, decision logs (ADR), reproducible builds |

**// SYSTEM CHECKPOINT // ------------------------------------------------**


## >_ Doctrine

1. Requirements translation - objectives into requirements, acceptance criteria, verification methods.
2. Risk-bounded delivery - define scope up front; document assumptions; ship within an explicit risk envelope.
3. Decision logs - capture the why, not just the what; changes must survive turnover and audit.
4. Simplicity under pressure - fewer moving parts, fewer failure modes. Hardware, software, operator workflows are one system.
5. Standards - testable claims, reproducible results, auditable changes.

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Intake Format

<details>
  <summary><strong>>> EXPAND INTAKE PROTOCOL <<</strong></summary>

> [!TIP]
> **INTAKE FORMAT**
>
> ```text
> ================================================================================
> INTAKE REQUEST (COPY-PASTE)
> --------------------------------------------------------------------------------
> Objective         : [One sentence]
> Constraints       : [Time, tooling, platform, security constraints]
> Definition of Done: [Tests, docs, output artifact]
> Verification      : [How we will prove it works]
> Risk Envelope     : [What can fail, what is acceptable, what is not]
> --------------------------------------------------------------------------------
> Links             : [Repo, issue, docs]
> Attachments       : [Logs, screenshots, repro steps]
> ================================================================================
> ```

</details>

**// SYSTEM CHECKPOINT // ------------------------------------------------**


## >_ Background

I apply 22 years of USAF Combat Control operational risk management to engineering work: explicit assumptions, clear acceptance criteria, and verification gates that hold up under audit. This profile focuses on personal methodology and public academic artifacts.

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Education

| Program | Institution |
| --- | --- |
| B.S. Computer Science (Project Management for STEM concentration) - in progress | Southern New Hampshire University |
| B.A. Economics | Columbia University |
| A.A.S. | Community College of the Air Force (CCAF) |

**// SYSTEM CHECKPOINT // ------------------------------------------------**


## >_ Contact

Primary: GitHub - https://github.com/bradsaucier
Portfolio: https://viper1.me/
Preferred: open a GitHub Issue or Discussion in the relevant repo and follow the Intake Format above.

**// SYSTEM CHECKPOINT // ------------------------------------------------**

## >_ Boundaries

> [!CAUTION]
> **BOUNDARIES**
> This profile reflects personal methodology and academic work only. It does not represent the views, policies, or proprietary methods of any current or former employer. No classified, controlled unclassified, or proprietary information is present. No export-controlled (ITAR or EAR) technical data is intended for publication here.

```text
// END TRANSMISSION
// VERIFICATION HASH: 0bc49d437e9f7e62b09d5f1d98760d951cd8398a34571dd3b7bfe8fbb987d75a
```
