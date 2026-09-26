# 09 \- User Story Mapping

## 1. Purpose

The user story map translates the post-alert compliance investigation process into a structured view of **user activities, user tasks, and planned releases**.

The primary persona is the **Compliance Analyst**, as the analyst performs the main investigation workflow and retains responsibility for the final compliance decision.

The story map is used to:

- organise functionality around the analyst's workflow;
- identify the minimum capabilities required for an end-to-end MVP;
- separate essential functionality from later improvements; and
- provide the basis for the product backlog and acceptance criteria.

---

## 2. User Story Map

**Primary Persona:** Compliance Analyst

**Workflow:**

**Access Case → Review Case → Gather Information → Make Decision → Document Decision → Complete / Escalate Case**

The story map decomposes this workflow into individual tasks such as opening a flagged case, reviewing case information and supporting evidence, identifying missing information, determining a case outcome, recording decision rationale, maintaining an audit trail, and closing or escalating the case.

**Primary Artefact:** *User Story Map — Compliance Investigation Workflow*
[https://miro.com/app/board/uXjVHpo0XT4=/?moveToWidgets=AQBUo\_Lzg\_iEgIAwAQEBAQEBAQEBAQEBAQEBAgEBAQEBAQEBAQEBAQEBAQEBAQEBAQESAQEBAQEBAQEBAQEBAQEBAZ-bsxD006MCfNiG3BKP67MGm9ADlKME6usD4wF\_ktCMFQEBAQEBAQEBAQEBAQEBg-h5TIMB](https://miro.com/app/board/uXjVHpo0XT4=/?moveToWidgets=AQBUo_Lzg_iEgIAwAQEBAQEBAQEBAQEBAQEBAgEBAQEBAQEBAQEBAQEBAQEBAQEBAQESAQEBAQEBAQEBAQEBAQEBAZ-bsxD006MCfNiG3BKP67MGm9ADlKME6usD4wF_ktCMFQEBAQEBAQEBAQEBAQEBg-h5TIMB)

---

## 3. Release Strategy

The user stories are organised into three incremental releases.

| Release | Objective | Focus |
| --- | --- | --- |
| **Release 1 — MVP** | Enable the analyst to complete the end-to-end investigation workflow. | Case access, basic AI-assisted summary, evidence review, risk indicators, additional information, human decision-making, rationale recording, audit trail and case completion/escalation. |
| **Release 2 — Improve Workflow** | Make the investigation process easier, faster and clearer. | Customised information display, evidence comparison, indicator explanations, information checklists, request tracking and structured rationale templates. |
| **Release 3 — Advanced / Intelligent Features** | Introduce more advanced intelligence and automation. | Context-aware summaries, AI-generated investigation summaries, evidence relationship identification, AI-assisted risk assessment, missing-information suggestions and AI-drafted rationale. |

---

## 4. Release 1 — MVP

Release 1 represents the **minimum end-to-end workflow** required to demonstrate the proposed solution.

The analyst can:

- open and review a flagged case;
- view a basic AI-assisted case summary;
- understand why the case was flagged;
- review consolidated supporting evidence and risk indicators;
- determine whether sufficient information is available;
- request and review additional information where necessary;
- decide whether to dismiss or escalate the case;
- record the decision rationale;
- preserve relevant evidence, decision details, analyst attribution and timestamps;
- maintain a chronological audit trail; and
- close a dismissed case or route an escalated case for further review.

The final compliance decision remains under **human analyst control**. AI-generated information is used to support investigation and does not independently determine the case outcome.

---

## 5. Future Releases

**Release 2** focuses on improving the usability and efficiency of the core workflow without changing its fundamental process. These improvements include clearer information presentation, evidence comparison, explanations, tracking of outstanding information requests and structured documentation support.

**Release 3** introduces more advanced AI-assisted capabilities. These features extend the MVP through contextual analysis, evidence relationships, risk-assessment support, identification of potentially missing information and drafting assistance. Analyst review and decision authority remain part of the workflow.

---

## 6. Outcome

The user story map establishes the relationship between the **compliance analyst's workflow and the planned product releases**.

Release 1 defines the functional boundary of the MVP, while Releases 2 and 3 establish a controlled path for future workflow improvements and intelligent capabilities.

The Release 1 stories will be carried forward into **10 — Product Backlog & Acceptance Criteria**, where they will be converted into formal user stories with priorities, requirement traceability and testable acceptance criteria.
