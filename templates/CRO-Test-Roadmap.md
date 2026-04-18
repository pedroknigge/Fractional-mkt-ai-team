# 📄 Template: CRO Test Roadmap

> [!QUOTE] **The Creed of the Experiment**
> *A test without a hypothesis is a guess with a logo on it.*

---

**Owner role:** [[Conversion-Rate-Optimizer]]
**Used in workflow:** [[Workflows#Campaign Launch]] · [[Workflows#Performance Review Cycle]]
**Review cadence:** Weekly backlog triage · Monthly readout · Quarterly win-rate audit

---

## 🧭 How to use this template

- This is a rolling quarterly doc. New ideas land in the backlog; prioritized tests move to the live roster.
- [[Conversion-Rate-Optimizer]] owns triage; [[Head-Digital-Marketing]] approves any test that changes the funnel.
- Approval path: hypothesis + ICE scored → [[Conversion-Rate-Optimizer]] prioritizes → [[Head-Digital-Marketing]] signs if test touches paid LP → [[Marketing-Data-Analyst]] verifies power + readout.
- "Done" roadmap: every live test has a hypothesis, a primary metric, an MDE, a runtime estimate, and a decision deadline.
- If a test has been "live but inconclusive" for 3x its planned runtime, kill it and document the learning. See [[Manifesto]] Article V.

---

## 1. Program fundamentals

- **Primary KPI:** [[KPIs#Digital Performance]] — site-wide conversion rate (target >3.5%)
- **Secondary KPIs:** lead quality, ROAS, time-on-page
- **Test velocity target:** <!-- guidance: tests/quarter, e.g. 12 -->
- **Win-rate target:** <!-- guidance: % of tests producing statistically significant wins, e.g. 25–30% -->
- **Statistical standard:** <!-- guidance: 95% confidence, 80% power, two-tailed -->
- **Tool:** <!-- guidance: Optimizely / VWO / Convert / in-house -->

## 2. Hypothesis backlog

<!-- guidance: new ideas land here; score with ICE before moving to roster -->

| ID | Hypothesis | Surface | Primary metric | Impact (1–10) | Confidence (1–10) | Ease (1–10) | ICE | Status |
|----|------------|---------|----------------|---------------|-------------------|-------------|-----|--------|
| <!-- T-042 --> | <!-- If we replace hero video with a 15s demo loop, then demo-clicks will rise because video drives intent faster than text --> | <!-- homepage --> | <!-- demo-click rate --> | <!-- 8 --> | <!-- 6 --> | <!-- 7 --> | <!-- 7.0 --> | <!-- queued --> |

## 3. Live test roster

<!-- guidance: currently in-market; max 4 simultaneous to avoid interaction effects -->

### Test ID: <!-- T-NNN -->

- **Hypothesis (if/then/because):** <!-- guidance: full sentence, testable -->
- **Surface:** <!-- guidance: exact URL / page / email -->
- **Variants:** <!-- guidance: Control + V1 (+ V2 if needed, max 3 arms) -->
- **Primary metric:** <!-- guidance: single conversion event -->
- **Guardrails:** <!-- guidance: secondary metrics that cannot regress >X% -->
- **MDE (minimum detectable effect):** <!-- guidance: e.g. +8% relative lift -->
- **Baseline rate:** <!-- guidance: current conversion rate, last 30 days -->
- **Required sample size / runtime:** <!-- guidance: calculator output, e.g. 22,400 sessions / 14 days -->
- **Traffic allocation:** <!-- guidance: 50/50 or split -->
- **Segments monitored:** <!-- guidance: device, source, geo -->
- **Start / end date:** <!-- --> / <!-- -->
- **Decision deadline:** <!-- guidance: when we call it regardless of significance -->
- **Owner:** [[Conversion-Rate-Optimizer]]

## 4. Completed tests (this quarter)

| ID | Hypothesis (short) | Result | Lift | Significance | Shipped? | Learning |
|----|--------------------|--------|------|--------------|----------|----------|
| <!-- T-041 --> | <!-- Sticky CTA bar --> | <!-- Win --> | <!-- +11% --> | <!-- 97% --> | <!-- Yes --> | <!-- scroll-depth trigger matters more than label --> |

## 5. Learnings library

<!-- guidance: principles extracted from tests; lives longer than any single experiment -->

- **What works on our audience:** <!-- e.g. specificity of numbers beats claims of superiority -->
- **What doesn't:** <!-- e.g. social proof logos above fold — three quarters of negative results -->
- **Segment quirks:** <!-- e.g. mobile users convert 2x better with a single CTA above fold; desktop prefers two -->

## 6. Dependencies & risks

- **Engineering dependencies:** <!-- guidance: dev time for surfaces not editable in CMS -->
- **Tracking dependencies:** <!-- guidance: [[Marketing-Ops-Manager]] tag QA before any test launches -->
- **Risks:** <!-- guidance: test collisions, seasonal confound, underpowered runs -->

## 7. Approver sign-off

- **Roadmap:** [[Conversion-Rate-Optimizer]]
- **Paid-LP changes:** [[Head-Digital-Marketing]] — see [[Decisions#CRO Test Launch]]
- **Measurement sign-off:** [[Marketing-Data-Analyst]]

---

## ⚠️ Common mistakes

> [!WARNING] **How CRO programs go flat**
> - *Testing without a hypothesis.* "Let's try a different button color" is not CRO, it's decoration.
> - *Calling wins too early.* 87% significance at day 5 is not significance. Hold the line.
> - *No guardrails.* CTR up, lead quality down, pipeline down. Vanity win.
> - *Too many tests at once.* Interaction effects make every result uninterpretable.
> - *Killed test = forgotten test.* Every test — win, loss, or null — produces a learning. Write it down.

---

## ✅ Example: "filled-in" version

**Program:** Q2 2026 CRO Roadmap · target 12 tests, 28% win rate.
**Tool:** Optimizely. Stats: 95% / 80% / two-tailed.

**Backlog (top 3 scored):**

| ID | Hypothesis | Surface | Metric | I | C | E | ICE |
|----|------------|---------|--------|---|---|---|-----|
| T-042 | If we swap the hero video for a 15s demo loop, then demo-clicks rise +10% because video drives intent faster than text | homepage | demo-click rate | 8 | 6 | 7 | 7.0 |
| T-043 | If we move pricing to above-the-fold on /pricing, then signup rate rises +8% because intent users currently bounce before scrolling | /pricing | signup rate | 7 | 7 | 9 | 7.7 |
| T-044 | If we add a "what you'll see in the demo" outline, then demo-show rate rises +12% because uncertainty is the #1 no-show driver | /demo confirm | demo-show rate | 9 | 7 | 8 | 8.0 |

**Live test T-044:**
- Hypothesis: If we add a "what you'll see in the demo" outline on the confirmation page, then demo-show rate rises because uncertainty drives no-shows.
- Surface: `/demo/confirmation`. Variants: Control vs V1 (outline block + host photo).
- Primary: demo-show rate. Guardrail: demo-book rate must not drop >5%.
- Baseline: 62% show rate. MDE: +5pp absolute.
- Sample: 1,800 bookings / ~18 days. Traffic 50/50. Start 2026-04-07 / decision 2026-04-28.
- Owner: [[Conversion-Rate-Optimizer]].

**Completed Q2 so far:**

| ID | Hypothesis | Result | Lift | Sig | Shipped | Learning |
|----|------------|--------|------|-----|---------|----------|
| T-041 | Sticky CTA bar on blog | Win | +11% demo-click | 97% | Yes | Trigger at 40% scroll outperforms always-on |
| T-040 | Social-proof logo bar above fold | Null | +0.4% | 62% | No | Not our audience — specificity beats logos |
| T-039 | Free-trial vs demo on hero | Loss | -6% | 95% | No | Our ICP wants hand-holding, not self-serve |

**Learnings:** specificity of numbers > claims of superiority; mobile = single CTA above fold; logos don't move our ICP.
**Approver:** [[Conversion-Rate-Optimizer]] · paid-LP changes [[Head-Digital-Marketing]] · measurement [[Marketing-Data-Analyst]].

---

## 🔗 Related

- Roles: [[Conversion-Rate-Optimizer]], [[Head-Digital-Marketing]], [[Marketing-Data-Analyst]], [[Marketing-Ops-Manager]]
- Workflow: [[Workflows#Campaign Launch]], [[Workflows#Performance Review Cycle]]
- Templates: [[Campaign-Brief]], [[Email-Nurture-Sequence]], [[Post-Mortem]]
- KPIs: [[KPIs#Digital Performance]], [[KPIs#Acquisition]]
