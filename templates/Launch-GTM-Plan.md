# 📄 Template: Launch GTM Plan

> [!QUOTE] **The Creed of the Launch**
> *A launch is a promise you make to a market. Plan it like it's the last one you'll ever ship.*

---

**Owner role:** [[Product-Marketing-Manager]] · [[VP-Product-Marketing]]
**Used in workflow:** [[Workflows#Product Launch GTM]]
**Review cadence:** T-90 discovery lock → T-60 strategy lock → T-14 enablement freeze → T-1 go/no-go → T+30 debrief

---

## 🧭 How to use this template

- Opened at T-90. If you're opening it at T-45, you are not doing a launch — you are doing an announcement.
- [[Product-Marketing-Manager]] owns the doc; every workstream lead has an assigned section.
- Approval path: [[Product-Marketing-Manager]] drafts → [[VP-Product-Marketing]] signs each phase gate → [[CMO]] signs final go/no-go.
- "Done" version has named owners per row, dates per milestone, and a green/yellow/red status on every workstream by T-7.
- If a section says TBD after T-21, that workstream is at risk and escalates to [[VP-Product-Marketing]].

---

## 1. Launch identity

- **Product / feature name:** <!-- guidance: internal codename + external name -->
- **Launch tier:** <!-- guidance: Tier 1 (company-level) / Tier 2 (segment) / Tier 3 (feature-level) — determines budget + PR posture -->
- **Launch date (T):** <!-- YYYY-MM-DD -->
- **Launch type:** <!-- guidance: new product / new segment / new market / major feature / repositioning -->

## 2. Strategic frame

- **Business objective:** <!-- guidance: one sentence, tied to annual plan -->
- **Primary KPI & target:** <!-- guidance: e.g. 8,000 signups in 30d, link [[KPIs#Acquisition]] or [[KPIs#Revenue & ROI]] -->
- **Secondary KPIs:** <!-- guidance: activation rate, CAC, share-of-voice -->
- **Definition of success at T+30 / T+90:** <!-- guidance: specific numeric thresholds, not adjectives -->
- **What failure looks like:** <!-- guidance: the number below which we publicly acknowledge we missed -->

## 3. Positioning & messaging

- **Positioning statement:** <!-- guidance: "For [ICP] who [problem], [product] is the [category] that [differentiator], unlike [alternative], we [proof]." -->
- **Category frame:** <!-- guidance: are we entering, redefining, or exiting a category? -->
- **Message pillars (3, max):** <!-- guidance: each with 1 proof point -->
- **Competitive moves anticipated:** <!-- guidance: how the 2 closest competitors are likely to respond -->
- **Objection handling doc:** <!-- guidance: link to FAQ for sales / support -->

## 4. Audience & segmentation

- **Primary ICP:** <!-- guidance: firmographic + role -->
- **Beachhead segment for T-Day:** <!-- guidance: narrower slice for concentrated launch spike -->
- **Expansion segments (T+30, T+60):** <!-- guidance: second-wave targets -->
- **Suppressions:** <!-- guidance: segments explicitly excluded at launch -->

## 5. Phase plan

| Phase | Window | Owner | Key deliverables | Status |
|-------|--------|-------|------------------|--------|
| Discovery | T-90 → T-60 | [[Product-Marketing-Manager]] | research, competitive, positioning v1 | <!-- --> |
| Strategy | T-60 → T-45 | [[VP-Product-Marketing]] | messaging framework, channel mix, budget | <!-- --> |
| Creation | T-45 → T-14 | [[Creative-Director]] | assets, LPs, email, video | <!-- --> |
| Enablement | T-14 → T-7 | [[Product-Marketing-Manager]] | sales deck, FAQ, partner brief | <!-- --> |
| Pre-launch | T-7 → T-1 | [[PR-Communications-Director]] | teaser, analyst brief, influencer seed | <!-- --> |
| Launch | T | [[Head-Digital-Marketing]] | coordinated multi-channel fire | <!-- --> |
| Post-launch | T+1 → T+30 | [[Marketing-Data-Analyst]] | daily monitoring, pivot decisions | <!-- --> |

## 6. Channel plan & budget

| Channel | Owner | Budget | Role in launch |
|---------|-------|--------|----------------|
| PR / analyst | [[PR-Communications-Director]] | $<!-- --> | narrative anchor |
| Paid social | [[Paid-Media-Manager]] | $<!-- --> | reach spike |
| Paid search | [[Paid-Media-Manager]] | $<!-- --> | intent capture |
| Content + SEO | [[Content-Strategy-Director]] | $<!-- --> | compounding tail |
| Email | [[Email-Marketing-Manager]] | $<!-- --> | installed-base activation |
| Influencer | [[Influencer-Marketing-Manager]] | $<!-- --> | credibility + demo |
| Events | [[VP-Content-Social]] | $<!-- --> | demo + press |
| **Total** | | **$<!-- -->** | |

## 7. Enablement & internal comms

- **Sales enablement owner:** [[Product-Marketing-Manager]]
- **Deck + demo video due:** <!-- T-10 -->
- **Sales certification required:** <!-- guidance: yes/no; if yes, who runs the test -->
- **All-hands announcement:** <!-- guidance: date + speaker -->
- **Customer Success brief:** <!-- guidance: owner + date -->

## 8. Risk register

| Risk | Likelihood | Impact | Mitigation | Owner |
|------|------------|--------|------------|-------|
| <!-- competitor pre-announces --> | <!-- M --> | <!-- H --> | <!-- shift narrative to --> | [[VP-Product-Marketing]] |
| <!-- product not ready T-5 --> | <!-- L --> | <!-- H --> | <!-- slip gate owned by CMO --> | [[CMO]] |
| <!-- press embargo break --> | <!-- L --> | <!-- M --> | <!-- response template ready --> | [[PR-Communications-Director]] |

## 9. Go / no-go criteria (T-1)

- [ ] Product GA confirmed by Eng VP
- [ ] Sales enablement cert rate ≥90%
- [ ] All creative in DAM + QA'd
- [ ] Tracking + UTM verified by [[Marketing-Ops-Manager]]
- [ ] PR embargoes confirmed
- [ ] Support + CS playbooks live
- [ ] Kill-switch owner named: <!-- [[Head-Digital-Marketing]] -->

**Final go/no-go:** [[VP-Product-Marketing]] (A), [[CMO]] (escalation). See [[Decisions#Launch Go/No-Go]].

## 10. Post-launch plan

- **Daily standup cadence:** T → T+7 daily, T+8 → T+30 every MWF
- **Pivot triggers:** <!-- guidance: named numeric thresholds that force reallocation -->
- **Debrief:** [[Post-Mortem]] at T+30, owned by [[Product-Marketing-Manager]]

---

## ⚠️ Common mistakes

> [!WARNING] **How launches under-deliver**
> - *Launch date set before positioning locks.* Every asset rebuilt twice.
> - *Sales enablement as a deck, not a conversation.* AEs fumble week one; pipeline leaks.
> - *No post-launch owner.* Week one celebration, week two silence, month two quiet death.
> - *"Tier 1 everything" inflation.* Every launch is huge, so none of them are.
> - *Success criteria written in qualitative adjectives.* "Strong launch" is not a metric. See [[Manifesto]] Article IV.

---

## ✅ Example: "filled-in" version

- **Product:** "Aurora 2.0" — compounding analytics layer · **Tier 1** · T = 2026-09-15

**Objective:** Establish Aurora as the category-defining analytics layer for mid-market SaaS.
**Primary KPI:** 12,000 signups in 30 days ([[KPIs#Acquisition]]).
**Secondary:** activation ≥3.5%, CAC ≤$2,200, +3pp aided awareness in ICP.
**Failure line:** <7,000 signups at T+30 triggers a public "we missed, here's why" post from [[CMO]].

**Positioning:** *"For mid-market marketing teams who can't trust their attribution, Aurora is the analytics layer that compounds learning across every channel, unlike single-model tools — we run two models in parallel and show you the delta."*
**Category frame:** redefining "attribution" as "compounding analytics."
**Pillars:** (1) Two-model truth; (2) Compounding learning; (3) CFO-ready reporting.
**Competitors anticipated:** Incumbent A will price-drop within 14 days; Incumbent B will accuse "complexity."

**Beachhead:** 200–1,000 FTE B2B SaaS, NAMER, CMO-led buying committee.

**Phases:** Discovery 2026-06-15 → 2026-07-15 · Strategy → 2026-07-31 · Creation → 2026-09-01 · Enablement → 2026-09-08 · Pre-launch → 2026-09-14 · Launch 2026-09-15 · Post +30 to 2026-10-15.

**Budget:** $2.4M total — PR $180k, paid social $680k, paid search $420k, content/SEO $260k, email $60k, influencer $300k, events $500k.

**Enablement:** deck 2026-09-01, cert required, 92% pass rate achieved by 2026-09-10. All-hands 2026-09-14 led by [[CMO]].

**Top risks:** (1) Incumbent A price drop (M/H, mitigation: pre-built rebuttal in sales deck, [[VP-Product-Marketing]]); (2) analytics pipeline not GA (L/H, [[CMO]] holds slip gate); (3) embargo break with TechCrunch (L/M, response template, [[PR-Communications-Director]]).

**Go/no-go** passed 2026-09-14 19:00 PT by [[VP-Product-Marketing]], [[CMO]] confirmed.

Post-launch: T+7 review 2026-09-22; [[Post-Mortem]] 2026-10-15.

---

## 🔗 Related

- Roles: [[Product-Marketing-Manager]], [[VP-Product-Marketing]], [[CMO]], [[Creative-Director]], [[PR-Communications-Director]], [[Head-Digital-Marketing]]
- Workflow: [[Workflows#Product Launch GTM]]
- Templates: [[Campaign-Brief]], [[Creative-Brief]], [[Content-Brief]], [[Email-Nurture-Sequence]], [[Post-Mortem]], [[Quarterly-Business-Review]]
- KPIs: [[KPIs#Acquisition]], [[KPIs#Brand]], [[KPIs#Revenue & ROI]]
