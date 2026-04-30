---
title: "ATR 72-600 vs A320 in Regional Southeast Asian Markets: When Each Aircraft Wins"
date: 2026-04-30 09:00:00 +0700
categories: [Aviation, Network Planning]
tags: [atr 72-600, a320, fleet planning, regional aviation, turboprop, southeast asia, route economics]
description: "A practitioner's comparison of the ATR 72-600 and Airbus A320 in Southeast Asian regional operations, covering trip cost, seat economics, runway access, schedule resilience, and the demand thresholds where each aircraft wins."
---

The ATR 72-600 versus A320 question is, in most published comparisons, framed as a turboprop-versus-jet debate with predictable answers: the ATR is cheaper to operate, the A320 carries more passengers, pick whichever fits your route. That framing is correct in the sense that the conclusion is right, but it misses the more useful question, which is **at what specific demand level does the cost-per-seat-mile crossover actually happen** in Southeast Asian conditions, and **what non-cost factors should override that economic analysis**.

This article walks through the comparison from a network planner's seat, not a marketing brochure's. Numbers used are realistic regional operating values. Specific operator economics will vary; the framework should not.

## 1. The fundamental physics

Before the economics, the physics. The two aircraft are designed for different missions and that design difference cascades through every other comparison.

| Specification | ATR 72-600 | A320ceo / A320neo |
|---|---|---|
| Typical seat count (single class) | 70 | 174–186 |
| Cruise speed (KTAS) | 275 | 447 |
| Range (full pax, MTOW) | ~825 nm | ~3,300 nm |
| Required runway length (MTOW, ISA, sea level) | ~1,300 m | ~2,100 m |
| Block fuel burn (1 hour cruise) | ~600 kg | ~2,400 kg |
| Pavement classification number requirement | Low | Medium-High |

The ATR cruises at roughly 60% of the A320's true airspeed. On a 250 nm sector, this means the ATR is in the air about 30 minutes longer than an A320 would be. On a 500 nm sector, the time gap stretches to 50 minutes or more, and crew duty implications start to matter for high-utilisation rotations.

The A320 needs roughly 60% more runway, more apron pavement strength, and a substantially more capable airport in terms of ground handling, fuel uplift speed, and air traffic services. This is the single most important non-economic factor in the comparison: **a large fraction of Southeast Asian secondary airports cannot safely accept an A320 at MTOW**, while the ATR family operates routinely from runways under 1,500 m.

## 2. Trip cost versus seat cost

The headline economic comparison most operators make is **trip cost** (total cost of operating one sector) versus **seat cost** (cost per available seat per sector, or CASK if normalised to distance).

For a typical 300 nm intra-ASEAN sector at standard regional fuel prices, illustrative trip cost components might look something like:

| Cost component | ATR 72-600 | A320 |
|---|---|---|
| Block fuel | ~720 kg @ $0.80/kg ≈ $580 | ~2,250 kg @ $0.80/kg ≈ $1,800 |
| Crew (block hours, two pilots, three FAs) | ~$300 | ~$520 |
| Maintenance reserves (block hour) | ~$450 | ~$900 |
| Lease / ownership (allocated per sector) | ~$1,400 | ~$3,200 |
| Navigation, landing, handling fees | ~$650 | ~$1,250 |
| **Total trip cost (illustrative)** | **~$3,380** | **~$7,670** |

Trip cost: A320 costs about 2.3 times more per sector. Seat cost tells a very different story.

| Seat economics | ATR 72-600 | A320 |
|---|---|---|
| Trip cost | $3,380 | $7,670 |
| Available seats | 70 | 180 |
| **Cost per available seat per trip** | **~$48** | **~$43** |

On per-seat economics, **the A320 is already slightly cheaper at full capacity**, before you even factor in any revenue side. This is the single most important number in regional fleet planning. A jet that fills up beats a turboprop that fills up, every time, on a route long enough to absorb the higher per-trip cost.

The question is whether the route can fill the jet. That is where load factor sensitivity comes in.

## 3. Load factor sensitivity: the real comparison

Trip cost and seat cost both assume 100% load factor, which is a fiction. Real revenue management lives in the 65 to 85% range. Compare cost per **revenue passenger** at realistic load factors:

| Load factor | ATR 72 (70 seats) | A320 (180 seats) |
|---|---|---|
| At 65% LF | 46 pax @ $73/pax | 117 pax @ $66/pax |
| At 75% LF | 53 pax @ $64/pax | 135 pax @ $57/pax |
| At 85% LF | 60 pax @ $57/pax | 153 pax @ $50/pax |

The A320 wins on cost per revenue passenger at every load factor, **but** the A320 also needs absolute volume of 117 to 153 daily passengers on the city pair to maintain those load factors. If the underlying demand is only 80 daily one-way passengers, the A320 operates at 44% load factor and costs $96/pax, while the ATR at 80 pax operates at 114% (i.e. demand exceeds capacity) and likely needs frequency expansion.

This produces the **fleet selection rule of thumb** that has held in Southeast Asian regional markets for at least two decades:

- **Daily one-way demand under ~90 passengers**: ATR 72 wins. Frequency the route at one or two daily rotations.
- **Daily one-way demand 90–140 passengers**: ambiguous zone. Frequency strategy and competitive position drive the choice.
- **Daily one-way demand above ~140 passengers**: A320 wins. Single daily rotation absorbs demand at healthy load factor.

The ambiguous zone is where most planning errors get made, in both directions: operators putting A320s on 110-pax routes and bleeding cash, or stubbornly running multi-frequency ATR rotations on 130-pax routes when one A320 round trip would do it cheaper.

## 4. The non-economic factors that override the demand math

The demand-threshold rule above assumes both aircraft can physically operate the route. Often only one can. The override factors:

**Runway length and pavement.** Many secondary airports in Southeast Asia have runways of 1,500 to 1,800 m and pavement classifications below A320 requirements. Sihanoukville, Battambang, Pakse, Mandalay's smaller airfields, several Indonesian regional strips, large parts of the Philippines outside Manila and Cebu: these are ATR markets by physical constraint, not by economic preference.

**Hot-and-high performance.** A320 takeoff weight penalties at hot-and-high airfields can be severe. The ATR 72-600 retains substantially more useful payload at high field elevations and high temperatures, which matters for several airports in northern Laos, Yunnan border airports, and inland Philippines.

**Approach category and navigation infrastructure.** Some regional strips support only non-precision approaches, sometimes with restrictive minima. The ATR's lower approach speeds and shorter visual circling requirements give it operational access that an A320 lacks even when the runway is long enough on paper.

**Slot availability at congested hubs.** This factor cuts the other way. At Bangkok Suvarnabhumi, Singapore Changi, and Kuala Lumpur during peak hours, slots are scarce and expensive. Putting a 70-seat ATR into a congested hub slot is a poor use of a constrained resource. If the route is BKK to a regional point with strong demand, the slot economics push toward the A320 even if the total demand wouldn't normally justify it.

**Aircraft commonality.** Operators with existing A320 fleets face training, parts, and maintenance commonality penalties when adding ATR. The reverse applies to ATR-heavy operators looking at jet expansion. The "right" aircraft for a single route may be wrong for fleet-wide simplicity. Many operators tolerate sub-optimal route economics to maintain single-fleet operations.

**Schedule resilience.** A single ATR delay propagates differently from a single A320 delay because the rotation patterns are different. ATR-heavy short-haul rotations with 60-minute ground turns are highly schedule-sensitive; A320 longer-sector rotations have more natural recovery buffer. Network planners building fleet mix decisions should factor this, especially in monsoon-prone markets.

## 5. Where each aircraft genuinely wins in SEA

Pulling the threads together, here is where each aircraft is the clearly correct choice in Southeast Asian regional operations:

**ATR 72-600 wins decisively on:**
- Domestic Cambodian routes outside the KTI–SAI–KOS triangle
- Domestic Lao operations from VTE
- Eastern Indonesian island networks (Maluku, Papua, NTT secondary routes)
- Philippine inter-island routes outside the major Manila/Cebu/Davao trunks
- Vietnam's secondary domestic network (Côn Đảo and similar)
- Northern Myanmar regional points (when the political situation allows operations)
- Cross-border routes to small airfields: SAI–CXR, SAI–LPQ, SAI–RGN, KTI–PQC

**A320 wins decisively on:**
- Major intra-ASEAN trunks: BKK–SIN, BKK–HKT, KUL–SIN, KUL–DPS, CGK–KUL
- Capital-to-capital city pairs with strong business and leisure mix: BKK–SGN, BKK–PNH, KUL–SGN, SIN–CGK
- Long thin routes that exceed ATR's range: any sector above 800 nm
- Hub-to-hub feeder traffic where slot economics dominate
- Mainland China routes from SEA hubs (CSX, KMG, CKG, CAN) at >2 hour block

**The contested middle ground:**
- Capital-to-secondary-city routes: BKK to Vientiane, Phnom Penh to Da Nang, Singapore to Penang. These are the routes where fleet planners sweat. Demand is enough to justify a jet but not always enough to fill one. Frequency strategy versus competitor positioning matters more than aircraft type.

## 6. The frequency question

A subtlety often missed in aircraft comparisons: the choice between ATR and A320 is also implicitly a choice between **frequency** and **capacity**.

Two daily ATR rotations on a 110-pax demand route deliver 140 seats and two timing options to the customer. One daily A320 on the same route delivers 180 seats but only one time. Business travellers value frequency; leisure travellers are mostly indifferent. Routes with strong business mix (especially same-day return demand) may justify ATR-doubled frequency even when the seat math weakly favours an A320.

This is why low-cost subsidiaries of full-service carriers in Southeast Asia frequently end up with A320 fleets on routes where their full-service parent runs ATRs: the LCC value proposition trades frequency for headline price, while the full-service positioning monetises frequency more than ticket price.

## 7. Practical fleet planning takeaways

For anyone doing real fleet selection on a real route, three working rules:

**Rule 1: Get the demand number right before getting the aircraft right.** Daily one-way realistic demand is the single most important input. Underestimating by 20% leads to ATR selection on routes that should be A320; overestimating by 20% leads to the reverse mistake. Use historical city-pair data, not optimistic forecasts.

**Rule 2: Verify physical airport capability before running economics.** A perfect ATR/A320 cost analysis is irrelevant if the destination airport cannot accept the chosen aircraft. Pull the runway length, pavement classification, and approach minima before opening Excel.

**Rule 3: Treat fleet commonality as a real cost, not a soft factor.** Adding a second fleet type to an operation imposes real training, maintenance, and operational complexity costs that don't show up in a per-route analysis. The threshold for adding a second fleet should be at least 3 to 5 routes that genuinely need the new type, not one.

## 8. Where the comparison is heading

The emerging factor that may shift this analysis in the coming years is the **ATR 72-600 with PW127XT engines** (the post-2022 standard) and the **A320neo family**, both of which improve fuel burn substantially over their predecessors. The neo improvements are larger in absolute terms but spread across more seats, so the per-seat-mile crossover point on demand thresholds is moving slowly downward in favour of the A320neo.

Hybrid-electric and hydrogen propulsion timelines remain too uncertain to factor into 5-year fleet plans. The next decade's regional fleet decisions will continue to be ATR-versus-A320 conversations, with both manufacturers iterating on existing platforms rather than introducing transformational alternatives.

For now, the practical conclusion stands: the ATR wins on thin routes and constrained airports. The A320 wins on volume routes and hub operations. The middle is where planners earn their salaries.

---

*This article uses illustrative regional operating values for comparison purposes. Actual operator economics depend on lease structures, fuel hedging, crew agreements, and route-specific cost factors that vary substantially across operators. Aircraft-specific performance values should be verified against the relevant manufacturer flight manuals and the operator's own performance database before route planning decisions.*
