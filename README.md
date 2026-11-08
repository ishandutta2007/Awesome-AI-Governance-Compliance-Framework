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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Credo AI**
  **AI governance platform** for policy, registry, and conformity. **Pricing**: **Enterprise (0–100 use cases) $153,750/year**; **101–500 use cases $307,500/year**; **501–1,000 use cases $512,500/year**; **Self-Hosted $102,500/year**; **On-Prem $102,500/year**; **Platform Readiness & Implementation $205,000 one-time**; **Additional Services $102,500 one-time** . **Free tier**: None. **Best for**: enterprises needing structured AI use case inventories with EU AI Act and ISO 42001 conformity evidence—**trade-off**: six-figure annual commitment; professional services add significantly.

- **IBM watsonx.governance**
  **AI governance** across predictive and generative models. **Pricing**: **Lite free** (up to 200 resource units, 3 use cases, 1 inventory); **Essentials $0.60 per resource unit** (up to 500 inventories); **Standard instance $795/month** (3 use cases, 3 custom attributes, up to 25 concurrent users); higher tiers scale . **Free tier**: Yes, Lite with 200 RUs. **Best for**: IBM-centric enterprises wanting model evaluation and risk management with a free entry point—**trade-off**: resource-unit metering requires usage modeling; full governance requires paid tiers.

- **Holistic AI**
  **AI governance and risk management** platform. **Pricing**: **No public pricing**—provider does not communicate price information; individual agreement required . **Free tier**: Free version and free trial listed on OMR, but scope unverified . **Best for**: organizations needing bias testing and shadow AI discovery—**trade-off**: reviewers cite high price and non-transparent pricing as barriers; integrations can be complex .

- **FairNow**
  **AI governance platform** (acquired by AuditBoard in 2025). **Features**: **AI model inventory** with ownership and lifecycle stage; **risk assessment workflows**; **bias and fairness testing**; **regulatory intelligence** tracking; **audit evidence collection** with hashing and retention; **audit logging** for EU AI Act Article 12; **third-party AI vendor risk** . **Pricing**: **No public pricing**—contact sales for quote . **Free tier**: Free trial listed but scope unverified . **Best for**: enterprises needing audit-ready evidence and harmonized controls across 25+ regulations—**trade-off**: no public pricing; now part of AuditBoard.

- **OneTrust AI Governance**
  **AI governance module** within OneTrust's GRC and privacy ecosystem. **Features**: **Centralized intake**; **risk assessment**; **lifecycle tracking** of AI systems; **flexible questionnaires and workflows**; **mapping to regulatory frameworks** . **Pricing**: **No public pricing**; reviewers describe TCO as expensive . **Free tier**: None. **Best for**: organizations already on OneTrust wanting AI governance within their existing GRC platform—**trade-off**: reviewers note it is "not very user friendly" with significant post-implementation work required .

- **CalypsoAI**
  **AI security and governance** for LLM deployments (acquired by F5 for $180M). **Features**: **Automated red-teaming**; **risk scoring**; **content moderation**; **compliance monitoring**; **granular access controls**; **audit trails**; only full-lifecycle platform for AI security at the inference layer . **Pricing**: **Enterprise-only**; may be prohibitive for smaller organizations . **Free tier**: None. **Best for**: enterprises needing runtime AI security alongside governance—**trade-off**: complex features require expertise; F5 ownership may change product direction .

- **SAS AI Navigator**
  **AI governance SaaS** on Microsoft Marketplace. **Features**: **AI use case inventory** organized around business impact; **governance extends to models and agents** powering each use case; **policy packs** for EU AI Act, NIST AI RMF, and internal generative AI policy; **full lifecycle coverage** from experimentation to phase-out; covers in-house and third-party AI . **Pricing**: **First six months free**; **pay-as-you-go after**; post-trial rate, metering, data residency, and SLAs not published . **Free tier**: Yes, 6-month trial. **Best for**: Microsoft-centric organizations wanting a free trial before committing—**trade-off**: discovery mechanism unclear; manual setup described by third parties; Entra ID required .

- **Microsoft Purview DSPM for AI**
  **Data security posture management for AI** (formerly AI Hub). **Features**: **Single pane of glass** over generative AI usage including Copilot and third-party apps; **surfaces sensitive-data exposure**; **ready-to-deploy policies** for risky AI use; **labels sensitive prompts/responses**; **feeds into Insider Risk Management** . **Pricing**: **Full capabilities require M365 E5, E5 Compliance add-on, or standalone Purview licenses**; lighter version available on E3 with Copilot licenses . **Free tier**: Limited on E3 with Copilot. **Best for**: Microsoft 365 organizations needing visibility into AI usage and data exposure—**trade-off**: full policy depth requires E5; prerequisites (Audit, sensitivity labels, Restricted Search) must be in place first .

- **Icertis Responsible AI Policy** (**Not a vendor platform**)
  **Corporate AI policy framework** published as reference documents. **Features**: **AI Acceptable Use Policy (AUP)** governing subscriber use of AI services—prohibited content/actions, consequential decisions, critical infrastructure, data protection; **Responsible AI Policy** with FORTE principles (Fairness, Openness, Respect, Teamwork, Execution) and Map-Evaluate-Mitigate process; board-level oversight . **Pricing**: N/A (policy documents). **Free tier**: N/A. **Best for**: organizations wanting a reference policy framework to adapt—**not a software platform**.

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
