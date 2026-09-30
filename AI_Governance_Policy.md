# Finstack Technologies — AI Governance Policy

**Status:** Draft, prepared as part of a GRC portfolio assessment
**Scope:** AI Fraud Detection Model and AI Support Copilot
**Prepared by:** Vignesh S

---

## 1. Purpose and Scope

This policy sets the rules for how Finstack builds, buys and uses AI systems that touch customer data. It applies to the fraud detection model and the support copilot, and to every employee, contractor and client-bank agent who uses them. Its goal is to protect customer data, keep AI decisions explainable, and meet the DPDP Act.

## 2. Roles and Accountability

2.1 The Head of Security owns this policy. Legal owns DPDP compliance. Engineering owns the AI models.
2.2 Finstack must keep a standing AI governance documentation pack, updated every quarter, ready for client questionnaires.
2.3 No new AI system may go live until a risk assessment is completed and approved by the Head of Security.

## 3. Approved Tools and Data Rules

3.1 Anyone handling customer data must use only the Finstack-approved AI copilot.
3.2 Customer data must never be typed, pasted or uploaded into any other AI tool, including public chatbots and browser extensions. Customer data means: name, phone number, address, account and card numbers, PAN, Aadhaar, transaction history, loan and credit details, and KYC documents.
3.3 Even in the approved copilot, users must ask only for the data the query needs.
3.4 Breaking these rules leads to disciplinary action. Employees face a warning up to termination. Client-bank agents lose access and their bank is informed. If customer data leaks, it is handled as a breach under Section 7.
3.5 Agents may only see customers of their own bank. Every lookup must be logged with who, which customer, and when. Customer data must be encrypted in storage and in transit.
3.6 Real customer data must not be used to train or fine-tune models. Anonymized or synthetic data must be used instead. Any AI use that needs real data requires customer consent that explicitly covers AI processing.
3.7 AI chat logs must be deleted after a fixed retention period (90 days). They are covered by customer access and erasure requests.

## 4. Human Oversight and Explainability

4.1 Every time the fraud model blocks a transaction, the system must automatically record the top 3 reasons, the time, and the model version.
4.2 If a customer or client bank disputes a block, a trained human reviewer must decide within 24 hours. A wrong block is reversed immediately.
4.3 The customer or client bank must be told the outcome and a clear, general reason, without revealing the detection rules.
4.4 Every wrong block is logged as a model error. The model team must fix the model, and errors are reported monthly to the risk committee.

## 5. Vendor Requirements

5.1 Before using any third-party AI vendor, Finstack must complete a vendor risk assessment.
5.2 The contract must require: encryption in transit and at rest, breach notice to Finstack within 24 hours, the data location stated in writing, and no use of Finstack customer data to train the vendor's own models.

## 6. Bias and Model Monitoring

6.1 The fraud model must be tested for bias across regions and customer segments every quarter.
6.2 If a group is flagged noticeably more often without a valid reason, the model team must investigate, fix it, and record the outcome.

## 7. Incident and Breach Handling

7.1 The Head of Security decides whether an incident is a personal data breach.
7.2 For a confirmed breach, Finstack must notify affected customers and the Data Protection Board, with a detailed report within 72 hours.
7.3 AI incidents, such as wrong blocks or data pasted into unapproved tools, must be reported internally within 24 hours of discovery.

## 8. Review and Enforcement

8.1 The policy is reviewed every 6 months, and after any major AI change or serious incident.
8.2 Breaking the policy leads to disciplinary action, as described in Section 3.
8.3 All employees and agents must complete AI data-handling training before getting access, and once a year after that.

---

*This is a fictional company built for a GRC portfolio project. It maps directly to the accompanying Risk Register, DPDP Gap Analysis, Vendor Risk Assessment, and AI Control Audit Checklist.*
