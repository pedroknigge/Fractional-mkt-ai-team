# 📄 Template: Crisis Response Statement

> [!QUOTE] **The Creed of the Crisis**
> *Silence is a statement. Make sure the one you make is the one you mean.*

---

**Owner role:** [[PR-Communications-Director]]
**Used in workflow:** [[Workflows#Crisis Communications]]
**Review cadence:** Draft within response SLA → Approver sign-off → Issue → Monitor 24/48h → Debrief

---

## 🧭 How to use this template

- Open the moment severity is assessed (see [[Workflows#Crisis Communications]] severity table). Do not wait for "more information."
- [[PR-Communications-Director]] drafts; [[Senior-Copywriter]] tightens language; Legal reviews claims; severity-based approver signs.
- Approval path (by severity): P1 → [[CMO]] · P2 → [[VP-Brand-Strategy]] · P3 → [[PR-Communications-Director]] · P4 → [[Community-Manager]].
- "Done" statement: facts verified, accountability owned, action named with a date, channels sequenced, spokesperson named.
- If the statement contains the phrase "we take this seriously" without a specific action and date, it is not done.

---

## 1. Incident identity

- **Incident codename (internal only):** <!-- guidance: neutral, not spicy, e.g. "Pixel-Leak-042" -->
- **Severity:** <!-- guidance: P1 / P2 / P3 / P4 per [[Workflows#Crisis Communications]] -->
- **Detected:** <!-- YYYY-MM-DD HH:MM tz -->
- **Detected by:** <!-- [[Community-Manager]] / [[Social-Media-Manager]] / external -->
- **Response SLA:** <!-- guidance: 1h / 4h / 24h / 48h based on severity -->
- **Approver:** <!-- severity-based, see above -->

## 2. Facts on the table

- **What happened (one paragraph, verified):** <!-- guidance: only facts that two independent sources have confirmed — flag any unverified with [UNVERIFIED] -->
- **Who is affected:** <!-- guidance: customers, employees, partners, public — scope as tight as truth allows -->
- **What is not true (rumors to correct):** <!-- guidance: false claims circulating publicly -->
- **What we do not yet know:** <!-- guidance: name the gaps explicitly — refusing to acknowledge unknowns looks like evasion -->
- **Legal + regulatory exposure:** <!-- guidance: GDPR, SEC, FTC, state AG — flag so Legal stays in the loop -->

## 3. Audience map

| Audience | Channel | Owner | Statement variant |
|----------|---------|-------|-------------------|
| Affected customers | direct email | [[Email-Marketing-Manager]] | detailed + remediation |
| Broader customer base | in-app + email | [[Email-Marketing-Manager]] | summary + link |
| Press / media | press release + exec quote | [[PR-Communications-Director]] | on-the-record |
| Social followers | X, LinkedIn, IG | [[Social-Media-Director]] | short + link to long |
| Employees | internal email + all-hands | [[CMO]] | full context |
| Regulators (if applicable) | formal filing | Legal | legally-reviewed |
| Partners | account-manager outreach | Sales | tailored |

## 4. Public statement (drafted)

### Headline / opening line
<!-- guidance: state the fact + accountability in the first sentence. No adjectives. -->

### What happened
<!-- guidance: 2–3 sentences. Facts only. No blame-shifting. -->

### Who is affected, and how
<!-- guidance: specific scope. Numbers if known. -->

### What we are doing about it (with a date)
<!-- guidance: concrete, verifiable actions. Each action has an owner and a date. "We will do better" is not an action. -->

### How affected people can get help
<!-- guidance: specific contact: dedicated email, phone line, portal — staffed, not a black hole -->

### What we will do differently (the post-incident commitment)
<!-- guidance: one structural change, one date. No more. -->

### Signed
<!-- guidance: spokesperson by name + title — not "the company" -->

## 5. Holding statements (for fast-moving situations)

- **T+0 holding (≤30 min):** *"We are aware of [situation]. We are investigating urgently and will share a verified update by [TIME]."*
- **T+1 update (if no full statement yet):** *"Here's what we know, here's what we don't, and here's when we'll update next."*

## 6. Do-not-say list

- <!-- guidance: phrases that corrode trust or create legal exposure, e.g. "isolated incident" (before root-cause), "we take this seriously" (without an action), "no comment," "our thoughts are with..." without action -->

## 7. Monitoring plan

- **Sentiment tracking:** [[Community-Manager]] + Brandwatch, every 1h for 24h post-issue
- **Social response ownership:** [[Social-Media-Director]] — approved response tree only, no ad-lib
- **Escalation trigger:** <!-- guidance: if top-tier publication picks up, or if sentiment drops >20pp — escalate to [[CMO]] -->
- **Next update window:** <!-- YYYY-MM-DD HH:MM -->

## 8. Debrief

- **Post-incident review:** [[Post-Mortem]] within 10 business days, owned by [[PR-Communications-Director]]
- **Structural change committed:** <!-- guidance: what gets fixed, by whom, by when -->

---

## ⚠️ Common mistakes

> [!WARNING] **How statements make the crisis worse**
> - *"We take this seriously."* Without an action and a date, this phrase is an admission that you don't.
> - *Lawyering the humanity out.* A technically-correct statement that reads as cold will outlast the facts on social.
> - *Silence as strategy.* 12 hours without a statement reads as guilt — even if it's just "we're investigating."
> - *One statement for all audiences.* Customers, press, and employees need different facts in different order.
> - *Apology without structural change.* Statement ships; nothing changes; the next incident is the same incident.

---

## ✅ Example: "filled-in" version

- **Codename:** Pixel-Leak-042 · **Severity:** P2 · **Detected:** 2026-03-14 08:17 PT by [[Community-Manager]] (viral X thread from a security researcher) · **SLA:** 4h · **Approver:** [[VP-Brand-Strategy]]

**Facts:** A GTM tag misconfiguration caused a third-party analytics pixel to capture form-submit payloads from `/contact` between 2026-03-07 and 2026-03-13. Payloads included name, email, company. No passwords, payment info, or SSNs. ~1,840 records.
**Not true:** Rumors of "credit card data exposure" — incorrect. **Unknown:** whether the third-party vendor persisted the data — vendor audit in progress.
**Legal:** GDPR notification required (183 EU records); 72h clock started 2026-03-13.

**Audience map:** affected 1,840 via direct email (EMM) · broader list in weekly digest · press via release + [[CMO]] quote · social via @brand + LinkedIn · employees via all-hands Friday.

**Public statement (excerpt):**

> On March 13, we discovered that a misconfigured analytics tag on our contact form captured form submissions for seven days. Names, email addresses, and company names of 1,840 people were shared with a third-party analytics vendor without authorization. No passwords, payment information, or government IDs were involved.
>
> We have removed the tag, begun an independent audit of the vendor's data handling, and are contacting every affected person directly today with specific details about their record. If you're affected, we've set up a dedicated address at privacy-042@brand.com, monitored by a named team, with a 24-hour response SLA through March 21.
>
> What we will change: every new third-party tag will now require dual sign-off from [[Marketing-Ops-Manager]] and our Security team, effective March 20, 2026. Our full post-incident review will be published within 10 business days.
>
> — Priya Ramanujan, VP Brand Strategy

**Holding issued 2026-03-14 08:52 PT.** Full statement approved by [[VP-Brand-Strategy]] + Legal 2026-03-14 12:14 PT, issued 12:30.

**Monitoring:** Brandwatch hourly 24h; sentiment dropped 14pp then recovered 8pp by T+18h. Top-tier pickup: one trade pub, neutral tone.

**Do-not-say enforced:** no "isolated incident," no "we take this seriously" without action.

**Debrief:** [[Post-Mortem]] scheduled 2026-03-26, owner [[PR-Communications-Director]]. Structural change: tag governance, [[Marketing-Ops-Manager]], effective 2026-03-20.

---

## 🔗 Related

- Roles: [[PR-Communications-Director]], [[CMO]], [[VP-Brand-Strategy]], [[Community-Manager]], [[Social-Media-Director]], [[Senior-Copywriter]]
- Workflow: [[Workflows#Crisis Communications]]
- Templates: [[Post-Mortem]]
- KPIs: [[KPIs#Brand]]
