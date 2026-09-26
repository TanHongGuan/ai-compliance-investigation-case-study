# 04 \- Stakeholder & User Needs Analysis

## 1. Purpose

This analysis identifies the stakeholders affected by the opportunities progressing from the Problem Analysis stage and defines the user needs that should guide subsequent requirements and solution design.

Two opportunities progress into this analysis:

| ID | Opportunity |
| --- | --- |
| **OP-01 — Compliance Investigation Efficiency** | How might we reduce repetitive information-gathering and analysis effort during flagged-transaction investigations while preserving analyst judgement, accuracy and regulatory oversight? |
| **OP-02 — Compliance Case Traceability** | How might we maintain consistent traceability of compliance-case evidence, reasoning, decisions and subsequent actions while minimising unnecessary documentation effort for analysts? |

OP-01 and OP-02 were progressed with conditions. OP-03 was placed on hold because the underlying unmet user need was not sufficiently established. Pasted text

---

## 2. Stakeholder Identification

| Stakeholder | Role in Process | OP-01 | OP-02 |
| --- | --- | --- | --- |
| **Compliance Analyst** | Reviews flagged transactions, gathers and assesses relevant information, determines case outcomes and documents reasoning. | Primary | Primary |
| **Compliance Manager / Reviewer** | Reviews escalated cases and relies on sufficient investigation information and decision reasoning. | Secondary | Secondary |
| **Compliance Auditor** | Requires traceable case records to review how compliance decisions were reached. | — | Secondary |
| **Regulator / Supervisory Authority** | Indirectly relies on appropriate investigation, record-keeping and regulatory reporting processes. | Indirect | Indirect |

The Compliance Analyst is the primary stakeholder across both opportunities. The previous analysis identified managers/reviewers as secondary stakeholders for investigation efficiency and managers, reviewers, assurance functions and supervisory authorities as relevant to traceability. Pasted text Pasted text

---

## 3. OP-01 — Compliance Investigation Efficiency

### 3.1 Primary Stakeholder

**Compliance Analyst**

Compliance analysts perform human-led investigation activities including reviewing alerts, gathering information, analysing customer activity and documenting case justifications. The magnitude of the resulting workload and scalability impact remains unquantified. Pasted text

### 3.2 User Need

> **Review flagged cases and relevant investigation information efficiently in one place while retaining control over the final decision and maintaining investigation quality.**

The need consists of three elements:

| Need Dimension | Description |
| --- | --- |
| **Information accessibility** | Relevant case information should be available for efficient review. |
| **Investigation efficiency** | Avoidable repetitive information-gathering and analysis effort should be reduced where possible. |
| **Human control** | Analysts must retain judgement and responsibility for the final compliance decision. |

### 3.3 Desired Outcome

Reduce avoidable investigation effort while maintaining:

- investigation quality;
- analyst judgement;
- accuracy;
- appropriate escalation; and
- regulatory oversight. Pasted text

### 3.4 Constraints

| Constraint | Requirement |
| --- | --- |
| **Human** | Analyst judgement and appropriate human review must be preserved. |
| **Regulatory** | Investigation and escalation processes must remain compatible with applicable AML/CFT obligations. |
| **Security** | Customer and investigation information must remain confidential. |
| **Business** | Existing investigation controls and operational continuity must not be weakened. |
| **Technical** | The project should not assume access to TNG Digital production systems. |

These constraints were explicitly carried forward from the opportunity analysis. Pasted text

---

## 4. OP-02 — Compliance Case Traceability

### 4.1 Primary Stakeholder

**Compliance Analyst**

The analyst requires a practical way to record the reasoning and actions associated with a compliance decision without unnecessary documentation effort.

### 4.2 User Need

> **Record compliance decisions and associated reasoning without having to manually structure the complete case history.**

The intended outcome is not to reduce required evidence. It is to maintain complete and retrievable case histories while avoiding unnecessary documentation burden. Pasted text

---

### 4.3 Secondary Stakeholders

**Compliance Manager / Reviewer**  
**Compliance Auditor**

These stakeholders require sufficient case history to understand and review how a compliance decision was reached.

### 4.4 User Need

> **Trace what occurred during a compliance case and understand the evidence, reasoning, decision and subsequent actions associated with it.**

The required case history should enable an authorised reviewer to determine:

- what occurred;
- what evidence was considered;
- what decision was made;
- why the decision was made; and
- what action followed.

### 4.5 Desired Outcome

Maintain a **complete, retrievable and understandable case history** without imposing unnecessary documentation effort. Pasted text

### 4.6 Constraints

| Constraint | Requirement |
| --- | --- |
| **Attribution** | Reasoning must remain attributable to the responsible reviewer or analyst. |
| **Record keeping** | Required records must remain complete and retrievable. |
| **Security** | Sensitive case information requires appropriate confidentiality and access controls. |
| **Evidence quality** | Reduced documentation effort must not result in weaker evidence. |
| **Technical** | The project should not assume access to existing TNG Digital production case-management systems. |

Pasted text

---

## 5. User Needs Summary

| ID | Opportunity | Stakeholder | User Need |
| --- | --- | --- | --- |
| **UN-01** | OP-01 | Compliance Analyst | Review flagged cases and relevant investigation information efficiently in one place while retaining control over the final decision and maintaining investigation quality. |
| **UN-02** | OP-02 | Compliance Analyst | Record compliance decisions and associated reasoning without manually structuring the complete case history. |
| **UN-03** | OP-02 | Compliance Manager / Reviewer / Auditor | Trace the case history and understand the evidence, reasoning, decision and subsequent actions associated with it. |

---

## 6. Assumptions and Validation Gaps

| Assumption / Gap | Impact | Further Validation |
| --- | --- | --- |
| The activities creating the greatest analyst investigation effort are not known. | UN-01 may target activities that provide limited efficiency improvement. | Analyst interviews / process observation |
| Investigation workload and turnaround time are not quantified. | The materiality of the efficiency opportunity remains uncertain. | Operational data |
| Existing TNG Digital case-management capabilities are unknown. | Some elements of UN-02 or UN-03 may already be adequately supported. | Internal system/process review |
| Analyst documentation burden has not been quantified. | The potential value of reducing documentation effort remains uncertain. | Analyst interview / observation |

These remain explicit research gaps from the preceding analysis. Pasted text

---

## 7. Analysis Outcome

Three user needs are carried forward:

> **UN-01 — Efficient Investigation Review**  
> Consolidate and simplify the review of relevant case information while preserving human judgement and investigation quality.

> **UN-02 — Efficient Decision Recording**  
> Enable analysts to record decisions and reasoning without unnecessary manual structuring.

> **UN-03 — Case Traceability**  
> Enable authorised reviewers to reconstruct and understand the evidence, reasoning, decision and subsequent actions associated with a compliance case.
