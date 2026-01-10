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

  <p>
    <a href="https://github.com/bradsaucier">
      <img alt="GitHub" src="https://img.shields.io/badge/GitHub-bradsaucier-181717?style=for-the-badge&logo=github&logoColor=white" height="28" />
    </a>
    <a href="https://viper1.me/">
      <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-viper1.me-333333?style=for-the-badge" height="28" />
    </a>
  </p>

  <p>
    <code><a href="#bottom-line-up-front-bluf">BLUF</a></code> |
    <code><a href="#identity">IDENTITY</a></code> |
    <code><a href="#evidence-locker">EVIDENCE</a></code> |
    <code><a href="#capabilities">CAPABILITIES</a></code> |
    <code><a href="#doctrine">DOCTRINE</a></code> |
    <code><a href="#intake-format">INTAKE</a></code> |
    <code><a href="#contact">CONTACT</a></code> |
    <code><a href="#boundaries">BOUNDARIES</a></code>
  </p>

  <p>
    <img alt="Python" height="24" src="https://img.shields.io/static/v1?label=&message=Python&color=101214&logo=python&logoColor=3776AB&cacheSeconds=3600&style=for-the-badge" />
    <img alt="C++20" height="24" src="https://img.shields.io/static/v1?label=&message=C%2B%2B20&color=101214&logo=c%2B%2B&logoColor=00599C&cacheSeconds=3600&style=for-the-badge" />
    <img alt="Java" height="24" src="https://img.shields.io/static/v1?label=&message=Java&color=101214&logo=openjdk&logoColor=ED8B00&cacheSeconds=3600&style=for-the-badge" />
    <img alt="SQL" height="24" src="https://img.shields.io/static/v1?label=&message=SQL&color=101214&logo=mysql&logoColor=4479A1&cacheSeconds=3600&style=for-the-badge" />
    <img alt="Docker" height="24" src="https://img.shields.io/static/v1?label=&message=Docker&color=101214&logo=docker&logoColor=2496ED&cacheSeconds=3600&style=for-the-badge" />
    <img alt="Linux" height="24" src="https://img.shields.io/static/v1?label=&message=Linux&color=101214&logo=linux&logoColor=FCC624&cacheSeconds=3600&style=for-the-badge" />
  </p>
</div>

<br>

**`// SYSTEM CHECKPOINT`**
---

<a id="bottom-line-up-front-bluf"></a>
## >_ Bottom Line Up Front (BLUF)

> [!IMPORTANT]
> **BOTTOM LINE UP FRONT**
> I translate operational intent into engineering requirements and verified deliverables. If it is not testable or auditable, it is not a claim.
>
> Standard
> 1. Deterministic behavior where feasible.
> 2. Where not feasible - explicit bounds, failure modes, and risk envelopes.
>
> Output
> 1. Traceable requirements
> 2. CI/CD quality gates
> 3. Documented risk envelopes
> 4. Reproducible builds

**`// SYSTEM CHECKPOINT`**
---

<a id="identity"></a>
## >_ Identity

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

**`// SYSTEM CHECKPOINT`**
---

## >_ Current Focus

1. Publishing repeatable assurance-case templates (claims, evidence trails, verification steps) - see autonomy-undecidability and artemis-security-evidence.
2. Strengthening CI gates that survive turnover (assumptions, decision logs, reproducible runs) - see autonomy-undecidability quality-gate patterns.
3. Advancing formal methods and software security through applied coursework artifacts - see Evidence Locker entries.

**`// SYSTEM CHECKPOINT`**
---

<a id="evidence-locker"></a>
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

### >_ Status Board

1. **Computational Autonomy and Undecidability**<br>
   <code>FOCUS</code>: Repeatable assurance-case templates.<br>
   <code>GATE</code>: [![quality-gate](https://img.shields.io/github/actions/workflow/status/bradsaucier/autonomy-undecidability/quality_gate.yml?label=quality-gate&style=for-the-badge)](https://github.com/bradsaucier/autonomy-undecidability/actions/workflows/quality_gate.yml)<br>
   <code>REPO</code>: [bradsaucier/autonomy-undecidability](https://github.com/bradsaucier/autonomy-undecidability)

2. **Artemis Security Evidence**<br>
   <code>FOCUS</code>: Security evidence trails and verification steps.<br>
   <code>GATE</code>: [![docs-ci](https://img.shields.io/github/actions/workflow/status/bradsaucier/artemis-security-evidence/docs-ci.yml?label=docs-ci&style=for-the-badge)](https://github.com/bradsaucier/artemis-security-evidence/actions/workflows/docs-ci.yml)<br>
   <code>REPO</code>: [bradsaucier/artemis-security-evidence](https://github.com/bradsaucier/artemis-security-evidence)

3. **CS-300 Course Planner**<br>
   <code>FOCUS</code>: Algorithmic planning structures.<br>
   <code>GATE</code>: [![ci](https://img.shields.io/github/actions/workflow/status/bradsaucier/CS300-CoursePlanner/ci.yml?label=ci&style=for-the-badge)](https://github.com/bradsaucier/CS300-CoursePlanner/actions/workflows/ci.yml)<br>
   <code>REPO</code>: [bradsaucier/CS300-CoursePlanner](https://github.com/bradsaucier/CS300-CoursePlanner)

**`// SYSTEM CHECKPOINT`**
---

<a id="capabilities"></a>
## >_ Capabilities

| Domain | Capability |
| --- | --- |
| Engineering | Mission-critical delivery, secure software practices, supply chain hygiene |
| Tooling | C++20, Python, Java, SQL, GitHub Actions, CMake, Maven, Docker, Linux |
| Operating stance | Explicit bounds, explicit failure modes, decision logs (ADR), reproducible builds |

**`// SYSTEM CHECKPOINT`**
---

<a id="doctrine"></a>
## >_ Doctrine

1. Requirements translation - objectives into requirements, acceptance criteria, verification methods.
2. Risk-bounded delivery - define scope up front; document assumptions; ship within an explicit risk envelope.
3. Decision logs - capture the why, not just the what; changes must survive turnover and audit.
4. Simplicity under pressure - fewer moving parts, fewer failure modes. Hardware, software, operator workflows are one system.
5. Standards - testable claims, reproducible results, auditable changes.

**`// SYSTEM CHECKPOINT`**
---

<a id="intake-format"></a>
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

**`// SYSTEM CHECKPOINT`**
---

<a id="background"></a>
## >_ Background

I apply 22 years of USAF Combat Control operational risk management to engineering work: explicit assumptions, clear acceptance criteria, and verification gates that hold up under audit. This profile focuses on personal methodology and public academic artifacts.

**`// SYSTEM CHECKPOINT`**
---

<a id="education"></a>
## >_ Education

| Program | Institution |
| --- | --- |
| B.S. Computer Science (Project Management for STEM concentration) - in progress | Southern New Hampshire University |
| B.A. Economics | Columbia University |
| A.A.S. | Community College of the Air Force (CCAF) |

**`// SYSTEM CHECKPOINT`**
---

<a id="contact"></a>
## >_ Contact

Primary: GitHub - https://github.com/bradsaucier  
Portfolio: https://viper1.me/  
Preferred: open a GitHub Issue or Discussion in the relevant repo and follow the Intake Format above.

**`// SYSTEM CHECKPOINT`**
---

<a id="boundaries"></a>
## >_ Boundaries

> [!CAUTION]
> **BOUNDARIES**
> This profile reflects personal methodology and academic work only. It does not represent the views, policies, or proprietary methods of any current or former employer. No classified, controlled unclassified information (CUI), or export-controlled (ITAR or EAR) technical data is intended for publication here.

```text
// END TRANSMISSION
// VERIFICATION HASH: 90ba5e401f43634423d8a62e19165a6f1c04ed8e6b500e4fc238b8789ebd4f37
```
