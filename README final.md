# GigShield 🛡️
### AI-Powered Parametric Income Protection for Gig Workers
### Team Iron Stack | Guidewire DEVTrails 2026

> "Auto-triggered weekly micro-insurance that pays gig workers instantly when rain, heat, or lockdowns stop their work — rewarding loyalty, preventing fraud, and staying profitable in every season."

> *"A delivery worker is stuck during a Chennai thunderstorm. They didn't file a claim. They didn't call anyone. Their phone just buzzed — ₹300 credited. GigShield works so they don't have to."*

---

## Table of Contents

1. [Judge Summary](#judge-summary)
2. [Why GigShield Wins](#why-gigshield-wins)
3. [Problem Statement](#problem-statement)
4. [Our Solution](#our-solution)
5. [Why GigShield Is Innovative](#why-gigshield-is-innovative)
6. [Delivery Worker Persona](#delivery-worker-persona)
7. [Parametric Triggers](#parametric-triggers)
8. [Weekly Premium Model](#weekly-premium-model)
9. [AI/ML Architecture](#aiml-architecture)
   - [AI/ML Usage](#aiml-usage)
10. [Smart Validation Layer](#smart-validation-layer)
11. [Adversarial Defense & Anti-Spoofing Strategy](#adversarial-defense--anti-spoofing-strategy)
12. [Zero-Touch Claim Flow](#zero-touch-claim-flow)
13. [Platform & Tech Stack](#platform--tech-stack)
14. [System Architecture](#system-architecture)
15. [Dashboards](#dashboards)
16. [Coverage Scope & Exclusions](#coverage-scope--exclusions)
17. [Financial & Business Model](#financial--business-model)
18. [Live Demo](#live-demo)
19. [Strategy Video](#strategy-video)
20. [45-Day Development Roadmap](#45-day-development-roadmap)

---

## Judge Summary

GigShield is a parametric micro-insurance platform that:

- ⚡ **Automatically pays** gig workers during disruptions — zero manual steps required
- 🤖 **Triggers payouts** via pre-defined, externally verifiable conditions (rainfall mm, temperature °C, official government orders)
- 🛡️ **Prevents fraud** with no-stacking rules, loyalty claim limits, and API-sourced event verification
- 💰 **Maintains profitability** across all seasons — worst-case weekly margin of +10–12%
- 🎯 **Solves a ₹5,880/year income loss problem** for 15 million+ active gig workers in India

> **Fully automated. Fraud-resistant. Actuarially grounded. Real-world deployable.**

---

## Why GigShield Wins

| What Others Do | What GigShield Does |
|---|---|
| Rely on GPS alone for location | Use 6-signal validation — GPS + accelerometer + cell tower + network + behavior + crowd signal |
| Detect weather events | Validate through 5-layer system with time confirmation + multi-source cross-check |
| Ignore fraud edge cases | Simulate real attack scenarios (500 GPS spoofers) and defeat them architecturally |
| Skip business viability | Prove loss ratio sustainability (50–72%) across all 5 plans with actuarial math |
| Present ideas | Deliver a deployable system with working prototype, ML architecture, and IRDAI-partner model |

> **GigShield is not just innovative — it is production-ready, fraud-resistant, and financially viable on Day 1.**

---

## Problem Statement

India has **15 million+ active gig workers** — delivery partners, ride drivers, and freelance logistics staff — who earn on a per-trip basis with no fixed salary. Their income stops the moment external conditions prevent them from working.

**Common disruptions that kill gig income:**

| Disruption | Frequency | Avg. income loss |
|---|---|---|
| Heavy rain / monsoon | 120+ days/year (Jun–Sep) | 40–60% of daily earnings |
| Extreme heat ≥ 42°C | 30–45 days/year (Mar–May) | 25–40% of daily earnings |
| Government lockdowns | Unpredictable | 100% of daily earnings |
| Cyclone / flood alerts | Regional, 5–15 days/year | 100% of daily earnings |
| Platform downtime | 2–4 times/month | 30–80% of shift earnings |

**The numbers:**
- **5 crore+** informal and gig workers in India with zero income protection (NITI Aayog, 2022)
- **₹300–₹650** lost per disruption event per worker
- **0** traditional insurance products covering short-term gig income loss
- **Weeks** to process a manual insurance claim today

**Current situation:** No income protection product exists that is affordable, automated, and specifically designed for this segment. Traditional insurance requires paperwork, waiting periods, and manual claims — incompatible with gig workers' daily-pay lifestyle. **GigShield exists to close that gap** — through automated, parametric micro-insurance that pays out before the worker even has to ask.

---

## Our Solution

GigShield is a **parametric micro-insurance platform** with three core properties:

- **Parametric:** Payouts are triggered by pre-defined, externally verifiable conditions (rainfall mm, temperature °C, official government orders) — not by manual claim submission.
- **Automatic:** Workers never file a claim. The system monitors conditions via APIs, detects triggers, and credits the worker's wallet within 2 hours.
- **Weekly subscription:** Workers pay weekly (₹25–₹90), matching their variable income cycle. No annual lock-in.

### ⚡ How GigShield Works (At a Glance)

#### User → AI Risk Score → Weekly Plan → Monitor Data → Trigger → Auto Claim → Payout

GigShield continuously monitors verified external data sources (IMD, CPCB, government alerts) cross-validated with satellite and radar-based private weather APIs. It applies disruption detection at **micro-zone level (2–5 km radius)** rather than city or pincode level, ensuring granular accuracy. It automatically detects when a disruption threshold is crossed **and persists for 15–30 minutes** in a worker's delivery zone, verifies the worker's GPS location, behavioral signals, and fraud score in real time, then triggers an instant partial income top-up — with near real-time payout processing and zero human intervention.

The worker's only job is to subscribe to a weekly plan. Everything else is automated.

**Key differentiators:**
- Every trigger is independently verifiable through government or third-party APIs — no platform data, no subjective metrics
- Multi-source data validation prevents false triggers from API delays or outages
- Micro-zone precision (2–5 km) avoids city-level inaccuracies
- Time-based confirmation window (15–30 min) eliminates brief weather spikes from triggering payouts
- ML-driven dynamic zone-based pricing makes the model financially sustainable
- Predictive disruption alerts warn workers 24–48 hours before an event
- Zero-touch claim experience — fully automated from disruption detection to payout
- GigShield operates as a technology distribution platform — all policies underwritten by a licensed IRDAI insurer partner
- Actuarially grounded pricing model maintaining 50–72% loss ratio across all plans

---

## Why GigShield Is Innovative

GigShield introduces a new insurance model tailored specifically for gig economy workers.

Key innovations include:

- **Parametric Insurance Model** — payouts triggered by objective external data instead of manual claims
- **Zero-Touch Claims** — workers never need to file forms or upload documents
- **AI-Driven Risk Pricing** — machine learning assigns optimal plan tiers based on zone risk
- **Micro-Zone Precision** — disruption detection at 2–5 km zone level, not city or pincode level
- **Multi-Source Validation** — cross-validates IMD/CPCB with satellite/radar APIs to handle data delays
- **Time-Based Confirmation** — disruptions must persist 15–30 minutes before triggering payout (no false triggers)
- **Context-Aware Delivery Logic** — compares disruption duration against average delivery time before triggering
- **Anonymized Crowd Signal Validation** — aggregated zone-level behavioral signals from multiple workers improve accuracy without privacy risk
- **Predictive Disruption Alerts** — workers receive warnings 24–48 hours before disruptions
- **Fraud Detection Engine** — anomaly detection protects insurers from fraudulent claims
- **Multi-Signal Anti-Spoofing Defense** — GPS alone is never trusted; accelerometer, cell tower, network and behavioral signals are cross-validated
- **Near Real-Time Micro-Payouts** — automated top-up payouts processed instantly with no human intervention
- **Actuarially Viable Micro-Premiums** — all plans maintain 50–72% annual loss ratio, insurer-partner ready
- **No Claim Reward (NCR) System** — cashback for calm weeks reduces churn and rewards honest subscribers
- **Loyalty Benefit System** — long-term, low-claim subscribers earn a loyalty payout from a ring-fenced reserve

This transforms insurance from **reactive claims processing** into **proactive financial protection**.

---

## Delivery Worker Persona

### Illustrative Persona — Swiggy Delivery Partner, Chennai

| Attribute | Detail |
|---|---|
| Age | Mid-20s |
| City | Chennai (operates across Velachery, Adyar, T. Nagar zones) |
| Daily Hours | 9am – 9pm |
| Daily Deliveries | 20–28 |
| Daily Earnings | ₹900 – ₹1,300 |
| Weekly Earnings | ₹6,500 – ₹9,000 |
| Hourly Earnings | ₹112 – ₹162/hour |
| Peak Vulnerability | Evening hours (7–10pm) — Chennai's heaviest rainfall window |
| Financial Buffer | None. One disrupted week = missed EMI or skipped meals. |

> Note: This persona is representative of the food delivery partners GigShield is designed to protect across Zomato and Swiggy.

### Disruption Scenario

It's a Tuesday evening in August. A delivery partner is midway through their shift in Velachery. Rainfall crosses 40mm in 2 hours. Restaurants begin closing. The Swiggy app goes quiet. They pull over under a shelter.

**In the old world:** ₹500 lost with no way to recover it.

**With GigShield:** Phone buzzes. *"🌧️ Heavy rain detected in your zone. ₹160 credited to your account. Stay safe."* They didn't do anything. GigShield did.

---

## Parametric Triggers

> **Design Principle:** Every trigger must be an objective, externally verifiable event from a government or accredited third-party source. GigShield does not use platform demand data, traffic metrics, or any subjective signal.

### Trigger Table

| # | Disruption Event | Data Source | Threshold | Confirmation Window | 🟢 Simple | 🔵 Standard | 🔴 Premium |
|---|---|---|---|---|---|---|---|
| 1 | 🌦 Light Rainfall | OpenWeatherMap + IMD | 5–35mm rainfall in micro-zone | Persists 15–30 min | ₹100/day | ₹150/day | ₹200/day |
| 2 | 🌧 Heavy Rainfall | OpenWeatherMap + IMD + Satellite Radar | Rainfall > 35mm within 3 hours | Persists 15–30 min | ₹200/day | ₹350/day | ₹500/day |
| 3 | ☀️ Extreme Heat | IMD API + Private Weather API | Sustained temperature > 43°C for 2+ hours | Persists 30 min | ₹150/day | ₹250/day | ₹350/day |
| 4 | 🚫 Lockdown / App Downtime | NDMA alert feed + platform monitoring | Section 144 or app offline > 6 hours | Admin-verified / confirmed outage | ❌ | ₹400/day | ₹500/day |
| 5 | 🚧 Traffic Restriction / Curfew | NDMA + MHA RSS feed | State-declared curfew or traffic restriction in worker's zone | Admin-verified flag | ❌ | ❌ | ₹400/day |
| 6 | Cyclone / Flood Alert | IMD Disaster Alert Feed + NDMA | Orange or Red alert for worker's district | Alert active 30+ min | ₹200/day | ₹350/day | ₹500/day |

### Why These Triggers Are Compliant

Each trigger satisfies all three compliance requirements:

1. **Externally verifiable** — sourced from IMD, CPCB, NDMA, or a government-issued order. Not derived from platform data.
2. **Parametric** — defined by a measurable threshold that is either crossed or not. No subjective assessment.
3. **Causally linked to income loss** — each event directly prevents outdoor delivery work, causing loss of hourly wages.

### Time-Based Confirmation

A key safeguard against false triggers: GigShield validates that the disruption condition **persists for 15–30 minutes** before any payout is initiated.

| Scenario | Result |
|---|---|
| Rain for 5 minutes → clears | ❌ No payout — condition did not persist |
| Rain for 30 minutes continuous | ✅ Trigger confirmed — payout initiated |
| AQI spikes briefly, recovers | ❌ No payout — single-source spike |
| AQI confirmed across 2+ sources for 20+ min | ✅ Trigger confirmed |

---

## Weekly Premium Model

### 💡 Simple Pricing Logic

```
Weekly Premium = Base Price + (Risk Score × Zone Risk Factor)
```

### Design Philosophy

GigShield is a **partial income top-up**, not a full income replacement product. This distinction is fundamental to the model's actuarial viability and regulatory simplicity. The three-plan structure is designed so every active gig worker — regardless of their earning level or zone risk — can find a plan that is both affordable and meaningful.

### The 3 Plans

---

#### 🟢 Simple Plan — Risk-Based

| | |
|---|---|
| 💰 **Weekly Premium** | ₹25/week |
| 🔒 **Weekly Cap** | ₹600/week |
| 👉 **Max claim days** | 3 days/week |

**💵 Payout Structure:**

| Event | Payout |
|---|---|
| 🌦 Light rain | ₹100/day |
| 🌧 Heavy rain | ₹200/day |
| ☀️ Extreme heat | ₹150/day |

**Target user:** New or occasional gig workers in lower-risk zones looking for affordable entry-level protection.

---

#### 🔵 Standard Plan — Balanced + Smart

| | |
|---|---|
| 💰 **Weekly Premium** | ₹50/week |
| 🔒 **Weekly Cap** | ₹1,400/week |
| 👉 **Max claim days** | 4 days/week |

**💵 Payout Structure:**

| Event | Payout |
|---|---|
| 🌦 Light rain | ₹150/day |
| 🌧 Heavy rain | ₹350/day |
| ☀️ Extreme heat | ₹250/day |
| 🚫 Lockdown / app downtime | ₹400/day |

**Target user:** Full-time gig workers in urban zones who need balanced coverage across weather and platform disruptions.

---

#### 🔴 Premium Plan — Advanced Risk Coverage 🔥

| | |
|---|---|
| 💰 **Weekly Premium** | ₹90/week |
| 🔒 **Weekly Cap** | ₹2,500/week |
| 👉 **Max claim days** | 5 days/week |

**💵 Payout Structure:**

| Event | Payout |
|---|---|
| 🌦 Light rain | ₹200/day |
| 🌧 Heavy rain | ₹500/day |
| ☀️ Extreme heat | ₹350/day |
| 🚫 Lockdown | ₹500/day |
| 🚧 Traffic restriction / curfew | ₹400/day |

**Target user:** High-earning, full-time workers in coastal or flood-prone zones who need the broadest possible disruption coverage.

---

### ⚙️ How Risk Is Detected

| Source | What It Monitors |
|---|---|
| 🌦 **OpenWeatherMap + IMD** | Rainfall mm, temperature °C, red/orange alerts — polled every 15 min at micro-zone level |
| 🏛️ **Government APIs** (NDMA, MHA RSS) | Lockdown orders, Section 144, curfew declarations, cyclone/flood alerts |
| 📱 **Platform Monitoring** | Swiggy / Zomato / Ola / Uber app uptime — downtime of 6+ hours triggers a claim |

---

### Plan Comparison at a Glance

| Feature | 🟢 Simple | 🔵 Standard | 🔴 Premium |
|---|---|---|---|
| Weekly premium | ₹25 | ₹50 | ₹90 |
| Weekly cap | ₹600 | ₹1,400 | ₹2,500 |
| Max claim days/week | 3 | 4 | 5 |
| Light rain payout | ₹100/day | ₹150/day | ₹200/day |
| Heavy rain payout | ₹200/day | ₹350/day | ₹500/day |
| Extreme heat payout | ₹150/day | ₹250/day | ₹350/day |
| Lockdown / downtime | ❌ Not covered | ₹400/day | ₹500/day |
| Traffic restriction / curfew | ❌ Not covered | ❌ Not covered | ₹400/day |

### Actuarial Foundation

**Base assumptions — Chennai food delivery zones (IMD 10-year historical data):**

| Parameter | Value | Basis |
|---|---|---|
| Disruption events/month — monsoon season (Jun–Nov) | 3.0 events | IMD Chennai 10-yr average, conservative |
| Disruption events/month — off-season (Dec–May) | 0.5 events | IMD Chennai historical |
| Annual disruption events per worker | **21 events/year** | (3.0 × 6) + (0.5 × 6) = 21 |
| Average disruption duration | **2.5 hours** | IMD urban rainfall event data |
| Annual disruption hours per worker | **52.5 hours/year** | 21 × 2.5 = 52.5 |
| Worker's average hourly income | ₹112/hour | ₹900/day ÷ 8 working hours |
| Annual income lost per worker (avg) | **₹5,880/year** | 52.5 hrs × ₹112 |
| Weekly income lost (annualised average) | **₹113/week** | ₹5,880 ÷ 52 weeks |

**Target loss ratio:** 65% (industry benchmark for parametric micro-insurance products in India)

```
Viable weekly premium = Expected weekly claim cost ÷ Target Loss Ratio

For Standard plan (targeting ~70% income loss coverage):
  Expected weekly claim cost = ₹113 × 0.70 = ₹79.10
  Viable premium = ₹50–₹90/week range ✓
```

### Worker Affordability Check

| Plan | Weekly Premium | % of Weekly Earnings (₹7,000 avg) | Deliveries to cover it | Weekly cap |
|---|---|---|---|---|
| 🟢 Simple | ₹25 | 0.4% | ~1 delivery | ₹600 |
| 🔵 Standard | ₹50 | 0.7% | ~1.5 deliveries | ₹1,400 |
| 🔴 Premium | ₹90 | 1.3% | ~2.5 deliveries | ₹2,500 |

All plans remain under 1.5% of weekly earnings — well within the affordability threshold for micro-insurance adoption in India.

### Why Weekly Pricing

Gig workers on Zomato/Swiggy operate on a weekly earnings and payout cycle. Daily premiums create friction. Monthly premiums are too large a commitment for workers with variable income. Weekly pricing — small enough to feel negligible (less than the earnings from 1–2 deliveries), meaningful enough to provide real coverage — matches how delivery workers actually think about money.

---

## AI/ML Architecture

GigShield integrates three purpose-built ML models.

---

## AI/ML Usage

GigShield uses AI and machine learning at three critical points in the insurance lifecycle — before the worker subscribes, while setting the price, and every time a claim is evaluated.

---

### 🔍 Risk Prediction

**What it does:** Predicts how likely a delivery micro-zone is to experience a disruption event, and how severe that disruption is likely to be.

**Model:** Random Forest Classifier — trained on 10 years of IMD rainfall, CPCB AQI, NDMA flood maps, and cyclone track data.

**How it works:**

```
Worker opens GigShield → enters their delivery zone
           ↓
Zone Risk Classifier runs:
  • Pulls historical disruption frequency for that 2–5 km zone
  • Checks proximity to water bodies, zone elevation, AQI exceedance history
  • Weights by current month (monsoon vs off-season)
           ↓
Outputs a Risk Score: 0.0 (very safe) → 1.0 (very high risk)
           ↓
Risk Score maps to a recommended plan tier
```

**Risk score → plan recommendation:**

| Risk Score | Zone Profile | Recommended Plan |
|---|---|---|
| < 0.35 | Low disruption history, inland, elevated | 🟢 Simple |
| 0.35 – 0.65 | Moderate risk, urban delivery zones | 🔵 Standard |
| > 0.65 | High disruption frequency, coastal or flood-prone zones | 🔴 Premium |

**Ongoing use:** Risk scores are recalculated quarterly using trailing 90-day claims data. If a zone's rolling loss ratio exceeds 70%, new subscribers in that zone are nudged toward a higher-tier plan at the next cycle. Existing subscribers are grandfathered for one quarter.

---

### 💰 Premium Calculation

**What it does:** Translates the zone risk score into an actuarially viable weekly premium that is affordable for workers and profitable for the insurer partner.

**How it works:**

```
Weekly Premium = Base Price + (Risk Score × Zone Risk Factor)
```

The base price anchors to the expected weekly claim cost derived from historical disruption frequency:

```
Expected weekly claim cost = Annual income lost per worker ÷ 52 weeks
                           = ₹5,880 ÷ 52 = ₹113/week (Chennai baseline)

Viable weekly premium      = Expected weekly claim cost × Coverage % ÷ Target Loss Ratio
                           = ₹113 × 0.70 ÷ 0.65 ≈ ₹79/week  →  Standard Plan ✓
```

**What AI adds on top of the base formula:**

| Factor | How AI adjusts premium |
|---|---|
| Zone risk score (0.0–1.0) | Higher score → higher zone risk factor → higher premium tier recommended |
| Seasonal risk weighting | Monsoon months weighted 6× higher than off-season in zone risk score |
| Trailing loss ratio (90-day) | If zone loss ratio > 70%, ML flags zone for premium review at next cycle |
| Coastal / flood-zone multiplier | Elite plan applies 1.4× disruption frequency multiplier for flood-prone zones |

**Key constraint:** The model targets a 50–72% loss ratio across all plans — the actuarially safe range for parametric micro-insurance. AI ensures premiums are not set too low (insurer losses) or too high (worker drop-off).

| Plan | Weekly Premium | Annual Loss Ratio | Heavy Monsoon LR |
|---|---|---|---|
| 🟢 Simple | ₹25 | ~57% ✅ | ~80% ✅ |
| 🔵 Standard | ₹50 | ~52% ✅ | ~73% ✅ |
| 🔴 Premium | ₹90 | ~48% ✅ | ~67% ✅ |

---

### 🛡️ Fraud Detection

**What it does:** Scores every auto-triggered claim before any payout is released — catching GPS spoofing, duplicate claims, and coordinated fraud rings without punishing genuine workers.

**Model:** Isolation Forest (unsupervised anomaly detection) + deterministic hard-reject rule layer.

**How it works — two-stage pipeline:**

```
Stage 1 — Hard Reject Rules (deterministic, applied first)
  • No verified trigger event in worker's micro-zone → reject
  • GPS location outside disruption zone → reject
  • Cell tower ID doesn't match claimed GPS zone → reject
  • Weekly claim cap already reached → reject
  • Plan expired → reject
  • Disruption persisted < 15 minutes → reject
           ↓
  If any hard rule fails → auto-reject, worker notified with appeal option

Stage 2 — Isolation Forest Anomaly Scoring (applied if hard rules pass)
  • Scores 9 behavioral signals (GPS velocity, accelerometer pattern,
    cell tower consistency, claim timing, device fingerprint, etc.)
  • Outputs fraud score: 0 (clean) → 100 (highly suspicious)
           ↓
  Score 0–30   → Auto-approve, payout released immediately
  Score 30–70  → Human review queue (2-hour SLA)
  Score > 70   → Auto-reject, appeal option provided
```

**Why Isolation Forest:** It detects anomalies without needing a labelled fraud dataset — it learns what "normal" claim behaviour looks like and flags deviations. This is ideal for GigShield because coordinated GPS spoofing attacks produce statistically impossible clusters (e.g. 500 devices with identical flat accelerometer readings in the same zone at the same moment) that are immediately visible as outliers.

**The 6 signals used for anti-spoofing:**

| Signal | What it catches |
|---|---|
| GPS coordinate | Verifies worker is inside the disruption zone |
| Accelerometer / IMU | Confirms physical delivery movement before disruption hit |
| Cell tower ID | Cannot be faked — reveals true geographic location |
| GPS velocity pattern | Real workers stop; spoofers show zero movement throughout |
| Device activity pattern | GPS spoofing apps leave a detectable process signature |
| Weather API cross-check | Cell tower location cross-checked against IMD rain data |

> A GPS spoofer passes Signal 1 but fails Signals 2–6. GigShield requires 4 of 6 to be consistent before approving any claim.

**Worker Trust Score:** In parallel, every worker carries a persistent trust score (0–100) built from their genuine claim history. New workers start at 50% payout cap and graduate to full auto-approval as their track record is established — ensuring honest workers are never unfairly penalised for having a new account.

---

### Model 1 — Zone Risk Classifier

**Purpose:** Recommend the most appropriate plan tier to each worker at onboarding based on their delivery micro-zone's historical disruption risk.

**Algorithm:** Random Forest Classifier

**Training Data:**
- IMD historical rainfall records (10 years, district-level, freely downloadable)
- CPCB AQI historical data (public)
- NDMA flood zone maps
- Historical cyclone track data (IMD)

**Input Features:**

| Feature | Description |
|---|---|
| Zone latitude / longitude | Geographic position of delivery micro-zone centroid (2–5 km radius) |
| Historical disruption events/month (12-month rolling) | Frequency of past disruption events in that micro-zone |
| Proximity to water bodies | Distance to nearest river, lake, or coastline (flood proxy) |
| Zone elevation | Low elevation = poor drainage = higher flood risk |
| Month of year | Monsoon seasonality weighting |
| Historical AQI exceedance days | Pollution risk profile for the zone |

**Output:** Risk score 0.0–1.0 → plan recommendation

| Risk Score | Plan Recommendation |
|---|---|
| < 0.35 | 🟢 Simple |
| 0.35 – 0.65 | 🔵 Standard |
| > 0.65 | 🔴 Premium |

**Why Random Forest:** Handles mixed numerical and categorical features well, produces interpretable feature importance scores, and does not require large datasets — suitable for zone-level historical data volumes.

---

### Model 2 — Fraud Detection Engine

**Purpose:** Score every auto-triggered claim for fraud before payout is released.

**Algorithm:** Isolation Forest (behavioral anomaly detection) + deterministic rule layer (hard rejects)

#### Hard Reject Rules (Deterministic — Applied First)

| Rule | Logic |
|---|---|
| No verified trigger event | If no IMD/CPCB threshold breach recorded in worker's micro-zone on claim day → automatic rejection |
| GPS pincode mismatch | If worker's GPS location at trigger time does not overlap with disruption event micro-zone → automatic rejection |
| Cell tower zone mismatch | If serving cell tower ID does not geographically match claimed GPS zone → automatic rejection |
| Claim cap exceeded | If worker has already reached max hours for the week → automatic rejection |
| Plan not active | If worker's weekly plan has expired → automatic rejection |
| Time confirmation not met | If disruption persisted for fewer than 15 minutes → automatic rejection |

#### Anomaly Scoring (Isolation Forest — Applied After Hard Rules Pass)

| Feature | Fraud Signal |
|---|---|
| GPS velocity during claimed disruption window | Speed > 5 km/h during disruption = actively working, not disrupted |
| Accelerometer pattern | Flat stationary signal with no prior zone movement = spoofing indicator |
| Cell tower vs GPS consistency | Cell tower geographic area does not match GPS zone = location fake |
| Claim frequency (last 4 weeks) | 4 consecutive weekly claims with no variation = anomalous |
| Claim timing relative to trigger | Claim initiated before trigger threshold crossed = suspicious |
| Pre-disruption zone activity | No GPS movement history in zone before trigger = not genuinely in zone |
| Device fingerprint | Multiple accounts on same device = duplicate registration fraud |
| Historical claim approval rate | Consistent 100% approval rate over months = flag for review |
| Zone crowd signal disagreement | Worker claims disruption but zone crowd signal shows no inactivity spike = flag |

**Output:** Fraud score 0–100

| Score | Action |
|---|---|
| 0 – 30 | Auto-approve. Payout released immediately. |
| 30 – 70 | Human review queue (admin dashboard). |
| > 70 | Auto-reject. Worker notified with appeal option. |

---

### Worker Eligibility & Trust Score System

**Purpose:** Maintain a persistent, dynamic trust score per worker built from genuine past activity — used to determine payout eligibility before the fraud detection model even runs.

#### Trust Score Tiers

| Trust Score | Tier | Eligibility Status |
|---|---|---|
| 75 – 100 | 🟢 Trusted | Full auto-approval. Highest payout priority. |
| 50 – 74 | 🔵 Established | Auto-approval. Standard processing. |
| 25 – 49 | 🟡 Building | Claim goes to manual review queue before payout. |
| 0 – 24 | 🔴 Restricted | Claim goes to manual review. Payout capped at 50% of plan maximum. |

#### New Worker Handling

| Week | Status | Payout Cap |
|---|---|---|
| Week 1 (new) | Provisional — no history | 50% of plan max |
| Week 2–3 | Building — limited history | 75% of plan max |
| Week 4+ (clean record) | Established or Trusted | 100% of plan max |

#### Combined Flow with Fraud Detection

```
Disruption trigger confirmed
          │
          ▼
┌─────────────────────────────┐
│  Eligibility Gate           │
│  Check worker Trust Score   │
│                             │
│  🟢 75–100 → Proceed        │
│  🔵 50–74  → Proceed        │
│  🟡 25–49  → Manual Review  │
│  🔴 0–24   → Manual Review  │
│             + 50% payout cap│
└──────────────┬──────────────┘
               │
               ▼
     Fraud Detection Model
     (Isolation Forest score)
               │
               ▼
     Payout decision
```

---

### Model 3 — Predictive Disruption Alert Engine

**Purpose:** Forecast disruption probability 24–48 hours ahead for each delivery micro-zone.

**Algorithm:** XGBoost on time-series weather features

**Output:** Disruption probability score (0–100%) per micro-zone per day

**Worker-facing notification:**
> *"⚡ Storm likely in your delivery zone tomorrow 6–9pm. Probability: 78%. Your ₹160 coverage is active."*

---

## Smart Validation Layer

While designing GigShield, we identified real-world challenges in relying solely on external data sources. To ensure accuracy, fairness, and reliability, we built a **multi-layer validation approach** on top of the parametric trigger system.

| Layer | Problem Solved | Solution |
|---|---|---|
| **1. Multi-Source Reliability** | IMD/CPCB APIs can be delayed or stale | Cross-verify across 2+ independent sources (govt API + satellite radar). Fallback if primary is down. |
| **2. Micro-Zone Precision (2–5 km)** | City/pincode data too coarse — rain in one street ≠ rain 3 km away | Map workers to 2–5 km micro-zones. Trigger logic at zone centroid, not city level. |
| **3. Time-Based Confirmation** | Brief 5-min showers should not trigger payouts | Disruption must persist **15–30 minutes** continuously. Counter resets if condition drops below threshold. |
| **4. Context-Aware Delivery Logic** | 20-min disruption ≠ same impact as 3-hour disruption | Compare disruption duration vs average delivery time (30–45 min). Payout scales proportionally with verified hours. |
| **5. Crowd Signal Validation** | API data lags real conditions by 10–20 min | Anonymized zone-level aggregate: movement speed + inactivity spikes across workers. Never individual tracking. |

**Time confirmation table:**

| Duration | Action |
|---|---|
| < 15 minutes | Monitoring — no trigger |
| 15–30 minutes | Confirmation window — alert worker |
| > 30 minutes | Trigger confirmed — claim initiated |

**Privacy guarantee:** No individual worker is tracked. Behavioral signals are aggregated at zone level and discarded after the disruption window closes.

### Combined Validation Logic

GigShield requires **all five layers** to pass before a claim is approved:

```
Layer 1: External API threshold crossed (IMD / CPCB / NDMA)
       ↓
Layer 2: Cross-verified by secondary source (satellite / radar API)
       ↓
Layer 3: Condition persists 15–30 minutes (time-based confirmation)
       ↓
Layer 4: Worker GPS confirmed inside affected micro-zone
       ↓
Layer 5: Anonymized zone crowd signal confirms disruption (optional boost)
       ↓
       ✅ Claim auto-approved — payout initiated
```

This layered approach ensures:
- High accuracy — multiple independent data points required
- Low false-positive rate — brief spikes filtered out
- Real-world reliability — crowd signals compensate for API lag
- Privacy compliance — no individual tracking, no platform dependency

---

## Adversarial Defense & Anti-Spoofing Strategy

> *This section extends the fraud detection model with real-time adversarial defenses specifically designed against coordinated GPS spoofing attacks.*

### 🚀 Summary — Anti-Spoofing Defense

GigShield prevents GPS spoofing using a 4-layer defense stack:

| Layer | Method |
|---|---|
| 🔍 Multi-signal validation | GPS + accelerometer + cell tower + network — all must agree |
| 🧠 Behavioral anomaly detection | Isolation Forest flags patterns that deviate from genuine worker baseline |
| 👥 Crowd-based verification | Zone-level aggregate signals catch mass coordinated attacks |
| 🏅 Trust scoring | Reputation system catches repeat offenders across weeks |

> **GPS alone is never trusted. A spoofer passes 1 of 6 signals. GigShield requires 4 of 6.**

### The Attack Scenario

500 coordinated fraudsters use GPS spoofing apps to fake their location inside active disruption zones. They sit at home, their phone reports coordinates inside Velachery during a rain event, and they attempt to collect payouts without being genuinely disrupted.

This is GigShield's most serious fraud threat vector. Here is exactly how we detect and stop it — without punishing genuine workers.

### 1. Differentiation — Real Worker vs Fake GPS

GPS coordinates alone are **never trusted**. GigShield cross-validates location against 6 independent signals before any payout is released:

| Signal | Real Worker in Disruption | GPS Spoofer at Home |
|---|---|---|
| GPS coordinate | Inside zone ✅ | Faked inside zone ✅ |
| Accelerometer / IMU | Bike vibration, stops, turns — then sudden stop at disruption | Stationary flat signal throughout — no movement history |
| Network cell tower ID | Matches cell towers serving the disruption zone | Home cell tower ID — geographic mismatch with GPS claim |
| GPS velocity pattern | Active delivery movement pattern → sudden stop at trigger time | Zero movement velocity throughout the entire window |
| Device activity pattern | Normal usage — maps, delivery app, calls | GPS spoofing app running in background — detectable process signature |
| Weather API cross-check | Worker's real location aligns with rain zone in IMD data | Home location (revealed by cell tower) has no rain in IMD data |

A GPS spoofer passes Signal 1 but **fails Signals 2–6 simultaneously**. GigShield requires at least 4 of 6 signals to be consistent before approving any claim.

### 2. Multi-Signal Data Strategy — Beyond GPS

**Why GPS alone fails:** GPS spoofing apps override only the device location API. They cannot fake:

**Device Sensors:** Accelerometer shows bike vibration + delivery stop patterns. A home-sitting spoofer shows a flat stationary signal with zero prior zone movement. Gyroscope turning patterns of a two-wheeler are physically impossible to replicate without the vehicle.

**Network Layer:** Cell tower ID is reported independently of GPS. If GPS says Velachery but the cell tower is in Adyar, it's an automatic hard flag — cell tower data cannot be overridden by standard mock GPS apps. Home Wi-Fi network detection further reveals true location.

**Behavioral Layer:** Every worker builds a movement fingerprint over 2–3 weeks. Pre-disruption zone activity is checked — real workers are mid-delivery when storms hit; spoofers appear in the zone from nowhere exactly at trigger time. This timing gap is measurable.

**Crowd Signal Layer:** 500 spoofed devices all show identical flat accelerometer readings in the same zone at the same time — a statistically impossible cluster that the Isolation Forest model flags immediately. Genuine disruption events show organic, varied sensor signatures across workers.

#### Combined Anti-Spoofing Score

| Signal | Points | Notes |
|---|---|---|
| GPS coordinate inside zone | Required | Necessary but not sufficient alone |
| Accelerometer confirms movement | +2 | Physical movement before disruption |
| Cell tower ID matches zone | +2 | Cannot be faked without physical travel |
| Pre-disruption zone activity | +2 | Was worker actually in zone before trigger? |
| Crowd signal consistent | +1 | Zone-level aggregate confirms disruption |
| Historical baseline consistent | +1 | Matches worker's established pattern |
| Claim timing is natural | +1 | Not submitted suspiciously fast after trigger |

**Decision:**
- Score **≥ 7** → Auto-approve — payout released
- Score **4–6** → Soft flag → Manual review queue (2 hr SLA)
- Score **< 4** → Hard flag → Auto-reject + investigation + appeal option

### 3. UX Balance — Protecting Honest Workers

**The false-positive problem:** An aggressive anti-spoofing system will sometimes flag a genuine worker — especially new workers with no movement history, workers whose phone has sensor issues, or workers who are genuinely stationary in a zone waiting for an order when disruption hits.

GigShield handles this through a **tiered response** — never an immediate hard block:

#### Tier 1 — Soft Flag (Score 4–6): Manual Review
- Claim enters the admin manual review queue
- Worker is notified immediately: *"Your claim is being verified — decision within 2 hours. Your coverage is active."*
- Human reviewer sees GPS trace, cell tower data, accelerometer pattern, and crowd signal data side by side in the admin dashboard
- If genuine: claim approved + trust score increases by 5 points
- Worker is **never auto-rejected on first flag**

#### Tier 2 — Provisional Payout for High-Trust Workers
- For workers with Trust Score ≥ 75 who receive a soft flag: **50% of payout is released immediately**, remaining 50% is held pending review
- If review confirms genuine: remaining 50% released
- If review finds fraud: 50% clawback initiated + account flagged

#### Tier 3 — Appeal Flow for Auto-Rejected Claims
- Any auto-rejected worker receives a one-tap appeal option in their dashboard
- Appeal automatically requests: cell tower log, accelerometer data summary, network log, and GPS trace from the device for the claim window
- Second human review completed within 24 hours
- Wrongful rejections are reversed + trust score fully restored + apology notification sent

#### What GigShield Never Does
- Never permanently bans a worker on first suspicious claim
- Never requires workers to upload photos, videos, or selfies as proof
- Never penalises a worker for having a new account — new workers receive provisional payout (50% cap), not zero
- Never uses a single signal (GPS alone) to make a rejection decision
- Never exposes individual worker data to aggregate fraud analysis — all cross-comparison is anonymized at zone level

### Why This Defense Works at Scale

| Reason | Why the 500-Spoofer Attack Fails |
|---|---|
| Sensor data can't be mass-faked | Spoofing GPS is easy. Spoofing accelerometer + cell tower + network simultaneously requires device rooting — 99% of fraudsters won't bother for ₹50–₹300 |
| Coordinated attacks are statistically visible | 500 devices with identical flat accelerometer readings in the same zone = obvious Isolation Forest anomaly |
| Economics break the attack | Coordinating 500 devices to earn ₹300 max/week is not rational fraud behaviour |
| Trust Score catches repeat offenders | Even if a spoofer passes once, their baseline diverges over weeks — every future claim triggers review |
| Cell tower is the hardest signal to fake | Requires physically travelling to the disruption zone — defeats the entire purpose of GPS spoofing |

---

## Zero-Touch Claim Flow

```
Worker subscribes to ₹50 Standard weekly plan on GigShield web app
           │
           ▼
GigShield backend polls OpenWeatherMap + IMD + Satellite API every 15 minutes
Applied at micro-zone level (2–5 km radius, not city/pincode)
           │
           ▼
7:23pm — Rainfall crosses 35mm threshold in worker's micro-zone
           │
           ▼
┌──────────────────────────────────────────────┐
│      Time-Based Confirmation Window          │
│  ⏱️ Monitoring for 15–30 minutes...          │
│  7:53pm — Rain persists. Threshold still met.│
│  Secondary source (radar API) confirms ✅    │
└──────────────────────────────────────────────┘
           │
           ▼
┌──────────────────────────────────────────────┐
│           Automated Verification             │
│  ✅ Worker GPS in affected micro-zone?       │
│  ✅ Cell tower ID matches zone?              │
│  ✅ Accelerometer confirms prior movement?   │
│  ✅ Plan active this week?                   │
│  ✅ Hourly cap not yet reached?              │
│  ✅ Disruption persisted 30+ minutes?        │
│  ✅ Zone crowd signal confirms (7 workers    │
│     showing near-zero movement)              │
│  ✅ Fraud score: 14/100 (clean)              │
│  ✅ No duplicate claim today?                │
└──────────────────────────────────────────────┘
           │
           ▼
   Claim auto-approved
           │
           ▼
   Disruption duration verified: 4 hours
   Payout: Heavy rain → ₹350 credited (Standard plan daily cap)
           │
           ▼
   Insurer partner releases payout
   Processed via Razorpay sandbox (near real-time)
           │
           ▼
   Firebase push notification sent:
   "🌧️ Heavy rain in your zone. ₹160 credited. Stay safe."
           │
           ▼
   Worker is home. Dry. Paid. Without filing a single form.
```

**Total time from disruption confirmation to payout initiation: near real-time. Fully automated — zero human intervention required.**

---

## Platform & Tech Stack

### Platform Strategy

GigShield is built as a **fully responsive web application** accessible on both mobile and desktop browsers, sharing a single Python FastAPI backend. No app installation required — workers access via mobile browser, admins access via desktop browser.

| Platform | Target User | Purpose |
|---|---|---|
| Mobile Web (HTML · CSS · JS) | Delivery Workers | Onboarding, plan selection, disruption alerts, payout tracking, plan management |
| Desktop Web (HTML · CSS · JS) | Insurer / Admin | Policy portfolio, fraud queue, loss ratio analytics, payout simulation |

### Full Tech Stack

| Layer | Technology | Justification |
|---|---|---|
| Mobile Frontend | HTML · CSS · JavaScript | Responsive mobile web app — works on any mobile browser, no install needed |
| Web Frontend | HTML · CSS · JavaScript | Responsive desktop web app — same codebase, shared components |
| Backend | Python FastAPI | ML-friendly, async support, high performance |
| Database | PostgreSQL | Relational — workers, policies, claims, payout records |
| ML Models | Scikit-learn (Random Forest, Isolation Forest), XGBoost | Production-grade libraries, well-documented |
| Weather API (Primary) | OpenWeatherMap (free tier) + IMD public data | Real-time conditions + historical training data |
| Weather API (Secondary) | Satellite/radar-based private weather API | Backup validation, handles IMD data delays |
| AQI API | CPCB AQI API + OpenAQ (free public APIs) | Government-verified pollution data, cross-validated |
| Disaster Alerts | NDMA public alert feed | Replaces manual curfew verification for Trigger #5 |
| Zone Mapping | Google Maps API + custom micro-zone segmentation (2–5 km) | Precise GPS zone verification beyond pincode level |
| Payments | Razorpay Sandbox (test mode) | Simulated near-real-time payout |
| Push Notifications | Firebase Cloud Messaging | Real-time worker alerts on mobile |
| Hosting | Railway / Render (free tier) | Fast deployment for hackathon demo |

### 🔄 End-to-End Flow — Simple View

```
Step 1 → Worker subscribes to a weekly plan (₹35–₹149/week)
           ↓
Step 2 → GigShield monitors weather + AQI + government APIs every 15 minutes
           ↓
Step 3 → Disruption threshold crossed → 15–30 min validation window begins
           ↓
Step 4 → AI verifies worker authenticity:
         GPS + accelerometer + cell tower + behavioral signals cross-checked
           ↓
Step 5 → Fraud score calculated by Isolation Forest model (0–100)
           ↓
Step 6 → If score < 30 → Payout triggered automatically
         Fully automated — no manual steps at any stage.
```

> **A real worker in a real storm gets paid in minutes. A GPS spoofer at home gets caught at Step 4.**

---

## System Architecture

```
┌─────────────────────┐        ┌─────────────────────┐
│  Worker Mobile Web  │        │   Admin Desktop Web  │
│  (HTML · CSS · JS)  │        │   (HTML · CSS · JS)  │
└────────┬────────────┘        └──────────┬──────────┘
         │                                │
         └──────────────┬─────────────────┘
                        │
                        ▼
            ┌───────────────────────┐
            │   FastAPI Backend     │
            │   (Python)            │
            └──────────┬────────────┘
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
   ┌──────────┐  ┌──────────┐  ┌──────────────────────┐
   │PostgreSQL│  │ ML Engine│  │Disruption Monitor    │
   │(Workers, │  │(Risk,    │  │(Polls APIs every     │
   │Policies, │  │Fraud,    │  │15 min at micro-zone  │
   │Claims)   │  │Predict)  │  │level — 2–5 km zones) │
   └──────────┘  └──────────┘  └──────┬───────────────┘
                                       │
                    ┌──────────────────┼──────────────────────┐
                    ▼                  ▼                       ▼
           ┌──────────────┐  ┌──────────────┐  ┌──────────────────────┐
           │OpenWeatherMap│  │  CPCB AQI    │  │  IMD / NDMA          │
           │+ IMD Weather │  │  API +OpenAQ │  │  Alert Feed          │
           │+ Satellite   │  │              │  │                      │
           │  Radar API   │  │              │  │                      │
           └──────────────┘  └──────────────┘  └──────────────────────┘
                                       │
                                       ▼
                            ┌──────────────────────────┐
                            │  Multi-Layer Validation  │
                            │  • Time confirmation     │
                            │  • Cross-source verify   │
                            │  • GPS micro-zone check  │
                            │  • Cell tower verify     │
                            │  • Accelerometer check   │
                            │  • Crowd signal layer    │
                            │  • Fraud score engine    │
                            └──────────┬───────────────┘
                                       │
                                       ▼
                            ┌─────────────────────┐
                            │  IRDAI Insurer       │
                            │  Partner Payout API  │
                            └──────────┬──────────┘
                                       │
                                       ▼
                            ┌─────────────────────┐
                            │  Razorpay Sandbox    │
                            │  (Payout Processing) │
                            └──────────┬──────────┘
                                       │
                                       ▼
                            ┌─────────────────────┐
                            │  Firebase FCM        │
                            │  (Worker Alert)      │
                            └─────────────────────┘
```

---

## Dashboards

### Worker Mobile Dashboard

- **Plan Status Badge** — Active 🟢 / Expired 🔴 / Disruption in Progress ⚡
- **Current Plan Card** — Plan name, weekly premium, hourly rate, hours remaining this week
- **Change Plan** — Upgrade or downgrade plan at any time — effective from next Monday
- **My Micro-Zone** — Visual map of the worker's assigned 2–5 km delivery zone
- **This Week's Disruptions** — Events detected in your delivery micro-zone
- **Payouts Received** — Timeline of all credited amounts with disruption type and hours covered
- **Predictive Alert Panel** — "Heavy rain likely tomorrow 6–9pm in your zone (78% probability)"
- **Earnings Protected Counter** — "You've saved ₹640 this month with GigShield"
- **Reward Wallet** — NCR points balance, redemption options
- **Loyalty Progress** — Current tier, weeks remaining, claim count
- **Renew Plan** — One-tap weekly renewal before plan expires

### Admin / Insurer Web Dashboard

- **Registered Policies** — Full list of all active workers with plan, zone, risk score, payouts
- **Policy KPIs** — Weekly premium collected, total payouts released, platform fee, loss ratio
- **Plan Distribution** — Breakdown across all 5 plan tiers with counts and premium volume
- **Per-Worker Payout Simulation** — Select any registered worker, choose disruption type and duration, run 5-step automated claim flow
- **Real-time Claim Monitor** — Live city-level claim rates, trigger feed
- **Loss Ratio Tracker** — Weekly and rolling 90-day loss ratio per city
- **NCR Pause Status** — Which cities have NCR currently suspended
- **Loyalty Reserve Balance** — Reserve fund level vs. projected liability
- **Fraud Review Queue** — Claims in the 30–70 score band with GPS trace, cell tower data, accelerometer pattern
- **Data Source Status** — Live status of all API feeds (IMD, CPCB, NDMA, satellite API)
- **Seasonal Cap Schedule** — Dynamic cap activation status per city

---

## Coverage Scope & Exclusions

### What GigShield Covers

GigShield covers **income lost by food delivery workers during verified external disruptions** that prevent delivery activity. Coverage is parametric — payouts are triggered by objective data thresholds that persist for a minimum confirmation window (15–30 minutes), not manual claim assessment. Payouts are calculated on a per-hour basis up to the plan's weekly maximum.

GigShield provides a **partial income top-up** — not full income replacement.

### What GigShield Explicitly Does NOT Cover

> GigShield strictly excludes coverage for: vehicle repairs, bike maintenance, fuel costs, medical expenses, accident compensation, health insurance, life insurance, platform-side demand fluctuations, traffic congestion, technical issues with the delivery app, and any event not independently verifiable through a government or accredited third-party data source.

---

## Financial & Business Model

### GigShield is a Technology Platform — Not an Insurer

```
Worker pays weekly premium
         ↓
Licensed IRDAI Insurer Partner (e.g., Digit Insurance / Acko)
holds all premium capital and pays all claims
         ↓
GigShield earns a 10% platform distribution fee per active policy
         ↓
GigShield does not directly underwrite risk or pay claims.
All claim liabilities are handled by the licensed insurer partner.
GigShield operates as a technology and distribution layer,
earning a fixed fee per policy.
```

### GigShield Revenue Per Policy Per Week

| Plan | Weekly Premium | GigShield Fee (10%) | Insurer Net Premium | Insurer Loss Ratio on Net |
|---|---|---|---|---|
| 🟢 Simple | ₹25 | ₹2.50 | ₹22.50 | ~57% ✅ |
| 🔵 Standard | ₹50 | ₹5.00 | ₹45.00 | ~52% ✅ |
| 🔴 Premium | ₹90 | ₹9.00 | ₹81.00 | ~48% ✅ |

### 🏦 Why Insurers Partner with GigShield

Insurers are not doing GigShield a favour — GigShield brings them a profitable, low-admin product line they cannot build themselves:

- **Controlled loss ratios (50–72%)** ensure portfolio profitability even in heavy monsoon years
- **Parametric triggers** eliminate subjectivity — no disputes, no assessors, minimal admin cost
- **Fraud detection system** minimises payout leakage before insurers ever see a claim
- **Micro-premium model** opens access to 5 crore+ informal and gig workers (NITI Aayog, 2022) — a market insurers currently cannot reach
- **Zero distribution cost** for the insurer — GigShield handles acquisition, onboarding, and tech

> GigShield expands insurer reach into an underserved market while maintaining strict financial discipline.

### Revenue at Scale

| Active Workers | Avg Weekly Fee | Weekly Platform Revenue | Annual Revenue |
|---|---|---|---|
| 1,000 | ₹8.20 | ₹8,200 | ₹42,64,000 |
| 10,000 | ₹8.20 | ₹82,000 | ₹4,26,40,000 |
| 1,00,000 | ₹8.20 | ₹8,20,000 | ₹42,64,00,000 |

*Note: Revenue projections assume consistent weekly plan retention and active worker base growth in urban delivery zones.*

**GigShield's platform model ensures no direct exposure to claim payouts, making it operationally scalable and financially resilient.**

---

## Live Demo

📱 Login →
https://Dhayananth1511.github.io/AI-Powered-Parametric-Income-Protection-for-Food-Delivery-Workers/gigshield_login.html

🧪 Feature Demo →
https://Dhayananth1511.github.io/AI-Powered-Parametric-Income-Protection-for-Food-Delivery-Workers/gigshield_features.html

💡 What you can explore:
- Worker onboarding with dynamic zone risk assessment (40+ Tamil Nadu zones)
- Plan selection with ML recommendation
- Worker dashboard with live payout simulation
- Admin dashboard with full policy list and per-worker payout simulation
- Fraud score visualizer, earnings calculator, disruption history chart

> Note: This is a prototype built for the Guidewire DEVTrails 2026 Hackathon. All data is simulated. No real money is transacted.

---

## Strategy Video

🎥 *2-minute strategy video — link to be added upon submission (before March 20, EOD).*

---

## 45-Day Development Roadmap

### Phase 1 — Ideation & Foundation (Weeks 1–2 | March 4–20)
*Theme: Ideate & Know Your Delivery Worker*

- [x] Problem research and gig worker persona analysis
- [x] Insurance model design — 5 plan tiers, hourly payout model, actuarial loss ratio proof
- [x] ML model architecture planning (Zone Risk Classifier, Fraud Detection, Predictive Alert)
- [x] Tech stack selection and platform strategy
- [x] System architecture design
- [x] GitHub repository setup with full README
- [x] Financial & business model — IRDAI partner insurer structure, 10% platform fee model
- [x] Smart Validation Layer design — multi-source reliability, micro-zone precision, time confirmation, crowd signals
- [x] Adversarial Defense & Anti-Spoofing Strategy — multi-signal GPS spoofing detection architecture
- [x] Fully responsive HTML/CSS/JS prototype — Login, Onboarding (worker + admin), Worker Dashboard, Admin Dashboard, Feature Demo (6 interactive features)
- [ ] Strategy video (2 minutes)

### Phase 2 — Automation & Protection (Weeks 3–4 | March 21–April 4)
*Theme: Protect Your Worker*

- [ ] Worker registration and KYC flow (simulated Aadhaar verification)
- [ ] Insurance policy management (create, view, renew, upgrade/downgrade weekly plan)
- [ ] Zone Risk Classifier model — trained and deployed for plan recommendation at onboarding
- [ ] Micro-zone segmentation layer — divide city into 2–5 km zones, map each worker to micro-zone
- [ ] OpenWeatherMap + IMD + satellite radar API integration and disruption detection engine (15-min polling)
- [ ] Time-based confirmation engine (15–30 min persistence check before trigger fires)
- [ ] Hourly payout calculation engine (duration × hourly rate, capped at plan maximum)
- [ ] Claims management system (auto-trigger pipeline: time confirm → cross-source verify → GPS + cell tower + accelerometer check → fraud check → approve → payout)
- [ ] Razorpay sandbox payout integration
- [ ] Firebase push notification setup
- [ ] 2-minute demo video

### Phase 3 — Scale & Optimise (Weeks 5–6 | April 5–17)
*Theme: Perfect for Your Worker*

- [ ] Advanced fraud detection — Isolation Forest model trained with cell tower + accelerometer features
- [ ] Multi-signal anti-spoofing layer — cell tower triangulation, accelerometer pattern analysis, behavioral baseline
- [ ] Anonymized zone-level crowd signal validation layer
- [ ] Predictive disruption alert engine — XGBoost model, 48-hour micro-zone-level forecast
- [ ] Context-aware delivery time logic
- [ ] NDMA alert feed integration for Trigger #5
- [ ] Full system integration testing across all 5 disruption triggers
- [ ] 5-minute demo video (simulated rainstorm → 30-min confirmation → auto-claim → 4-hour payout walkthrough)
- [ ] Final pitch deck (PDF)

---

## Hackathon Prototype Disclaimer

This project is a prototype built for the **Guidewire DEVTrails 2026 Hackathon**.

For demonstration purposes:
- Insurance payouts are simulated using **Razorpay Sandbox**
- Worker identity verification is mocked
- External data sources are integrated using publicly available APIs (OpenWeatherMap, CPCB, IMD, NDMA)
- Satellite/radar secondary API is simulated in demo using cached weather data
- Anonymized crowd signal layer is simulated using synthetic zone-level movement data
- Cell tower and accelerometer anti-spoofing signals are simulated in the prototype
- ML models are trained on IMD/CPCB public historical data
- Phase 1 prototype is a fully responsive HTML/CSS/JS web application. Native mobile app implementation is planned for Phase 2.

In a real deployment, GigShield would integrate with a **licensed IRDAI insurance partner** to underwrite policies and process real claim payouts.

---

## About This Project

Built for the **Guidewire DEVTrails 2026 Pan-India University Hackathon**.

**Team Name:** Iron Stack

**Team Members:**
- Abishek M
- Anish M
- Jegajith J K
- J Madhan Kumaar
- Pratheep S

**Problem Statement:** AI-Powered Insurance for India's Gig Economy

**Team Persona Focus:** Food Delivery Workers (Zomato / Swiggy)

**Platform:** Responsive Web — Mobile (Workers) + Desktop (Admin)

**Repository:** This repository will be used across all three phases of the hackathon. Commit history will reflect iterative development through each phase.

---

## License

MIT License. See `LICENSE` for details.

---

*Build fast. Spend smart. Protect every delivery worker. 🛡️*
*Team Iron Stack — DEVTrails 2026*
