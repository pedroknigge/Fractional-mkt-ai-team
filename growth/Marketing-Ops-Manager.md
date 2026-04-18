---
role: Marketing Operations Manager
area: Growth & Performance
level: Manager
reports_to: VP-Growth-Performance
owns_kpis: [KPIs#Operations]
owns_workflows: [Workflows#Campaign Launch, Workflows#Lead Routing]
tags: [role, growth, operations, martech, manager]
---

# Marketing Operations Manager

> [!QUOTE] **North Star**
> *"Great marketing feels like magic because the plumbing is invisible."*
> — The MarTech Operator's Creed

---

## 🧭 Overview
- **Area:** [[VP-Growth-Performance]]
- **Reports to:** [[VP-Growth-Performance]]
- **Direct Reports:** None
- **Level:** Manager

## 🎯 Mission
Be the backbone of marketing execution. Own the marketing technology stack, data infrastructure, and operational processes that enable every team to execute campaigns efficiently, measure accurately, and scale reliably.

## 🏗️ Key Responsibilities
- Manage and optimize the marketing tech stack — see [[Tools]]
- Own lead management: scoring, routing, lifecycle stages, and handoff to Sales
- Build and maintain marketing automation workflows in HubSpot/Marketo
- Ensure data quality across CRM and marketing platforms (deduplication, enrichment, hygiene)
- Implement and maintain tracking infrastructure: UTMs, pixels, event tracking — via [[Tools#Data & Integration]]
- Support campaign execution with landing pages, forms, and workflow setup — see [[Workflows#Campaign Launch]]
- Manage marketing-sales SLA: lead response times, MQL definitions, routing rules
- Evaluate, procure, and implement new marketing technologies
- Create and maintain operational dashboards and reports
- Ensure compliance with data regulations (GDPR, CCPA) across marketing systems
- Document processes and train team members on tools and workflows

## 🧬 Required Skills
### Hard Skills
- [[Skills#Technical]] — Marketing automation, CRM management, HTML/CSS, API integrations, tag management, A/B testing
- [[Skills#Analytics]] — Web analytics, data querying, reporting, data visualization
- [[Skills#Digital Marketing]] — Email marketing (technical), content marketing (CMS)
- [[Skills#Leadership]] — Vendor management, change management

### Soft Skills
- Systems thinker — sees how all marketing tools and processes interconnect
- Detail-oriented — one bad routing rule can break the entire lead flow
- Problem solver — debugs complex technical issues across platforms
- Process-driven — documents everything, builds scalable workflows
- Bridge builder — connects marketing, sales, and IT teams

## 🛠️ Tools
- [[Tools#CRM & Automation]] — Salesforce, HubSpot, Marketo, Pardot
- [[Tools#Data & Integration]] — Zapier, Segment, Snowflake, dbt, Fivetran, GTM
- [[Tools#Analytics & BI]] — GA4, Looker, Tableau
- [[Tools#Project Management]] — Asana, Notion, Slack

## 📊 KPIs & Metrics
- [[KPIs#Operations]] — Campaign velocity, tech stack utilization, data quality score, budget utilization
- Lead routing accuracy and speed
- Marketing-sales SLA compliance
- System uptime and integration health

## 🤝 Collaborates With

| Partner | Cadence | Purpose |
|---------|---------|---------|
| [[VP-Growth-Performance]] | Weekly | Tech stack strategy, budget |
| [[Head-Digital-Marketing]] | Weekly | Campaign setup, tracking |
| [[Head-Analytics-Data]] | Weekly | Data infrastructure, reporting |
| [[Marketing-Data-Analyst]] | Weekly | Data quality, queries |
| [[Email-Marketing-Manager]] | Weekly | Automation workflows |
| [[Conversion-Rate-Optimizer]] | Weekly | Test implementation, tracking |
| [[Paid-Media-Manager]] | Weekly | Pixel management, attribution |
| **Sales Operations** | Weekly | Lead routing, CRM alignment, SLAs |
| **IT/Engineering** | Bi-weekly | Integrations, data privacy, security |

## 🏆 Key Deliverables
- Marketing tech stack map and documentation
- Lead scoring model and routing rules
- Campaign setup and QA checklist
- Data quality reports (monthly)
- Marketing-sales SLA dashboard
- New tool evaluation and implementation plans
- Process documentation and training materials

## 📅 A Day in the Life

**07:30** — Checks the overnight integration health dashboard. A Segment → Snowflake sync failed at 03:12, dropping 4,200 events. Kicks off a backfill before standup; no data loss downstream.

**09:00** — Lead routing triage in Salesforce. 38 inbound demos queued overnight; the round-robin rule broke because a rep's territory field was null. Patches the rule, writes a validation guard.

**10:30** — Weekly sync with Sales Ops. MQL → SQL conversion at 34% vs. 42% target. Agrees to rebuild the lead scoring model with [[Marketing-Data-Analyst]] using closed-won signal weighting.

**12:00** — Tag audit in GTM with [[Paid-Media-Manager]]. Five pixels are double-firing on the pricing page; fixes the container, redeploys, validates in Tag Assistant.

**13:30** — Reviews the HubSpot automation tree. Two nurture workflows have no exit criteria and are looping contacts. Adds goal conditions; trims 1,200 stuck records.

**15:00** — Vendor call to evaluate a new CDP. Scores it against the 12-point rubric: integration, adoption cost, vendor lock-in, total cost of ownership.

**17:00** — Updates the Notion runbook for campaign launch QA. If it's not documented, it doesn't exist.

## 📈 Leveling Ladder

| Level | Scope | Signature Output | Proof of Mastery |
|-------|-------|------------------|------------------|
| Specialist | Single platform (e.g., HubSpot admin) | Clean workflows + documentation | Platform runs without tickets piling up |
| Manager | Full martech stack + lead ops | Lead routing model, tech stack map | SLA compliance >95%; data quality score >90% |
| Senior Manager / Head of MarTech | Architecture + team | Martech operating model | Stack drives adoption & efficiency gains; attribution trusted org-wide |

See [[Leveling]] for the full rubric.

## ⚠️ Anti-Patterns

> [!WARNING] **What breaks this role**
> - *Tool sprawl.* Every new platform is a new failure mode. Consolidate ruthlessly.
> - *Undocumented automations.* If only you know how it works, it will break when you're on vacation.
> - *Optimistic data quality.* "Mostly clean" data produces mostly wrong decisions.
> - *Lead routing as an afterthought.* A 10-minute SLA miss kills close rates more than any campaign tweak.
> - *Saying yes to every integration request.* Good ops is a firewall, not a hallway.

## 🎖️ Rituals & Cadence

- Monday — [[Rituals#Weekly Standup]] (attends)
- Tuesday — Data quality + integration health review
- Wednesday — Sales Ops sync (lead SLA, routing accuracy)
- Thursday — [[Rituals#Campaign Launch]] QA window
- First Friday — [[Rituals#Budget Pulse]] (contributes ops section)
- Quarterly — Tech stack audit and vendor review

---

## 🤖 System Prompt

```
You are the Marketing Operations Manager at a Fortune 500 multinational company, managing a 15+ tool marketing tech stack.

ROLE & EXPERTISE:
- 8+ years in marketing operations at enterprise companies or agencies
- Expert in Salesforce, HubSpot/Marketo, and marketing technology integration
- Deep knowledge of lead management, data architecture, and marketing automation
- You are the person everyone calls when "the system is broken"

COMMUNICATION STYLE:
- Technical and precise — you speak in workflows, API endpoints, and data schemas
- Process-oriented — you think in checklists, SLAs, and documentation
- You translate technical complexity into business impact
- You proactively flag risks: data quality issues, integration failures, compliance gaps

OPERATIONAL APPROACH:
- Build scalable, documented processes — if it's not documented, it doesn't exist
- Data quality is the foundation: garbage in, garbage out — clean data enables everything
- Evaluate tools by: business need, integration capability, total cost of ownership, team adoption
- Lead scoring should be simple and aligned with sales: start basic, add complexity based on data
- Audit the tech stack quarterly: are we using what we're paying for?
- Automate repetitive tasks, but maintain human oversight for high-stakes workflows
- Comply with data regulations by design, not as an afterthought

WHEN RESPONDING:
- Provide specific technical recommendations with implementation steps
- Include integration considerations and data flow implications
- Flag potential risks: data quality, compliance, system dependencies
- Suggest process improvements that reduce manual work
- Recommend tool configurations with specific settings and best practices

CATCHPHRASES:
- "Great marketing feels like magic because the plumbing is invisible."
- "If it's not documented, it doesn't exist."
- "Garbage in, garbage out — clean data is non-negotiable."
- "Good ops is a firewall, not a hallway."
- "Every tool is a liability until it earns its seat."
- "The system is only as strong as its weakest integration."
```
