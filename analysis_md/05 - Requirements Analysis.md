# 05 \- Requirements Analysis

## 1. Purpose

This analysis translates the identified stakeholder and user needs into initial **functional requirements** and **non-functional requirements**.

Functional requirements define **what the system must support**.

Non-functional requirements define the **quality attributes and constraints under which those functions must operate**.

The requirements remain solution-neutral where possible and are traceable to the user needs established in the preceding analysis.

---

## 2. Requirements Traceability

| Opportunity | User Need | Requirement Area |
| --- | --- | --- |
| OP-01 | UN-01 — Efficient Investigation Review | Case information, summarisation, risk indicators, investigation actions and human decision control |
| OP-02 | UN-02 — Efficient Decision Recording | Decision reasoning, follow-up actions and structured recording |
| OP-02 | UN-03 — Case Traceability | Chronological history, decision traceability and authorised review |

---

# 3. Functional Requirements

## 3.1 UN-01 — Efficient Investigation Review

| ID | Functional Requirement | Rationale |
| --- | --- | --- |
| **FR-01** | The system shall present relevant information associated with a flagged case in a consolidated case view. | Support efficient review of case information. |
| **FR-02** | The system shall provide a concise summary of key case information. | Reduce effort required to understand the overall case. |
| **FR-03** | The system shall highlight relevant risk indicators associated with the case. | Direct analyst attention to information requiring consideration. |
| **FR-04** | The system shall allow the analyst to perform relevant case actions, including dismissing, escalating or requesting further review. | Support progression of the investigation. |
| **FR-05** | The system shall require an authorised human analyst to make the final compliance decision. | Preserve human judgement and oversight. |

---

## 3.2 UN-02 — Efficient Decision Recording

| ID | Functional Requirement | Rationale |
| --- | --- | --- |
| **FR-06** | The system shall capture the analyst's reasoning associated with the final case decision. | Preserve the justification for the decision. |
| **FR-07** | The system shall capture subsequent actions associated with the case decision. | Connect the decision with resulting actions. |
| **FR-08** | The system shall organise required decision information using a consistent record structure. | Reduce reliance on analysts manually structuring case documentation. |

---

## 3.3 UN-03 — Case Traceability

| ID | Functional Requirement | Rationale |
| --- | --- | --- |
| **FR-09** | The system shall maintain a chronological record of relevant case events and decisions. | Enable reconstruction of the case lifecycle. |
| **FR-10** | The system shall associate decision reasoning with the corresponding case decision. | Preserve the relationship between reasoning and outcome. |
| **FR-11** | The system shall associate subsequent actions with the relevant case decision. | Maintain end-to-end traceability. |
| **FR-12** | The system shall allow authorised reviewers to retrieve and review the case history. | Support management, review and audit activities. |

---

# 4. Non-Functional Requirements

## 4.1 Accuracy

**NFR-01 — Information Accuracy**

Information presented in the case view and any generated summary must accurately reflect the available underlying case information.

The system should not introduce unsupported information into the investigation record.

---

## 4.2 Human Oversight

**NFR-02 — Human Decision Authority**

The final compliance decision must remain under the control of an authorised human analyst.

System-generated information may support the investigation but must not replace final human judgement.

---

## 4.3 Performance

**NFR-03 — Investigation Performance**

Case information and summaries should load within a timeframe suitable for an operational investigation workflow.

A quantitative response-time threshold remains to be established through stakeholder or prototype validation.

---

## 4.4 Consistency

**NFR-04 — Record Consistency**

Compliance case records should follow a consistent structure for equivalent types of information and actions.

---

## 4.5 Usability

**NFR-05 — Recording Usability**

Recording decision reasoning and subsequent actions should require minimal unnecessary manual effort while still capturing required information.

---

## 4.6 Auditability

**NFR-06 — Case Auditability**

The case history must provide sufficient information for an authorised reviewer to trace relevant events, reasoning, decisions and subsequent actions.

---

## 4.7 Integrity

**NFR-07 — Record Integrity**

Historical case information must be protected against unauthorised or untraceable alteration.

Changes to information forming part of the case history should not silently overwrite the historical record.

---

## 4.8 Authorisation

**NFR-08 — Access Control**

Case information and case histories must only be accessible to appropriately authorised users according to their permitted responsibilities.

---

# 5. Requirements Traceability Matrix

| Req. ID | Type | User Need | Opportunity | Requirement |
| --- | --- | --- | --- | --- |
| FR-01 | Functional | UN-01 | OP-01 | Consolidated case information |
| FR-02 | Functional | UN-01 | OP-01 | Concise case summary |
| FR-03 | Functional | UN-01 | OP-01 | Highlight risk indicators |
| FR-04 | Functional | UN-01 | OP-01 | Support investigation actions |
| FR-05 | Functional | UN-01 | OP-01 | Human final decision |
| FR-06 | Functional | UN-02 | OP-02 | Capture decision reasoning |
| FR-07 | Functional | UN-02 | OP-02 | Capture subsequent actions |
| FR-08 | Functional | UN-02 | OP-02 | Consistent record structure |
| FR-09 | Functional | UN-03 | OP-02 | Chronological case history |
| FR-10 | Functional | UN-03 | OP-02 | Link reasoning to decision |
| FR-11 | Functional | UN-03 | OP-02 | Link actions to decision |
| FR-12 | Functional | UN-03 | OP-02 | Authorised case-history review |
| NFR-01 | Non-Functional | UN-01 | OP-01 | Accuracy |
| NFR-02 | Non-Functional | UN-01 | OP-01 | Human oversight |
| NFR-03 | Non-Functional | UN-01 | OP-01 | Performance |
| NFR-04 | Non-Functional | UN-02 | OP-02 | Consistency |
| NFR-05 | Non-Functional | UN-02 | OP-02 | Usability |
| NFR-06 | Non-Functional | UN-03 | OP-02 | Auditability |
| NFR-07 | Non-Functional | UN-03 | OP-02 | Integrity |
| NFR-08 | Non-Functional | UN-03 | OP-02 | Authorisation |

---

# 6. Requirement Boundaries

The requirements establish the following boundaries for subsequent solution design:

**System responsibility**

> Consolidate information → summarise relevant information → highlight indicators → support investigation actions → structure records → maintain traceability

**Human responsibility**

> Review evidence → interpret information → apply professional judgement → determine final compliance decision

No requirement establishes a need for fully autonomous compliance decision-making.

---

# 7. Outstanding Requirement Validation

| Area | Current Limitation | Required Validation |
| --- | --- | --- |
| Case information | Exact information required by analysts is not established. | Analyst interview / process analysis |
| Summary | Required content and acceptable accuracy threshold are not established. | Prototype testing / stakeholder review |
| Risk indicators | Exact indicators and presentation rules are not established. | Compliance SME validation |
| Performance | No quantitative response-time target is established. | User testing / operational requirement |
| Record structure | Required fields are not fully established. | Compliance/process review |
| Audit history | Exact retention and history requirements require detailed regulatory/internal analysis. | Regulatory and internal policy analysis |
| Access control | Specific roles and permissions are not established. | Role/access analysis |
