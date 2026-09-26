# 10 \- Product Backlog & Acceptance Criteria

# 10 — Product Backlog & Acceptance Criteria

## 1. Purpose

This stage converts the **Release 1 — MVP items from the User Story Map** into formal, implementation-ready user stories.

Each backlog item defines:

- the user performing the action;
- the capability required;
- the value provided;
- its priority; and
- testable acceptance criteria.

The backlog also establishes the handoff from **business analysis into development and QA**, allowing each requirement to be implemented and subsequently verified.

---

## 2. User Story Format

User stories follow the structure:

> **As a** \[user\],  
> **I want to** \[capability/action\],  
> **so that** \[value/outcome\].

Acceptance criteria use **Given–When–Then**:

> **Given** \[precondition/context\],  
> **When** \[action/event\],  
> **Then** \[expected system behaviour\].

---

# 3. MVP Product Backlog

## US-01 — Open Flagged Case

**Priority:** Must Have  
**Traceability:** FR-01

> **As a** Compliance Analyst,  
> **I want to** open a flagged case assigned to me,  
> **so that** I can begin reviewing the case for investigation.

### Acceptance Criteria

**AC-01**

> **Given** a flagged case has been assigned to the analyst,  
> **When** the analyst opens the case,  
> **Then** the system displays the available case information.

**AC-02**

> **Given** the analyst is not authorised to access a case,  
> **When** the analyst attempts to open it,  
> **Then** access is denied.

---

## US-02 — View Case Information

**Priority:** Must Have  
**Traceability:** FR-01

> **As a** Compliance Analyst,  
> **I want to** view relevant case and transaction information in one place,  
> **so that** I can review the case without unnecessarily navigating between multiple sources.

### Acceptance Criteria

**AC-01**

> **Given** an analyst has opened a case,  
> **When** the case view loads,  
> **Then** the system displays the available information relevant to the investigation.

**AC-02**

> **Given** some expected case information is unavailable,  
> **When** the case is displayed,  
> **Then** the unavailable information is clearly indicated rather than presenting unsupported information.

---

## US-03 — View AI-Assisted Case Summary

**Priority:** Must Have  
**Traceability:** FR-02, NFR-01, NFR-02

> **As a** Compliance Analyst,  
> **I want to** view an AI-assisted summary of the case,  
> **so that** I can quickly understand the key information before conducting my detailed review.

### Acceptance Criteria

**AC-01**

> **Given** case information is available,  
> **When** the analyst opens the case summary,  
> **Then** the system presents a concise summary based on the available case information.

**AC-02**

> **Given** information required for the summary is unavailable,  
> **When** the summary is generated,  
> **Then** the system does not fabricate or present the unavailable information as fact.

**AC-03**

> **Given** an AI-assisted summary has been generated,  
> **When** it is presented to the analyst,  
> **Then** it is identifiable as AI-generated supporting information and does not represent a final compliance decision.

---

## US-04 — Review Supporting Evidence

**Priority:** Must Have  
**Traceability:** FR-01

> **As a** Compliance Analyst,  
> **I want to** review the evidence associated with a flagged case,  
> **so that** I can assess the case using the available supporting information.

### Acceptance Criteria

**AC-01**

> **Given** supporting evidence exists for a case,  
> **When** the analyst reviews the case,  
> **Then** the system makes the relevant evidence available for review.

**AC-02**

> **Given** an evidence item is associated with the case,  
> **When** it is displayed,  
> **Then** the system maintains its association with the corresponding case.

---

## US-05 — View Risk Indicators

**Priority:** Should Have  
**Traceability:** FR-03

> **As a** Compliance Analyst,  
> **I want to** see relevant risk indicators highlighted,  
> **so that** I can identify information requiring closer investigation.

### Acceptance Criteria

**AC-01**

> **Given** relevant risk indicators have been identified,  
> **When** the analyst reviews the case,  
> **Then** the system clearly distinguishes those indicators from general case information.

**AC-02**

> **Given** no supported risk indicator is available,  
> **When** the case is displayed,  
> **Then** the system does not create unsupported risk indicators.

---

## US-06 — Identify Information Sufficiency

**Priority:** Must Have  
**Traceability:** FR-04

> **As a** Compliance Analyst,  
> **I want to** determine whether sufficient information is available,  
> **so that** I can either continue the investigation or request additional information.

### Acceptance Criteria

**AC-01**

> **Given** the analyst has reviewed the available case information,  
> **When** the analyst determines that additional information is required,  
> **Then** the system allows the analyst to proceed with an information request.

**AC-02**

> **Given** the analyst determines that sufficient information is available,  
> **When** the investigation continues,  
> **Then** the analyst can proceed to evaluate the case outcome.

---

## US-07 — Request Additional Information

**Priority:** Must Have  
**Traceability:** FR-04

> **As a** Compliance Analyst,  
> **I want to** request additional information for an incomplete investigation,  
> **so that** I can obtain the information required to continue reviewing the case.

### Acceptance Criteria

**AC-01**

> **Given** additional information is required,  
> **When** the analyst submits an information request,  
> **Then** the request is associated with the relevant case.

**AC-02**

> **Given** additional information becomes available,  
> **When** it is added to the case,  
> **Then** the case is updated without removing the existing investigation information.

---

## US-08 — Review Updated Case

**Priority:** Must Have  
**Traceability:** FR-04

> **As a** Compliance Analyst,  
> **I want to** review newly added case information,  
> **so that** I can reassess whether sufficient information exists to make a decision.

### Acceptance Criteria

**AC-01**

> **Given** additional information has been added,  
> **When** the analyst reopens or refreshes the case,  
> **Then** the updated information is available for review.

**AC-02**

> **Given** the analyst has reviewed the updated information,  
> **When** the review is completed,  
> **Then** the analyst can reassess information sufficiency.

---

## US-09 — Determine Case Outcome

**Priority:** Must Have  
**Traceability:** FR-04, FR-05, NFR-02

> **As a** Compliance Analyst,  
> **I want to** dismiss or escalate a reviewed case,  
> **so that** the investigation can proceed according to my assessment.

### Acceptance Criteria

**AC-01**

> **Given** the analyst has completed the required case review,  
> **When** the analyst determines the case outcome,  
> **Then** the system allows the analyst to select an available case action.

**AC-02**

> **Given** a final analyst decision is required,  
> **When** the system provides supporting information or AI assistance,  
> **Then** the system does not independently make or submit the final compliance decision.

---

## US-10 — Record Decision Rationale

**Priority:** Must Have  
**Traceability:** FR-06, FR-08

> **As a** Compliance Analyst,  
> **I want to** record the reasoning behind my case decision,  
> **so that** the basis for the decision can be understood during subsequent review.

### Acceptance Criteria

**AC-01**

> **Given** the analyst selects a case outcome,  
> **When** the decision is submitted,  
> **Then** the system records the associated decision rationale.

**AC-02**

> **Given** decision rationale is required,  
> **When** the analyst attempts to complete the decision without providing it,  
> **Then** the system prevents completion and identifies the missing required information.

---

## US-11 — Maintain Case Audit History

**Priority:** Must Have  
**Traceability:** FR-07–FR-11, NFR-06, NFR-07

> **As an** authorised reviewer,  
> **I want to** view a chronological history of the case,  
> **so that** I can trace the evidence, reasoning, decisions and subsequent actions associated with the investigation.

### Acceptance Criteria

**AC-01**

> **Given** a relevant case event occurs,  
> **When** the event is recorded,  
> **Then** the audit history records the event with its associated user and timestamp.

**AC-02**

> **Given** a decision has been made,  
> **When** the audit history is reviewed,  
> **Then** the decision can be associated with its recorded rationale and subsequent action.

**AC-03**

> **Given** historical case information has already been recorded,  
> **When** subsequent case activity occurs,  
> **Then** the existing history is preserved without silent overwrite.

---

## US-12 — Escalate Case for Review

**Priority:** Must Have  
**Traceability:** FR-07, FR-12

> **As a** Compliance Analyst,  
> **I want to** route an escalated case to an authorised reviewer,  
> **so that** cases requiring further assessment can continue through the appropriate review process.

### Acceptance Criteria

**AC-01**

> **Given** the analyst selects an escalation outcome and records the required rationale,  
> **When** the escalation is submitted,  
> **Then** the case is marked as escalated and made available for authorised review.

**AC-02**

> **Given** a case has been escalated,  
> **When** an authorised reviewer accesses it,  
> **Then** the reviewer can access the relevant case history and recorded decision information.

---

## US-13 — Close Dismissed Case

**Priority:** Must Have  
**Traceability:** FR-07

> **As a** Compliance Analyst,  
> **I want to** close a dismissed case,  
> **so that** completed investigations are clearly identified and retained as part of the case history.

### Acceptance Criteria

**AC-01**

> **Given** the analyst selects a dismissal outcome and provides the required rationale,  
> **When** the decision is submitted,  
> **Then** the system records the decision and closes the case.

**AC-02**

> **Given** a case has been closed,  
> **When** an authorised user reviews its history,  
> **Then** the recorded decision, rationale, relevant evidence and case events remain retrievable.

---

# 4. Backlog Summary

| ID | Backlog Item | Priority |
| --- | --- | --- |
| US-01 | Open Flagged Case | Must |
| US-02 | View Case Information | Must |
| US-03 | View AI-Assisted Case Summary | Must |
| US-04 | Review Supporting Evidence | Must |
| US-05 | View Risk Indicators | Should |
| US-06 | Identify Information Sufficiency | Must |
| US-07 | Request Additional Information | Must |
| US-08 | Review Updated Case | Must |
| US-09 | Determine Case Outcome | Must |
| US-10 | Record Decision Rationale | Must |
| US-11 | Maintain Case Audit History | Must |
| US-12 | Escalate Case for Review | Must |
| US-13 | Close Dismissed Case | Must |
