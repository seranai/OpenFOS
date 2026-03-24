# Persona Scoring & Validation Framework

## Reference File for OpenFOS Skill 4: Persona Definition & Testing

Read this file before producing the Full Persona Card in Phase 3. It contains the
detailed rubrics, validation criteria, and counter-arguments for building testable
B2B buyer personas.

---

## Part 1: The JTBD-Infused Persona Model

Traditional buyer personas focus on WHO the buyer is (demographics, firmographics).
Jobs-to-Be-Done focuses on WHY they buy (the outcome they're trying to achieve).
The OpenFOS model fuses both, because each answers different questions:

| Framework | Answers | Informs |
|-----------|---------|---------|
| Demographics/Firmographics | Where do I find this buyer? | Channel strategy, targeting |
| Psychographics/Behavior | How does this buyer act? | Messaging tone, content format |
| JTBD (Functional) | What task are they trying to accomplish? | Product features, positioning |
| JTBD (Emotional) | How do they want to feel? | Brand, trust signals, copy |
| JTBD (Social) | How do they want to be perceived? | Social proof, status signaling |
| Buying Committee | Who else needs to say yes? | Sales strategy, content variety |

**Key research backing this fusion:**
- B2B International (2024): Demographic criteria are relevant for only 15% of B2B
  purchasing decisions. Functional requirements (87%), strategic goals (72%), and
  process-related factors (64%) dominate.
- Gartner (2025): JTBD-based marketing strategies lead to 34% higher conversion rates
  in B2B sales.
- Nielsen Norman Group: Personas and JTBD are complementary, not competing frameworks.
  The best personas include behavioral and motivational data, not just demographics.

**The counter-argument:** Some practitioners (notably Intercom's Des Traynor) argue
that traditional personas are actively harmful because they create false segmentation
based on demographics rather than motivations. The counterpoint: in B2B, demographics
DO matter — job title determines budget authority, company size determines buying
process, and industry determines regulatory context. The answer is not to abandon
demographics but to subordinate them to JTBD as supplementary targeting data.

---

## Part 2: The Buying Committee Framework

### Why Single-Buyer Personas Are Dangerous in B2B

The single-decision-maker persona is a myth in modern B2B purchasing:

- **Gartner (2024):** Average B2B buying group includes 6-10 decision-makers, each
  entering with 4-5 pieces of independent research.
- **Forrester (2024):** Average B2B purchase involves 13 stakeholders, with 89% of
  buying decisions crossing multiple departments.
- **HBR (2017):** Average B2B purchase involved 6.8 decision-makers (this number has
  since increased).
- **CEB (Challenger):** Purchase likelihood drops to 30% as the buying group expands
  beyond 5 stakeholders.
- **6sense:** Buyers are 69% through their journey before contacting a vendor.

**What this means for early-stage founders:** You may be selling to a single person
at small companies (sub-50 employees), but the moment you move upmarket, you're selling
to a committee. The persona skill must prepare founders for both scenarios.

### The Five Buying Committee Roles

Every B2B purchase involves some combination of these roles. In small companies, one
person may fill multiple roles. In enterprise, each role may involve multiple people.

**1. Champion (Internal Advocate)**

The person who discovers your solution and sells it internally. This is your PRIMARY
persona — the person your marketing should attract and your content should arm.

| Attribute | Scoring Criteria |
|-----------|-----------------|
| Problem ownership | Champions OWN the problem your product solves. It's their daily pain. |
| Internal influence | Can convene a meeting about this. Peers respect their judgment. |
| Motivation | Personal career benefit from solving this (promotion, recognition, reduced stress) |
| Risk profile | Willing to champion a new/unknown vendor. Comfortable with some career risk. |
| Information behavior | Active researcher. Reads industry content. Joins communities. |

**How to identify in the wild:** Champions are the people who respond to your cold
outreach, attend your webinars, and ask detailed questions. They're mid-level (manager
to director) — senior enough to have influence but junior enough to still feel the
pain directly.

**Common founder mistake:** Targeting the economic buyer directly. VPs and C-suite don't
respond to cold outreach from unknown startups. They respond to internal recommendations
from champions they trust. Always start with the champion.

**2. Economic Buyer (Budget Owner)**

The person who approves the spend. Controls the checkbook.

| Attribute | Scoring Criteria |
|-----------|-----------------|
| Budget authority | Can approve purchases up to $[X] without escalation |
| Decision criteria | ROI, payback period, strategic alignment, risk |
| Engagement style | Enters late in the process. Wants executive summary, not details. |
| Veto power | HIGH — can kill a deal at any stage |
| Trust signals | Peer references (other executives), analyst endorsement, brand recognition |

**Key insight:** The economic buyer cares about OUTCOMES, not features. Never pitch
features to an economic buyer. Pitch business impact: revenue gained, costs reduced,
risk eliminated, compliance achieved.

**The counter-argument:** In PLG (product-led growth) motions, the economic buyer may
be bypassed entirely at the initial purchase — the champion uses a credit card or free
tier. The economic buyer only enters when spend exceeds a threshold. For founders
building PLG motions, the economic buyer persona matters less at first but becomes
critical at the expansion stage.

**3. Technical Validator (IT/Security/Architecture)**

The person who evaluates whether the solution actually works and is safe.

| Attribute | Scoring Criteria |
|-----------|-----------------|
| Focus areas | Security, compliance, integration, data privacy, scalability |
| Decision criteria | Technical specs, API documentation, SOC2/ISO compliance, uptime SLAs |
| Engagement style | Wants to test. Self-serve evaluation preferred. Documentation-first. |
| Veto power | MEDIUM-HIGH — can block on security or integration concerns |
| Common objections | "How does this integrate with [existing tool]?" "Where is data stored?" |

**When this role matters most:** Enterprise sales, regulated industries (healthcare,
finance, government), and any product that handles sensitive data.

**When this role barely matters:** SMB sales, tools that don't touch sensitive data,
products that sit on top of existing platforms with established integrations.

**4. End User (Daily Operator)**

The person who actually uses the product day-to-day.

| Attribute | Scoring Criteria |
|-----------|-----------------|
| Focus areas | Ease of use, workflow fit, time savings, learning curve |
| Decision criteria | "Will this make my job easier or harder?" |
| Engagement style | Wants to try before the company buys. Free trial or demo. |
| Veto power | LOW (formally) but HIGH (practically — poor adoption kills renewals) |
| Adoption risk | The #1 reason B2B software churns is low end-user adoption |

**Critical insight:** The end user may not be involved in the purchase decision but
determines whether the purchase succeeds. A tool the champion loves, the economic
buyer approves, and the end user ignores is a churned account in 6 months.

**5. Procurement / Legal / Compliance**

The gatekeepers who manage vendor relationships, contracts, and compliance.

| Attribute | Scoring Criteria |
|-----------|-----------------|
| Focus areas | Contract terms, pricing, vendor risk, data processing agreements |
| Decision criteria | Compliance with internal policies, favorable terms |
| Engagement style | Enters very late. Process-driven. Requires specific documentation. |
| Veto power | MEDIUM — can delay significantly but rarely kill a deal the business wants |
| Common friction | Security questionnaires, DPA requirements, payment terms, insurance |

**When this role matters:** Enterprise (always), mid-market (sometimes), SMB (rarely).
For early-stage founders targeting SMB, this role can usually be ignored in the
persona exercise.

---

## Part 3: Persona Confidence Scoring

### The 5-Level Confidence Scale

Persona confidence is determined by the quality and quantity of evidence behind each
element. This prevents founders from treating hypothetical personas as validated truth.

**Level 5: Research-Validated ⬛⬛⬛⬛⬛**
- Based on 10+ structured customer/prospect conversations
- Key JTBD statements validated by multiple independent sources
- Buying committee map confirmed across 5+ deal cycles
- Day-in-the-life description reviewed by actual buyers
- Messaging tested and refined based on response data
- **Use for:** Product roadmap decisions, major marketing investments, hiring

**Level 4: Interview-Informed ⬛⬛⬛⬛◻**
- Based on 3-9 structured conversations
- Primary JTBD confirmed by multiple buyers
- Buying committee partially mapped from real deal experience
- Some messaging tested (outreach response rates, demo conversions)
- **Use for:** First outbound campaigns, landing page copy, sales playbook v1

**Level 3: Evidence-Supported ⬛⬛⬛◻◻**
- Based on market research (reports, competitor analysis, community observation)
  plus 1-2 conversations
- JTBD inferred from competitor positioning and customer reviews
- Buying committee estimated from industry norms
- **Use for:** Hypothesis testing, initial outreach experiments, content strategy

**Level 2: Hypothesis-Stage ⬛⬛◻◻◻**
- Based on analogies to similar products/markets
- JTBD derived from founder experience or adjacent markets
- Buying committee assumed from company size norms
- **Use for:** Discovery conversation guides, initial LinkedIn targeting

**Level 1: Assumption-Based ⬛◻◻◻◻**
- Based primarily on founder intuition
- Limited or no direct buyer input
- **Use for:** NOTHING without validation. This persona needs primary research
  before any investment.

### How to Assess Confidence for Each Persona Element

Not all elements need the same confidence level. Some are cheap to get wrong;
others are expensive.

**High cost of being wrong (need Level 3+ before acting):**
- Who the champion is (wrong title = wasted outreach)
- Primary JTBD (wrong job = wrong positioning)
- Economic buyer identity (wrong person = deal stalls)
- Primary objection (wrong objection = wrong sales playbook)

**Medium cost of being wrong (Level 2 is acceptable initially):**
- Day-in-the-life details
- Secondary triggers
- Anti-persona characteristics
- Specific communities/channels

**Low cost of being wrong (Level 1 is acceptable, iterate quickly):**
- Persona name/archetype label
- Emotional/social JTBD nuances
- Specific vocabulary/phrases
- Content format preferences

---

## Part 4: The Anti-Persona Framework

### Why Anti-Personas Save More Time Than Personas

A well-defined anti-persona prevents the founder from spending weeks pursuing
prospects who look promising but will never convert. Common anti-persona patterns:

**The Tire-Kicker:** Engages enthusiastically with content and demos but has no
budget authority, no timeline, and no urgency. Often a junior employee researching
"for future reference." Signal: asks many questions, never involves others, can't
articulate a timeline.

**The Feature Blocker:** Interested but has a specific technical requirement your
product doesn't meet (and won't meet soon). Signal: asks about a feature in the first
2 minutes of every conversation, evaluates everything through that lens.

**The Wrong Size:** Company is too small to afford your price or too large to accept
your maturity level. Signal: sticker shock or enterprise security requirements you
can't meet.

**The Satisfied Customer (of someone else):** Already using a competitor and is
moderately satisfied. Switching costs exceed switching benefits. Signal: "We use [X]
and it's fine" — the word "fine" is a red flag.

**The Innovator Tourist:** Loves your concept, early adopter mindset, but is in an
organization that won't support the purchase. Signal: individual enthusiasm with
organizational inertia.

### Anti-Persona Scoring

For each anti-persona characteristic, the founder should ask: "If I see this signal
in the first 5 minutes of a conversation, should I disqualify?"

| Signal Strength | Action |
|----------------|--------|
| Hard disqualifier (present in every lost deal) | Walk away immediately |
| Soft disqualifier (present in most lost deals) | Probe further, but lower priority |
| Yellow flag (sometimes present in won deals too) | Note but don't disqualify |

---

## Part 5: Persona Testing Methodology

### The 3-Source Validation Method

No single data source is sufficient for persona validation. Cross-reference at least
three of these five sources:

1. **Direct conversations** with people matching the persona (most valuable)
2. **Customer behavior data** from existing users if available (sign-up patterns,
   feature usage, support tickets)
3. **Competitor customer reviews** on G2, Capterra, TrustRadius (reveals pain
   language and buying criteria)
4. **Community observation** in Slack groups, Reddit, LinkedIn groups (reveals
   what this persona talks about unprompted)
5. **Job postings** for this role (reveals priorities, tools used, skills valued)

### Pattern Recognition in Discovery Conversations

When conducting the 5-8 discovery conversations in Week 1 of the validation sprint,
track these patterns:

**Strong validation patterns:**
- 3+ buyers independently use the same language to describe the problem
- Buyers name the same trigger event without prompting
- Buyers quantify the cost of the problem (time, money, risk)
- At least one buyer expresses urgency: "When can I use this?"
- The buying committee description matches across conversations

**Weak validation patterns:**
- Buyers acknowledge the problem but use different language each time
- Triggers vary widely — no consistent pattern
- Buyers can't quantify the cost
- Interest is polite but passive: "That's interesting"
- Committee structures differ significantly across companies

**Invalidation patterns:**
- The person you thought was the champion says "that's not my problem"
- The title you targeted doesn't exist at most companies in the segment
- The trigger event you hypothesized rarely happens
- Buyers consistently name a different job as higher priority
- The buying committee is dramatically different from your map

### Updating the Persona

After the 2-week sprint, update the persona card with a clear change log:

| Element | Original Hypothesis | Validated/Changed | Evidence |
|---------|--------------------|--------------------|----------|
| Title | [original] | [validated/changed to X] | [what you heard] |
| Primary JTBD | [original] | [validated/changed to X] | [what you heard] |
| Trigger | [original] | [validated/changed to X] | [what you heard] |
| Committee | [original] | [validated/changed to X] | [what you heard] |

This change log is valuable because it shows the founder (and their team) how
the persona evolved from assumption to evidence. It builds intellectual honesty
into the process.

---

## Part 6: The Data That Informs This Framework

Key research points used throughout this skill:

1. **42% of startups fail** because they build something nobody needs (CB Insights).
   A precise persona prevents building for the wrong buyer.

2. **Average B2B purchase involves 6-10 decision-makers** (Gartner 2024). The
   single-buyer persona is a dangerous fiction.

3. **89% of B2B buying decisions cross multiple departments** (Forrester 2024).
   Marketing that targets one department misses the committee.

4. **Buyers spend only 17% of purchase time with vendors** (Gartner). The rest is
   internal research and consensus-building. Your persona must account for how the
   buyer behaves when you're not in the room.

5. **41% of B2B buyers have a preferred vendor before formal evaluation** (Forrester
   2024). The persona should inform how you become the pre-preferred vendor through
   content and community presence.

6. **Demographic criteria drive only 15% of B2B purchasing decisions** (B2B
   International 2024). Functional requirements (87%) and strategic goals (72%)
   dominate. This is why JTBD must be the core of the persona.

7. **54.5% misalignment between seller and buyer problem definitions** (Emblaze 2024).
   When alignment improves, win rates increase by 38%. The persona's JTBD statement
   is the alignment tool.

8. **More than half of lost B2B deals are lost to "no decision"** — not to competitors.
   The buying committee fails to reach consensus. The persona's committee map is
   the tool for preventing this.

### The Counter-Narrative

Important limitations to acknowledge:

- Personas are models, not reality. Every individual buyer will deviate from the
  persona in some way. The persona captures the 80% pattern; the salesperson handles
  the 20% variation.

- B2B buying is becoming less linear and more "swarming" (Gartner's term).
  Committee roles are fluid, not fixed. The champion in one deal might be the
  blocker in another.

- In product-led growth (PLG) motions, the traditional buying committee may not
  apply at initial adoption. The end user becomes the champion, and the economic
  buyer only enters at expansion. Founders building PLG should weight the End User
  persona more heavily.

- AI is changing B2B buyer behavior. Buyers are using AI to research vendors, compare
  solutions, and even draft RFPs. This compresses timelines and changes information
  behavior. Personas built in 2026 should account for AI-augmented buyer behavior.

- Emerging market buyers may have fundamentally different committee structures,
  decision processes, and relationship expectations. Don't assume US/EU buying
  patterns apply globally.
