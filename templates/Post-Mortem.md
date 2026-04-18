# 📄 Template: Post-Mortem

> [!QUOTE] **The Creed of the Retro**
> *A campaign that isn't written down cannot be repeated, improved, or taught. The learning is the asset.*

---

**Owner role:** Any team after a campaign / launch / incident — facilitated by the workstream lead
**Used in workflow:** [[Rituals#Retro]] · [[Workflows#Campaign Launch]] · [[Workflows#Product Launch GTM]] · [[Workflows#Crisis Communications]]
**Review cadence:** Within 10 business days of campaign close, launch T+30, or incident closure

---

## 🧭 How to use this template

- Open within 10 business days. A post-mortem delayed past 30 days returns 20% of the learning.
- Workstream lead facilitates; [[Head-Analytics-Data]] brings the numbers; every participant writes their section before the meeting.
- Approval path: draft → participants review → publish to knowledge base → linked from the originating [[Campaign-Brief]] / [[Launch-GTM-Plan]] / [[Crisis-Response-Statement]].
- "Done" post-mortem: facts separated from opinions, 3 keep / 3 change / 3 kill decisions, every action item has an owner + date.
- Blameless on people. Ruthless on systems. If a section reads as finger-pointing, rewrite it.

---

## 1. Post-mortem identity

- **Initiative type:** <!-- guidance: campaign / product launch / crisis / experiment / event -->
- **Initiative name:** <!-- guidance: link to upstream brief or plan -->
- **Dates:** <!-- guidance: start → end -->
- **Facilitator:** <!-- guidance: workstream lead -->
- **Participants:** <!-- guidance: list everyone material — wikilink roles -->
- **Date of post-mortem:** <!-- YYYY-MM-DD -->

## 2. What we set out to do

- **Original objective:** <!-- guidance: one sentence from the brief -->
- **Primary KPI + target:** <!-- guidance: from brief, no revisionism -->
- **Secondary KPIs:** <!-- guidance: from brief -->
- **Success definition:** <!-- guidance: what "win" looked like at the outset -->

## 3. What actually happened

- **Primary KPI actual vs target:** <!-- guidance: number + variance -->
- **Secondary KPIs:** <!-- guidance: numbers + variances -->
- **Timeline: plan vs actual:** <!-- guidance: milestone slippage / compression -->
- **Budget: plan vs actual:** <!-- guidance: $ variance by line -->
- **Unplanned events:** <!-- guidance: pivots, outages, competitor moves, surprises -->

## 4. Facts (not opinions)

<!-- guidance: verified events in chronological order. Each row is a fact with a timestamp and a source. Opinions go in Section 6. -->

| Date | Event | Source | Impact |
|------|-------|--------|--------|
| <!-- --> | <!-- --> | <!-- dashboard / Slack / ticket --> | <!-- --> |

## 5. Five whys (root cause, per key outcome)

<!-- guidance: apply to 1–3 most significant outcomes (positive or negative). Stay systemic, not personal. -->

**Outcome:** <!-- -->
- Why 1: <!-- -->
- Why 2: <!-- -->
- Why 3: <!-- -->
- Why 4: <!-- -->
- Why 5: <!-- root systemic cause -->

## 6. What worked

<!-- guidance: max 3, each with the mechanism — why it worked, not just that it did -->

- <!-- -->
- <!-- -->
- <!-- -->

## 7. What didn't

<!-- guidance: max 3, each traced to a system failure, not a person -->

- <!-- -->
- <!-- -->
- <!-- -->

## 8. What surprised us

<!-- guidance: unexpected signals — often the highest-value learnings -->

- <!-- -->
- <!-- -->

## 9. Decisions (keep / change / kill)

| Category | Action | Rationale | Owner | Due |
|----------|--------|-----------|-------|-----|
| **Keep** | <!-- --> | <!-- --> | <!-- --> | <!-- ongoing --> |
| **Keep** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Keep** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Change** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Change** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Change** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Kill** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Kill** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |
| **Kill** | <!-- --> | <!-- --> | <!-- --> | <!-- --> |

## 10. Systemic fixes (workflow, template, playbook)

<!-- guidance: this is where one-time learnings become permanent upgrades. Link to the artifact being changed. -->

- <!-- Update [[Workflows#Campaign Launch]] RACI to add kill-switch owner row -->
- <!-- Update [[Campaign-Brief]] template to require UTM schema pre-approval -->
- <!-- Add to [[Manifesto]] creed library --> — only if the learning is enduring

## 11. Teach-forward

- **What we will share broadly:** <!-- guidance: short writeup for all-hands or newsletter -->
- **What stays internal:** <!-- guidance: competitive intel, legal-sensitive -->
- **Teammate who should teach this lesson next time:** <!-- -->

## 12. Approver sign-off

- **Document owner:** <!-- facilitator -->
- **Review:** all participants + workstream VP
- **Published to:** knowledge base + linked from source brief — see [[Decisions#Post-Mortem Actions]]

---

## ⚠️ Common mistakes

> [!WARNING] **How post-mortems fail to compound**
> - *Blame the person, not the system.* The individual leaves, the bug stays.
> - *Three nice-to-haves instead of three decisions.* "We should probably…" — no owner, no date, no change.
> - *Revisionist targets.* Rewriting the objective to match the outcome kills the entire learning loop.
> - *Facts and opinions intermingled.* Makes every claim arguable; nothing gets decided.
> - *Published and forgotten.* If it isn't linked from the template you'd use next time, it doesn't exist.

---

## ✅ Example: "filled-in" version

- **Initiative:** Campaign — Q3-Compound · **Dates:** 2026-08-05 → 2026-09-15 · **Facilitator:** [[Head-Digital-Marketing]] · **Participants:** [[Product-Marketing-Manager]], [[Paid-Media-Manager]], [[Creative-Director]], [[Email-Marketing-Manager]], [[Marketing-Data-Analyst]] · **Date:** 2026-09-22

**Set out to do:** Drive 3,800 mid-market MQLs in NAMER+UK. Secondary: ROAS >4.0x, +2pp aided awareness.

**Actual:** 4,240 MQLs (+11.6%), ROAS 4.3x (+7.5%), aided awareness +1.4pp (-0.6pp vs target). Budget: $1.2M planned / $1.24M actual (+3.3%). Unplanned: Incumbent A launched a competing category report 2026-08-12, forcing a creative pivot on LinkedIn by 2026-08-18.

**Facts (excerpt):**

| Date | Event | Source | Impact |
|------|-------|--------|--------|
| 2026-08-12 | Incumbent A report launched | LinkedIn signal | +18% CPL on our LinkedIn carousel |
| 2026-08-18 | Creative v2 live (pivoted hero) | Ad platform | CPL normalized within 72h |
| 2026-08-29 | Email sequence 3 outperformed 2 by 2.1x CTOR | ESP | Reordered for remaining enrollees |

**Five whys — aided awareness miss:**
- Why 1: OOH flight cut from 3 cities to 1. → Why 2: budget reallocated mid-flight to Meta. → Why 3: LinkedIn CPL spike triggered reflow. → Why 4: brand-vs-performance budget not ring-fenced. → Why 5: **systemic — our brief template allows reallocation without a brand guardrail. Fix in [[Campaign-Brief]].**

**Worked:** (1) Two-model POV resonated — 4.3x ROAS confirms thesis; (2) Email sequence reorder after mid-flight signal — +14% demo bookings; (3) Creative pivot within 6 days of competitor move — agility, not panic.

**Didn't:** (1) Brand awareness under-delivered due to unprotected OOH budget (see five-whys); (2) LinkedIn audience was still too broad at launch (same lesson as Q2 '25 — we did not apply it); (3) Post-campaign dashboard wasn't ready at T+7, slowed reallocation decisions by ~5 days.

**Surprised us:** Maya Writes Marketing's LinkedIn essay ([[Influencer-Partnership-Brief]]) drove more qualified MQLs per dollar than Meta retargeting. Next campaign will lead with creators, not chase them.

**Decisions:**

| | Action | Rationale | Owner | Due |
|-|--------|-----------|-------|-----|
| Keep | Two-model message architecture | 4.3x ROAS, strongest resonance in 4 qtrs | [[Product-Marketing-Manager]] | ongoing |
| Keep | Weekly mid-flight creative pivot meeting | enabled 72h response to competitor | [[Creative-Director]] | ongoing |
| Keep | Creator-led narrative entry | best CPL in the mix | [[Influencer-Marketing-Manager]] | ongoing |
| Change | Ring-fence brand/OOH budget in brief | prevent reflow into performance | [[Head-Digital-Marketing]] | [[Campaign-Brief]] v1.3, 2026-10-01 |
| Change | LinkedIn ICP filter at launch, not week 2 | repeat miss from Q2 '25 | [[Paid-Media-Manager]] | 2026-09-30 |
| Change | T+7 dashboard ready at T-1 | cut reallocation latency | [[Marketing-Data-Analyst]] | 2026-10-15 |
| Kill | "General SaaS" LinkedIn audience | 3x CPL of tight ICP | [[Paid-Media-Manager]] | immediate |
| Kill | Static-image LinkedIn carousel format | 40% lower ER vs video | [[Art-Director]] | immediate |
| Kill | Mid-funnel Meta interest-stack | LTV:CAC <2 three campaigns running | [[Paid-Media-Manager]] | 2026-09-30 |

**Systemic fixes:** update [[Campaign-Brief]] (brand ring-fence row); update [[Workflows#Campaign Launch]] RACI (add dashboard-readiness at T-1 to [[Marketing-Data-Analyst]]).

**Teach-forward:** Head-Digital-Marketing writes a 400-word all-hands note on "repeating misses we can't afford anymore." Maya's creator outperformance becomes a case study in [[Influencer-Partnership-Brief]] examples.

Approved by [[Head-Digital-Marketing]] + [[VP-Growth-Performance]] on 2026-09-23. Linked from Q3-Compound [[Campaign-Brief]].

---

## 🔗 Related

- Roles: workstream lead, [[Head-Analytics-Data]], [[CMO]], all participating managers
- Workflow: [[Rituals#Retro]], [[Workflows#Campaign Launch]], [[Workflows#Product Launch GTM]], [[Workflows#Crisis Communications]]
- Templates: [[Campaign-Brief]], [[Creative-Brief]], [[Content-Brief]], [[Launch-GTM-Plan]], [[Email-Nurture-Sequence]], [[CRO-Test-Roadmap]], [[Crisis-Response-Statement]], [[Influencer-Partnership-Brief]], [[Quarterly-Business-Review]]
- KPIs: [[KPIs]] (all sections as relevant)
