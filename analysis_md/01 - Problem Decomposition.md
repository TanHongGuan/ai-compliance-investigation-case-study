# 01 \- Problem Decomposition

**Problem Statement Breakdown - MindMap**

## 1. Original Problem Statement

The project begins with the challenge of building a **secure, AI-driven eWallet platform** that improves digital payment transparency, automates regulatory compliance, and provides real-time financial insights for users and regulators.

Rather than moving directly into solution design, the challenge was decomposed to understand **what each objective means, who it affects, and why it matters**. The mind map explores three main areas: **transparency, regulatory compliance automation, and real-time financial insights**.

---

## 2. Problem Decomposition

### 2.1 Transparency

The transparency objective was explored through three questions:

**Who needs transparency?**  
Three primary stakeholder groups were identified:

- **Users** — individuals using the eWallet.
- **Compliance teams** — internal teams responsible for ensuring regulatory compliance.
- **Regulators** — particularly Bank Negara Malaysia (BNM).

**What needs to be transparent?**

| Stakeholder | Information requiring transparency |
| --- | --- |
| Users | Transaction information |
| Compliance teams | Risk and flagging decisions |
| Regulators | Compliance actions |

**Why is transparency needed?**

For **users**, transparency means being able to understand what happened to their money, why a transaction succeeded or failed, and why an activity may have been flagged.

For **compliance teams**, transparency supports understanding and justifying flagged transactions or suspicious activities so that informed decisions can be made.

For **regulators**, transparency provides visibility into compliance records, decisions and actions, supporting regulatory verification.

The decomposition therefore indicates that transparency has different meanings depending on the stakeholder: **users need understanding, compliance teams need understanding and justification, while regulators need visibility for verification and oversight**.

---

## 3. Regulatory Compliance Automation

The second branch examines what it means to **automate regulatory compliance**. Instead of assuming that the entire compliance process should be automated, the analysis separates activities that currently require human involvement from those that can already be automated.

### Current Manual Activities

The mind map identifies several activities requiring human involvement:

- Reviewing flagged activities.
- Performing case-by-case assessments requiring human judgement.
- Documenting human decisions.

A key question raised was **why these activities remain manual**. The initial observation is that compliance decisions can be highly contextual. For example, a payment pattern that appears unusual may still be legitimate depending on the customer's circumstances. Human judgement may therefore remain necessary when interpreting the context surrounding an alert.

### Existing Automation

The analysis also recognises that some compliance activities can already be automated, including:

- Transaction monitoring.
- Rule or threshold checking.
- Alert generation.
- eKYC checks.

This distinction is important because it reframes the challenge from simply asking **“How can compliance be automated?”** to investigating **which parts benefit from automation and which parts still require human judgement and oversight**.

---

## 4. Real-Time Financial Insights

The third branch explores what constitutes a meaningful **real-time financial insight** and who requires these insights.

### Users

Initial examples of user-facing insights include:

- Spending tracking.
- Identification of unusually large spending.

These examples suggest that user insights should help individuals understand their financial activity rather than simply presenting raw transaction data.

### Regulators

For regulators, the focus is broader. The mind map explores monitoring indicators such as:

- The number of unresolved cases.
- Trends in flagged cases.
- Whether cases remain unresolved.
- Whether flagged activity is becoming more frequent.

The purpose of these insights is initially understood as supporting the identification of increasing suspicious or fraudulent activity, emerging risk patterns, the handling of high-risk cases, the effectiveness of compliance controls, and areas that may require regulatory attention.

However, the mind map also raises an important unresolved question: **why must these insights be real-time?** Existing reporting may already allow regulators to assess historical information and identify trends. Therefore, whether real-time visibility provides sufficient additional value remains an area requiring further validation.

---

## 5. Stakeholder Overview

The decomposition identifies three major stakeholder groups across the challenge:

| Stakeholder | Primary interest identified |
| --- | --- |
| Users | Understanding their transactions and financial activity |
| Compliance teams | Investigating, understanding and justifying risk/flagging decisions |
| Regulators | Verifying compliance activity and monitoring broader risk patterns |

The stakeholder analysis also highlights that the same concept can serve different purposes. For example, “transparency” for a user concerns understanding personal transactions, whereas transparency for a regulator concerns the ability to verify compliance activity.

---

## 6. Key Questions Explored

The problem decomposition was driven by several groups of exploratory questions.

**Transparency questions** focused on who requires transparency, what information should be transparent, and why that visibility is valuable.

**Compliance questions** examined which activities are currently manual, why human judgement is required, and which activities are already automated.

**Financial insight questions** explored what qualifies as an insight, what information users and regulators require, why those insights are valuable, and whether they genuinely need to be delivered in real time.

These questions helped move the analysis from the broad wording of the original challenge toward more specific areas that can subsequently be investigated.

---

## 7. Initial Areas Requiring Further Investigation

At this stage, the mind map identifies **potential areas of concern rather than validated pain points**.

For compliance teams, the reliance on manual review, contextual judgement and decision documentation may create opportunities to improve investigation efficiency. However, the extent of any actual operational problem has not yet been established.

For regulators, more timely visibility into unresolved cases, flagged-case trends and emerging risks may provide supervisory value. However, the need for genuinely real-time information compared with existing periodic reporting requires validation.

For users, clearer transaction information and useful financial insights may improve their understanding of their financial activity, but the specific unmet user needs have not yet been demonstrated.

These observations should therefore be treated as **hypotheses for investigation**, rather than confirmed problems.

---

## 8. Outcome of the Problem Breakdown

The decomposition transformed the broad challenge into several more specific investigation areas:

**Transparency** is primarily a question of providing the right information to the right stakeholder for understanding, justification or verification.

**Regulatory compliance automation** requires distinguishing repetitive or automatable activities from decisions where contextual human judgement remains important.

**Real-time financial insights** require further examination of both the information stakeholders actually need and whether delivering that information in real time creates meaningful additional value.

The analysis therefore provides a clearer foundation for investigating where genuine problems exist before determining requirements or proposing a solution.
