# Free & Low-Cost Microsoft Offerings for SAP Developers and Architects

Are you interested in **connecting SAP with Microsoft AI**? Integrating an **SAP RAP app with Work IQ**? Connecting **Copilot Studio with the MCP Gateway for SAP Integration Suite**? Wiring **SAP Datasphere into Microsoft Fabric**? Or **securing your CAP app with Sentinel**?

Then this is the place to start.

| If you want to… | Start here |
|---|---|
| Connect SAP with Microsoft AI | [2. AI, agents & Copilot](#2-ai-agents--copilot) |
| Integrate an SAP RAP app with Work IQ | [4. Microsoft 365 & Graph](#4-microsoft-365--graph) |
| Connect Copilot Studio with the MCP Gateway for SAP Integration Suite | [2. AI, agents & Copilot](#2-ai-agents--copilot) |
| Connect SAP Datasphere with Microsoft Fabric | [6. Data & analytics](#6-data--analytics) |
| Secure your CAP app with Sentinel | [8. Security & threat protection](#8-security--threat-protection) |
| Just try a model before building anything | [3. AI playgrounds](#3-ai-playgrounds--try-before-you-build) |

A curated starter kit of Microsoft programs, trials and free tiers that an SAP-minded developer, consultant or architect can sign up for today — mostly without a credit card, and without asking their employer for a budget.

Each entry says **what it is**, **what it costs**, and **why it matters** if your day job revolves around SAP.

**Legend:** 🟢 free tier / free program · 🟡 time-boxed or credit-boxed trial · 🟣 paid, but cheap for what you get

> ⚠️ Offers, quantities and eligibility rules change often. Always check the linked page for current terms, and set a budget alert on any Azure subscription you create. Details verified September 2026.

---

## How to use this list

If you work in and around SAP — as a developer, consultant, architect or basis person — the hardest part of learning the Microsoft side is usually not the technology. It's getting a *legitimate place to try things*. Customer landscapes are off-limits, corporate tenants have trials switched off, and "can I get a budget for a sandbox?" is a conversation nobody wants to have twice.

This list solves exactly that problem. Everything here is something you can sign up for **yourself, today**, with your own identity: free tiers that never expire, time-boxed trials, and a small number of paid programs that are cheap enough to be worth it personally. Most need no credit card; the ones that do say so.

**A suggested first hour, if you're starting from zero:**

1. **[Azure free account](https://azure.com/free)** — your USD 200 of credit and the always-free services. Set a budget alert immediately.
2. **[Microsoft 365 Developer Program](https://developer.microsoft.com/en-us/microsoft-365/dev-program)** — check your eligibility *first*, because this is the one that unlocks everything else. A renewable **Microsoft 365 E5 developer sandbox**: your own tenant, 25 user licences, Teams, SharePoint, Outlook and Office pre-provisioned with sample data. Crucially, the sandbox gives you Microsoft Entra ID-backed **work or school accounts** (for example, `admin@yourtenant.onmicrosoft.com`). You can use one of these accounts wherever a personal Microsoft account is not accepted — including to sign up for Copilot Studio and the Power Apps Developer Plan. It means you can build and demo against a real tenant instead of borrowing a customer's. If you hold a Visual Studio Professional or Enterprise *standard* subscription, link it and the sandbox auto-renews for as long as that subscription lives.
3. **[Power Apps Developer Plan](https://learn.microsoft.com/en-us/power-platform/developer/plan)** — free, and the only place you get premium and custom connectors without a licence. This is where an SAP OData proof of concept actually happens.
4. **[Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)** — start the trial early using a **work or school account from the developer tenant in step 2**, because this is where the strategic conversation is right now. It is the low-code surface where an agent meets your business process: connectors, topics, actions, and — via [MCP](https://modelcontextprotocol.io/) — tools that reach into an SAP system. If you only build one thing this year to show a customer, build this. Pair it with the developer tenant from step 2 and the connectors from step 3 and you have a complete, licence-free path from prompt to SAP transaction.
5. **[GitHub Copilot Free](https://github.com/features/copilot/plans)** in **[VS Code](https://code.visualstudio.com/)** — no card, agent mode, MCP support.
6. **An [AI playground](#3-ai-playgrounds--try-before-you-build)** — five minutes to find out whether a model can do the thing, before you build anything around it.
7. **[Microsoft Learn](https://learn.microsoft.com/en-us/training/)** — free training with hosted sandboxes, plus the [SAP on Azure](https://learn.microsoft.com/en-us/azure/sap/) documentation.

**Three things worth knowing before you commit time:**

- **"Free tier" usually means "free up to a monthly quantity, on a specific SKU."** It is not the same as "free service." Check the exact quantity before you deploy.
- **Eligibility rules move.** The Microsoft 365 Developer Program in particular reworked its qualification model — it is no longer open sign-up.
- **Trials that auto-enrol can bill you.** Defender for Cloud and similar services start protecting everything unless you opt out, and charge once the trial window closes. Budget alerts are not optional.

---

## 1. Azure & cloud infrastructure

| Offer | Type | What you get |
|---|---|---|
| [Azure free account](https://azure.com/free) | 🟡🟢 | USD 200 credit for the first 30 days, free monthly amounts of popular services for 12 months, plus a large set of always-free services. *SAP angle: enough for a small Linux VM, storage account and function app — the classic integration PoC playground.* |
| [Explore free Azure services](https://azure.microsoft.com/en-us/pricing/free-services/) | 🟢 | The searchable table of every "12 months free" and "always free" service with exact monthly quantities and SKUs. *Check this before you deploy — the SKU is the difference between a free lab and a surprise invoice.* |
| [Azure Dev/Test pricing](https://azure.microsoft.com/en-us/pricing/offers/dev-test/) | 🟣 | Discounted Azure rates for non-production workloads (Visual Studio subscribers / enterprise offer). *The pragmatic way to keep a long-lived SAP demo landscape alive after the credits run out.* |
| [Azure for Students](https://azure.microsoft.com/en-us/free/students/) | 🟢 | Free developer tools + USD 100 credit, no credit card, academic email only. *Worth flagging to trainees and dual-study students.* |
| [SAP on Azure documentation](https://learn.microsoft.com/en-us/azure/sap/) | 🟢 | Reference architectures, deployment guides, certified configurations. *Not an "offer", but the most useful free asset here.* |

## 2. AI, agents & Copilot

| Offer | Type | What you get |
|---|---|---|
| [Azure AI Foundry / Microsoft Foundry](https://ai.azure.com/) | 🟡🟢 | Build, evaluate and deploy AI agents and models; usable within Azure free-account credit, several underlying services have free monthly quantities. Now branded **Microsoft Foundry** in the portal. *Where you'd prototype an agent reasoning over SAP data via OData or MCP.* |
| [GitHub Copilot Free](https://github.com/features/copilot/plans) | 🟢 | 2,000 code completions/month, agent mode in supported editors, MCP server integration, Copilot CLI. No credit card. *Works fine on CAP/Node/Java, Fiori/UI5, and Terraform for SAP landscapes.* |
| [Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio) | 🟡 | Low-code agent building with connectors, topics and actions; time-limited trial from the product page. *The usual starting point for "chat with my SAP business process".* |
| [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) | 🟢 | Open protocol + open-source SDKs for exposing tools and data to AI agents. *Cheapest way to make an SAP system agent-callable — wrap an RFC, BAPI or OData entity set as a tool.* |

## 3. AI playgrounds — try before you build

No subscription, no deployment, no `az login`. These are the fastest way to sanity-check whether a model can do the thing before you write a line of integration code — and they demo well from a conference Wi-Fi connection.

| Playground | Type | What you get |
|---|---|---|
| [MAI Playground](https://playground.microsoft.ai/) | 🟡 | Microsoft AI's own limited-preview playground for new and experimental **MAI** models — currently MAI-Thinking-1 (reasoning), MAI-Transcribe-2 (speech-to-text), MAI-Voice-2 (speech generation) and MAI-Image-2.5 / 2.6 (image generation), plus a "Chatter" voice experience. Browser-based, log in to use. *Transcribe is the sleeper for SAP folks: drop in a recorded requirements workshop or a support call and get a domain-accurate transcript to feed downstream. Note it's an experimental preview — don't build a customer demo on top of it.* |
| [Microsoft AI — models overview](https://microsoft.ai/models/) | 🟢 | The catalogue behind the playground: what each MAI model is for, plus MAI-Code-1.1-Flash (the lightweight agentic coding model built into GitHub Copilot and VS Code). *Useful context when someone at TechEd asks "which model should I use for what?"* |
| [Microsoft Foundry playgrounds](https://ai.azure.com/) | 🟡🟢 | Chat, agent, image and audio playgrounds inside Foundry, sitting on a broad model catalogue. You can prompt, compare models and tune parameters before you deploy anything, then export working code. *The step up from MAI Playground when you need your own endpoint, your own data and a supported production path.* |
| [Microsoft Copilot](https://copilot.microsoft.com/) | 🟢 | The free consumer/web Copilot — chat, image generation and web-grounded answers, no licence needed. *Handy as a zero-friction "show me what an LLM does" opener in a workshop before you get into architecture.* |
| [Microsoft Learn sandbox exercises](https://learn.microsoft.com/en-us/training/) | 🟢 | Many Learn modules include a hosted sandbox that provisions temporary Azure resources for the exercise — no subscription of your own required. *The cheapest hands-on lab environment in this whole document.* |

## 4. Microsoft 365 & Graph

| Offer | Type | What you get |
|---|---|---|
| [Microsoft 365 Developer Program](https://developer.microsoft.com/en-us/microsoft-365/dev-program) | 🟢 | A free, renewable **Microsoft 365 E5 developer subscription** — instant sandbox tenant, 25 user licences, pre-provisioned Teams/SharePoint/Outlook/Office and sample data. Those users are Microsoft Entra ID-backed **work or school accounts**, so they also provide the organizational identity required to sign up for services such as Copilot Studio and the Power Apps Developer Plan. Eligibility via a Visual Studio Professional/Enterprise **standard** subscription, or via the ISV Success Program / eligible Microsoft AI Cloud Partner Program tiers. Joining directly gives a 90-day renewable sandbox; linking a Visual Studio subscription makes it auto-renew. *A clean tenant for Teams apps, Graph calls and Copilot extensibility — without touching a customer's production tenant.* |
| [Microsoft Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) | 🟢 | Run Graph queries in the browser against sample data or your own tenant, zero setup. |
| [Microsoft 365 developer docs & Agents Toolkit](https://learn.microsoft.com/en-us/microsoft-365/developer/) | 🟢 | Free tooling for Teams apps, message extensions and M365 Copilot agents, including the VS Code extension. *Surface an SAP approval or PO lookup directly in Teams.* |

## 5. Low-code: Power Platform

| Offer | Type | What you get |
|---|---|---|
| [Power Apps Developer Plan](https://learn.microsoft.com/en-us/power-platform/developer/plan) | 🟢 | Free dev environment for Power Apps, Power Automate and Dataverse. Open to anyone with a work/school account backed by Microsoft Entra ID. Includes **premium and custom connectors** and on-premises data gateway access. Limits: 750 flow runs/month, 2 GB database. *Premium connectors on a free plan is the headline — that's how you reach an SAP OData service. Solutions export cleanly to production later.* |
| [Create a developer environment (walkthrough)](https://learn.microsoft.com/en-us/power-platform/developer/create-developer-environment) | 🟢 | Step-by-step provisioning, including what to do with no work account. *Use the developer environment, not your tenant's default — that's what unlocks premium/custom connectors.* |

## 6. Data & analytics

| Offer | Type | What you get |
|---|---|---|
| [Microsoft Fabric trial capacity](https://learn.microsoft.com/en-us/fabric/fundamentals/fabric-trial) | 🟡 | 60 days of near-full Fabric — Data Factory, Data Engineering, Data Science, Real-Time Intelligence, Power BI — with up to 1 TB OneLake storage. Copilot and some AI experiences are **not** supported on trial capacity. *Long enough for a full SAP-data-to-OneLake pipeline demo.* |
| [Start a Fabric trial with a personal email](https://learn.microsoft.com/en-us/fabric/fundamentals/free-trial-account-personal-email) | 🟡 | Documented route via an Azure account + Entra ID user. *Useful when your corporate tenant has trials disabled — a common blocker.* |
| [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) | 🟢 | Full modelling and report authoring, free on your own machine. *Connects to SAP HANA and SAP BW out of the box.* |

## 7. Identity & integration

| Offer | Type | What you get |
|---|---|---|
| [Microsoft Entra ID Free](https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing) | 🟢 | User/group management, SSO to cloud apps, app registrations — included with any Azure or M365 subscription. *Everything you need to practise SAML federation with SAP IAS and OAuth 2.0 / OIDC against an SAP system.* |
| [Azure API Management — Consumption tier](https://azure.microsoft.com/en-us/products/api-management) | 🟢 | Free monthly allowance of API calls (see the free-services table for the current quantity). *A façade in front of an SAP OData or RFC endpoint with policy-based auth and throttling.* |
| [Azure Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/) | 🟣 | Consumption-priced workflows with hundreds of connectors, including a dedicated SAP connector. *Idle workflows cost essentially nothing — ideal for event-driven SAP demos.* |

## 8. Security & threat protection

| Offer | Type | What you get |
|---|---|---|
| [Microsoft Sentinel — free trial](https://learn.microsoft.com/en-us/azure/sentinel/billing) | 🟡 | Enable Sentinel on a Log Analytics workspace and the **first 10 GB/day ingested on the Analytics logs plan is free for 31 days** — both the Log Analytics ingestion charge and the Sentinel analysis charge are waived up to that limit. Subject to a 20-workspace limit per Azure tenant. Automation, bring-your-own-ML and data lake charges still apply. *31 days and 10 GB/day is genuinely enough to run a real SAP security proof of concept end to end.* |
| [Microsoft Sentinel solutions for SAP](https://learn.microsoft.com/en-us/azure/sentinel/sap/solution-overview) | 🟢🟡 | Two Microsoft-owned solutions: one for **SAP applications** (business logic, application, database and OS layers) and one for **SAP BTP** (via the official audit log API) — deploy either or both. SIEM plus SOAR: detections for privilege escalation, unapproved changes, unauthorised access and misuse of sensitive transactions, with automated response playbooks that talk back to the SAP system. Certified and listed on the SAP Business Accelerator Hub for SAP ECC, Business Suite and other NetWeaver-based products (any cloud or on-premises), S/4HANA Cloud Private Edition (RISE), and hybrid estates. Extend it with SAP LogServ for RISE platform logs, partner add-ons, or the community repository on GitHub. *This is the single most SAP-specific thing Microsoft ships. The solution content is Microsoft-published; your cost is the data you ingest — which the 31-day trial above covers for a PoC.* |
| [Microsoft Defender for Cloud — Foundational CSPM](https://azure.microsoft.com/en-us/pricing/details/defender-for-cloud/) | 🟢🟡 | **Foundational CSPM is free**: continuous assessments, security recommendations, Secure Score and the Microsoft cloud security benchmark across Azure, AWS **and** Google Cloud — plus asset inventory, DevOps posture visibility, infrastructure-as-code security and compliance management. The paid plans (Defender CSPM, Defender for Servers, SQL, Containers, Storage…) are free for the first 30 days. *Point it at the subscription hosting your SAP VMs and you get a hardening backlog for free.* ⚠️ **Enabling it auto-enrols every resource unless you explicitly opt out, and billing starts at day 31.** |
| [Microsoft Entra ID Free](https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing) | 🟢 | See [section 7](#7-identity--integration) — the free tier is where you practise SAML federation with SAP IAS and OAuth 2.0 / OIDC against an SAP system. Identity is the front door to every SAP security conversation. |
| [MSRC Security Update Guide](https://msrc.microsoft.com/update-guide) | 🟢 | Microsoft's authoritative, free CVE and patch database, with filtering, an API and exportable data. *If you track patch cadence across an enterprise estate — and compare it with SAP Security Patch Day — this is the primary source, not a blog summary.* |
| [Microsoft Sentinel documentation](https://learn.microsoft.com/en-us/azure/sentinel/) | 🟢 | Full deployment guides, KQL reference and detection content. *Heads-up worth repeating on stage: after 31 March 2027 Sentinel will no longer be supported in the Azure portal and moves entirely to the Microsoft Defender portal — plan any demo environment accordingly.* |


## 9. Developer tooling

| Offer | Type | What you get |
|---|---|---|
| [Visual Studio Code](https://code.visualstudio.com/) | 🟢 | Free editor with extensions for ABAP, CAP, Fiori/UI5, Terraform, Bicep, containers and MCP clients. |
| [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) | 🟢 | Full IDE, free for individuals, OSS contributors, academic use and small teams. |
| [GitHub Free](https://github.com/pricing) | 🟢 | Unlimited public and private repos, Actions minutes for public repos, Codespaces, Issues. *Where the SAP-on-Azure community publishes samples, Terraform modules and MCP servers.* |
| [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) | 🟢 | Free for up to 5 users, unlimited private Git repos, monthly pipeline minutes. |

## 10. Learning & certification

| Offer | Type | What you get |
|---|---|---|
| [Microsoft Learn training](https://learn.microsoft.com/en-us/training/) | 🟢 | The full self-paced catalogue, including hands-on sandbox exercises that run without your own subscription. |
| [Exam AZ-120: Azure for SAP Workloads](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-120/) | 🟢 | Study guide, learning paths and prep material are free; only the exam is paid. *The clearest credential for an SAP architect moving into Azure.* |
| [Explore Azure for SAP workloads (learning path)](https://learn.microsoft.com/en-us/training/paths/explore-azure-for-sap-workloads/) | 🟢 | Introductory path on architecting, sizing and operating SAP on Azure. |

## 11. Partner & startup programs

| Offer | Type | What you get |
|---|---|---|
| [Microsoft AI Cloud Partner Program](https://partner.microsoft.com/) | 🟣 | Joining is free; benefit packages such as the Microsoft Action Pack carry a modest annual fee and bundle internal-use software, Azure credits, technical benefits and go-to-market support. *Also a qualifying route into the M365 E5 developer sandbox.* |
| [ISV Success / Frontier Accelerate for Marketplace](https://partner.microsoft.com/en-us/partnership/frontier-accelerate-for-marketplace) | 🟣 | Development credits, technical consultations and marketplace publishing support for software vendors. Also a qualifying path for the M365 developer sandbox. |
| [Microsoft for Startups Founders Hub](https://www.microsoft.com/en-us/startups) | 🟡 | Azure credits, AI services access, developer tools and technical support for eligible startups, granted in tiers. *By far the largest pool of free Azure on this list.* |

## 12. Community & content

| Resource | Type | What you get |
|---|---|---|
| [Microsoft Tech Community — SAP on Azure](https://techcommunity.microsoft.com/category/sap) | 🟢 | Blogs, announcements and Q&A from the teams working on SAP integration and SAP on Azure. |
| [SAP on Azure scripts and utilities](https://github.com/Azure/SAP-on-Azure-Scripts-and-Utilities) | 🟢 | Microsoft's open-source scripts and utilities for deploying and operating SAP on Azure. |
| [SAP on Azure video podcast](https://www.youtube.com/@SAPonAzure) | 🟢 | Regular conversations with SAP and Microsoft engineers and community members. |

---

## Contributing

Spotted a missing offer, or one whose terms have changed? Open an issue or a pull request. Please keep entries in the existing format: **what it is → what it costs → why an SAP person should care.**
