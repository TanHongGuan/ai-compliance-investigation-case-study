# 03 \- Opportunity Analysis

# 1. Opportunity Overview

## 1.1 Input Problems

| Pain Point | Refined Problem | Evidence | Validation |
| --- | --- | --- | --- |
| **PP-01** | Human-led transaction-monitoring investigations require multi-source evidence gathering, analysis and documentation; the magnitude of the efficiency/scalability impact remains unquantified. | **4/5** | Partially Validated |
| **PP-02** | Compliance investigations carry a material requirement for evidence and decision traceability, but deficiencies in TNG Digital's existing process are not established. | **3/5** | Partially Validated |
| **PP-03** | Transaction exceptions create a need for understandable status and next-step information, but an unmet transparency problem has not been established. | **3/5** | Partially Validated |

## 1.2 Initial Opportunities

| ID | Source | Initial Opportunity |
| --- | --- | --- |
| **OP-01** | PP-01 | Reduce repetitive information-gathering and analysis effort while preserving analyst judgement, accuracy and regulatory oversight. |
| **OP-02** | PP-02 | Make compliance-case evidence, reasoning, decisions and actions consistently traceable while minimising analyst documentation burden. |
| **OP-03** | PP-03 | Help users understand exceptional transaction states and appropriate next actions without unnecessary technical complexity. |

All three are appropriately outcome-oriented rather than feature-oriented, consistent with the protocol's opportunity-quality criteria. 03\_opportunity\_statement\_analys…

# 2. OP-01 — Compliance Investigation Efficiency

## 2.1 Source Problem

**Pain Point:** PP-01  
**Evidence Strength:** 4/5  
**Validation Result:** Partially Validated

**Refined Problem**

> TNG Digital's transaction-monitoring investigations require analysts to review alerts, gather information from multiple internal and external sources, analyse customer activity and document case justifications. The magnitude of the resulting workload and scalability impact remains unquantified.

Current TNG Digital role descriptions continue to support this underlying process: analysts review system-generated alerts, analyse customer activity, gather evidence from internal systems, public searches, commercial databases and other stakeholders, and prepare narratives and justifications. [LinkedIn](https://my.linkedin.com/jobs/view/associate-transaction-monitoring-1-year-contract-tng-digital-at-touch-n-go-group-4056257753?utm_source=chatgpt.com)

## 2.2 Initial Opportunity Statement

> **How might we reduce repetitive information-gathering and analysis effort during flagged-transaction investigations while preserving analyst judgement, accuracy and regulatory oversight?**

## 2.3 Problem-to-Opportunity Logic

Because analysts perform several human-led information-gathering, analysis and documentation activities during investigations, reducing avoidable repetitive effort could improve investigation efficiency.

TNG Digital also explicitly refers to turnaround-time requirements, false-positive reduction and improving AML/CFT system efficiency. [LinkedIn](https://www.linkedin.com/jobs/view/3936676641/?utm_source=chatgpt.com)

The opportunity should **not**, however, be interpreted as evidence that the current process is excessively slow or overloaded.

## 2.4 Primary and Secondary Stakeholders

**Primary:** Compliance / transaction-monitoring analysts.

**Secondary:** Compliance managers and reviewers, because they review escalated cases and rely on investigation quality.

BNM/regulators are indirect stakeholders where investigation outcomes lead to regulatory reporting.

## 2.5 Desired Outcome

Reduce avoidable investigation effort while maintaining:

- investigation quality;
- analyst judgement;
- accuracy;
- appropriate escalation;
- regulatory oversight.

## 2.6 Potential Value

**Stakeholder Value:** Analysts could spend less effort on repetitive investigation activities.

**Business Value:** Potentially improves investigation efficiency and scalability. TNG Digital itself identifies timely case handling, false-positive reduction and AML/CFT system efficiency as operational concerns. [LinkedIn](https://www.linkedin.com/jobs/view/3936676641/?utm_source=chatgpt.com)

**Compliance / Regulatory Value:** Efficiency cannot come at the expense of risk-based assessment, accurate escalation or STR obligations.

**Challenge Alignment: 5/5 — Directly central.** It directly addresses the challenge's regulatory-compliance automation dimension.

## 2.7 Opportunity Value Assessment

**Value: 4/5 — High**

There is a clear relationship between the documented investigation workflow and potential efficiency improvement. A 5/5 is not justified because public evidence does not quantify current investigation workload, processing time or cost.

## 2.8 Assumptions

| Assumption | Evidence | Impact if False |
| --- | --- | --- |
| Analysts spend meaningful effort gathering and analysing information | Partial | High |
| Some of this effort can be reduced | Partial | High |
| Relevant information can be made easier to process | Partial | Medium |
| Efficiency can improve without weakening judgement | Not yet demonstrated | High |
| Investigation quality can be preserved | Required condition | High |

## 2.9 Constraints to Preserve

**Human:** Analyst judgement and appropriate human review.

**Regulatory:** AML/CFT obligations, appropriate investigation and escalation, record keeping and STR processes. BNM requires reporting institutions to maintain AML/CFT programmes and records. [Bank Negara Malaysia AML/CFT](https://amlcft.bnm.gov.my/are-you-a-reporting-institution?utm_source=chatgpt.com)

**Security:** Confidentiality of customer and investigation information.

**Business:** Existing investigation controls and operational continuity.

**Technical:** No assumed access to TNG Digital production systems.

## 2.10 Dependencies

| Dependency | Type | Importance |
| --- | --- | --- |
| Transaction/case information | Data | High |
| Existing monitoring process | Internal | High |
| AML/CFT policies | Regulatory | High |
| Analyst workflow knowledge | Stakeholder | High |
| Existing systems/integrations | Technical | Medium |

## 2.11 Feasibility Assessment

| Dimension | Score | Rationale |
| --- | --- | --- |
| Data | **3/5** | Real investigation data is sensitive/unavailable, but representative synthetic cases could support prototyping. |
| Technical | **4/5** | The improvement outcome can reasonably be explored without requiring production deployment. |
| Access | **3/5** | Internal systems and analysts are not guaranteed to be accessible; simulation can reduce this limitation. |
| Skills | **4/5** | A scoped prototype is achievable without reproducing the full AML platform. |
| Time / Scope | **4/5** | The opportunity can be bounded to post-alert investigation rather than AML detection as a whole. |

**Overall Feasibility: 4/5 — High, with constraints**

**Critical Blocker:** No blocker to demonstrating the opportunity at prototype level. Production validation would require real workflow/data access.

## 2.12 Key Risks / Uncertainties

- Actual analyst time distribution is unknown.
- Existing systems may already automate some assumed repetitive activities.
- Efficiency improvements could negatively affect investigation quality if human oversight is weakened.
- Synthetic cases may not fully represent production complexity.

## 2.13 Refined Opportunity Statement

No material revision is required:

> **How might we reduce repetitive information-gathering and analysis effort during flagged-transaction investigations while preserving analyst judgement, accuracy and regulatory oversight?**

## 2.14 Opportunity Decision

**Progress with Conditions**

The opportunity is well aligned with documented TNG processes and the challenge and is feasible to explore. However, the scale of the current efficiency problem remains unquantified.

**Carry forward:** preserve human judgement and validate assumptions about where investigation effort is actually spent.

---

# 3. OP-02 — Compliance Case Traceability

## 3.1 Source Problem

**Pain Point:** PP-02  
**Evidence Strength:** 3/5  
**Validation:** Partially Validated

TNG Digital's current FCC role descriptions refer to investigation quality, escalation, case handling, documentation and clear audit trails in related financial-crime activities. [LinkedIn](https://www.linkedin.com/jobs/view/4441429839/?utm_source=chatgpt.com)

BNM requires relevant records to be retained and available to supervisory or competent authorities, while internally generated STRs and supporting documents are subject to at least six years' retention. [Bank Negara Malaysia AML/CFT](https://amlcft.bnm.gov.my/faq/tfs-fi/record-keeping?utm_source=chatgpt.com)

## 3.2 Initial Opportunity Statement

> **How might we make compliance-case evidence, reasoning, decisions and subsequent actions consistently traceable while minimising additional documentation burden on analysts?**

## 3.3 Problem-to-Opportunity Logic

Traceability is materially relevant to the compliance process because investigation evidence, decisions, escalation and regulatory reporting must be documented and retained.

However, the research has **not established that TNG Digital's existing case records are currently fragmented or inadequate**.

Therefore this opportunity is better framed around strengthening/maintaining traceability efficiently, rather than "fixing" an assumed broken audit trail.

## 3.4 Stakeholders

**Primary:** Compliance analysts.

**Secondary:** Compliance reviewers/managers, internal assurance functions and relevant supervisory authorities.

## 3.5 Desired Outcome

Maintain complete, retrievable and understandable case histories without imposing unnecessary documentation effort.

## 3.6 Potential Value

**Stakeholder Value:** Potentially reduces the effort involved in maintaining/reconstructing case documentation.

**Business Value:** Supports consistent case management and internal review.

**Compliance / Regulatory Value:** High. BNM requires reporting institutions to maintain transaction records and relevant AML documentation, and supporting STR documentation must be retained. [Bank Negara Malaysia AML/CFT](https://amlcft.bnm.gov.my/faq/tfs-fi/record-keeping?utm_source=chatgpt.com)

**Challenge Alignment: 5/5 — Directly central** to regulatory compliance and transparency.

## 3.7 Opportunity Value

**4/5 — High**

Traceability has clear regulatory and operational relevance. A 5/5 is not justified because the research has not established a material deficiency in TNG Digital's existing traceability process.

## 3.8 Assumptions

| Assumption | Evidence | Impact if False |
| --- | --- | --- |
| Documentation creates meaningful analyst effort | Partial | Medium |
| Existing traceability could be improved | No direct evidence | High |
| Relevant investigation events can be consistently linked | Partial | High |
| Reduced documentation burden can coexist with adequate records | Not established | High |

## 3.9 Constraints

**Human:** Reasoning must remain attributable to the responsible reviewer.

**Regulatory:** Records must remain complete, retrievable and retained as required.

**Security:** Sensitive case information requires appropriate confidentiality and access controls.

**Business:** Reduced documentation effort cannot result in weaker evidence.

**Technical:** Prototype should not assume access to TNG production case systems.

## 3.10 Dependencies

| Dependency | Type | Importance |
| --- | --- | --- |
| Case lifecycle | Internal | High |
| Evidence records | Data | High |
| Analyst/reviewer actions | Stakeholder | High |
| Record-keeping rules | Regulatory | High |
| Existing case-management capabilities | Technical | High |

## 3.11 Feasibility

| Dimension | Score | Rationale |
| --- | --- | --- |
| Data | **4/5** | Representative case/evidence histories can be simulated. |
| Technical | **4/5** | Traceability concepts are readily prototypeable. |
| Access | **3/5** | Existing TNG case-management capabilities are unknown. |
| Skills | **4/5** | Feasible at prototype scope. |
| Time / Scope | **4/5** | Can be bounded to one compliance-case lifecycle. |

**Overall Feasibility: 4/5**

**Critical Blocker:** None for prototype exploration. Internal access would be required to establish whether the opportunity represents a real improvement over TNG's current system.

## 3.12 Risks / Uncertainties

- Existing TNG systems may already provide strong traceability.
- Additional recording could increase rather than decrease analyst workload.
- Minimising documentation cannot weaken regulatory records.
- The source pain point establishes a **requirement** more strongly than an existing failure.

## 3.13 Refined Opportunity Statement

A slight refinement avoids implying current traceability is deficient:

> **How might we maintain consistent traceability of compliance-case evidence, reasoning, decisions and subsequent actions while minimising unnecessary documentation effort for analysts?**

## 3.14 Opportunity Decision

**Progress with Conditions**

The opportunity has strong regulatory relevance and high feasibility, but the next stage must preserve the important uncertainty that **existing TNG traceability deficiencies have not been demonstrated**.

---

# 4. OP-03 — Transaction Exception Transparency

## 4.1 Source Problem

**Pain Point:** PP-03  
**Evidence Strength:** 3/5  
**Validation:** Partially Validated

TNG's own support information confirms that users can encounter unsuccessful and pending transactions. For unsuccessful DuitNow QR payments, users are instructed to check transaction history; pending payments may take up to 24 hours and unsuccessful payments are subsequently reversed. [Touch 'n Go eWallet Help Centre](https://support.tngdigital.com.my/hc/en-my/articles/360063455053-What-should-I-do-if-my-DuitNow-QR-payment-is-unsuccessful?utm_source=chatgpt.com)

Reload failures also have numerous possible causes, including connectivity, wallet limits, card details, bank rejection, device conditions and high traffic. [Touch 'n Go eWallet Help Centre](https://support.tngdigital.com.my/hc/en-my/articles/4405483924761-Why-can-t-I-reload-with-my-credit-debit-card?utm_source=chatgpt.com)

## 4.2 Initial Opportunity Statement

> **How might we help users understand exceptional transaction states and appropriate next actions without overwhelming them with unnecessary technical information?**

## 4.3 Problem-to-Opportunity Logic

Exceptional transaction states exist and users require status and next-step information.

However, TNG already provides support guidance explaining these situations. Therefore, the evidence does not establish that users currently receive **insufficient** explanation.

## 4.4 Stakeholders

**Primary:** eWallet users.

**Secondary:** Customer-support/operations teams where users seek assistance.

## 4.5 Desired Outcome

Improve users' ability to understand exceptional transaction states and determine an appropriate next action.

## 4.6 Potential Value

**Stakeholder Value:** Potential improvement in clarity and confidence during payment exceptions.

**Business Value:** Could potentially reduce avoidable support interactions, but no evidence currently establishes this effect.

**Compliance Value:** Limited compared with OP-01/02.

**Challenge Alignment: 4/5 — Strongly aligned** with payment transparency, but less directly with regulatory-compliance automation.

## 4.7 Opportunity Value

**3/5 — Moderate**

The underlying situation is real, but evidence of an unmet user need remains limited.

## 4.8 Assumptions

| Assumption | Evidence | Impact if False |
| --- | --- | --- |
| Users struggle to understand transaction exceptions | Not established | High |
| Current explanations are insufficient | Not established | High |
| Better explanations would improve experience | Plausible, not directly validated | Medium |
| Users want more information without technical detail | Not established | Medium |

## 4.9 Constraints

**Security:** Explanations must not expose sensitive transaction/system information.

**Business:** Information should remain accurate and consistent with actual transaction state.

**User:** Additional detail should not increase confusion.

## 4.10 Dependencies

| Dependency | Type | Importance |
| --- | --- | --- |
| Transaction-status information | Data | High |
| Exception/reason information | Technical | High |
| User research | Stakeholder | High |
| Current UX/support journey | Internal | High |

## 4.11 Feasibility

| Dimension | Score | Rationale |
| --- | --- | --- |
| Data | **4/5** | Representative exception scenarios are publicly identifiable and can be simulated. |
| Technical | **4/5** | A concept can be explored without production integration. |
| Access | **4/5** | Public help information provides usable context, though actual support data is unavailable. |
| Skills | **4/5** | Manageable prototype scope. |
| Time / Scope | **5/5** | Narrow and easily bounded. |

**Overall Feasibility: 4/5**

**Critical Blocker:** None technically. The main blocker is **problem validation rather than implementation feasibility**.

This distinction is important because the protocol explicitly says high feasibility must not compensate for weak problem evidence. 03\_opportunity\_statement\_analys…

## 4.12 Risks / Uncertainties

- TNG may already explain transaction exceptions adequately.
- The opportunity may address an inconvenience rather than a material pain point.
- Additional information could create more complexity.
- No user interviews, complaints or support-volume evidence currently establish unmet need.

## 4.13 Refined Opportunity Statement

The existing wording remains appropriately neutral:

> **How might we help users understand exceptional transaction states and appropriate next actions without overwhelming them with unnecessary technical information?**

## 4.14 Opportunity Decision

**Hold**

The opportunity is feasible and challenge-aligned, but the underlying unmet user need is insufficiently established.

**What would change the decision:** user interviews, usability research, complaint/support data or other direct evidence showing that users struggle to understand exceptional transaction states.

---

# 5. Cross-Opportunity Analysis

**OP-01 and OP-02 are closely related but should remain separate.** They operate within the same compliance-case lifecycle, but target different outcomes:

> OP-01 → **investigation efficiency**  
> OP-02 → **case traceability**

They may reinforce each other: reducing repetitive investigation work could interact with how evidence and decisions are captured, while better traceability could potentially reduce reconstruction effort. This is a potential relationship, not yet a solution design.

**OP-03 is substantially separate.** It concerns the customer-facing transaction experience rather than the internal compliance-investigation lifecycle.

The major trade-offs are also different. OP-01 creates an **efficiency vs oversight/accuracy** tension. OP-02 creates a **documentation burden vs completeness/traceability** tension. OP-03 creates an **information completeness vs simplicity** tension.

# 6. Opportunity Prioritisation Summary

| ID | Opportunity | Problem Evidence | Value | Feasibility | Alignment | Critical Blocker | Decision |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **OP-01** | Investigation efficiency | **4/5** | **4/5** | **4/5** | **5/5** | Production data/access for real-world validation | **Progress with Conditions** |
| **OP-02** | Case traceability | **3/5** | **4/5** | **4/5** | **5/5** | Current TNG traceability capability unknown | **Progress with Conditions** |
| **OP-03** | Transaction exception transparency | **3/5** | **3/5** | **4/5** | **4/5** | Unmet user need not established | **Hold** |

These scores are **not summed**, as required by your protocol. 03\_opportunity\_statement\_analys…

# 7. Opportunities Progressing

## OP-01 — Compliance Investigation Efficiency

**Final Opportunity Statement**

> **How might we reduce repetitive information-gathering and analysis effort during flagged-transaction investigations while preserving analyst judgement, accuracy and regulatory oversight?**

**Primary Stakeholder:** Compliance analysts

**Desired Outcome:** Reduce avoidable investigation effort while preserving investigation quality and human oversight.

**Important Constraints:** analyst judgement, accuracy, AML/CFT obligations, confidentiality, regulatory oversight.

**Carry Forward:** Determine which investigation activities actually create meaningful analyst effort and avoid assuming the magnitude of efficiency gains.

## OP-02 — Compliance Case Traceability

**Final Opportunity Statement**

> **How might we maintain consistent traceability of compliance-case evidence, reasoning, decisions and subsequent actions while minimising unnecessary documentation effort for analysts?**

**Primary Stakeholder:** Compliance analysts

**Desired Outcome:** Maintain complete and retrievable case histories without unnecessary documentation burden.

**Important Constraints:** record completeness, attribution, integrity, confidentiality and regulatory record-keeping.

**Carry Forward:** Do not assume TNG's existing traceability process is deficient; validate current workflow/capabilities where possible.

These are now appropriate inputs for **04 – Stakeholder & User Needs Analysis**, which is exactly the handoff defined by your protocol. 03\_opportunity\_statement\_analys…

# 8. Opportunities Not Progressing

| Opportunity | Decision | Reason | What Would Change It |
| --- | --- | --- | --- |
| **OP-03** | **Hold** | Transaction exceptions exist, but insufficient evidence establishes that current explanations create a material user problem | User interviews, usability testing, complaint/support data demonstrating difficulty understanding transaction status or next actions |

# 9. Remaining Research Gaps

| Research Gap | Opportunity | Why it matters | Recommended Method |
| --- | --- | --- | --- |
| Analyst time by investigation activity | OP-01 | Establish where repetitive effort actually occurs | Process observation / interview |
| Alert volumes and investigation turnaround | OP-01 | Establish materiality | Operational data |
| False-positive rates | OP-01 | Determine unnecessary investigation demand | Monitoring data |
| Current case-management/audit capabilities | OP-02 | Establish whether a traceability gap actually exists | Internal system/process review |
| Analyst documentation effort | OP-02 | Establish burden | Interview / observation |
| User understanding of exception states | OP-03 | Establish unmet need | User research |
| Support contacts caused by transaction confusion | OP-03 | Establish materiality | Support/complaint data |

# 10. Decision Log

| ID | Decision | Reason | Impact |
| --- | --- | --- | --- |
| **D-01** | OP-01 progresses with conditions | Strongest problem evidence; relevant and feasible, but impact magnitude unquantified | Progress to Stakeholder & User Needs |
| **D-02** | OP-02 progresses with conditions | Traceability has clear compliance relevance, but existing deficiency is unproven | Progress while preserving uncertainty |
| **D-03** | OP-03 held | High feasibility does not compensate for insufficient evidence of unmet user need | Further user validation before progression |

The most important outcome from this stage is therefore **not that OP-01 “won.”** Rather, **OP-01 and OP-02 have sufficient support to continue into stakeholder/user-needs analysis, while OP-03 currently needs stronger validation before consuming further project scope.** That follows the protocol's definition of Progress/Hold decisions.
