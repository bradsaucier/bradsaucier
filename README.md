<div align="center">
  <h1><a href="https://viper1.me/">Bradley Saucier</a></h1>
  <p><strong>>_ Verification-first engineering - testable claims, auditable changes, bounded risk.</strong></p>
  <p>Deputy Operations Manager - Anduril Industries - USAF Combat Controller (Ret.)</p>

  <p>
    <a href="https://github.com/bradsaucier">
      <img alt="GitHub profile" src="https://img.shields.io/badge/GitHub-bradsaucier-0d1117?style=for-the-badge&logo=github&logoColor=white" height="28" />
    </a>
    <a href="https://viper1.me/">
      <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-viper1.me-333333?style=for-the-badge" height="28" />
    </a>
  </p>
</div>

```text
CLASSIFICATION: UNCLASSIFIED // PUBLIC RELEASE
OWNER: SAUCIER, BRADLEY // VIPER1
```



---

<a id="bluf"></a>
## Bottom Line Up Front (BLUF)

> [!IMPORTANT]
> I translate operational intent into engineering requirements and verified deliverables. If it is not testable or auditable, it is not a claim.
>
> **Standard** - Deterministic behavior where feasible. Where not feasible - explicit bounds, failure modes, risk envelopes.
>
> **Output** - Traceable requirements, CI quality gates, documented risk envelopes, reproducible builds.


---

<a id="identity"></a>
## Identity

<details>
<summary><strong>Identity block (YAML)</strong></summary>

```yaml
SYSTEM   : viper1.me
PROFILE  : Operator mindset applied to engineering (verification-first)

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
```

</details>

---

<a id="focus"></a>
## Current Focus

1. Publishing repeatable assurance-case templates (claims, evidence trails, verification steps).
2. Hardening CI gates that survive turnover (assumptions, decision logs, reproducible runs).
3. Building public, scrubbed evidence artifacts aligned to coursework and professional practice.

---

<a id="evidence"></a>
## Evidence Locker

Each entry follows a compact assurance-case structure (CAE or GSN style): claim, context, evidence, verification path.

<details>
<summary><strong>Evidence format (CAE or GSN style)</strong></summary>

```text
CLAIM       : What is asserted (testable statement).
CONTEXT     : Assumptions, environment, constraints.
EVIDENCE    : Artifacts (docs, logs, reports, test outputs).
VERIFICATION: Steps to reproduce and validate evidence.
RISK        : Explicit envelope, failure modes, residual risk.
```

</details>

### Status Board

| Project | Focus | Gate |
|:--|:--|:--|
| [bradsaucier/autonomy-undecidability](https://github.com/bradsaucier/autonomy-undecidability) | Assurance-case templates for computational autonomy | [![gate](https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=gate&style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml) |
| [bradsaucier/artemis-security-evidence](https://github.com/bradsaucier/artemis-security-evidence) | Security evidence trails and verification steps | [![docs](https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs&style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml) |
| [bradsaucier/CS300-CoursePlanner](https://github.com/bradsaucier/CS300-CoursePlanner) | Algorithmic planning structures (academic artifact) | [![ci](https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml) |
| [bradsaucier/test-discipline](https://github.com/bradsaucier/test-discipline) | Deterministic services, JUnit suites, JaCoCo enforcement (CS-320) | [![build](https://img.shields.io/github/actions/workflow/status/bradsaucier/test-discipline/maven-build.yml?label=build&style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bradsaucier/test-discipline/actions/workflows/maven-build.yml) |
| [bradsaucier/cct-ui-evidence-locker](https://github.com/bradsaucier/cct-ui-evidence-locker) | UI-UX evidence locker: traceability, risk register, design tokens (CS-319) | [![links](https://img.shields.io/github/actions/workflow/status/bradsaucier/cct-ui-evidence-locker/links.yml?label=links&style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bradsaucier/cct-ui-evidence-locker/actions/workflows/links.yml) |

---

<a id="capabilities"></a>
## Capabilities

| Domain | Capability |
|:--|:--|
| Engineering | Mission-critical delivery, secure software practices, supply chain hygiene |
| Verification | Unit and integration testing, deterministic seams, CI gate enforcement, regression discipline |
| UI-UX | Constraint-first interface design, traceability from requirements to screens, accessibility posture |
| Tooling | C++20, Python, Java, SQL, GitHub Actions, CMake, Maven, Docker, Linux |
| Operating stance | Explicit bounds, explicit failure modes, decision logs (ADR), reproducible builds |

---

<a id="doctrine"></a>
## Doctrine

1. **Requirements translation** - Objectives into requirements, acceptance criteria, verification methods.
2. **Risk-bounded delivery** - Define scope up front; document assumptions; ship within an explicit risk envelope.
3. **Decision logs** - Capture the why, not just the what; changes must survive turnover and audit.
4. **Simplicity under pressure** - Fewer moving parts, fewer failure modes; hardware, software, operator workflows are one system.

---

<a id="intake"></a>
## Intake Format

Preferred format for collaboration requests. Expand for the full template.

<details>
<summary><strong>INTAKE REQUEST TEMPLATE</strong></summary>

<br>

```text
================================================================================
INTAKE REQUEST
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

</details>

---

## Background and Education

<details>
<summary><strong>Background</strong></summary>

I apply operational risk management to engineering work: explicit assumptions, clear acceptance criteria, and verification gates that hold up under audit. This profile focuses on personal methodology and public academic artifacts.

</details>

<details>
<summary><strong>Education</strong></summary>

| Program | Institution |
|:--|:--|
| B.S. Computer Science (Project Management for STEM concentration) - in progress | Southern New Hampshire University |
| B.A. Economics | Columbia University |
| A.A.S. | Community College of the Air Force (CCAF) |

</details>

---

<a id="contact"></a>
## Contact

| Method | Detail |
|:--|:--|
| Preferred | Open an Issue or Discussion in the relevant repo and use the Intake Format above |
| Web | https://viper1.me/ |

---

<a id="boundaries"></a>
## Boundaries

> [!CAUTION]
> **BOUNDARIES**
> This profile reflects personal methodology and academic work only. It does not represent the views, policies, or proprietary methods of any current or former employer. No classified, controlled unclassified information (CUI), or export-controlled (ITAR or EAR) technical data is intended for publication here.

```text
// END TRANSMISSION
// VERIFICATION HASH: 90ba5e401f43634423d8a62e19165a6f1c04ed8e6b500e4fc238b8789ebd4f37
```
