# [Bradley Saucier](https://github.com/bradsaucier)
#### Deputy Operations Manager - Anduril Industries - USAF Combat Controller (Ret.)

<p align="center">
  <img alt="Python" height="28" src="https://img.shields.io/static/v1?label=Python&message=%20&style=for-the-badge&color=101214&labelColor=101214&logo=python&logoColor=3776AB&cacheSeconds=3600" />
  <img alt="C++" height="28" src="https://img.shields.io/static/v1?label=C%2B%2B&message=%20&style=for-the-badge&color=101214&labelColor=101214&logo=c%2B%2B&logoColor=00599C&cacheSeconds=3600" />
  <img alt="Java" height="28" src="https://img.shields.io/static/v1?label=Java&message=%20&style=for-the-badge&color=101214&labelColor=101214&logo=openjdk&logoColor=ED8B00&cacheSeconds=3600" />
  <img alt="Docker" height="28" src="https://img.shields.io/static/v1?label=Docker&message=%20&style=for-the-badge&color=101214&labelColor=101214&logo=docker&logoColor=2496ED&cacheSeconds=3600" />
  <img alt="Linux" height="28" src="https://img.shields.io/static/v1?label=Linux&message=%20&style=for-the-badge&color=101214&labelColor=101214&logo=linux&logoColor=FCC624&cacheSeconds=3600" />
</p>

---

**Mission** - Build and lead verification-first engineering teams. Standard: testable claims, auditable changes, bounded risk, reproducible results.

## Table of Contents
1. [Bottom Line Up Front (BLUF)](#bottom-line-up-front-bluf)
2. [Current Focus](#current-focus)
3. [Evidence Locker](#evidence-locker)
4. [Capabilities](#capabilities)
5. [Leadership and Delivery Doctrine](#leadership-and-delivery-doctrine)
6. [Collaboration SOP](#collaboration-sop)
7. [Background and Boundaries](#background-and-boundaries)
8. [Education](#education)

## Bottom Line Up Front (BLUF)
I translate operational intent into engineering requirements and verified deliverables.

Standard:
1. Deterministic behavior where feasible.
2. Explicit bounds, failure modes, and risk envelopes where it is not.

Signal:
1. A claim is only credible when it is backed by runnable verification: CI, tests, and traceable artifacts.

Output:
1. Traceable requirements, automated verification gates, documented risk envelopes.

## Current Focus
1. Publishing repeatable assurance-case templates across repos (claims, evidence trails, verification steps).
2. Strengthening CI gates that survive turnover (assumptions, decision logs, reproducible runs).
3. Advancing formal methods and software security through applied coursework artifacts.

## Evidence Locker
Each entry is a compact assurance case (CAE/GSN style): Mission, Claim, Evidence, Verify.
If a repo must remain private (academic policy or boundary control), evidence is mirrored as sanitized docs in a public proxy repo and linked here.

### Computational Autonomy and Undecidability
**Repo**: [bradsaucier/autonomy-undecidability](https://github.com/bradsaucier/autonomy-undecidability)

[![quality-gate](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml/badge.svg)](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml)

**Mission**  
Demonstrate why universal, unbounded autonomy verification is undecidable in general, and what bounded assurance can prove.

**Claim**  
Full computational autonomy is a nontrivial semantic property; per Rice's Theorem, no algorithm can decide it for all programs. What we can do is define scope, enforce bounds, and verify the bounded model with runnable reductions and repeatable tests.

**Evidence**
1. [Start here - start_here.md](https://github.com/bradsaucier/autonomy-undecidability/blob/master/start_here.md)
2. [Theory notes - theory/](https://github.com/bradsaucier/autonomy-undecidability/tree/master/theory)
3. [Reproducible tests - tests/](https://github.com/bradsaucier/autonomy-undecidability/tree/master/tests)

**Verify**
Success criteria - repeatable from a clean environment using documented commands and expected outputs.
1. Execute the demo cases via the repo instructions.
2. Validate scope constraints against the bounded model before drawing conclusions.

### Artemis Security Evidence
**Repo**: [bradsaucier/artemis-security-evidence](https://github.com/bradsaucier/artemis-security-evidence)

[![docs-ci](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml/badge.svg)](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml)

**Mission**  
Documentation Body of Evidence (SNHU CS-305). Covers risk assessment, hardening practices, and verification artifacts.

**Claim**  
Security posture is only credible when scoped, reproducible, and artifact-backed. Narrative reports are not enough without traceable evidence and an explicit verification path.

**Evidence**
1. [Verification notes - docs/VERIFICATION.md](https://github.com/bradsaucier/artemis-security-evidence/blob/main/docs/VERIFICATION.md)
2. [Reports - reports/](https://github.com/bradsaucier/artemis-security-evidence/tree/main/reports)
3. [Evidence artifacts - evidence/](https://github.com/bradsaucier/artemis-security-evidence/tree/main/evidence)

**Verify**
Success criteria - repeatable from a clean environment using documented commands and expected outputs.
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
Success criteria - repeatable from a clean environment using documented commands and expected outputs.
1. Build from a clean environment using the repo instructions.
2. Validate input handling and prerequisite checks using the provided sample data and docs.

## Capabilities
**Engineering**
1. Reliability under constraint - deterministic behavior where feasible; explicit bounds and failure modes where not.
2. Verification and CI - repeatable runs, automated gates, and evidence trails that survive turnover.
3. Security evidence - scoped claims, traceable artifacts, and verification notes.

Where applicable, repos include explicit constraints (time, memory, failure modes) and measurable verification criteria (tests, CI gates, reproducible runs).

**Stack (demonstrated across repos)**
1. Languages - Python, C++17, Java
2. Automation - GitHub Actions, CI quality gates
3. Environments - Linux-first workflows; containers where they improve reproducibility

## Leadership and Delivery Doctrine
1. Requirements translation - objectives into requirements, acceptance criteria, and verification methods.
2. Risk bounded delivery - define scope up front; document assumptions; ship within an explicit risk envelope.
3. Decision logs - capture the why, not just the what; changes must survive turnover and audit.
4. Integration mindset - hardware, software, and operator workflows are one system; failure modes live in the seams.
5. Standards - testable claims, reproducible results, auditable changes.

## Collaboration SOP
Quick start (copy-paste into an issue):
"I need help with [X] in [repo]. What I tried: [Y]. Output/error: [Z]. Constraints: [time/safety/interfaces]. Success: [definition]."

<details>
<summary><strong>Routing, required issue content, and full template</strong></summary>

**Routing**
1. Repo-specific topics - open an issue in that repository.
2. Cross-repo topics - open an issue in the repo that best matches the problem and link artifacts.

**Required issue content**
1. Context - system, environment, what changed.
2. Constraints - time, safety, interfaces, policy, dependencies.
3. Desired outcome - what success looks like.
4. Definition of done - tests, checks, artifacts, acceptance criteria.
5. Evidence - logs, repro steps, commands run, links.

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
Core mapping: environment establishment, flow control under constraint, incident decisioning (OODA) translated into verification-first delivery.

This is personal work and does not represent any employer or agency. No proprietary, classified, sensitive, or export-controlled (ITAR or EAR) technical data is intended for publication here.

## Education
1. B.S. Computer Science (in progress, expected 2026) - Southern New Hampshire University (STEM Project Management)
2. B.A. - Columbia University
3. A.A.S. - Community College of the Air Force
