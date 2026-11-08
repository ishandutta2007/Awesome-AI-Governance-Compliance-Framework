# Awesome-AI-Governance-Compliance-Framework

# Awesome-AI-Governance-Compliance-Framework

**Top AI Governance Compliance Framework (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI System Inventories, Risk Classification, EU AI Act Evidence & Self-Hosted Agent Oversight*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Governance & Compliance**. These tools enable organizations to inventory AI systems, classify risk, map controls to regulations (EU AI Act, ISO 42001, NIST AI RMF), and generate audit-ready evidence—from fully managed enterprise platforms with pre-built regulatory workflows to open-source layers that provide tamper-evident agent oversight without vendor lock-in.



**Examples** include Credo AI, Holistic AI, IBM watsonx.governance, FairNow, OneTrust AI Governance, CalypsoAI, SAS AI Navigator, Microsoft Purview DSPM for AI, and Icertis Responsible AI Policy (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted AI governance, runtime agent oversight, and open compliance infrastructure. **Critical note**: True open-source AI governance is nascent—**Vaara** is the only purpose-built open-source governance and evidence layer for AI agents, producing tamper-evident, independently verifiable audit trails mapped to EU AI Act articles . For policy frameworks, **Icertis** publishes its AI Acceptable Use Policy and Responsible AI Policy as reference documents, not software. No open-source project matches Credo AI's regulatory mapping or Holistic AI's bias testing depth, but for runtime agent oversight, Vaara fills a real gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI Governance and Compliance market is estimated at ~$250M–$2.6B in 2025 and projected to reach ~$415M–$3.3B by 2026 (growing at ~24%–36% CAGR), propelled by regulatory enforcement including the EU AI Act and ISO 42001. The sector is currently moderately fragmented across niche point solutions (e.g., algorithmic bias auditing, LLM guardrails, runtime agent oversight), but is transitioning rapidly toward consolidation as hyperscalers and established GRC incumbents acquire specialists and expand horizontal governance suites.

## SaaS/Hosted Platforms

| Company / Product | Company Size (Valuation / Revenue) | Pricing | Free Tier / Free Trial Limits | Key Focus & Strengths |
| :--- | :--- | :--- | :--- | :--- |
| **Microsoft Purview DSPM for AI** | ~$3.8T–$3.9T Market Cap / ~$282B+ Rev (FY25) | Starts at **$12/user/month** (standalone Purview Suite add-on) or included in **Microsoft 365 E5 at $60/user/month**; multi-cloud scanning billed via pay-as-you-go Azure meters | **No dedicated standalone free tier**; 30-day trial available via Microsoft 365 E5 / Purview enterprise trial (up to 25 user licenses) | Single-pane visibility into enterprise Copilot and third-party generative AI usage, sensitive-data exposure detection, and automated labeling. |
| **IBM watsonx.governance** | ~$231B Market Cap / ~$67.5B Rev (FY25) | **Lite: $0/month**; **Essentials: $0.60 per resource unit (RU)** (up to 500 inventories); **Standard instance: $795/month** (includes 3 use cases, 3 custom attributes, up to 25 concurrent users) | **Free forever plan (Lite Tier)**: Up to 200 resource units (RUs), 3 use cases, and 1 inventory with model tracking | Model evaluation, risk management, and lifecycle tracking across both predictive and generative AI workflows. |
| **SAS AI Navigator** | ~$3.0B Annual Revenue (Private) | **Pay-as-you-go via Microsoft Azure Marketplace** post-trial (custom consumption / quote-based contract) | **6-month free trial** via Microsoft/Azure Marketplace (full access to inventory and lifecycle packs during promotional trial window) | AI use case inventory linked to business impact, governance of underlying models and agents, and EU AI Act/NIST RMF policy packs. |
| **OneTrust AI Governance** | ~$4.5B Valuation (scaled toward $500M ARR) | Enterprise contracts typically start at **~$50,000/year** (hybrid metric based on admin/governance seats and tracked inventory volume; platform minimum base ~$10,000/yr) | **No free tier**; 14-day scoped pilot/trial available for enterprise evaluation upon sales consultation | Deep integration into broader enterprise GRC, risk scoring, vendor assessments, and regulatory mappings (EU AI Act, ISO 42001). |
| **FairNow** (AuditBoard / Optro) | ~$3.0B+ Parent Valuation (AuditBoard acquired by Hg for $3B+; $200M+ ARR) | Modular annual enterprise contracts; median AuditBoard contracts start at **~$21,000–$45,947/year** (scales with tracked models, audit scope, and seats) | **No free tier**; 14-day custom proof-of-concept (PoC) / pilot available upon guided sales qualification | AI model inventory, bias/fairness auditing, tamper-evident audit evidence retention, and EU AI Act Article 12 compliance logging. |
| **CalypsoAI** (F5) | ~$180M Acquisition (Acquired by F5) | Enterprise subscription starting at **custom annual quotes** based on monitored inference requests, LLM endpoints, and deployment footprint | **No free tier**; 14-day to 30-day guided enterprise sandbox / pilot available upon request | Full-lifecycle runtime AI security at the inference layer: automated red-teaming, guardrails, prompt scanning, and adversarial attack defense. |
| **Holistic AI** | ~$8M ARR / $35M+ Venture Funding | Custom enterprise subscription scaling by monitored AI systems and governance modules; typical enterprise deployments start at **~$15,000–$30,000/year** | **No free tier**; guided custom proof-of-concept (PoC) pilot available for qualified enterprise evaluations | In-depth bias and fairness audits, shadow AI discovery, and conformity assessments aligned with EU AI Act and NYC Local Law 144. |
| **Credo AI** | ~$3.7M–$7.9M ARR / $41.3M Total Funding | Structured tiered pricing: **Enterprise (0–100 use cases): $153,750/year**; **101–500 use cases: $307,500/year**; **501–1,000 use cases: $512,500/year**; Self-Hosted / On-Prem: $102,500/year | **No free tier or public self-serve trial**; scoped custom enterprise evaluation pilot available on request | Enterprise AI registry, compliance workflows, and comprehensive EU AI Act / ISO 42001 conformity evidence packs. |

*(Note: **Icertis Responsible AI Policy** was previously noted in literature as a policy framework reference document rather than a standalone SaaS governance software platform, and is preserved as reference material in the documentation).*



## Open-Source GitHub Projects



- **Vaara**

  **Open-source governance and evidence layer for AI agents** (AGPL-3.0, ~15 GitHub stars) — **the only purpose-built open-source AI governance platform** found in this research, addressing runtime agent oversight and audit evidence . **Features**: **Policy enforcement at action time**—each agent action is checked against a defined policy; risk scored; decided to allow, block, or escalate for human review; risk score adapts as outcomes are reported back . **Tamper-evident audit trail**—hash-chained records where any change to a past record is detectable; records can be signed, timestamped, and verified offline using only a public key; independent verification without trusting the organization . **Framework adapters**—LangChain, CrewAI, OpenAI Agents SDK; can act as a proxy for MCP servers . **Shadow mode**—records decisions without enforcing them, allowing policy testing first . **EU AI Act evidence reports**—mapped to articles, flagging where evidence is insufficient . **Tech stack**: Python . **Deploy**: Self-hosted (Python library/proxy) . **Trade-off**: **Early-stage project** (15 stars)—limited community validation; **does not certify compliance**; requires integration with agent frameworks. **Best for**: organizations deploying AI agents that need tamper-evident records of what the agent did and why—especially those preparing for EU AI Act Article 14 (human oversight) and Article 12 (record-keeping) evidence requirements.



### Additional Strong Open-Source Options



- **No mature open-source AI governance platform exists beyond Vaara.** Credo AI, Holistic AI, IBM watsonx.governance, FairNow, OneTrust, CalypsoAI, SAS, and Microsoft Purview are proprietary. **Vaara** provides runtime agent governance and evidence but not AI system inventory, risk classification, or regulatory mapping workflows. For full AI governance programs, commercial platforms are required.



**Frameworks for building custom systems**: **Vaara** provides the runtime governance and evidence layer for AI agents. For AI system inventory, risk classification, and regulatory mapping, no open-source alternative exists—commercial platforms or custom development are required.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI governance platforms handling model inventories and risk assessments must comply with data protection regulations (GDPR, CCPA, etc.) and emerging AI regulations (EU AI Act, etc.). **Open-source tools do not certify compliance**—they provide evidence that must be reviewed and validated by qualified professionals.

- **The "AI system inventory/risk mapping" vs. "runtime agent governance" vs. "data security posture" vs. "policy framework" distinction is critical.** **Credo AI, Holistic AI, FairNow, OneTrust, and SAS AI Navigator** are **AI system inventory/risk mapping** platforms—they catalog AI use cases, classify risk, map controls to regulations, and generate conformity evidence . **IBM watsonx.governance** spans model evaluation and inventory with a free entry tier . **CalypsoAI** is **AI security at inference**—red-teaming, risk scoring, and content moderation at runtime . **Microsoft Purview DSPM for AI** is **data security posture**—it surfaces AI usage and sensitive-data exposure within M365 . **Vaara** is **runtime agent governance**—it enforces policy on agent actions and produces tamper-evident evidence . **Icertis** provides **policy framework documents**, not software . **Choose based on whether you need inventory/risk mapping, runtime security, data exposure visibility, agent oversight, or a policy template.**

- **Credo AI's pricing is publicly documented and six-figure.** Enterprise for 0–100 use cases is **$153,750/year**; self-hosted is **$102,500/year**; implementation adds **$205,000 one-time** . **Do not evaluate without enterprise budget approval** .

- **IBM watsonx.governance has a genuinely free Lite tier**—200 resource units, 3 use cases, 1 inventory . **The trade-off**: resource-unit metering; Essentials is **$0.60/RU**; Standard instance **$795/month** for 3 use cases and 25 concurrent users .

- **SAS AI Navigator's first six months are free**—a real trial period, not free access . **Post-trial rate, metering, data residency, and SLAs are not published**—ask before committing .

- **OneTrust's AI Governance is expensive and complex.** Reviewers describe TCO as expensive, the tool as "not very user friendly," and significant post-implementation work required . **For organizations already on OneTrust, the integration value may justify it; for others, evaluate carefully** .

- **CalypsoAI is now part of F5** (acquired for $180M). **Enterprise-only pricing may be prohibitive for smaller organizations**; F5 ownership may change product direction .

- **Vaara is the only functional open-source AI governance tool**—hash-chained audit trails, policy enforcement at action time, and EU AI Act evidence reports . **The trade-off**: 15 stars; early-stage; does not certify compliance. **For teams deploying AI agents that need tamper-evident records, it is the starting point.**

- Self-hosted open-source solutions require proper setup (Python for Vaara) and integration with agent frameworks. **AI governance tools handle model inventories and risk assessments**—ensure your deployment meets your organization's compliance and audit requirements before relying on it for regulatory evidence.



---



**Made for AI governance leads, compliance officers, and organizations building transparent AI oversight solutions.**

Let's make AI Governance & Compliance more open, data-driven, and evidence-verifiable.
