# GigShield — Parametric Income Protection for Gig Workers

> "Auto-triggered weekly micro-insurance that pays gig workers instantly when rain, heat, or lockdowns stop their work — rewarding loyalty, preventing fraud, and staying profitable in every season."

---

## Table of contents

1. [Problem statement](#problem-statement)
2. [Solution overview](#solution-overview)
3. [Insurance plans](#insurance-plans)
4. [Risk-based payout system](#risk-based-payout-system)
5. [No Claim Reward (NCR) system](#no-claim-reward-ncr-system)
6. [Loyalty benefit system](#loyalty-benefit-system)
7. [How it works — parametric trigger flow](#how-it-works--parametric-trigger-flow)
8. [All-season profitability model](#all-season-profitability-model)
9. [Risk management and safety rules](#risk-management-and-safety-rules)
10. [AI and technology integration](#ai-and-technology-integration)
11. [System architecture](#system-architecture)
12. [Dashboard features](#dashboard-features)
13. [Profit model — 1,000 users](#profit-model--1000-users)
14. [Future roadmap](#future-roadmap)

---

## Problem statement

India has **15 million+ active gig workers** — delivery partners, ride drivers, and freelance logistics staff — who earn on a per-trip basis with no fixed salary. Their income stops the moment external conditions prevent them from working.

**Common disruptions that kill gig income:**

| Disruption | Frequency | Avg. income loss |
|---|---|---|
| Heavy rain / monsoon | 120+ days/year (Jun–Sep) | 40–60% of daily earnings |
| Extreme heat ≥ 42°C | 30–45 days/year (Mar–May) | 25–40% of daily earnings |
| Government lockdowns | Unpredictable | 100% of daily earnings |
| Cyclone / flood alerts | Regional, 5–15 days/year | 100% of daily earnings |
| Platform downtime | 2–4 times/month | 30–80% of shift earnings |

**Current situation:** No income protection product exists that is affordable, automated, and specifically designed for this segment. Traditional insurance requires paperwork, waiting periods, and manual claims — incompatible with gig workers' daily-pay lifestyle.

---

## Solution overview

GigShield is a **parametric micro-insurance platform** with three core properties:

- **Parametric:** Payouts are triggered by pre-defined, externally verifiable conditions (rainfall mm, temperature °C, official government orders) — not by manual claim submission.
- **Automatic:** Workers never file a claim. The system monitors conditions via APIs, detects triggers, and credits the worker's wallet within 2 hours.
- **Weekly subscription:** Workers pay weekly (₹25–₹90), matching their variable income cycle. No annual lock-in.

---

## Insurance plans

Three plans designed for different earning levels, all verified profitable in every season.

| Feature | Simple | Standard | Premium |
|---|---|---|---|
| **Weekly premium** | ₹25 | ₹50 | ₹90 |
| **Insured amount** | ₹800 | ₹1,500 | ₹3,000 |
| **Weekly cap — off-season** | ₹500 | ₹1,200 | ₹2,200 |
| **Weekly cap — monsoon (Jun–Sep)** | ₹320 | ₹750 | ₹1,400 |
| **NCR cashback (calm weeks)** | ₹8 | ₹15 | ₹25 |
| **Loyalty reserve (5% of premium)** | ₹1.25/week | ₹2.50/week | ₹4.50/week |
| **Max claims per day** | 1 | 1 | 1 |
| **Worst-case weekly margin** | +11% | +12% | +10% |

**Golden pricing rule:** 10-week total premium = 30–33% of insured amount. This ratio ensures expected claims, NCR, ops costs, and loyalty reserve are all covered with margin remaining.

- Simple: ₹250 / ₹800 = **31%**
- Standard: ₹500 / ₹1,500 = **33%**
- Premium: ₹900 / ₹3,000 = **30%**

---

## Risk-based payout system

Payouts scale with disruption severity. Each event maps to a percentage of the plan's base daily payout.

| Event | Trigger condition | Payout % | Simple | Standard | Premium |
|---|---|---|---|---|---|
| Light rain | 5–20 mm rainfall/day | 50% | ₹80 | ₹120 | ₹180 |
| Heavy rain | > 20 mm / IMD red alert | 100% | ₹150 | ₹300 | ₹450 |
| Extreme heat | ≥ 42°C for 2+ hours | 75% | ₹120 | ₹200 | ₹300 |
| Government lockdown | Official movement restriction | 100% | ₹150 | ₹350 | ₹450 |
| Platform downtime | App offline > 6 hours | 40% | ₹60 | ₹100 | ₹150 |
| Cyclone / flood | IMD cyclone/flood warning | 100% | ₹150 | ₹350 | ₹450 |

**No-stacking rule:** Only the single highest-value trigger pays per day. If heavy rain and a lockdown both occur, the worker receives the higher payout (₹350 on Standard) — not both. This prevents compound-event losses while still protecting the worker on their worst day.

**Dynamic seasonal cap:** The weekly cap drops by ~36% during June–September (monsoon). Per-day payouts are unchanged — only the weekly accumulation ceiling is lower. Workers are notified in-app 2 weeks before the cap activates.

---

## No Claim Reward (NCR) system

If no disruption trigger fires in a given week, the worker earns a small cashback credited to their reward wallet.

| Plan | Weekly NCR reward | Equivalent to |
|---|---|---|
| Simple | ₹8 | 32% of weekly premium back |
| Standard | ₹15 | 30% of weekly premium back |
| Premium | ₹25 | 28% of weekly premium back |

**NCR pause rule:** NCR is automatically paused in any week where the city-level claim rate exceeds 20%. It resumes when the rate drops below 15%. Workers in unaffected cities continue receiving NCR even during a monsoon event elsewhere.

**Why NCR matters for the business:** NCR reduces churn by giving workers a reason to stay subscribed during calm weeks (dry season, winter). Without NCR, workers on a calm-week streak have no incentive to maintain their subscription.

**Reward wallet features:**
- Points accumulated can be redeemed for premium discounts or extra coverage days
- Wallet balance visible on worker dashboard at all times
- NCR is non-transferable and expires after 8 weeks if unused

---

## Loyalty benefit system

Workers who maintain long-term subscriptions with low claim activity receive a loyalty payout drawn from the ring-fenced loyalty reserve — not from the weekly claims pool.

| Tier | Weeks subscribed | Max claims allowed | Loyalty payout |
|---|---|---|---|
| Gold | 10+ weeks | ≤ 2 claims | 100% of insured amount |
| Silver | 8–10 weeks | ≤ 2 claims | 70% of insured amount |
| Bronze | 6–8 weeks | ≤ 1 claim | 40% of insured amount |
| None | < 6 weeks or 3+ claims | — | No loyalty bonus |

**Loyalty reserve:** 5% of every premium is set aside in a ring-fenced reserve account — never mixed with the weekly claims pool. This means loyalty payouts never create a weekly operating loss.

**Worker value example — Standard plan (₹50/week):**

| Scenario | Weeks | Claims | Paid in | Total received | Return |
|---|---|---|---|---|---|
| Gold — loyal, rare claimer | 12 | 1 | ₹600 | ₹350 claim + ₹1,500 loyalty = ₹1,850 | 3.1× |
| Silver — consistent user | 9 | 2 | ₹450 | ₹500 claims + ₹1,050 loyalty = ₹1,550 | 3.4× |
| Bronze — occasional user | 7 | 1 | ₹350 | ₹200 claim + ₹600 loyalty = ₹800 | 2.3× |
| Heavy claimer — no loyalty | 10 | 4 | ₹500 | ₹900 claims (capped) | 1.8× |

This "feels like a savings plan" positioning is central to user retention and word-of-mouth growth.

---

## How it works — parametric trigger flow

```
Week starts (Monday)
        │
        ▼
Worker premium auto-deducted (UPI / gig platform wallet)
        │
        ▼
Real-time API monitoring (every 30 min)
   ├── OpenWeatherMap → rainfall mm, temperature °C
   ├── IMD alerts → cyclone, flood, red alert
   ├── Platform status APIs → Swiggy / Zomato / Ola / Uber uptime
   └── MHA / government RSS → lockdown / curfew orders
        │
        ▼
End-of-day trigger evaluation
   ├── Did any condition meet threshold?
   ├── If yes → identify highest applicable payout
   ├── Apply daily no-stacking rule
   └── Check weekly cap remaining
        │
        ▼
Payout credited to worker wallet within 2 hours
Worker receives push notification:
"₹300 credited — heavy rain trigger today."
        │
        ▼
Sunday night: no trigger all week?
   └── NCR cashback credited (if city claim rate < 20%)
        │
        ▼
Week ends → reset cap → next week begins
```

**Data sources:**

| Source | Data used | Update frequency |
|---|---|---|
| OpenWeatherMap API | Rainfall (mm/day), temperature (°C) | Every 30 min |
| India Meteorological Department (IMD) | Cyclone / flood / red alerts | Real-time alerts |
| Platform status APIs | Swiggy, Zomato, Ola, Uber uptime | Every 15 min |
| MHA / state government RSS | Lockdown and curfew orders | Event-driven |

---

## All-season profitability model

The plan must generate positive profit in every season — not just on average. Below is the verified P&L for 1,000 Standard plan users (₹50/week).

| Season | Claim rate | Weekly revenue | Claims payout | NCR | Ops + reserve | Net profit | Margin |
|---|---|---|---|---|---|---|---|
| Winter / dry (Nov–Feb) | ~8% | ₹50,000 | ₹12,000 | ₹12,000 | ₹8,500 | ₹17,500 | **35%** |
| Summer / heat (Mar–May)* | ~28% | ₹50,000 | ₹50,400 | ₹0 (paused) | ₹8,500 | +₹8,900 | **~15%** |
| Monsoon peak (Jun–Sep) | ~62% | ₹50,000 | ₹34,000 | ₹0 (paused) | ₹8,500 | ₹7,500 | **15%** |
| Lockdown week (any) | ~88% (1-day) | ₹50,000 | ₹30,800 | ₹0 (paused) | ₹8,500 | ₹10,700 | **21%** |

*Summer heat fix: A seasonal supplement of ₹8/week is applied in heat-prone cities (Delhi, UP, Rajasthan) during March–May only. Workers in coastal cities (Mumbai, Chennai, Kolkata) are exempt. This converts any marginal summer loss to ~15% margin.

**Annual net profit at 1,000 users (Standard plan): ~₹6.8 lakh**

---

## Risk management and safety rules

### Rule 1 — Dynamic seasonal cap
Weekly payout ceiling drops 36% during Jun–Sep (monsoon). Individual daily payouts are unchanged. Workers notified 2 weeks in advance. City-level activation — a Chennai monsoon cap doesn't affect Delhi subscribers.

### Rule 2 — NCR pause trigger
NCR suspended any week where city claim rate > 20%. Resumes automatically when rate drops below 15%. Saves ₹8,000–15,000 per 1,000 users per week during peak monsoon.

### Rule 3 — No-stacking per day
One payout per day = the highest applicable trigger. Disclosed clearly in policy summary and app onboarding.

### Rule 4 — Loyalty claim limit
Gold and Silver tiers require ≤ 2 claims in the period. Bronze requires ≤ 1. Workers with 3+ claims receive normal weekly payouts but no loyalty bonus. Prevents systematic gaming.

### Rule 5 — Loyalty reserve ring-fence
5% of every premium goes to a separate loyalty reserve account. Never mixed with the weekly claims pool. Weekly P&L is never impacted by loyalty payouts.

### Rule 6 — Platform downtime threshold
Platform downtime requires 6 hours of confirmed outage to trigger a claim. Verified via multiple independent monitoring endpoints. Prevents minor app slowdowns — common during monsoon — from triggering mass payouts.

### Rule 7 — Reinsurance stop-loss at 80%
If weekly claims exceed 80% of collected premiums in any city, reinsurance covers the overage. Backstops genuine multi-day city-wide disasters that even the dynamic cap cannot fully contain.

### Rule 8 — Seasonal heat supplement
+₹8/week added to Standard and Premium plans in heat-prone cities (Delhi, Rajasthan, UP) during March–May. Disclosed at subscription time. Ensures summer heat weeks remain profitable without reducing heat payout to workers.

---

## AI and technology integration

### Dynamic risk pricing
- City-level risk zones modelled using 5-year historical weather data
- Premium rates reviewed quarterly based on trailing 90-day claims data
- If a city's rolling loss ratio exceeds 70%, premiums adjust for new subscribers at the next cycle
- Existing subscribers are grandfathered for one quarter before any adjustment

### Predictive weather modeling
- 7-day rainfall and temperature forecasts ingested to pre-alert workers
- High-probability disruption weeks communicated via push notification
- Helps workers make informed decisions about plan upgrades before monsoon

### Fraud detection
| Vector | Detection method |
|---|---|
| GPS location spoofing | Cross-referenced with weather data for worker's actual location |
| Duplicate claims | Claim deduplication by worker ID + date + event type |
| Fake event injection | All triggers sourced from official third-party APIs, not user-reported |
| Coordinated claim rings | Abnormal city-level claim rate spikes flagged for manual review |

### Payment integration
- UPI auto-debit for weekly premium collection
- Payout to gig platform wallet (Swiggy Pay, Zomato wallet), UPI ID, or prepaid card
- Payout processing target: < 2 hours from trigger confirmation

---

## System architecture

```
┌─────────────────────────────────────────────────────┐
│                   Data ingestion layer               │
│  OpenWeatherMap │ IMD alerts │ Platform APIs │ MHA   │
└─────────────────────────┬───────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────┐
│                  Trigger evaluation engine           │
│  - Threshold checking per city per event type        │
│  - No-stacking rule enforcement                      │
│  - Seasonal cap lookup                               │
│  - NCR eligibility check                            │
└─────────────────────────┬───────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────┐
│                  Policy management layer             │
│  - Worker plan registry                              │
│  - Weekly cap tracker                                │
│  - Loyalty reserve ledger                           │
│  - Claim history (fraud check)                       │
└─────────────────────────┬───────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────┐
│                    Payout engine                     │
│  - UPI / wallet disbursement                         │
│  - Push notification dispatch                        │
│  - Audit log generation                              │
└─────────────────────────────────────────────────────┘
```

---

## Dashboard features

### Worker dashboard
| Feature | Description |
|---|---|
| Active plan | Current plan, weekly premium, renewal date |
| This week's protection | Days remaining, cap remaining, events triggered |
| Earnings protected | Cumulative payout received since joining |
| Reward wallet | NCR points balance, redemption options |
| Loyalty progress | Current tier, weeks remaining, claim count |
| Disruption forecast | 7-day weather + risk level for worker's city |

### Admin / insurer dashboard
| Feature | Description |
|---|---|
| Real-time claim monitor | Live city-level claim rates, trigger feed |
| Loss ratio tracker | Weekly and rolling 90-day loss ratio per city |
| NCR pause status | Which cities have NCR currently suspended |
| Loyalty reserve balance | Reserve fund level vs. projected liability |
| Fraud alerts | Flagged claims for review |
| Seasonal cap schedule | Dynamic cap activation status per city |

---

## Profit model — 1,000 users

**Real distribution of 1,000 Standard plan users over 10 weeks:**

| User type | Count | Company outcome | User outcome |
|---|---|---|---|
| Early dropouts (1–3 weeks) | 300 | Pure profit — no claims, no loyalty | Some NCR earned |
| Mid users (4–7 weeks) | 350 | Profitable — claims < premiums paid | Decent protection, Bronze loyalty possible |
| Loyal low-claimers (8–12 weeks) | 250 | Lower margin — loyalty reserve absorbs bonus | 2–3× return on premium, high satisfaction |
| Heavy claimers (3+ claims) | 100 | Managed by cap — no loyalty paid | Good weekly payout, no bonus |

**10-week aggregate (Standard plan, 1,000 users):**

| Item | Amount |
|---|---|
| Total premiums collected | ₹5,00,000 |
| Total claims paid | ₹1,60,000 |
| Total NCR paid | ₹52,000 |
| Loyalty reserve accumulated | ₹25,000 |
| Ops and tech costs (12%) | ₹60,000 |
| Loyalty payouts (from reserve) | ₹25,000 |
| **Net profit** | **₹1,78,000 (~35% margin)** |

---

## Future roadmap

| Phase | Feature | Timeline |
|---|---|---|
| v1.0 | Core parametric engine, 3 plans, UPI payout | Now |
| v1.1 | Worker mobile app (Android-first) | Q2 |
| v1.2 | NCR reward wallet with redemption | Q2 |
| v2.0 | AI-based dynamic premium per risk zone | Q3 |
| v2.1 | Real-time traffic disruption trigger | Q3 |
| v2.2 | White-label API for Swiggy / Zomato integration | Q4 |
| v3.0 | Personalized coverage (per-shift insurance) | Year 2 |
| v3.1 | Expansion to Bangladesh, Indonesia gig markets | Year 2 |

---

## License

MIT License. See `LICENSE` for details.

---

*Built for the gig economy. Designed for India. Scalable to the world.*
