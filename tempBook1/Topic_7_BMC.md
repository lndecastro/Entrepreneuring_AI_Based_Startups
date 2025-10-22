# Topic 7: Business Model Canvas (BMC)
The **Business Model Canvas** is a strategic tool that visually describes how a startup **creates, delivers, and captures value**. For AI-based startups, the BMC connects user needs (Topic 5) and Lean validation (Topic 6) with the **economic logic** that sustains the venture. We will define the nine blocks, apply **AI-enhanced analysis** to each, stress-test assumptions, and link decisions to **unit economics** and **engines of growth**.

## Suggested Readings
- Osterwalder, A., & Pigneur, Y. (2010). *Business Model Generation*. John Wiley and Sons.  
- Osterwalder, A., Pigneur, Y., Bernarda, G., & Smith, A. (2014). *Value Proposition Design: How to Create Products and Services Customers Want*. Wiley.  
- Maurya, A. (2012). *Running Lean: Iterate from Plan A to a Plan That Works*. O’Reilly.  

---

## 7.1 What Is a Business Model? (for AI Startups)
A **business model** explains the logic of **value creation** (what and for whom), **value delivery** (how it reaches users), and **value capture** (how money is made).  
**Relevance for AI-based startups**:  
- Aligns **Customer Development** insights with monetization and operations.  
- Forces clarity on **data, model, and platform** dependencies (risk & costs).  
- Connects **MVP learning** (Topic 6) to **pricing, margins, and scale**.

## 7.2 The Business Model Canvas — Nine Blocks
![Business Model Canvas](./Data/business_model_canvas_poster.pdf)

**Value Creation**
- **Key Partners (KP)** — external organizations that help you operate (suppliers, platforms, distribution, co-innovation).  
- **Key Activities (KA)** — core tasks that deliver the value (data ops, model dev, sales, support).  
- **Key Resources (KR)** — assets required (team, data, models, IP, infrastructure, capital).

**Value Proposition**
- **Value Propositions (VP)** — the bundle of benefits that solve customer jobs, relieve pains, and create gains.

**Value Delivery**
- **Customer Relationships (CR)** — how you acquire, onboard, engage, and retain users (self-serve, assisted, communities).  
- **Channels (CH)** — how users discover, evaluate, purchase, receive, and are supported (web, partners, app stores).  
- **Customer Segments (CS)** — groups you serve (ICP, micro-segments, early adopters).

**Value Capture**
- **Cost Structure (C$)** — fixed vs. variable costs (compute, data, talent, GTM, support).  
- **Revenue Streams (R$)** — how you earn (one-time, subscription, usage-based, licensing, marketplace, ads).

## 7.3 Linking BMC to Lean Startup & Customer Development
- **Discovery → Validation (Topic 6)** informs **CS & VP**.  
- **MVP experiments** de-risk **R$** (pricing), **CH/CR** (conversion/retention), and **C$** (unit economics).  
- **Engines of Growth** map to **CR/CH/R$** choices; pivots update the canvas blocks accordingly.

## 7.4 AI-Enhanced BMC (Where AI Helps)
- **CS:** clustering & **micro-segmentation**, LTV prediction, churn risk signals.  
- **VP:** message testing, competitive differentiation scans, value quantification.  
- **CH/CR:** attribution modeling, CAC optimization, journey personalization.  
- **R$:** price sensitivity, dynamic pricing, scenario forecasting.  
- **C$:** predictive cost modeling (compute, support), efficiency suggestions.  
- **KR/KA/KP:** capability gap analysis, partner mapping, dependency risks.

## 7.5 Tools & Applications

### 7.5.1 Customer Segments (CS)
**Goal:** Identify high-value segments and early adopters.

**AI Prompt (Segmentation)**
```
We are building [startup]. Based on this brief [context, industry, geography],
propose 5 micro-segments with: pains/gains, willingness to pay, preferred channels,
key adoption barriers, and an early-access plan. Output a table.
```

**Deliverable:** Table of segments with size proxy, LTV potential, and priority rank.

### 7.5.2 Value Propositions (VP) with VPC
**Goal:** Align Jobs–Pains–Gains with Products/Services, Pain Relievers, Gain Creators.

**AI Prompt (VP Variants)**
```
Given this VPC summary [jobs, pains, gains], produce 5 VP statements:
(1) core benefit, (2) differentiator vs. alternatives, (3) measurable outcome,
(4) emotional hook, (5) risk reversal. Suggest 3 A/B test ideas per VP.
```

**Deliverable:** Shortlist of VP statements + test plan.

---

### 7.5.3 Channels (CH) & Customer Relationships (CR)
**Goal:** Map awareness → evaluation → purchase → delivery → support.

**AI Prompt (Channel Mix)**
```
Given our ICPs and VP [paste], rank channels by CAC efficiency and expected conversion.
Design a simple multi-touch journey (5 stages) with one KPI per stage and a 2-week test plan.
```

**Deliverable:** Journey diagram + KPI table (AARRR alignment).

---

### 7.5.4 Revenue Streams (R$) & Pricing
**Goal:** Choose model(s) and estimate revenue under scenarios.

**AI Prompt (Pricing & Forecast)**
```
Recommend revenue model(s) for [startup]. Propose price points/tiers,
estimate ARPU and revenue under conservative/base/optimistic scenarios,
and list 5 pricing experiments. Return a 12-month simple forecast table.
```

**Deliverable:** Model choice, pricing ladder, 12-month forecast (base/bear/bull).

### 7.5.4.1 Common Revenue Models for Startups

**Revenue models** define *how* value is captured once it is created and delivered. AI-based startups can combine multiple models depending on the market segment, data strategy, and scalability potential.  

| **Model** | **Description** | **AI-Relevant Examples** | **When to Use** |
|------------|-----------------|--------------------------|----------------|
| **Subscription** | Recurring fee for continued access (monthly/annual). | SaaS platforms (e.g., ChatGPT Plus, Jasper AI). | Predictable revenue, sticky user base. |
| **Freemium** | Free basic tier; users pay for advanced features or limits. | Grammarly, Notion AI. | Easy adoption, viral growth, upsell path. |
| **Pay-per-Use / Usage-Based** | Users pay proportionally to consumption (API calls, minutes, tokens). | OpenAI API, AWS AI services. | Variable usage patterns, scalable cloud models. |
| **Commission / Marketplace** | Platform takes a % of each transaction between two parties. | Fiverr, Upwork, Airbnb. | Multi-sided platforms connecting providers and consumers. |
| **Licensing** | Sell or lease the right to use technology or IP. | Enterprise AI model licensing. | B2B deals, proprietary algorithms, data/IP leverage. |
| **Advertising / Data Monetization** | Free service monetized through ads or anonymized data insights. | Google, Meta, data-analytics dashboards. | High user volume, low willingness to pay directly. |
| **Affiliate / Referral** | Earn a share for promoting or referring third-party products. | Influencer or AI-content recommendation engines. | Complementary product ecosystems. |
| **Transactional / One-Time Sales** | Direct purchase of a digital or physical product. | AI-powered devices, e-books, datasets. | Simple offerings, low maintenance. |
| **Hybrid** | Combination (e.g., subscription + usage + ads). | Spotify Premium, many SaaS bundles. | Multiple revenue streams or user types. |

> **Tip:** Start with one **dominant revenue model** to validate product–market fit and add complementary ones only after clear evidence of traction and unit-economic health.

**AI Prompt (Revenue Model Design)**
```
For this startup [describe briefly], recommend 2–3 viable revenue models.
For each, outline:
- Customer value logic (why they would pay)
- Pricing unit (seat, API call, minute, outcome, etc.)
- Key pros and cons
- Required data or infrastructure
- Short validation test (≤2 weeks)
Return as a table.
```

---

### 7.5.5 Cost Structure (C$) & Unit Economics
**Goal:** Compute CLV, CAC, CLV:CAC, and payback; highlight sensitivities.

**AI Prompt (Unit Economics)**
```
Using these assumptions [retention, ARPU, COGS, CAC], compute CLV, CLV:CAC, payback period.
Identify top 3 sensitivity drivers and propose changes to improve each metric.
```

**Deliverable:** Unit economics sheet + sensitivity notes.

---

### 7.5.6 KR/KA/KP & Partnership Mapping
**Goal:** Secure the capabilities and leverage the ecosystem.

**AI Prompt (Partner Map)**
```
For this BMC [paste], list 10 potential partners by type (supplier/tech/distribution/innovation),
value they add, risks, and a 3-step activation plan. Prioritize by impact vs. effort.
```

**Deliverable:** Prioritized partner pipeline.

---

### 7.5.7 Full-Canvas Consistency Check
**AI Prompt (Consistency & Risks)**
```
Review this BMC [paste]. Check consistency (CS↔VP↔CH/CR↔R$↔C$),
flag missing pieces, list top 5 risks with mitigations, and propose 2 alternative model variants.
Return a 30-60-90 day action sequence.
```

**Deliverable:** Issues list + 90-day plan.

---

## 7.6 Worked Examples (Topic 5 Startups)

### Case A — AI Personal Health Companion

**BMC Snapshot**
- **CS:** Adults with chronic conditions; caregivers; clinic programs (B2B2C).  
- **VP:** *Plain-language, timely “insight cards”* that reduce anxiety and improve adherence.  
- **CH:** Organic content, clinician referrals, app stores; B2B2C pilots.  
- **CR:** Onboarding tips, weekly progress emails, caregiver sharing.  
- **R$:** Subscription (consumer/family); B2B2C per-member-per-month; clinician dashboard upsell.  
- **KR:** Medical NLP/LLM, data connectors (EHR/wearables), clinician advisory.  
- **KA:** Data ingestion, inference, QA, compliance, GTM experiments.  
- **KP:** Wearable vendors, clinics, cloud/PHI-compliant infra.  
- **C$:** Compute, data pipelines, support, GTM, compliance.

**Unit Economics (illustrative)**
- **ARPU (consumer):** $12/mo   **Gross margin:** 70%  
- **CAC (consumer):** $24   **Payback:** ≈3 months (at 70% GM)  
- **CLV (12 mo @ net retention 80%):** ≈ $115   **CLV:CAC:** ≈ 4.8  

**Primary Engine:** **Sticky** (timely insights build habit).  
**Pivot Watch:** If D+28 retention < 10% → **Customer Need** pivot (content vs. timing) or **Zoom-In** on “trend cards”.

---

### Case B — AI-Powered Language Tutor for Immigrants

**BMC Snapshot**
- **CS:** Newcomers, job seekers, community-college students, NGOs (site licenses).  
- **VP:** *Low-anxiety, job-relevant role-plays* with real-time corrections and progress badges.  
- **CH:** SEO/YouTube, partner NGOs/colleges, WhatsApp communities.  
- **CR:** Streaks, weekly reviews, peer practice invites.  
- **R$:** Freemium minutes; paid “coach review” packs; school/NGO licenses.  
- **KR:** ASR/NLU models, conversation flows, teacher community.  
- **KA:** Content scripting, evaluation, cohort growth experiments.  
- **KP:** NGOs, colleges, employer groups, cloud/ASR vendors.  
- **C$:** Compute, content ops, support, partner rev-share.

**Unit Economics (illustrative)**
- **ARPU (mixed):** $6/mo   **Gross margin:** 60%  
- **CAC (freemium → paid blended):** $9   **Payback:** ≈ 2.5–3 mo (with viral assists)  
- **CLV (8 mo @ net retention 70%):** ≈ $34   **CLV:CAC:** ≈ 3.8  

**Primary Engine:** **Viral** (peer/teacher invites).  
**Pivot Watch:** If student cohorts outperform others → **Customer Segment** focus or **Zoom-In** on “Interview Coach”.

---

## 7.7 CW 7.1 In-Class Exercise — BMC Assembly & Stress Test
**Objective:** Produce a coherent BMC, compute basic unit economics, and stress-test assumptions.

**Steps (30–35 min):**
1) **Draft BMC (15’):** Fill all 9 blocks; mark 3 riskiest assumptions (⭐).  
2) **Unit Economics (7’):** Estimate CLV, CAC, CLV:CAC, payback.  
3) **Stress Test (8–13’):** Discuss scenarios (**CAC ×2**, **fast follower**, **key partner fails**, **demand +10×**). Write one mitigation per risk.

**Submission (in class):**  
- One-page BMC + one-page metrics & risks (PDF).  
- Add 2 next experiments (what, metric, threshold, decision rule).

---

## 7.8 HW 7.1 Homework — BMC + Validation Plan (2–3 pages)
**Deliverables:**
1) **Finalized BMC** with top 5 assumptions & mitigations.  
2) **Revenue & Pricing:** chosen model(s), pricing ladder, 12-month base/bear/bull.  
3) **Unit Economics:** CLV, CAC, CLV:CAC, payback, top sensitivities.  
4) **90-Day Plan:** 3 experiments (hypothesis, metric, threshold, decision rule).

**Rubric (10 pts)**
- BMC clarity & coherence (3)  
- Pricing/revenue logic & scenarios (2)  
- Unit economics (2)  
- Experiments & decision rules (2)  
- Formatting/clarity (1)

---

## Final Deliverables (Upload to Canvas)
- **CW 7.1:** BMC + metrics & risks (PDF, 2 pages).  
- **HW 7.1:** BMC + validation plan (PDF, 2–3 pages).  
- (Optional) Screenshots of AI prompt outputs supporting decisions.

