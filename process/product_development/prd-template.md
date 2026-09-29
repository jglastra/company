# PRD: [Problem-Oriented Title]

> **Naming tip:** Name the PRD after the problem or outcome, not a specific solution (e.g. "Activity Aggregation," not "Activity Clusters"). Solution-specific names quietly narrow the team's thinking.

| | |
|---|---|
| **Author** | [PM name] |
| **Product designer** | [Name] |
| **Tech lead** | [Name] |
| **Other stakeholders** | [Names / teams] |
| **Status** | Draft · In review · Approved · In build · Launched · Retrospective done |
| **Last updated** | YYYY-MM-DD |
| **Target launch** | [Quarter / date / TBD] |
| **Related links** | [Research, designs, tickets, dashboards] |

---

## How to use this template

This is a **living document**, not a locked spec. Work through it in this order:

1. **Draft the four critical sections first:** Customer Problem → Why → Success Metrics → Prioritized Requirements. Work backward from the success metrics to decide which requirements are must-haves.
2. **Leave the Solution section as "TBD."** Bring the problem framing to working sessions with design and engineering and explore options together.
3. **Keep it current.** Re-order requirements, and log assumptions, risks and dependencies as teammates raise them.
4. **Fill in the Solution** once the team picks a direction, framed as a hypothesis.
5. **Come back after launch** and record what actually happened.

Delete this section (and the italic guidance under each heading) once you're writing for real.

---

## 1. Customer Problem ⭐

_Describe the problem from the user's point of view, not yours. Avoid "our app can't do X" — that's a missing feature (a solution), not a problem. Paint a vivid picture of who the user is, what they are trying to achieve, and what gets in the way._

**Who is the user?**
[Segment, role, context, relevant characteristics]

**What are they trying to accomplish?**
[The job, goal or outcome they care about]

**What pain do they experience today?**
[What happens now, how they work around it, what it costs them in time, money, confidence, etc.]

**Evidence**
- Customer quote: "[Verbatim quote]" — [source, date]
- Customer quote: "[Verbatim quote]" — [source, date]
- Data point: [e.g. support ticket volume, drop-off rate, survey result]

> ✅ Self-check: Could someone read this section and understand the user's world without knowing anything about our product's feature list?

---

## 2. Why This Matters (The Why) ⭐

_Build the case. Explain why the company should invest in this problem, and why now. Teams without a clear "why" struggle to get approval and to stay motivated._

**Value to customers**
[What changes for users if we solve this well?]

**Value to the business**
[Revenue, retention, activation, cost reduction, strategic positioning, etc.]

**Why now?**
[Urgency: market shift, competitor move, growing pain, strategic priority, cost of waiting]

**Strategic alignment**
[Which company / team goal or OKR this supports]

---

## 3. Success Metrics ⭐

_Define, before building, how you'll know the problem is solved. Agreeing up front prevents post-launch arguments about whether it "worked." Only choose metrics you can actually track._

| Metric | Type | Baseline | Target | Timeframe | How measured |
|---|---|---|---|---|---|
| [e.g. % of new users who activate] | Primary | [x%] | [y%] | [e.g. 60 days post-launch] | [Dashboard / event name] |
| [e.g. Feature adoption rate] | Secondary | [—] | [z%] | [...] | [...] |
| [e.g. Avg. spend per user] | Guardrail (must not drop) | [$x] | [≥ $x] | [...] | [...] |

**Definition of success:** [One or two sentences stating what outcome counts as a win.]

**Trade-off rules:** [If metrics move in opposite directions, which one wins? e.g. "Activation lift is a success only if spend per user stays within 5% of baseline."]

**Tracking readiness:** [ ] Events / instrumentation exist or are included in scope

---

## 4. Requirements (Prioritized) ⭐

_Describe what must be true for users, not how to build it. Keep language as generic as possible ("users can quickly narrow down their activities" rather than "users can push a filter button") so the team has room to find creative solutions. Derive Must-haves from the minimum needed to hit the success metrics._

### Must-haves
_Use cases the chosen solution must address. Listed in priority order._

| # | Requirement / user story | Rationale (link to problem or metric) | Notes |
|---|---|---|---|
| M1 | As a [user], I need to [goal] so that [outcome]. | [Why it's essential] | |
| M2 | | | |
| M3 | | | |

### Nice-to-haves
_Valuable, but we can live without them. Only pursue after Must-haves are done._

| # | Requirement / user story | Rationale | Notes |
|---|---|---|---|
| N1 | | | |
| N2 | | | |

### Out of scope
_Use cases we've explicitly decided **not** to solve now. Stating these keeps the team focused._

| # | Item | Reason for excluding | Revisit? |
|---|---|---|---|
| O1 | | | [Later phase / Never / TBD] |
| O2 | | | |

---

## 5. Solution

_Leave as **TBD** in early drafts. Fill in only after exploring options with design and engineering. Frame the chosen solution as a hypothesis — a bet the team is making._

**Status:** TBD

### Options considered
| Option | Summary | Pros | Cons | Effort | Decision |
|---|---|---|---|---|---|
| A | | | | S / M / L | Chosen / Rejected / Deferred |
| B | | | | | |

### Chosen solution
[Description, with links to designs, prototypes or technical specs.]

### Hypothesis
> We believe that **[solution]** for **[user]** will **[outcome]**. We'll know we're right when **[success metric reaches target]** within **[timeframe]**.

### Rollout plan
[Phasing, experiment / A-B test, feature flags, beta group, launch criteria]

---

## 6. Assumptions, Risks & Dependencies

_Keep this updated as teammates and stakeholders raise concerns during working sessions and build._

### Assumptions
| # | Assumption | How we'll validate | Status |
|---|---|---|---|
| A1 | | | Unvalidated / Validated / Invalidated |

### Risks
| # | Risk | Likelihood | Impact | Mitigation | Owner |
|---|---|---|---|---|---|
| R1 | | L / M / H | L / M / H | | |

### Dependencies
| # | Dependency (team, system, vendor) | What we need | Needed by | Status |
|---|---|---|---|---|
| D1 | | | | |

---

## 7. Open Questions

| # | Question | Owner | Due | Answer / decision |
|---|---|---|---|---|
| Q1 | | | | |

---

## 8. Decision & Change Log

_Record meaningful changes so the PRD stays the source of truth — especially edge cases and roadblocks discovered during build._

| Date | Change / decision | Why | Made by |
|---|---|---|---|
| YYYY-MM-DD | Initial draft | | |

---

## 9. Post-Launch Review

_Return to this section after launch. Your future self and future colleagues will rely on it._

**Launch date:** [YYYY-MM-DD]

**Results vs. targets**
| Metric | Target | Actual | Met? |
|---|---|---|---|
| | | | ✅ / ❌ |

**Was the hypothesis correct?**
[Confirmed / Disproven / Inconclusive — and why]

**What we learned**
- 
- 

**What's next**
[Iterate, expand, pick up Nice-to-haves, sunset, or move on]

---

## Pre-Review Checklist

- [ ] The customer problem is written from the user's point of view, not as a missing feature
- [ ] The problem includes real customer quotes and/or data
- [ ] The "why" and "why now" are clear to someone outside the team
- [ ] Success metrics are defined, trackable, and include a guardrail or trade-off rule
- [ ] Requirements are bucketed into Must-have, Nice-to-have and Out of scope
- [ ] Requirements describe needs, not a specific solution
- [ ] Solution is TBD or explicitly framed as a hypothesis
- [ ] Design and tech leads have reviewed the draft

---

_Template inspired by "Your PRDs are part of your legacy" from the Academy of Product Management: https://blog.academyofpm.com/p/prds_
