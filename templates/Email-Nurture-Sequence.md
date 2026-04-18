# 📄 Template: Email Nurture Sequence

> [!QUOTE] **The Creed of the Inbox**
> *An email is a door knock. Knock with intent, or don't knock.*

---

**Owner role:** [[Email-Marketing-Manager]]
**Used in workflow:** [[Workflows#Campaign Launch]] · [[Workflows#Content Pipeline]]
**Review cadence:** Sequence brief → Copy review (T-7) → Build + QA (T-3) → Activation → Per-send perf review

---

## 🧭 How to use this template

- Open when an entry condition (gated download, demo request, event signup, churn signal) exists and is measurable in the ESP.
- [[Email-Marketing-Manager]] owns the doc; [[Senior-Copywriter]] writes, [[Marketing-Ops-Manager]] builds triggers.
- Approval path: [[Email-Marketing-Manager]] → [[Content-Strategy-Director]] voice check → [[Brand-Manager]] visual check → activation.
- "Done" sequence: every email has a single goal, a subject A/B, a mobile-first render, and a measurable exit condition.
- If any email in the sequence has a generic subject line (e.g. "Just checking in"), stop and rewrite.

---

## 1. Sequence identity

- **Sequence name:** <!-- guidance: clear intent, e.g. "Attribution-Report Nurture / Q2-AR-N01" -->
- **Sequence type:** <!-- guidance: welcome / nurture / lead-qual / re-engage / post-purchase / win-back -->
- **Linked campaign / content:** <!-- guidance: [[Campaign-Brief]] or [[Content-Brief]] link -->
- **ESP tool:** <!-- guidance: HubSpot / Marketo / Iterable / Customer.io -->
- **Go-live date:** <!-- YYYY-MM-DD -->

## 2. Audience & entry

- **Entry trigger:** <!-- guidance: "Submitted form ID 1842 — Attribution Decision Tree download" -->
- **Segment filters:** <!-- guidance: ICP match = true; country in [US, CA, UK]; lifecycle stage = Lead -->
- **Suppressions:** <!-- guidance: existing customers; opted-out; in active sales cycle; competitor domains -->
- **Volume estimate:** <!-- guidance: expected enrollments/week -->

## 3. Sequence goal & metrics

- **Primary goal:** <!-- guidance: one action the sequence exists to drive — e.g. book a demo -->
- **Primary KPI:** <!-- guidance: MQL conversion rate from sequence (target %), link [[KPIs#Email]] -->
- **Per-send targets:** <!-- guidance: open rate >35%, CTOR >12%, unsub <0.3% -->
- **Exit conditions (positive):** <!-- guidance: demo booked / opportunity created / content downloaded -->
- **Exit conditions (negative):** <!-- guidance: unsubscribe / bounce / 3 non-opens in a row -->

## 4. Sequence map

| # | Email | Delay | Goal | Subject A | Subject B | CTA | Success metric |
|---|-------|-------|------|-----------|-----------|-----|----------------|
| 1 | <!-- Welcome + asset delivery --> | 0h | deliver + set tone | <!-- --> | <!-- --> | open attachment | open >55% |
| 2 | <!-- Context + POV --> | +2d | reinforce thesis | <!-- --> | <!-- --> | read related piece | CTOR >15% |
| 3 | <!-- Proof / case study --> | +4d | credibility | <!-- --> | <!-- --> | read case | CTR >4% |
| 4 | <!-- Soft offer --> | +7d | micro-commit | <!-- --> | <!-- --> | 15-min consult | meetings booked |
| 5 | <!-- Hard offer / exit --> | +11d | qualify or graduate | <!-- --> | <!-- --> | book demo | MQL rate |

## 5. Per-email briefs

Repeat this block for each email in the sequence.

### Email #<!-- N -->: <!-- working name -->

- **Goal (one verb):** <!-- guidance: e.g. "prove" / "invite" / "teach" -->
- **Reader state at open:** <!-- guidance: what they just did / felt -->
- **Subject A / Subject B:** <!-- guidance: A = curiosity-led, B = benefit-led -->
- **Preview text:** <!-- guidance: 70–90 chars, complements subject -->
- **From name + reply-to:** <!-- guidance: human > brand where possible; reply-to must be monitored -->
- **Opening line:** <!-- guidance: no "hope this finds you well" — reference the trigger -->
- **Body structure:** <!-- guidance: 3–5 short paras, one idea each, mobile-scannable -->
- **CTA (primary):** <!-- guidance: button label + URL + UTM -->
- **CTA (secondary, optional):** <!-- guidance: soft link -->
- **P.S.:** <!-- guidance: optional; often outperforms the body CTA -->

## 6. Design & deliverability

- **Template:** <!-- guidance: plain-text-feel / branded / hybrid -->
- **Image-to-text ratio:** <!-- guidance: ≤40% image -->
- **Mobile render check:** <!-- guidance: tested on iOS Mail + Gmail app — date + initials -->
- **Deliverability warm-up needed?** <!-- guidance: yes/no; if new domain, ramp plan owner [[Marketing-Ops-Manager]] -->
- **Accessibility:** <!-- guidance: alt text on all images; min 14pt body; color contrast checked -->

## 7. QA checklist

- [ ] Trigger fires in test mode with sample record
- [ ] All links resolve + UTMs present
- [ ] Unsubscribe link works + routes to ESP
- [ ] Dark-mode render OK
- [ ] Legal footer + physical address present
- [ ] Subject A/B split configured 50/50
- [ ] Exit conditions tested (positive + negative)
- [ ] Reply-to inbox monitored + owner named

## 8. Approver sign-off

- **Copy approval:** [[Senior-Copywriter]]
- **Voice + brand pass:** [[Brand-Manager]]
- **Activation sign-off:** [[Email-Marketing-Manager]] — see [[Decisions#Email Activation]]

---

## ⚠️ Common mistakes

> [!WARNING] **How nurtures go to the bin**
> - *"Just checking in" subject lines.* The reader has read that subject 4,000 times. Write better.
> - *Every email pitches the demo.* Sequence reads like a stalking, not a conversation. Earn the ask.
> - *Cadence too dense.* Five emails in seven days = unsubscribe spike, not pipeline.
> - *Subject A/B without hypothesis.* You learn nothing. Write a one-line prediction before every test.
> - *No exit on opportunity created.* Sales AE gets pinged by an automated "are you still interested?" mid-deal. Trust dies.

---

## ✅ Example: "filled-in" version

- **Sequence name:** Attribution-Report Nurture / Q2-AR-N01
- **Type:** nurture (MOFU) · **ESP:** HubSpot · **Go-live:** 2026-05-10

**Entry trigger:** Form 1842 submit — "Attribution Decision Tree" download.
**Segment:** ICP=true; country in [US, CA, UK]; lifecycle=Lead.
**Suppressions:** customers; in-cycle opps; @competitor.com domains.
**Volume:** ~450/week expected.

**Goal:** drive demo bookings from content-downloaders.
**KPI:** MQL→demo rate ≥12% across sequence ([[KPIs#Email]]).
**Per-send:** open >40%, CTOR >15%, unsub <0.3%.
**Positive exit:** demo booked. **Negative exit:** unsub or 3 non-opens.

| # | Email | Delay | Subject A | Subject B | CTA |
|---|-------|-------|-----------|-----------|-----|
| 1 | Deliver + set thesis | 0h | "Your Attribution Decision Tree is attached" | "Before you open this — one thing" | Open PDF |
| 2 | The CFO question | +2d | "What your CFO actually wants to know" | "The question that kills attribution decks" | Read post |
| 3 | Aurora case | +4d | "Aurora reallocated $600k. Here's what happened." | "+18% pipeline, one model change" | Read case |
| 4 | Soft invite | +7d | "15 minutes on your attribution mess?" | "I'll trade you 15 min for one honest answer" | Book consult |
| 5 | Hard offer / exit | +11d | "Last note — then I'll stop" | "If not now, what would make it a yes?" | Book demo |

Design: plain-text-feel, from = "Maya @ [Brand]", reply-to monitored by [[Email-Marketing-Manager]]. Mobile-tested 2026-05-06 (EM). Deliverability: existing warm IP, no ramp.

QA passed 2026-05-08. Approver: [[Email-Marketing-Manager]]; voice pass [[Brand-Manager]] 2026-05-07.

T+30 results (2026-06-09): 1,840 enrolled, open 47%, CTOR 18%, demo-book rate 14.3% = **263 demos**, 112 MQLs, 38 opps, $1.1M pipeline.

---

## 🔗 Related

- Roles: [[Email-Marketing-Manager]], [[Senior-Copywriter]], [[Marketing-Ops-Manager]], [[Content-Strategy-Director]]
- Workflow: [[Workflows#Campaign Launch]], [[Workflows#Content Pipeline]]
- Templates: [[Campaign-Brief]], [[Content-Brief]], [[CRO-Test-Roadmap]], [[Post-Mortem]]
- KPIs: [[KPIs#Email]], [[KPIs#Acquisition]]
