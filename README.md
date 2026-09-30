# Finstack Technologies — AI Governance & DPDP Compliance Assessment

A GRC portfolio project: a full risk and compliance assessment for a fictional Bengaluru Banking-as-a-Service (BaaS) platform rolling out an AI fraud detection model and an LLM-based customer support copilot.

**Prepared by:** Vignesh S · [LinkedIn](https://www.linkedin.com/in/vignesh-s-89891a22b/) · [Email](mailto:vigneshvigu38@gmail.com)

## Why this project

Most GRC portfolio projects cover a single framework in isolation. This one stacks two together the way a real engagement would: India's DPDP Act (a legal requirement) and responsible AI governance (an emerging expectation with no established playbook yet), applied to a company that has to satisfy both individual retail customers and 40+ enterprise B2B clients at once.

## Scenario

Finstack is a Bengaluru-headquartered BaaS platform providing KYC, payments, and lending infrastructure to 40+ neobanks across India and Southeast Asia. It is deploying an AI-powered fraud detection model (automated transaction blocking) and an LLM-based support copilot (natural-language account queries for support agents).

**In scope:** data flows into/out of the AI systems, explainability of automated fraud decisions, DPDP compliance for retail customer data, third-party (LLM vendor) risk in both directions, and model bias.

**Out of scope:** company-wide ISO 27001 programme, HR and physical security, non-AI parts of the platform.

## What's in this repo

| File | What it is |
|---|---|
| `Finstack_GRC_Risk_and_DPDP_Assessment.xlsx` | Risk Register (6 risks, inherent → residual scoring), 5×5 Heat Maps, DPDP Act Gap Analysis (6 requirements), Vendor Risk Assessment (13-question comparison of two mock LLM vendors), and AI Control Audit Checklist |
| `AI_Governance_Policy.md` | The governance policy written to close every gap identified in the risk register and gap analysis |

## Method

**Risk scoring:** Likelihood (1–5) × Impact (1–5), scored twice per risk — once before controls (inherent) and once after (residual) — to show measurable risk reduction, not just identification.

**Compliance rating:** each DPDP Act requirement checked against the scenario and rated Compliant / Partial / Non-compliant, with an evidence-based finding and a recommendation with an owner and target date, in the format a real audit report uses.

**Vendor evaluation:** the same questionnaire answered by two mock vendors — one with verifiable, specific commitments, one with vague, unverifiable answers — to demonstrate how to tell real assurance from marketing language.

## Key finding

Of 6 DPDP requirements assessed, 3 were rated Non-compliant and 3 Partial — none fully compliant — driven mainly by the AI systems being added after the original consent and access-control design. The policy and controls in this repo close every identified gap.

---

*Finstack Technologies is a fictional company created for this portfolio project. It is not affiliated with any real entity.*
