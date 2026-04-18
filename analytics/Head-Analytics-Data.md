---
role: Head of Analytics & Data
area: Analytics
level: Director
reports_to: VP-Growth-Performance
owns_kpis: [KPIs#Revenue & ROI, KPIs#Operations]
owns_workflows: [Workflows#Performance Review Cycle]
tags: [role, analytics, director]
---

# Head of Analytics & Data

> [!QUOTE] **North Star**
> *"Numbers don't decide. They reveal the decision."*
> — The Analytics Creed

---

## 🧭 Overview
- **Area:** [[VP-Growth-Performance]]
- **Reports to:** [[VP-Growth-Performance]]
- **Direct Reports:** [[Marketing-Data-Analyst]]
- **Level:** Director

## 🎯 Mission
Build the marketing organization's measurement and intelligence capability. Transform raw data into actionable insights that drive better decisions, optimize spend, and prove marketing's contribution to revenue.

## 🏗️ Key Responsibilities
- Define the marketing measurement framework: KPIs, attribution models, reporting standards
- Own marketing attribution: multi-touch, media mix modeling, incrementality testing
- Build and maintain executive marketing dashboards — see [[Workflows#Performance Review Cycle]]
- Lead deep-dive analyses for campaign performance, channel efficiency, and customer behavior
- Present quarterly marketing business reviews to [[CMO]] and board
- Design experiments and measurement plans for new initiatives
- Manage the marketing data stack with [[Marketing-Ops-Manager]]: data warehouse, BI tools, CDP
- Hire, mentor, and develop [[Marketing-Data-Analyst]]
- Establish data governance standards for marketing data
- Partner with Finance on marketing ROI reporting and budget planning

## 🧬 Required Skills
### Hard Skills
- [[Skills#Analytics]] — Web analytics, data visualization, SQL & data querying, statistical analysis, attribution modeling, reporting
- [[Skills#Technical]] — A/B testing, API integrations, tag management
- [[Skills#Strategy]] — Business acumen, market research
- [[Skills#Leadership]] — Team management, stakeholder management, cross-functional collaboration

### Soft Skills
- Translates complex data into clear business narratives
- Strategic thinker — connects metrics to business outcomes
- Intellectually curious — always asking "why?" behind the numbers
- Executive presence — comfortable presenting to C-suite and board
- Influential — drives data-driven culture across the organization

## 🛠️ Tools
- [[Tools#Analytics & BI]] — GA4, Adobe Analytics, Looker, Tableau, Mixpanel, Amplitude
- [[Tools#Data & Integration]] — Snowflake, dbt, Segment, Fivetran
- [[Tools#CRM & Automation]] — Salesforce (pipeline data)
- SQL, Python/R for advanced analysis

## 📊 KPIs & Metrics
- [[KPIs#Revenue & ROI]] — Marketing ROI, marketing-sourced revenue, marketing-influenced revenue, LTV:CAC ratio
- [[KPIs#Operations]] — Data quality score
- Reporting accuracy and timeliness
- Insight adoption rate (% of recommendations acted upon)

## 🤝 Collaborates With

| Partner | Cadence | Purpose |
|---------|---------|---------|
| [[VP-Growth-Performance]] | Weekly | Measurement strategy, performance insights |
| [[CMO]] | Monthly | Board-level reporting, marketing ROI narrative |
| [[Marketing-Data-Analyst]] | Daily | Analysis priorities, dashboard QA, coaching |
| [[Marketing-Ops-Manager]] | Weekly | Data infrastructure, tracking, warehouse health |
| [[Head-Digital-Marketing]] | Weekly | Channel performance analysis, MMM inputs |
| [[Conversion-Rate-Optimizer]] | Bi-weekly | Experiment design, statistical rigor |
| [[Paid-Media-Manager]] | Weekly | Attribution, ROAS, incrementality reads |
| **Finance** | Monthly | Budget reporting, ROI reconciliation |
| **Data Engineering** | Bi-weekly | Pipeline SLAs, warehouse governance |

## 🏆 Key Deliverables
- Marketing measurement framework document
- Weekly performance snapshot for leadership
- Monthly channel performance deep-dives
- Quarterly marketing business review (board-level)
- Attribution model documentation and validation
- Annual marketing ROI report

## 📅 A Day in the Life

**07:15** — Coffee and the morning Looker board `exec_marketing_pulse_v4`. Paid search CAC jumped 18% overnight; opens the Snowflake tab, writes a quick CTE against `fct_marketing_attribution` joined to `dim_campaign` to see whether it's a spend spike or a conversion drop. It's conversion. Slacks [[Paid-Media-Manager]] before standup.

**09:30** — Reviews a dbt PR from [[Marketing-Data-Analyst]] rebuilding `stg_segment_events__web`. Catches a silent deduplication bug that would have double-counted signups. Requests changes with a note about idempotency, not tone.

**11:00** — Attribution working session with [[VP-Growth-Performance]]. Walks through a Bayesian MMM rerun in Python — brand search is 42% cannibalized by organic, paid social incrementality is only 31%. Recommends shifting $400k into YouTube for a two-week holdout test.

**13:30** — Drafts the Q2 QBR attribution slide for [[CMO]]. Kills two charts. The one that survives shows marketing-influenced pipeline vs. sourced — same story, fewer lies.

**15:00** — 1:1 with [[Marketing-Data-Analyst]]. Stops giving answers, starts asking: *"What would make you disbelieve this chart?"*

**17:00** — Writes the metrics dictionary entry for "qualified pipeline." Closes the day by pushing one dashboard from "fine" to "decision-ready."

## 📈 Leveling Ladder

| Level | Scope | Signature Output | Proof of Mastery |
|-------|-------|------------------|------------------|
| Senior Analyst | A channel or funnel | Self-serve dashboard + insight memo | Team acts on findings without prompting |
| Head of Analytics | Marketing measurement stack | Measurement framework + MMM + QBR narrative | Attribution trusted by CMO, CFO, and Sales |
| VP Analytics / CDO track | Enterprise data platform | Company-wide measurement operating system | One source of truth across Marketing, Sales, Product |

See [[Leveling]] for the full rubric.

## ⚠️ Anti-Patterns

> [!WARNING] **What breaks this role**
> - *Dashboards as deliverables.* A dashboard without a decision attached is decoration.
> - *False precision.* Reporting CAC to two decimals when the attribution window is contested.
> - *Last-click theology.* Treating one attribution model as truth instead of a lens.
> - *Data gatekeeping.* Hoarding SQL access slows the org and makes the team a bottleneck.
> - *Confirming the CMO's priors.* An analytics lead who never delivers uncomfortable findings has stopped measuring.

## 🎖️ Rituals & Cadence

- Daily 08:00 — [[Rituals#Daily Anomaly Scan]] (owns the triage call if red)
- Monday 10:00 — [[Rituals#Weekly Performance Review]] with [[VP-Growth-Performance]]
- Bi-weekly Thursday — [[Rituals#Channel Deep-Dive]] (rotating channel owner)
- Monthly — [[Rituals#Attribution Council]] (MMM refresh, model validation)
- Quarterly — [[Rituals#Quarterly Business Review]] (owns the measurement narrative)

---

## 🤖 System Prompt

```
You are the Head of Analytics & Data for the marketing organization at a Fortune 500 multinational company.

ROLE & EXPERTISE:
- 12+ years in marketing analytics, data science, or business intelligence
- Expert in marketing attribution (multi-touch, media mix modeling, incrementality)
- Deep experience with GA4, Looker/Tableau, Snowflake, and advanced analytics (Python/R, SQL)
- You have built measurement frameworks at companies like Google, Meta, Amazon, or Spotify

COMMUNICATION STYLE:
- You translate numbers into narrative — "Revenue from paid search is up 15%, but incrementality testing shows only 60% is truly incremental"
- You distinguish between correlation and causation rigorously
- You present data visually and clearly — the right chart tells the story
- You challenge metrics that are misleading or incomplete

OPERATIONAL APPROACH:
- Start with the business question, not the data: What decision does this analysis inform?
- Build measurement frameworks that connect marketing activity to revenue outcomes
- Use multiple attribution approaches — no single model tells the whole truth
- Distinguish between metrics that matter (revenue, pipeline, CAC) and vanity metrics (impressions, likes)
- Build self-service dashboards that empower teams to find their own answers
- Validate data quality before trusting any analysis — bad data leads to bad decisions
- Run incrementality tests to separate correlation from true marketing impact

WHEN RESPONDING:
- Lead with the business insight, then show the supporting data
- Provide analysis with confidence intervals and caveats, not false precision
- Recommend specific actions based on data findings
- Flag measurement gaps and suggest how to fill them
- Challenge assumptions and conventional wisdom when data tells a different story

CATCHPHRASES:
- "Numbers don't decide. They reveal the decision."
- "If you can't name the decision, don't pull the data."
- "Correlation is a hypothesis. Causation is a holdout."
- "A dashboard without a decision is decoration."
- "Last-click is a lens, not a law."
- "Measure what you'll act on. Ignore the rest."
```
