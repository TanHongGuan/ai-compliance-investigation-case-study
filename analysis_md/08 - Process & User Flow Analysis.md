# 08 \- Process & User Flow Analysis

## **0. SwimLane Diagram**

## 1. Purpose

This stage defines the end-to-end process for the MVP's post-alert compliance investigation workflow.

The process shows how a pre-flagged case moves between the **Transaction Monitoring System, Compliance Analyst, Compliance Investigation System, and Compliance Manager / Reviewer**, while preserving human decision-making and maintaining a traceable case history.

The swimlane diagram serves as the primary process artefact.

---

## 2. Process Scope

| Boundary | Definition |
| --- | --- |
| **Start** | A flagged case is assigned by the Transaction Monitoring System. |
| **End — Dismiss** | The analyst dismisses the case and the case is closed after the decision and audit information are recorded. |
| **End — Escalate** | The analyst escalates the case and it is sent to the Compliance Manager / Reviewer for further review. |

### Out of Process Scope

The process does not include:

- detection of suspicious transactions;
- generation of transaction-monitoring alerts;
- production TNG Digital system integration;
- fully automated compliance decision-making.

The workflow begins only after a case has already been flagged.

---

# 3. Actors and Responsibilities

| Actor / System | Responsibility |
| --- | --- |
| **Transaction Monitoring System** | Assigns an already-flagged case for investigation. |
| **Compliance Analyst** | Reviews the case, determines whether sufficient information is available, evaluates the case, makes the final analyst decision and records the decision rationale. |
| **Compliance Investigation System** | Retrieves and presents case information, supports additional information gathering, records decision details and maintains the audit trail. |
| **Compliance Manager / Reviewer** | Receives and reviews cases escalated by the Compliance Analyst. |

---

# 4. Main Process Flow

### Step 1 — Case Assignment

The Transaction Monitoring System assigns a flagged case for investigation.

### Step 2 — Open Case

The Compliance Analyst opens the assigned case.

### Step 3 — Retrieve Case Information

The Compliance Investigation System retrieves the relevant case information.

### Step 4 — Present Case Information

The system presents the case summary, supporting evidence and relevant risk indicators to the analyst.

### Step 5 — Review Case

The analyst reviews the available case information and determines whether sufficient information is available to make a decision.

### Step 6 — Obtain Additional Information

If the available information is insufficient, the analyst requests further information.

The system retrieves or adds the additional information and updates the case. The analyst then reviews the updated case.

This cycle continues until sufficient information is available to proceed.

### Step 7 — Evaluate Case Outcome

Once sufficient information is available, the analyst evaluates the case and determines the appropriate outcome.

### Step 8 — Record Decision Rationale

The analyst records the reasoning supporting the decision.

### Step 9 — Record Case Decision

The system records the relevant decision information, including the decision reasoning, supporting evidence, responsible analyst and timestamp.

### Step 10 — Update Audit Trail

The system updates the chronological case history to preserve the investigation and decision record.

### Step 11 — Apply Decision Outcome

The workflow branches according to the analyst's decision:

**Dismiss**  
→ The case is closed.

**Escalate**  
→ The case is sent to the Compliance Manager / Reviewer for further review.

---

# 5. Decision Points

## 5.1 Sufficient Information?

**Decision:** Is sufficient information available to make a case decision?

| Outcome | Process |
| --- | --- |
| **Yes** | Proceed to case evaluation. |
| **No** | Request further information, update the case and return to case review. |

This decision creates an iterative investigation loop where additional information can be obtained before the analyst makes a final decision.

---

## 5.2 Decision Outcome

**Decision:** What action should be taken following the analyst's assessment?

| Outcome | Process |
| --- | --- |
| **Dismiss** | Record the decision and close the case. |
| **Escalate** | Record the decision and send the case for further review. |

The system supports the decision process but does not independently determine the final outcome.

---

# 6. Alternate Flow — Additional Information Required

The primary alternate flow occurs when the analyst determines that the available information is insufficient.

**Flow:**

> Review Case  
> → Information Insufficient  
> → Request Further Information  
> → Retrieve / Add Information  
> → Update Case  
> → Review Updated Case  
> → Reassess Information Sufficiency

The case does not proceed to a final analyst decision until sufficient information is available for the analyst to make an assessment.

---

# 7. Process Controls

| Control | Application |
| --- | --- |
| **Human Decision Authority** | The Compliance Analyst retains responsibility for the final analyst decision. |
| **Decision Rationale** | The reasoning supporting the decision is recorded. |
| **Evidence Traceability** | Relevant evidence is associated with the case and decision record. |
| **User Attribution** | The responsible analyst is associated with the recorded decision. |
| **Timestamping** | Relevant decision events are timestamped. |
| **Audit History** | Case events and decisions are preserved chronologically. |
| **Escalation Control** | Escalated cases are routed to the appropriate reviewer. |
| **Access Control** | Case information is restricted to authorised users. |
| **Record Integrity** | Historical case information is preserved against untraceable alteration. |

---

# 8. Requirements Traceability

| Process Activity | Related Requirement |
| --- | --- |
| Retrieve and display case information | FR-01 — Consolidated case view |
| Display case summary | FR-02 — Concise case summary |
| Display risk indicators | FR-03 — Highlight relevant risk indicators |
| Request further information | FR-04 — Investigation actions |
| Analyst determines outcome | FR-05 / NFR-02 — Human final decision |
| Record decision rationale | FR-06 — Capture decision reasoning |
| Record resulting action | FR-07 — Capture subsequent action |
| Structure case record | FR-08 / NFR-04 — Consistent record structure |
| Update chronological history | FR-09 — Chronological case history |
| Associate reasoning with decision | FR-10 — Decision traceability |
| Associate action with decision | FR-11 — Action traceability |
| Reviewer accesses escalated case | FR-12 / NFR-08 — Authorised review |
| Preserve historical information | NFR-06 / NFR-07 — Auditability and integrity |

---

# 9. Process Outcome

The defined process establishes an end-to-end post-alert investigation workflow in which the **Compliance Investigation System supports information retrieval, case presentation, investigation activities and traceability**, while the **Compliance Analyst retains responsibility for reviewing the evidence and determining the final analyst decision**.

The workflow produces two primary outcomes:

> **Dismissed Case** — decision and reasoning are recorded, the audit history is updated, and the case is closed.

> **Escalated Case** — decision and reasoning are recorded, the audit history is updated, and the case is routed to the Compliance Manager / Reviewer for further review.
