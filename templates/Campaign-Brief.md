# 📄 Template: Campaign Brief

> [!QUOTE] **The Creed of the Brief**
> *A campaign without a brief is a rumor in motion. Write the brief, or don't write the check.*

---

**Owner role:** [[Product-Marketing-Manager]] · [[Brand-Manager]] · [[Head-Digital-Marketing]]
**Used in workflow:** [[Workflows#Campaign Launch]]
**Review cadence:** Draft → Strategy lock (T-14) → Creative kickoff (T-10) → Go/no-go (T-1)

---

## 🧭 How to use this template

- Open this file the moment a campaign is *requested*, not the moment it is *scheduled*. No brief, no kickoff.
- The requester fills Section 1–4. [[Head-Digital-Marketing]] fills Section 5–7. [[Creative-Director]] reads before accepting.
- Approval path: [[Product-Marketing-Manager]] drafts → [[Head-Digital-Marketing]] signs on strategy → [[VP-Growth-Performance]] signs on budget → [[VP-Brand-Strategy]] signs on creative frame.
- A "done" brief fits on one scroll, has one success metric, names one accountable owner, and has zero TBDs in red.
- If any field below is still a `<!-- guidance -->` comment at the go/no-go, the campaign slips. No exceptions.

---

## 1. Campaign identity

- **Campaign name:** <!-- guidance: internal codename + external name if different, e.g. "Q3-Compound / Compound Your Category" -->
- **Campaign type:** <!-- guidance: Acquisition / Brand / Retention / Launch-support / ABM -->
- **Requesting team:** <!-- guidance: Product Marketing, Brand, Demand Gen, etc. -->
- **Date brief submitted:** <!-- guidance: YYYY-MM-DD -->

## 2. Objective & success metric

- **Business objective (one sentence):** <!-- guidance: what business outcome this campaign moves, e.g. "Drive mid-market pipeline in NAMER ahead of Q4 sales push." -->
- **Primary KPI:** <!-- guidance: link to a single metric in KPIs, e.g. [[KPIs#Acquisition]] — MQLs -->
- **Target value:** <!-- guidance: absolute number + baseline, e.g. "3,800 MQLs (vs 2,600 trailing 90-day avg)" -->
- **Secondary KPIs (max 2):** <!-- guidance: e.g. [[KPIs#Digital Performance]] — ROAS >4.0x; [[KPIs#Brand]] — +2pp aided awareness in target segment -->
- **Guardrail metrics (don't regress):** <!-- guidance: e.g. CAC <$2,400, unsubscribe rate <0.3% -->

## 3. Audience / ICP

- **Primary ICP:** <!-- guidance: firmographic + role, e.g. "B2B SaaS companies, 200–1,000 FTE, VP Marketing / CMO, NAMER + UK" -->
- **Buying stage:** <!-- guidance: Unaware / Problem-aware / Solution-aware / Vendor-aware / Decision -->
- **Insight powering the campaign:** <!-- guidance: the one human truth the creative will hinge on -->
- **Exclusions / suppressions:** <!-- guidance: existing customers? competitor employees? regions? -->

## 4. Offer & message

- **Core message (≤12 words):** <!-- guidance: the one line the audience should remember -->
- **Proof points (3 max):** <!-- guidance: stats, case studies, product capabilities — link to DAM assets -->
- **CTA:** <!-- guidance: "Book a demo" / "Download the report" / "Start free trial" — one primary CTA, max -->
- **Offer / hook:** <!-- guidance: gated asset, event, discount, waitlist, etc. -->

## 5. Channel mix & budget

| Channel | Owner | Budget | % of total | Target CPA/CPL |
|---------|-------|--------|-----------|----------------|
| <!-- Meta paid --> | [[Paid-Media-Manager]] | $<!-- --> | <!-- % --> | $<!-- --> |
| <!-- Google Search --> | [[Paid-Media-Manager]] | $<!-- --> | <!-- % --> | $<!-- --> |
| <!-- LinkedIn --> | [[Paid-Media-Manager]] | $<!-- --> | <!-- % --> | $<!-- --> |
| <!-- Email nurture --> | [[Email-Marketing-Manager]] | $<!-- --> | <!-- % --> | $<!-- --> |
| <!-- Organic social --> | [[Social-Media-Manager]] | $<!-- --> | <!-- % --> | n/a |
| **Total** | | $<!-- --> | 100% | blended $<!-- --> |

- **UTM schema:** <!-- guidance: utm_source / utm_medium / utm_campaign convention, e.g. src={channel}_mkt_campaign={codename}_variant={v1..vN} -->
- **Tracking owner:** [[Marketing-Ops-Manager]]

## 6. Timeline & key dates

| Milestone | Date | Owner |
|-----------|------|-------|
| Brief approved | <!-- T-28 --> | [[Head-Digital-Marketing]] |
| Creative kickoff | <!-- T-21 --> | [[Creative-Director]] |
| Creative v1 review | <!-- T-14 --> | [[VP-Brand-Strategy]] |
| Build + QA complete | <!-- T-5 --> | [[Marketing-Ops-Manager]] |
| Go / no-go | <!-- T-1 --> | [[VP-Growth-Performance]] |
| Launch | <!-- T --> | [[Paid-Media-Manager]] |
| Mid-flight review | <!-- T+7 --> | [[Marketing-Data-Analyst]] |
| Post-mortem | <!-- T+30 --> | [[Head-Analytics-Data]] |

## 7. Dependencies & risks

- **Cross-team dependencies:** <!-- guidance: Sales enablement deck? Product feature flag? Legal review? -->
- **Creative assets required:** <!-- guidance: hero video, static ad set (5x formats), landing page, email x3 — reference [[Creative-Brief]] -->
- **Known risks:** <!-- guidance: e.g. holiday blackout overlap, pricing change in-flight, competitor launch rumor -->
- **Kill-switch criteria:** <!-- guidance: "If CPL >$120 by T+5, pause LinkedIn and reallocate to Meta" -->

## 8. Approver sign-off

- **Strategy approver:** [[Head-Digital-Marketing]] — see [[Decisions#Campaign Launch]]
- **Budget approver:** [[VP-Growth-Performance]]
- **Creative approver:** [[VP-Brand-Strategy]]
- **Final go/no-go:** [[VP-Growth-Performance]], escalation to [[CMO]]

---

## ⚠️ Common mistakes

> [!WARNING] **How this brief gets wasted**
> - *Two primary KPIs.* You now have zero. Pick one.
> - *Audience described as "everyone who would benefit".* That's not an audience, that's a wishlist.
> - *Budget allocated before the channel hypothesis.* Money should follow the message, not the media rep.
> - *No kill-switch.* The campaign runs past the red line because no human has authority to stop it.
> - *Brief edited after launch to match results.* See [[Manifesto]] Article IV. Don't.

---

## ✅ Example: "filled-in" version

- **Campaign name:** Q3-Compound / "Compound Your Category"
- **Campaign type:** Acquisition (mid-market)
- **Requesting team:** Product Marketing · submitted 2026-06-03

**Objective:** Drive 3,800 mid-market MQLs in NAMER + UK ahead of Q4 sales push.
**Primary KPI:** [[KPIs#Acquisition]] — MQLs. Target **3,800** (vs 2,600 trailing-90 baseline).
**Secondary:** ROAS >4.0x; +2pp aided awareness in target ICP.
**Guardrail:** blended CPL <$85; unsubscribe <0.3%.

**ICP:** B2B SaaS, 200–1,000 FTE, VP Mktg / CMO, NAMER + UK. Stage: problem-aware.
**Insight:** "Our buyers have a brand-vs-performance war inside their own org — they need ammunition, not a pitch."
**Exclusions:** existing customers, competitors, sub-50 FTE.

**Core message:** *"Brand is the interest rate. Performance is the principal."*
**Proof:** (1) Forrester TEI 412% ROI; (2) Aurora case study 3.4x pipeline; (3) Category report download.
**CTA:** Download the 2026 Compound Report (gated).

| Channel | Owner | Budget | % | CPL |
|---------|-------|--------|---|-----|
| Meta paid | [[Paid-Media-Manager]] | $420k | 35% | $70 |
| LinkedIn | [[Paid-Media-Manager]] | $480k | 40% | $95 |
| Google Search | [[Paid-Media-Manager]] | $180k | 15% | $60 |
| Email nurture | [[Email-Marketing-Manager]] | $40k | 3% | $25 |
| Organic social | [[Social-Media-Manager]] | $80k | 7% | n/a |
| **Total** | | **$1.2M** | 100% | blended **$82** |

UTM: `src={channel}_mkt_campaign=q3compound_variant={v1..v4}`
Launch T = 2026-08-05. Go/no-go 2026-08-04 with [[VP-Growth-Performance]].
Kill switch: LinkedIn pauses if CPL >$130 by T+5; budget reflows to Meta retargeting.

---

## 🔗 Related

- Roles: [[Product-Marketing-Manager]], [[Brand-Manager]], [[Head-Digital-Marketing]], [[Paid-Media-Manager]], [[Creative-Director]]
- Workflow: [[Workflows#Campaign Launch]]
- Templates: [[Creative-Brief]], [[Email-Nurture-Sequence]], [[CRO-Test-Roadmap]], [[Post-Mortem]]
- KPIs: [[KPIs#Acquisition]], [[KPIs#Digital Performance]]
