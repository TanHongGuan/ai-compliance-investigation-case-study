# 02 \- Problem Analysis & Validation

# Executive Summary

External research produced **three defensible central pain-point candidates**:

1. **Compliance investigation workload and scalability**
2. **Compliance-case evidence and decision traceability**
3. **Transaction-status understanding during exceptions**

A fourth theme—**real-time regulatory visibility**—is relevant to the challenge but is better retained as an **unresolved hypothesis** rather than promoted to a validated pain point at this stage.

The strongest direct evidence currently concerns TNG Digital's transaction-monitoring process. TNG Digital job descriptions show analysts conducting first-level reviews, in-depth investigations, gathering information from internal systems, public searches, commercial databases and business units, documenting evidence and preparing narratives/justifications. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)

Importantly, this proves that these activities exist. It does **not** prove excessive workload or poor performance.

# 1. Pain Point Discovery

## 1.1 Issues Identified

| ID | Issue identified | Initial interpretation |
| --- | --- | --- |
| I-01 | Analysts conduct in-depth reviews of transaction-monitoring alerts | Investigation activity |
| I-02 | Analysts gather evidence from multiple internal and external sources | Contributing factor |
| I-03 | Analysts prepare findings, narratives and justifications | Contributing factor |
| I-04 | TNG monitors timely alert/case closure and investigation turnaround time | Potential workload/efficiency indicator |
| I-05 | TNG recalibrates transaction-monitoring parameters to reduce false positives | Potential workload/quality contributor |
| I-06 | Compliance records/evidence must be retained and retrievable | Regulatory constraint |
| I-07 | Compliance decisions and supporting evidence require traceability | Potential central pain point |
| I-08 | Some failed/pending transactions require users to inspect status, wait or seek support | Potential user transparency problem |
| I-09 | Regulatory supervision can benefit from more timely/data-driven monitoring | Potential opportunity/risk |
| I-10 | Real-time regulatory visibility is assumed to be necessary | Unresolved hypothesis |

## 1.2 Issue Classification

| Issue | Classification | Reason |
| --- | --- | --- |
| Repetitive/deep transaction investigation | Central Pain Point candidate | Potential material workload/scalability impact |
| Evidence gathered from multiple sources | Contributing Factor | Contributes to investigation effort |
| Narrative/justification preparation | Contributing Factor | Part of investigation/documentation workload |
| False-positive alerts | Contributing Factor | Can create unnecessary review workload |
| Timely case closure requirement | Constraint / Requirement | A required operational outcome, not itself a pain |
| Evidence retention | Constraint / Requirement | Regulatory obligation |
| Case traceability | Central Pain Point candidate | Relevant to auditability/compliance |
| Transaction exception understanding | Central Pain Point candidate | Potential user transparency impact |
| Real-time regulator monitoring | Potential Risk / unresolved need | Additional value to BNM/TNG not directly established |

## 1.3 Consolidation

The first important consolidation is:

> alert review + searching internal systems + external searches + evidence gathering + stakeholder inquiries + narrative preparation

should **not** become six separate pain points.

TNG Digital's own role descriptions show these activities forming part of the same investigation workflow. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)

They are therefore consolidated into:

> **PP-01 — Compliance investigations involve substantial human-led evidence gathering and analysis, potentially creating workload and scalability constraints.**

Similarly, record retention, evidence preservation, rationale, reviewer activity and regulator access are related to a broader traceability issue rather than separate pain points.

## 1.4 Candidate Pain Point Shortlist

| ID | Candidate Pain Point | Stakeholder / Process | Potential Impact | Classification | Proceed? |
| --- | --- | --- | --- | --- | --- |
| PP-01 | Compliance investigations involve substantial human-led evidence gathering and analysis, potentially constraining efficiency and scalability | Compliance analysts | Workload, efficiency, scalability | Central Pain Point | **Yes** |
| PP-02 | Compliance cases require evidence, reasoning and actions to remain consistently traceable and retrievable across the case lifecycle | Analysts / reviewers / regulators | Auditability, compliance, decision quality | Central Pain Point | **Yes** |
| PP-03 | Users may face uncertainty when payment/reload transactions enter failed or pending states | eWallet users | Transparency, customer experience | Central Pain Point | **Yes** |
| PP-04 | Regulators may lack sufficiently timely visibility into emerging compliance risks | Regulators | Oversight, risk visibility | Potential Risk / unresolved hypothesis | **Hold** |

---

# 2. PP-01 — Compliance Investigation Workload and Scalability

## 2.1 Candidate Pain Point

TNG Digital's transaction-monitoring process requires human investigation, evidence gathering, analysis and case documentation, which may create an efficiency or scalability constraint.

## 2.2 Known Facts

TNG Digital recruitment material describes first-level alert review and in-depth investigation of flagged transactions. Analysts gather data and record evidence using internal systems, public searches, commercial databases and inquiries to business units or other stakeholders, then prepare findings and justifications for escalation. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)

TNG Digital management roles also explicitly mention timely review/closure, turnaround-time requirements, recalibrating parameters to reduce false-positive alerts and enhancing AML/CFT systems to improve efficiency. [LinkedIn](https://www.linkedin.com/jobs/view/3936676641/?utm_source=chatgpt.com)

## 2.3 Assumptions Requiring Validation

- Current workload is excessive.
- Evidence gathering takes excessive time.
- Current alert volumes create a scalability problem.
- False positives materially consume analyst capacity.
- Existing systems insufficiently support investigation.
- Automation would materially reduce investigation time.

## 2.4 Testable Hypotheses

**H1:** Human-led investigation forms a material part of TNG Digital's transaction-monitoring process.

**H2:** Investigation involves multiple information-gathering and documentation activities.

**H3:** These activities create a meaningful efficiency/workload constraint.

**H4:** Alert volumes and false positives create a material scalability issue.

## 2.5 Evidence Required

Supporting evidence would include direct workflow descriptions, workload metrics, alert volumes, investigation time, turnaround time, backlogs, false-positive rates, staffing demand and evidence of process/system improvement targeted at workload.

Evidence weakening the hypothesis would include high automation rates, low investigation workload, low false-positive rates, consistently short turnaround times or evidence that recent systems have already removed the proposed bottleneck.

| Implication | Meaning |
| --- | --- |
| **Strengthens** | Evidence clearly supports the hypothesis |
| **Partially strengthens** | Supports part of it, but not enough to support the whole claim |
| **Neutral** | Doesn't meaningfully support or challenge it |
| **Weakens** | Gives reason to doubt the hypothesis |
| **Contradicts** | Directly conflicts with the hypothesis |

## 2.6 Findings

### Finding F1 — Human investigation is directly established

> **Finding:** Direct evidence from TNG Digital shows human analysts review alerts and conduct in-depth investigations.
> 
> **Evidence:** TNG Digital's Transaction Monitoring role requires first-level alert review, analysis of customer/account activity and investigation of flagged transactions. [LinkedIn](https://my.linkedin.com/jobs/view/senior-associate-transaction-monitoring-tng-digital-at-touch-n-go-group-4022564716?utm_source=chatgpt.com)
> 
> **Interpretation:** H1 is directly supported.
> 
> **Limitation:** It does not establish that the activity is inefficient.
> 
> **Implication:** **Strengthens.**

### Finding F2 — Investigation requires multiple evidence sources

> **Finding:** Direct TNG Digital evidence shows analysts gather and record information from several source types.
> 
> **Evidence:** The role specifies internal systems, public searches, commercial databases, business units and other stakeholders, plus detailed narratives and justifications. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)
> 
> **Interpretation:** H2 is directly supported and indicates a multi-step information-synthesis process.
> 
> **Limitation:** No public evidence quantifies how much analyst time this consumes.
> 
> **Implication:** **Strengthens.**

### Finding F3 — Efficiency and false positives are recognised operational concerns

> **Finding:** TNG Digital management roles explicitly reference reducing false-positive alerts and improving AML/CFT system efficiency.
> 
> **Evidence:** The Assistant Manager role calls for parameter recalibration to reduce false positives and system enhancements to improve AML/CFT system efficiency. [LinkedIn](https://www.linkedin.com/jobs/view/3936676641/?utm_source=chatgpt.com)
> 
> **Interpretation:** This provides direct evidence that efficiency and false-positive management are operational considerations.
> 
> **Limitation:** It still does not establish the magnitude of the problem or that analysts are overloaded.
> 
> **Implication:** **Partially strengthens.**

## 2.7 Contradictory Evidence

The same evidence indicates that TNG Digital already uses an **AML transaction-monitoring platform** and automated alert generation rather than relying on an entirely manual compliance process. [LinkedIn](https://www.linkedin.com/jobs/view/3936676641/?utm_source=chatgpt.com)

Therefore, the claim should **not** be framed as:

> "TNG's AML process is manual."

The defensible claim concerns the **human investigation stage after alerts are generated**.

## 2.8 Research Gaps

- alert volumes
- false-positive rate
- average investigation time
- analyst caseload
- case backlog
- proportion of investigation time spent gathering information
- current automation capabilities

## 2.9 Validation Assessment

**Evidence Strength: 4/5 — Multiple Independent Direct Evidence**

**Validation Result: Partially Validated**

The existence and multi-step nature of human investigation are strongly supported. Efficiency is also directly recognised as an improvement concern. However, public evidence does not establish the **magnitude** of workload, delay or scalability impact.

## 2.10 Refined Problem Statement

> TNG Digital's transaction-monitoring investigations require analysts to review alerts, gather information from multiple internal and external sources, analyse customer activity and document case justifications. Available evidence indicates an opportunity to improve investigation efficiency, but the magnitude of the current workload and scalability impact remains unquantified.

## 2.11 Opportunity Statement

> **How might we reduce repetitive information-gathering and analysis effort during flagged-transaction investigations while preserving analyst judgement, accuracy and regulatory oversight?**

---

# 3. PP-02 — Compliance Decision Traceability

## Candidate Pain Point

Compliance investigations require supporting evidence, reasoning and resulting actions to remain traceable and retrievable.

### Key Finding

TNG Digital analysts are explicitly required to gather and record evidence and prepare complete narratives/justifications when escalating suspicious alerts. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)

BNM separately requires reporting institutions to retain relevant AML records; internally generated STR reports and supporting documents must be retained for at least six years, and records must be available to supervisory or competent authorities when required. [Bank Negara Malaysia AML/CFT](https://amlcft.bnm.gov.my/faq/tfs-fi/record-keeping?utm_source=chatgpt.com)

This establishes a strong **traceability requirement**.

However, it does **not establish that TNG Digital's current records are fragmented, inconsistent or difficult to retrieve.**

### Validation

**Evidence Strength: 3/5 — Single Direct Evidence for organizational process, reinforced by regulatory requirements**

**Validation Result: Partially Validated**

The need for evidence/documentation/traceability is validated. A current TNG-specific **traceability failure** is not.

### Refined Problem Statement

> TNG Digital's compliance investigations require evidence and case justification to be recorded, while Malaysian AML requirements require relevant records and supporting documentation to remain available for supervisory purposes. The available evidence establishes a material traceability requirement but does not demonstrate deficiencies in TNG Digital's current audit-trail process.

### Opportunity Statement

> **How might we make compliance-case evidence, reasoning, decisions and subsequent actions consistently traceable while minimising additional documentation burden on analysts?**

---

# 4. PP-03 — Transaction Exception Transparency

## Candidate Pain Point

Users may experience uncertainty when transactions enter failed, delayed or pending states.

### Key Finding

TNG's own current support material shows that some transaction types can remain pending for up to 24 hours and directs users to transaction history to determine status; unsuccessful transactions may subsequently be automatically reversed. [Touch 'n Go eWallet Help Centre](https://support.tngdigital.com.my/hc/en-my/articles/360063455053-What-should-I-do-if-my-DuitNow-QR-payment-is-unsuccessful?utm_source=chatgpt.com)

Other current help material lists numerous possible causes of reload failure, including connectivity, downtime, wallet limits, incorrect card details, issuing-bank rejection, device issues and high traffic. [Touch 'n Go eWallet Help Centre](https://support.tngdigital.com.my/hc/en-my/articles/4405483924761-Why-can-t-I-reload-with-my-credit-debit-card?utm_source=chatgpt.com)

This establishes that transaction exceptions exist and that users sometimes need status/reason information.

However, it does **not demonstrate that TNG's current explanations are inadequate**. In fact, the help centre itself is evidence that explanatory information already exists.

### Validation

**Evidence Strength: 3/5 — Direct target-organisation evidence**

**Validation Result: Partially Validated**

Transaction-status exceptions are real; the claimed **unmet transparency problem** remains unproven without user research, complaints data or usability evidence.

### Refined Problem Statement

> TNG eWallet users encounter transaction states such as failed, pending or delayed processing for which status, cause and next-step information may be important. Existing TNG support resources already provide explanations for many scenarios, so whether users currently lack sufficient transaction transparency requires further user-level validation.

### Opportunity Statement

> **How might we help users understand exceptional transaction states and appropriate next actions without overwhelming them with unnecessary technical information?**

---

# 5. PP-04 — Real-Time Regulatory Visibility

This one should **not yet be promoted to a validated Central Pain Point**.

BNM clearly performs AML/CFT supervisory and financial-intelligence functions, including receiving and analysing STRs and supervising reporting institutions. [Bank Negara Malaysia AML/CFT](https://amlcft.bnm.gov.my/my-amlcft-regime?utm_source=chatgpt.com) BIS research also shows that real-time monitoring is an established SupTech concept and differs from automated periodic reporting. [Bank for International Settlements](https://www.bis.org/fsi/publ/insights19.pdf?utm_source=chatgpt.com)

But neither establishes:

> **BNM currently lacks sufficiently timely information from TNG Digital.**

Nor do they establish:

> **BNM needs continuous real-time access to TNG's compliance dashboard.**

Your original PDF was therefore correct to leave this unresolved: it explicitly questions whether real-time visibility adds enough value over existing reporting. T2H-01 - Problem Decomposition-…

**Current status: Hold as unresolved hypothesis / potential opportunity.**

---

# Cross-Pain-Point Analysis

The strongest relationship is between **PP-01 and PP-02**:

**Flag generated → analyst investigates → information gathered → evidence assessed → decision made → rationale documented → case escalated/closed → records retained.**

PP-01 concerns the **effort required to perform the investigation**. PP-02 concerns the **traceability of what happened during and after that investigation**. They therefore share the same compliance-case lifecycle but represent different desired outcomes: **efficiency** versus **auditability**.

PP-03 belongs to the user-facing transparency branch and is materially more separate.

PP-04 belongs to regulatory oversight and could later consume outputs from PP-01/PP-02, but the current research does not justify making it a primary problem.

# Final Validation Summary

| ID | Refined Pain Point | Stakeholder | Impact | Evidence | Result |
| --- | --- | --- | --- | --- | --- |
| **PP-01** | Human-led investigation requires multi-source evidence gathering, analysis and documentation | Compliance analysts | Efficiency / scalability | **4/5** | **Partially Validated** |
| **PP-02** | Compliance cases carry a material requirement for evidence and decision traceability; current deficiencies are unproven | Compliance / reviewers / regulators | Auditability / compliance | **3/5** | **Partially Validated** |
| **PP-03** | Transaction exceptions create a need for understandable status/next-step information; unmet transparency is unproven | Users | Transparency / CX | **3/5** | **Partially Validated** |
| **PP-04** | Insufficient real-time regulatory visibility | Regulators | Oversight | **2/5** | **Not Validated** |

## Final Research Gaps

| Research Gap | Why It Matters | Recommended Validation |
| --- | --- | --- |
| Alert volume / analyst caseload | Establish PP-01 materiality | Internal operational data |
| Investigation turnaround time | Establish actual efficiency impact | Case/system logs |
| False-positive rate | Quantify unnecessary review | AML monitoring data |
| Analyst time by investigation activity | Identify actual bottleneck | Interviews + process observation |
| Existing audit-trail capability | Determine whether PP-02 is actually a problem | System/process review |
| User complaints about failed/pending transactions | Establish PP-03 unmet need | Complaint/support data |
| BNM/TNG reporting cadence | Establish PP-04 | Regulatory/process documentation |
| Regulator demand for greater timeliness | Determine real-time value | BNM evidence/interviews |
