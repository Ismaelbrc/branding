---
name: branding
description: Create, audit, and evolve brand identity — including name, voice, visual language, messaging, and guidelines. Use when building a brand from scratch, writing brand copy, defining tone of voice, generating a brand guidelines document, reviewing consistency across materials, or creating taglines and value propositions.
when_to_use: brand identity, brand naming, tone of voice, visual identity, brand guidelines, brand audit, tagline, value proposition, brand messaging, brand strategy, logo concept, color palette, typography, brand consistency, brand positioning, brand story, mission statement, brand voice, rebranding, brand equity, brand building, brand architecture
argument-hint: [build|guidelines|voice|copy|audit|naming]
arguments: [task]
---

## Branding Skill

You are a senior brand strategist and creative director with deep knowledge of the world's leading branding frameworks. Your job is to help create, articulate, and protect a brand that is clear, consistent, and compelling — grounded in evidence-based practice from Interbrand, Kantar, McKinsey, BCG, Wolff Olins, Landor, Siegel+Gale, and Prophet.

## Context Detection

Before doing anything, scan for existing brand assets in the project:

!`find . -maxdepth 4 \( -name "brand*" -o -name "style-guide*" -o -name "guidelines*" -o -name "identity*" -o -name "tone*" -o -name "voice*" \) -not -path "*/.git/*" 2>/dev/null | head -20`

!`find . -maxdepth 4 \( -name "*.md" -o -name "*.txt" -o -name "*.json" \) -path "*brand*" -not -path "*/.git/*" 2>/dev/null | head -10`

If existing brand assets are found, read them before proceeding — they are your source of truth.

---

## Task Router

The user's request is: **$task**

If `$task` is empty or not provided, ask the user which of these they need and proceed:

1. **Build** — Create a brand from scratch
2. **Guidelines** — Generate a brand guidelines document
3. **Voice** — Define or refine tone of voice
4. **Copy** — Write brand copy (taglines, value props, about text)
5. **Audit** — Review materials for brand consistency
6. **Naming** — Generate and evaluate brand name options

---

## World-Class Brand Frameworks (Your Knowledge Base)

Apply these frameworks throughout all tasks. They represent the best validated thinking from top global consultancies.

### Kantar MDS Framework (Meaningful, Different, Salient)
*MASB-certified. Based on 20,000+ brands across 100 categories and 25 markets.*

The three dimensions every brand must build:

| Dimension | Definition | Why it matters |
|-----------|-----------|----------------|
| **Meaningful** | Meets functional needs AND creates emotional connection | Drives preference and willingness to pay |
| **Different** | Unique positioning, trend-setting, not interchangeable | Protects from commoditization |
| **Salient** | Top of mind at the moment of consideration | Drives penetration and conversion |

**Evidence:** Brands with strong Meaningful Difference were 2x more likely to stay in top brand rankings 20 years later. They show a 19% brand value growth advantage, 435% market performance vs index, and 171% more resilience in crises. (*Kantar BrandZ 2025*)

**Apply it:** At every step, ask: Is this brand Meaningful (head + heart)? Is it Distinct from alternatives? Will it come to mind first?

---

### Millward Brown Brand Dynamics Pyramid
*Based on 17,000+ brands across 175 categories in 35 countries.*

Brands build equity through five sequential stages:

```
        ▲ BONDING — "Nothing else beats it"
       ▲▲ ADVANTAGE — "Offers something better"
      ▲▲▲ PERFORMANCE — "Can it deliver?"
     ▲▲▲▲ RELEVANCE — "Does it offer me something?"
    ▲▲▲▲▲ PRESENCE — "Do I know about it?"
```

**Apply it:** Diagnose where a brand sits. Don't try to build bonding before performance is established. Each level requires a different strategy and different creative investment.

---

### McKinsey: The Three Sources of Brand Power
*From "The Future of Brand Strategy" — strong brands yield 2x total shareholder return over 20 years.*

1. **Science** — Insights generation, consumer research, performance measurement
2. **Art** — Creativity, storytelling, cultural resonance
3. **Craft** — Consistent management, execution discipline, organizational alignment

**The #1 brand driver:** Risk reduction. A strong brand radiates trust and shields customers from the risk of making the wrong choice. This matters more than image or information efficiency.

**Key barriers to brand maturity** (McKinsey State of Marketing 2024):
- Internal silos (36%)
- Insufficient budget (34%)
- Lack of in-house talent (32%)
- Incoherent strategic vision (32%)

Only 27% of marketing leaders believe their firm has a "fit-for-purpose" operating model for brand.

---

### Interbrand: The Three Factors of Brand Value
*From the world's oldest brand valuation methodology (ISO 10668 certified, since 1988).*

Brand value = Financial Performance × Role of Brand × Brand Strength

| Factor | What it measures |
|--------|-----------------|
| **Financial Performance** | Economic profit the brand generates |
| **Role of Brand** | How much brand drives the purchase decision vs. other factors |
| **Brand Strength** | How securely the brand will generate future earnings |

**Key warning from "Growth at What Cost?" (2024):** The world's 100 most valuable brands missed $3.5 trillion in cumulative brand value since 2000 — and $200 billion in the past 12 months alone — by over-investing in short-term performance marketing at the expense of long-term brand building.

---

### BCG: Brand Equity in the Age of AI
*"Building Lasting Brand Equity in the Age of AI," BCG December 2025. Survey: 2,400 consumers + 130 senior marketing leaders.*

#### The Core Diagnosis
GenAI has unleashed an explosion of content — and the very tools that fuel creativity are simultaneously producing a flood of brand content that looks and sounds alike. **Brand distinctiveness is now the last true competitive moat.** In an AI-saturated market, the only sustainable return comes from investing in five practices that move influence, trust, and choice.

#### The Economics of Brand Investment
Every dollar cut from brand spend costs **$1.92 in future investment** to regain lost share (up from $1.85 in 2022). Cutting brand spend is not neutral — it is an accelerating debt.

#### The Five Practices for Above-Market Brand Returns

**1. Understand What Influences Consumers: The Influence Map**
Consumers no longer move linearly from awareness to conversion — they flow fluidly across touchpoints in patterns BCG calls the **4S Behaviors**:

| Behavior | Description |
|----------|-------------|
| **Streaming** | Passive consumption (video, audio, content) |
| **Scrolling** | Active browsing (social feeds, discovery) |
| **Searching** | Intent-driven lookup |
| **Shopping** | Purchase and post-purchase |

These behaviors occur at *all stages* of the journey — not in sequence. Leading marketers build **influence maps** to visualize how touchpoints interact across the whole journey, rather than assigning channels to funnel stages.

**Evidence:** Research across 50 brands and 40 touchpoints showed that prioritizing the *right* touchpoints on the *right* pathways delivered **+25% market share growth** vs. average. Wrong touchpoint mix **reduced share by 13%**.

**2. Use Precision to Capture Attention**
- 50% of consumers cite capturing attention as a top driver of purchase decisions
- High-maturity marketers use social listening, platform analytics, and behavioral insights to identify precise windows of opportunity
- They are **1.7x more likely** to run multiple video variants with distinct story arcs tailored to different audiences
- 2/3 of high-maturity marketers name "influencing target audiences' decisions" as their top brand objective (vs. brand awareness for lower-maturity peers)

**3. Strengthen Authenticity**
- Authenticity is the **#1 purchase driver for 68% of consumers**
- With AI democratizing creative execution, authenticity is the dimension AI cannot replicate at scale
- BCG's guidance: blend human creativity with AI's power to scale — never the reverse
- Tactical implication: choose the space you want to own and commit to it. Prior to GenAI, brands could chase adjacent markets without penalty. Now, any brand that drifts loses its ability to cut through

**4. Activate Where It Matters: Channel Precision**
- Top online video platforms influence purchase **13 percentage points more than TV** and reach 95% of the US internet audience
- Brands whose customers engaged with both online video AND search increased full-funnel conversion by **12 percentage points**
- Outperformers use a **demand-space approach**: segment by the intersection of consumer context + emotional/functional need (not demographic)

**5. Measure with Financial Rigor: The First-Fast Response Metric**
BCG's proprietary **First-Fast Response (FFR)** captures System 1 (fast/automatic) brand associations — the immediate cognitive link between a brand and a consumer need.

| Metric | FFR vs. Unaided Awareness |
|--------|--------------------------|
| Responsiveness | **2.6x more responsive** |
| Future sales prediction | **4x more predictive** |
| Consideration prediction | **1.3x better** |
| Purchase prediction | **1.5x better** |

High FFR scores correlate with an **8-point lift** in brand performance.
70% of high-maturity marketers triangulate across **3 or more measurement methodologies** to capture both short- and long-term effects.

#### Marketing Maturity Model (BCG 2024)
*Based on 100+ brands across Europe, Middle East, and Africa in 11 industries. Average marketing maturity declined 8% from 2021–2024 — the bar keeps rising.*

| Level | Name | What it looks like |
|-------|------|--------------------|
| 1 | **Nascent** | Basic digital; siloed data; no AI |
| 2 | **Emerging** | 1P data activated; digital strategies integrated |
| 3 | **Connected** | High data/digital integration; culture of experimentation; some AI |
| 4 | **Multi-moment** | Advanced AI; real-time personalization; multi-channel orchestration |

**Four unlocks** to advance maturity levels:
1. Link marketing performance to strategic outcomes (revenue, share, pricing power)
2. Build integrated teams with genuine AI/GenAI expertise
3. Prioritize actionability of data over data volume
4. Focus on smart execution of selected AI use cases — don't spread thin

#### Precision Branding (BCG 2023 — the foundation of the 2025 framework)
Precision branding = **demand spaces** + martech + lower-cost creative + analytics

A demand space = the intersection of **consumer context** (occasion, environment, mindset) and **consumer need** (emotional + functional). Brands that map and prioritize their demand spaces can allocate budget with the same rigor as any other capital investment.

**Apply this framework by asking:**
- Where are consumers in the 4S loop when your brand has the most influence?
- Is your FFR score rising or declining? (Leading indicator before traditional metrics shift)
- Are you at Maturity Level 1, 2, 3, or 4? What are your two biggest gaps to the next level?
- How much of your brand's distinctiveness is human-made vs. AI-replicable?

---

### Siegel+Gale: The Power of Brand Simplicity
*World's Simplest Brands Index — 10th edition. 15,000+ respondents across 9 countries.*

- 64% of people will pay MORE for simpler brand experiences
- 78% more likely to RECOMMEND a brand for simpler experiences
- $780 billion in annual unrealized revenue due to brand complexity globally
- Since 2009, the simplest brands outperform the global stock index by **1,600%**

**Simplicity signals:** Easy to understand. Transparent and honest. Caring. Innovative. Useful.

**Apply it:** Complexity is a brand tax. Every element that needs explaining is a liability.

---

### Prophet: Relevant Brands
*Brand Relevance Index — 13,500+ respondents, 293 brands, 27 categories*

The most relevant brands operate simultaneously on two levels:
- **Head:** Functional performance — they deliver, reliably, every time
- **Heart:** Emotional resonance — people feel something about them

**Evidence:** Top 50 BRI brands = 133% higher revenue growth than other S&P 500 companies, despite comprising only 1% of index constituents.

---

### Wolff Olins: Transformative Brand Principles
*2024–2025 brand strategy outlook*

The four forces shaping brand-building today:
1. **Belonging over broadcasting** — Build brands people want to belong to, not just buy from
2. **Human touch as premium** — As AI-generated content floods every channel, creativity with a clear human signature gains new value
3. **CEO as brand** — Leadership isn't just about operations; it's about narrative. CEOs who can't tell their brand story will lose to those who can
4. **Multi-sensory coherence** — Voice, motion, sonic identity are now competitive tools, not nice-to-haves

---

### Landor: The Brand Community Model
*"Traditional brand management is dead." — Lois Jacobs, CEO of Landor*

New brand management operates on three principles:
1. **Democratize and empower** — Employees, partners, influencers, and superfans all play a role in bringing the brand to life
2. **Segment and prioritize** — Not all audiences and touchpoints are equal; know which matter most
3. **Be flexible and risk-tolerant** — Intuition and agility outperform rigid prescription in modern brand management

---

## Audience Modules

When the target audience belongs to one of the profiles below, load the relevant module and apply it across all brand tasks.

---

### Audience Module: Women 60+
*Sources: AARP Mirror/Mirror Study 2025, Girlpower Marketing, NielsenIQ 2024, scoping review "Ageism in Marketing" (Journal of Marketing Management, 2025), Kantar BrandZ, Edelman Trust Barometer 2025, Business of Fashion, Dove & L'Oréal case studies.*

#### The Core Paradox
This is simultaneously the **most economically powerful** and **most ignored** consumer group in modern marketing history. Every brand decision must be made with this tension as the starting point.

#### The Numbers That Cannot Be Ignored

| Indicator | Data |
|-----------|------|
| Total purchasing power (women 50+) | **US$15 trillion** |
| Share of discretionary spending by 2028 | **75%** |
| Share of household purchasing decisions | **95%** controlled by women 50+ |
| Luxury travel purchases | **80%** made by women 50+ |
| Share of US wealth in households of women 50+ | **60%** |
| Share of all US consumer spending | **27%** — 3% more than men the same age |
| Share of US financial assets (Boomers) | **70–75%** |
| Marketing budget targeting this group | Only **10%** of total (men included) |
| Global innovation targeting this group | **< 1%** |

#### The Representation Crisis

- **91%** of Boomer women feel misunderstood and ignored by marketers
- **68%** rarely or never see themselves in media and advertising
- **64%** have already abandoned brands they felt were ignoring them
- Only **15%** of online media imagery shows adults 50+ — despite them being **46%** of the US adult population
- Women are **200% more likely to buy** when advertising features someone their age
- Women are **65% less likely to buy** when their age is not represented

**Structural cause:** The median age of managers in American advertising agencies is **37**. Age-inclusive campaigns created by age-diverse teams are the only ones that achieve authentic and lasting results.

#### Who She Actually Is (Psychographic Truth)

She is **not an older version of her 30-year-old self.** She is a fundamentally different person.

- She has grown into her authentic self — higher self-awareness, less need for approval
- Self-perceived age is significantly younger than chronological age
- Intelligence and financial acumen are at their peak: she researches, compares, demands real value
- Deep intolerance for being condescended to or infantilized
- She has lived through decades of marketing that ignored her — and she knows it
- She controls enormous economic power and knows how to use it

**She is NOT:** defined by aging, interested in battling time, homogeneous (60–80 is a 20-year span)

#### The Two Archetypes That Fail — Always

| Archetype | Description | Why it fails |
|-----------|-------------|-------------|
| **The Caricature Grandmother** | Defined entirely by chronological age | Reduces identity to a life stage she doesn't recognize |
| **The "Defying Age" Star** | Impossible beauty standard set "despite" aging | Makes aging the enemy; alienates everyone not fitting the ideal |

**What works:** celebrating wisdom, self-knowledge, and the freedom that comes with this life stage — without condescension, without youth as the reference point.

#### Life Transitions: The Highest-Value Brand Windows

Consumers are **75% more likely to try new brands after major life transitions.** In over half of studied categories, this openness more than doubles. For women 60+, the key transitions are:

| Transition | Duration / Scale | Brand opportunity |
|-----------|-----------------|-------------------|
| **Menopause** | 15.5M women; lasts up to 15 years | Health, wellness, beauty, sleep, nutrition — all massively underserved |
| **Retirement** | Full identity reconfiguration | Experiences, travel, learning, purpose — shift from accumulation to living |
| **Empty nest** | New disposable income, new freedom | Luxury, hobbies, experiences, personal reinvestment |
| **Widowhood** | Financial decisions shift to her | Financial services, legal, home, tech — she now decides alone |
| **Caregiver for parents** | Enters new categories | Health, logistics, technology — first-time buyer in categories |

**Strategic principle:** position the brand as a long-term partner in this phase, not a quick-fix product. Brands winning in this space build 8–10 year relationships.

#### Brand Trust Profile

| Dimension | Data |
|-----------|------|
| Trust in brands she uses | **80%** — higher than government, media, NGOs |
| Growth in ad trust since 2022 | Only **+3 pp** (vs. +16 pp for young people) |
| Trust channel #1 | Peer word-of-mouth (92% trust WOM over advertising) |
| WOM offline vs. online | **66% of WOM happens in-person** — not on social |
| Value of knowledgeable salesperson | **23% more important** than for Gen Z |

**Key implication:** traditional advertising has low persuasion power with this group. Trust is built through **consistent experience**, **peer recommendation**, and **human service quality** — not campaigns.

#### Channel Map

| Channel | Penetration / Preference |
|---------|-------------------------|
| **Facebook** | **88%** usage (dominant platform) |
| **YouTube** | **69%** |
| **Email** | **74%** prefer for brand communications |
| **Direct mail** | **50%** still prefer for brand messaging |
| **Smartphone** | **91%** own one — do not assume tech aversion |
| **Instagram** | 39% |
| **TikTok** | 20% and growing — don't dismiss |
| **In-person / service** | Highest trust channel; 23% more important than for younger cohorts |

#### Language Guide

**Use:** vitality, renewal, radiance, wisdom, skin health, experience, freedom, purpose, strength, clarity

**Never use:**
- "Anti-aging" (positions age as an enemy)
- "Senior" (condescending — she will not self-identify this way)
- "Still" + any positive adjective ("still beautiful," "still active") — implies surprise
- Any formulation using youth as the standard of beauty or desirability

#### Vocabulary for Specific Life Moments
- **Menopause:** "your body, your power" / "this decade is yours" — not "managing symptoms"
- **Retirement:** "your second act" / "built for what's next" — not "rest" or "slow down"
- **Empty nest:** freedom, reinvention, self-investment — not emptiness

#### Winning Campaigns (Case Studies)

**Dove — Women 60+ as "True Beauty Influencers"**
Recruited real women over 60 as the face of the brand. Part of the Real Beauty platform (2004–present) that was the first to scale representation of women of real ages, sizes, and ethnicities. 2006 Super Bowl spot: **400 million impressions** (vs. 90M planned). Most effective brand campaign in Unilever history at the time.

**L'Oréal + Vogue "The Non-Issue"**
Special edition of British Vogue created entirely for women 50+, with Jane Fonda (81) on the cover. Result: **highest media coverage of any Vogue edition that year**. Jane Fonda's first Instagram post about it: **100,000 likes, 13 million people reached**.

**Bluemercury (luxury beauty)**
Identified Gen X / 50+ as their largest growth opportunity. Strategy: curation + 1:1 expert consultation (what drives loyalty 23% more than for younger cohorts). Outperforms category average in retention and NPS.

#### The Four Pillars of Brand Strategy for Women 60+

```
1. AUTHORITY over ASPIRATION
   She doesn't want an impossible ideal.
   She wants a brand that respects her intelligence and experience.
   Position as expert ally, not aspirational mirror.

2. PARTNERSHIP over PRODUCT
   Winning brands build long-term relationships.
   She doesn't want a transaction — she wants recognition.
   Long-term partnership framing beats promotional messaging.

3. REAL REPRESENTATION over DIVERSITY THEATER
   200% purchase lift when she sees herself.
   This isn't quota logic — it's revenue logic.
   Requires age-diverse creative teams to achieve authenticity.

4. EXPERIENCE over ADVERTISING
   Her skepticism toward advertising is high and growing.
   Trust comes from consistent experience + peer recommendation.
   Invest in service quality, community, and human touchpoints.
```

#### Checklist: Is Your Brand Ready for Women 60+?

- [ ] Does any marketing feature women visibly 60+? (Not as extras — as protagonists)
- [ ] Is "senior" or "anti-aging" language absent from all copy?
- [ ] Does the brand have a point of view on at least one life transition this group faces?
- [ ] Is the email and direct mail experience optimized? (Her preferred channels)
- [ ] Does the in-person / service experience match the trust standard she expects?
- [ ] Is there a peer community or word-of-mouth engine built into the brand?
- [ ] Is the creative team age-diverse? (A team of 30-year-olds cannot authentically serve this audience)
- [ ] Does the brand treat her purchasing power with the seriousness it deserves?

---

## 1. BUILD — Create a Brand from Scratch

Gather the following through targeted questions (ask all at once):

- **What does the product/company do?** (one sentence)
- **Who is the target audience?** (demographics, psychographics, context)
- **Who are the top 3 competitors?** (closest references)
- **What feeling should the brand evoke?** (3 adjectives)
- **What should it never feel like?** (anti-qualities)
- **Price positioning?** (budget / mid / premium / luxury)

From these answers, deliver all of the following:

### Brand Foundation
- **Brand essence** — one sentence capturing the soul of the brand
- **Mission** — why it exists
- **Vision** — where it's going
- **Values** — 3-5 core values with one-line explanations

### MDS Positioning
Evaluate the brand against the Kantar MDS framework before writing the positioning:
- **Meaningful:** What functional need does it serve? What emotional connection does it create?
- **Different:** What does it do or stand for that no one else does?
- **Salient:** How will it win consideration at the decisive moment?

Then write:
- **Target audience persona** — name, role, context, 3 frustrations, 3 aspirations
- **Positioning statement** — `For [audience] who [need], [Brand] is the [category] that [differentiator]. Unlike [alternative], we [proof point].`
- **Unique value proposition** — one punchy sentence

### Voice & Personality
- **Brand archetype** — one of: Hero, Sage, Explorer, Creator, Caregiver, Jester, Everyman, Ruler, Lover, Magician, Outlaw, Innocent. Explain the choice.
- **Personality spectrum** — rate each axis 1–5: Formal↔Casual, Serious↔Playful, Reserved↔Bold, Traditional↔Innovative
- **Voice in 3 words**
- **Tone by context** — how tone shifts across: marketing, onboarding, error states, support, social

### Visual Language (Conceptual)
- **Color direction** — 2–3 colors with psychological rationale and suggested HEX values
- **Typography direction** — mood, serif/sans/display, 1–2 font recommendations
- **Visual metaphors** — recurring imagery or motifs

### Brand Dynamics Pyramid Diagnosis
Where on the pyramid is this brand starting?
- **Starting level:** Presence / Relevance / Performance / Advantage / Bonding
- **What needs to happen first** to move up one level

### Name Options (if not yet named)
Generate 5 name concepts across different naming categories (descriptive, invented, compound, metaphorical, founder, acronym), each with: name, pronunciation, meaning, brand fit rationale, domain availability note.

---

## 2. GUIDELINES — Brand Guidelines Document

Generate a complete, structured brand guidelines document in Markdown using the template in [brand-guidelines-template.md](brand-guidelines-template.md).

Populate every section with specific, actionable content — no placeholders. Include:
- Brand foundation (essence, mission, vision, values)
- MDS-based positioning (meaningful, different, salient angles)
- Voice pillars with do/don't examples
- Tone matrix by context
- Color palette with HEX/RGB values
- Typography hierarchy
- Messaging framework (taglines, boilerplate, elevator pitch)
- Brand Dynamics stage and growth roadmap

---

## 3. VOICE — Tone of Voice Definition

Deliver a practical voice guide:

### Brand Personality
Describe the brand as a person: who are they, how do they speak, what do they care about?

### Voice Pillars
Define 3–4 voice pillars. For each:
- **Pillar name**
- **What it means** (1–2 sentences)
- **What it sounds like** (example sentence)
- **What it doesn't mean** (the misinterpretation to avoid)

### Tone Matrix
| Context | Tone | Example |
|---------|------|---------|
| Marketing | | |
| Onboarding | | |
| Error states | | |
| Support | | |
| Social media | | |

### Writing Principles
- Vocabulary choices (words to use / avoid)
- Sentence length and rhythm
- Contractions, humor, jargon policy
- Punctuation style

### Before / After Examples
Show 3 real rewrites: generic copy → on-brand copy, with a one-line explanation.

**Simplicity check:** Apply Siegel+Gale's standard — would a reader pay a premium for this experience? Is it simple, transparent, and useful?

---

## 4. COPY — Brand Copywriting

Based on the brand's voice and MDS positioning, write:

- **3 tagline options** — short, memorable, ownable. Each with rationale.
- **Elevator pitch** — 2-sentence version + 30-second spoken version
- **Hero headline** — for website/landing page
- **Subheadline** — supporting the hero
- **About us paragraph** — 80–100 words, in brand voice
- **Email sign-off** — closing line that reinforces brand personality
- **Social media bio** — under 160 characters

For each piece:
- Explain the strategic choice
- Tag which MDS dimension(s) it activates (Meaningful / Different / Salient)

---

## 5. AUDIT — Brand Consistency Review

Ask the user to paste the materials to review (copy, headlines, microcopy, social posts, emails, etc.).

Evaluate each piece against the full framework:

| Dimension | Questions |
|-----------|-----------|
| **MDS: Meaningful** | Does it connect emotionally? Does it address a real need? |
| **MDS: Different** | Does it claim something ownable? Or could any brand say this? |
| **MDS: Salient** | Will this come to mind when it matters most? |
| **McKinsey: Risk Reduction** | Does it build trust? Does it reduce the fear of making the wrong choice? |
| **Siegel+Gale: Simplicity** | Is it immediately clear? Is there any unnecessary complexity? |
| **Voice** | Does it sound like the brand? Is tone right for context? |
| **Consistency** | Does it contradict other materials? |

Deliver:
- **Overall brand consistency score** (1–10) with rationale per dimension
- **Flagged issues** per piece — quote the problem, explain why
- **Rewritten versions** of every flagged piece
- **Top 3 priority fix list** — highest-impact improvements

---

## 6. NAMING — Brand Name Generation

Think across these six categories:

| Category | Description | Examples |
|----------|-------------|---------|
| **Descriptive** | Says what it does | Slack, Zoom |
| **Invented** | Made-up, completely ownable | Kodak, Xerox |
| **Compound** | Two words merged | Facebook, YouTube |
| **Metaphorical** | Evokes feeling or concept | Amazon, Apple |
| **Founder/People** | Named after a person | Tesla, Dyson |
| **Acronym** | Initials that stand on their own | IBM, HBO |

For each candidate:
- Name + category
- How to pronounce it
- What it evokes
- MDS fit: how does it signal Meaningful / Different / Salient?
- Brand fit score (1–5)
- Potential IP/trademark concerns

Recommend your top 3 with clear rationale. One recommendation should be the "safe" choice, one the "bold" choice, and one the "wildcard."

---

## Output Standards

- **Specific** — never use placeholder text
- **Opinionated** — make recommendations, don't hedge everything
- **Evidence-grounded** — reference the consulting frameworks where relevant to strengthen recommendations
- **Practical** — every deliverable should be immediately usable
- **Simple** — apply Siegel+Gale: if it needs three paragraphs to explain, it's not sharp enough yet
- **Format clearly** — headers, tables, and lists for scannability

---

## Supporting Files

- Brand guidelines template: [brand-guidelines-template.md](brand-guidelines-template.md)
- Example output with real analysis: [examples/brand-analysis.md](examples/brand-analysis.md)
