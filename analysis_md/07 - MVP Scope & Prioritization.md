# 07 \- MVP Scope & Prioritization

## 1. Purpose

This stage defines the Minimum Viable Product (MVP) required to demonstrate the core value of the proposed compliance investigation solution.

The scope is derived from the stakeholder needs and requirements established in the preceding analysis. It determines:

- which capabilities are required for the MVP;
- which capabilities provide additional value but are not essential;
- which capabilities are deliberately excluded; and
- the boundary within which the MVP will be designed and evaluated.

The MVP is intended to demonstrate a **post-alert compliance investigation workflow** rather than reproduce TNG Digital's complete transaction-monitoring or AML/CFT environment.

---

## 2. MVP Objective

The MVP will demonstrate whether a compliance analyst can:

> **Review a pre-flagged transaction efficiently, understand relevant case information, retain control of the final decision, record the reasoning and resulting action, and produce a structured and traceable case history.**

The MVP therefore combines the two progressing opportunities:

| Opportunity | MVP Value |
| --- | --- |
| **OP-01 — Compliance Investigation Efficiency** | Support more efficient review of flagged cases while preserving human judgement. |
| **OP-02 — Compliance Case Traceability** | Maintain a consistent and traceable record of evidence, reasoning, decisions and subsequent actions. |

---

# 3. MVP Boundary

## 3.1 Start Boundary

The MVP begins **after a transaction has already been flagged for investigation**.

The process that detects suspicious activity or determines whether a transaction should be flagged is outside the MVP boundary.

## 3.2 End Boundary

The MVP ends when:

1. the analyst has reviewed the case;
2. the analyst has made a decision;
3. the reasoning and relevant action have been recorded; and
4. the case history has been preserved for authorised review.

## 3.3 Boundary Definition

> **Flagged Case → Case Review → Information Assessment → Human Decision → Reason Recording → Follow-up Action → Audit History**

The MVP does not attempt to automate the complete compliance lifecycle.

---

# 4. Prioritisation Method

MoSCoW prioritisation is used to distinguish between capabilities required to prove the MVP's core value and capabilities that can be deferred.

| Priority | Definition |
| --- | --- |
| **Must Have** | Essential to complete the core workflow or preserve a critical control. Without it, the MVP cannot adequately demonstrate its intended value. |
| **Should Have** | Important and valuable, but the core MVP can still operate without it. |
| **Could Have** | Useful enhancement that may improve the experience but is not required to validate the MVP. |
| **Won't Have for Now** | Deliberately excluded from the current MVP due to scope, access, complexity or lack of necessity for validating the core proposition. |

---

# 5. Must Have

These capabilities are necessary to demonstrate the complete post-alert investigation and traceability workflow.

| ID | Capability | Rationale |
| --- | --- | --- |
| **M-01** | Consolidated case view | Provides analysts with relevant case information in one location. |
| **M-02** | Case summary | Supports efficient understanding of the flagged case. |
| **M-03** | Decision reason captured | Preserves the analyst's justification for the final decision. |
| **M-04** | Follow-up case actions | Supports dismiss, escalate or further-review actions. |
| **M-05** | Human final decision | Preserves analyst judgement and prevents autonomous compliance decisions. |
| **M-06** | Consistent record structure | Ensures required case information is recorded consistently. |
| **M-07** | Chronological case history | Enables reconstruction of relevant events, decisions and actions. |
| **M-08** | Preservation of audit history | Prevents historical case information from being silently lost or overwritten. |
| **M-09** | Access control | Restricts sensitive case information to authorised users. |
| **M-10** | Retention of important case information | Ensures relevant information remains available throughout the case lifecycle. |

These capabilities collectively establish the minimum end-to-end workflow required to demonstrate both investigation assistance and traceability.

---

# 6. Should Have

These capabilities materially improve the usefulness, quality or usability of the MVP but are not required for the basic workflow to function.

| ID | Capability | Rationale |
| --- | --- | --- |
| **S-01** | Key risk indicators highlighted | Helps analysts identify information requiring attention more efficiently. |
| **S-02** | Short explanation accompanying the case summary | Improves interpretability of the information presented to the analyst. |
| **S-03** | Fast case-page loading | Reduces avoidable delays during investigation. |
| **S-04** | Usable and efficient recording interface | Reduces unnecessary effort when recording decisions and actions. |
| **S-05** | Tamper-resistant case records | Strengthens confidence in the integrity of historical case information. |

Quantitative performance, usability and integrity thresholds remain subject to later validation.

---

# 7. Could Have

These capabilities provide additional operational value but are not necessary to demonstrate the MVP's core proposition.

| ID | Capability | Rationale |
| --- | --- | --- |
| **C-01** | Advanced filtering across raised alerts | Improves navigation and prioritisation when working with larger numbers of cases. |
| **C-02** | Dedicated manager / reviewer view | Provides a role-specific interface for secondary stakeholders. |

These capabilities should only be included if time and implementation capacity remain after the Must Have and Should Have requirements are adequately addressed.

---

# 8. Won't Have for Now

The following capabilities are deliberately excluded from the current MVP.

| ID | Excluded Capability | Reason |
| --- | --- | --- |
| **W-01** | Direct integration with TNG Digital production systems | Production-system access is not available and is not required to demonstrate the concept. |
| **W-02** | Real TNG Digital customer or investigation data | Sensitive production data is unnecessary for prototype validation; representative synthetic data can be used. |
| **W-03** | End-to-end fully automated compliance decision-making | Conflicts with the requirement to preserve human judgement and is unnecessary for the proposed MVP. |

These exclusions are intentional scope decisions rather than missing functionality.

---

# 9. In-Scope

The MVP includes the following capability areas.

## 9.1 Case Review

- consolidated case information;
- one-view case summary;
- concise explanation of relevant case information;
- highlighted key indicators;
- relevant information retained throughout the case.

## 9.2 Investigation Actions

- dismiss case;
- escalate case;
- request or indicate need for further follow-up;
- analyst remains responsible for the final decision.

## 9.3 Decision Recording

- analyst decision recorded;
- decision reasoning captured;
- subsequent action captured;
- consistent record structure.

## 9.4 Traceability

- chronological case history;
- preservation of historical records;
- association between decision, reasoning and subsequent action;
- authorised access to relevant case information.

## 9.5 Quality Attributes

- usable investigation workflow;
- suitable case-page performance;
- integrity protection for historical records;
- role-appropriate access restrictions.

## 9.6 Supporting Enhancements

Subject to available implementation capacity:

- advanced alert filtering;
- dedicated manager/reviewer view.

---

# 10. Out-of-Scope

## 10.1 Transaction Detection

The MVP will not implement a production transaction-monitoring engine responsible for detecting suspicious transactions.

Cases enter the MVP **already flagged**.

## 10.2 Production TNG Integration

The MVP will not connect directly to TNG Digital production infrastructure, databases or compliance systems.

## 10.3 Real Customer Data

The MVP will not require real TNG Digital customer, transaction or investigation records.

Representative or synthetic case information will be used where data is required.

## 10.4 Autonomous Compliance Decisions

The MVP will not independently determine the final compliance outcome.

The analyst remains responsible for the final decision.

---

# 11. Scope Traceability

| MVP Capability | Source Requirement | User Need |
| --- | --- | --- |
| Consolidated case view | FR-01 | UN-01 |
| Case summary | FR-02 | UN-01 |
| Highlight risk indicators | FR-03 | UN-01 |
| Dismiss / escalate / further review | FR-04 | UN-01 |
| Human final decision | FR-05 / NFR-02 | UN-01 |
| Capture decision reasoning | FR-06 | UN-02 |
| Capture subsequent action | FR-07 | UN-02 |
| Consistent record structure | FR-08 / NFR-04 | UN-02 |
| Chronological case history | FR-09 | UN-03 |
| Reasoning linked to decision | FR-10 | UN-03 |
| Action linked to decision | FR-11 | UN-03 |
| Authorised case-history access | FR-12 / NFR-08 | UN-03 |
| Accurate case information | NFR-01 | UN-01 |
| Investigation performance | NFR-03 | UN-01 |
| Recording usability | NFR-05 | UN-02 |
| Auditability | NFR-06 | UN-03 |
| Record integrity | NFR-07 | UN-03 |

---

# 12. MVP Validation Criteria

The MVP should demonstrate that the defined workflow can support the following outcomes.

| Validation Area | MVP Demonstration |
| --- | --- |
| **Investigation efficiency** | Analyst can review relevant case information without navigating multiple simulated sources. |
| **Information comprehension** | Analyst can identify the important information and indicators associated with the case. |
| **Human oversight** | No final compliance outcome is produced without an analyst decision. |
| **Decision documentation** | Analyst reasoning and resulting actions are recorded as part of the case. |
| **Traceability** | An authorised reviewer can reconstruct the relevant sequence of case events and decisions. |
| **Integrity** | Historical information is preserved rather than silently overwritten. |
| **Access control** | Restricted case information is only available through authorised roles. |

These criteria demonstrate the MVP concept. They do not establish production-level effectiveness or regulatory compliance.
