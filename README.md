# [Bradley Saucier](https://github.com/bradsaucier)
#### Deputy Operations Manager - Anduril Industries - USAF Combat Controller (Ret.)

<p align="center">
  <img alt="Python" height="28" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101214&cacheSeconds=3600" />
  <img alt="C++" height="28" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white&labelColor=101214&cacheSeconds=3600" />
  <img alt="Java" height="28" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=101214&cacheSeconds=3600" />
  <img alt="Docker" height="28" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=101214&cacheSeconds=3600" />
  <img alt="Linux" height="28" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=white&labelColor=101214&cacheSeconds=3600" />
</p>

---

**Mission** - Build and lead verification-first delivery via testable claims, auditable changes, and bounded risk.

## Bottom Line Up Front (BLUF)
I translate operational intent into engineering requirements and verified deliverables. Standard: deterministic behavior where feasible, explicit bounds where not. Proof signals must be validated in CI, tests, and artifacts.

## Capabilities
**Engineering**

1. Reliability under constraint - deterministic behavior where feasible, explicit bounds where not.
2. Verification and CI - repeatable runs, automated gates, testable claims.
3. Security evidence - scoped findings, traceable artifacts, verification notes.

**Stack (demonstrated across repos)**

1. Python, C++17, Java
2. GitHub Actions
3. Linux and container workflows where appropriate

## Evidence locker
Each entry is structured as a compact assurance case: mission, claim, evidence, verify.

### Computational Autonomy and Undecidability
**Repo**: [bradsaucier/autonomy-undecidability](https://github.com/bradsaucier/autonomy-undecidability)

[![quality-gate](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml/badge.svg)](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml)

**Mission**  
Demonstrate why universal, unbounded autonomy verification is undecidable in general, and what bounded assurance can prove.

**Claim**  
Full computational autonomy is a nontrivial semantic property; per Rice's Theorem, no algorithm can decide it for all programs. This repo makes the reduction pattern runnable and keeps bounds explicit.

**Evidence**

1. [Start here - start_here.md](https://github.com/bradsaucier/autonomy-undecidability/blob/master/start_here.md)
2. [Theory notes - theory/](https://github.com/bradsaucier/autonomy-undecidability/tree/master/theory)
3. [Reproducible tests - tests/](https://github.com/bradsaucier/autonomy-undecidability/tree/master/tests)

**Verify**

1. Execute the demo cases via the repo instructions.
2. Validate scope constraints against the bounded model before drawing conclusions.

### Artemis Security Evidence
**Repo**: [bradsaucier/artemis-security-evidence](https://github.com/bradsaucier/artemis-security-evidence)

[![docs-ci](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml/badge.svg)](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml)

**Mission**  
Documentation Body of Evidence (SNHU CS-305). Covers risk assessment, hardening practices, and verification artifacts.

**Claim**  
Security posture is only credible when scoped, reproducible, and artifact-backed. This repo prioritizes traceable reports and verification notes over narrative.

**Evidence**

1. [Verification notes - docs/VERIFICATION.md](https://github.com/bradsaucier/artemis-security-evidence/blob/main/docs/VERIFICATION.md)
2. [Reports - reports/](https://github.com/bradsaucier/artemis-security-evidence/tree/main/reports)
3. [Evidence artifacts - evidence/](https://github.com/bradsaucier/artemis-security-evidence/tree/main/evidence)

**Verify**

1. Read the primary report first (reports directory).
2. Use the verification notes to reproduce or validate the evidence trail.

### CS-300 Course Planner
**Repo**: [bradsaucier/CS300-CoursePlanner](https://github.com/bradsaucier/CS300-CoursePlanner)

[![ci](https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml/badge.svg)](https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml)

**Mission**  
Deterministic course advising tool: ingest CSV, validate prerequisites, support fast lookup, print sorted catalog output.

**Claim**  
Defensive ingestion plus explicit data structure choices can produce predictable behavior and performance under constraint.

**Evidence**

1. [Complexity and design rationale - docs/](https://github.com/bradsaucier/CS300-CoursePlanner/tree/main/docs)
2. [Source implementation - src/](https://github.com/bradsaucier/CS300-CoursePlanner/tree/main/src)

**Verify**

1. Build from a clean environment using the repo instructions.
2. Validate input handling and prerequisite checks using the provided sample data and docs.

## Leadership and delivery doctrine
1. Requirements translation - objectives into requirements, acceptance criteria, and verification methods.
2. Delivery tempo - bounded risk with decision logs that survive turnover.
3. Integration mindset - align hardware, software, and operator workflows to reduce failure modes.
4. Standards - testable claims, reproducible results, auditable changes.

## Collaboration SOP
**Routing**

1. Repo-specific topics - open an issue in that repository.
2. Cross-repo topics - open an issue in the repo that best matches the problem and link artifacts.

**Required issue content**

1. Context - system, environment, what changed.
2. Constraints - time, safety, interfaces, policy, dependencies.
3. Desired outcome - what success looks like.
4. Definition of done - tests, checks, artifacts, acceptance criteria.
5. Evidence - logs, repro steps, commands run, links.

<details>
<summary><strong>Copy-paste issue template</strong></summary>

```yaml
Context:
  System:
  Environment:
  What changed:

Constraints:
  Time:
  Safety:
  Interfaces:
  Policy:
  Dependencies:

Desired outcome:
  What success looks like:

Definition of done:
  Tests:
  Checks:
  Artifacts:
  Acceptance criteria:

Evidence:
  Logs:
  Repro steps:
  Commands run:
  Links:
```

</details>

## Background and boundaries
I apply 22 years of USAF Combat Control operational risk management to software delivery and engineering leadership.

This is personal work and does not represent any employer or agency. No sensitive or export-controlled technical data is intended for publication here.

## Education
1. B.S. Computer Science (Candidate) - Southern New Hampshire University (STEM Project Management)
2. B.A. - Columbia University
3. A.A.S. - Community College of the Air Force
