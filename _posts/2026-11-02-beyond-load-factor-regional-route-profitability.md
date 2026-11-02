---
title: "Beyond Load Factor: How to Evaluate Regional Route Profitability"
date: 2026-11-02 09:26:00 +0700
categories: [Aviation, Network Planning]
tags: [route profitability, load factor, route economics, break even, regional aviation, network planning, yield]
description: "A practical framework for regional route profitability, linking net revenue, avoidable costs, break-even load factor, seasonality, network contribution, and aircraft opportunity cost."
---

A flight departs almost full and still loses money. Another leaves with visibly empty seats and contributes more to the airline. Neither outcome is unusual once the fare, cost base, and decision being evaluated are made explicit.

Load factor answers how much offered capacity was used. It does not tell the planner what passengers paid, what the flight cost, or which alternative use of the aircraft was available.

This article extends the earlier discussions of [ATR versus A320 economics](/posts/atr72-vs-a320-regional-sea-comparison/) and [revenue management](/posts/airline-revenue-management-fundamentals/). The aim is a route review that supports an actual decision: retain, retime, reprice, resize, reduce, or exit.

## 1. Define the decision and the accounting boundary

A departure decision, a seasonal schedule decision, and a fleet investment decision do not use identical costs.

For an individual flight close to departure, some expenses are already committed. For the next season, handling arrangements, crew deployment, and aircraft assignments may change. Over a fleet-planning horizon, aircraft ownership or leasing, support capability, and organisational costs become part of the choice.

Keep three views:

| View | What it measures | Useful decision |
|---|---|---|
| Departure contribution | Net flight revenue less the costs defined as avoidable for that decision | Whether operating the departure improves the result relative to the feasible alternative |
| Route result | Contribution across the period, less route-specific fixed costs and identified allocations | Whether the route supports the chosen service level |
| Network and fleet value | Incremental network result, aircraft opportunity cost, and longer-term commitments | Whether this is the best use of constrained resources |

These are analytical definitions for the framework, rather than universal accounting labels. The company should document its own treatment and apply it consistently.

The relevant comparison is a feasible counterfactual. Cancelling a departure can create refunds, rerouting costs, and aircraft positioning needs; those consequences belong in the cancellation alternative.

## 2. Start with net revenue

The ticket amount seen by the passenger can include taxes and charges collected for others. Separate those from airline revenue. Then identify discounts, commissions, payment expenses, refunds, and interline allocation without subtracting the same item twice.

Include ancillary and cargo contribution where supported by evidence. For connecting passengers, use the agreed revenue allocation for the sector and assess the network effect separately. Assigning the entire through fare to each leg would count revenue more than once.

Build a revenue bridge from the sales record to the route result. If a figure is already net of a distribution expense, do not deduct that expense again in the cost table. Use a consistent currency and document exchange-rate treatment.

For planning, expected revenue should reflect travel dates, direction, booking curve, and fare mix. An advertised lead-in fare and an annual average yield are both weak substitutes for the expected mix on a particular departure.

## 3. A fuller flight can contribute less

The following is a constructed example for a 70-seat aircraft. The amounts are arithmetic assumptions, not ATR operating-cost benchmarks or data from an actual airline. Both scenarios use a hypothetical USD 3,400 avoidable flight cost plus USD 8 per passenger.

| Item | Scenario A: fuller, lower fare | Scenario B: fewer passengers, higher fare |
|---|---:|---:|
| Passengers | 63 | 49 |
| Seat occupancy | 90% | 70% |
| Net fare revenue per passenger | USD 45 | USD 78 |
| Net ancillary revenue per passenger | USD 5 | USD 5 |
| Total revenue | USD 3,150 | USD 4,067 |
| Avoidable flight cost | USD 3,400 | USD 3,400 |
| Passenger-related cost | USD 504 | USD 392 |
| Total cost in this contribution view | USD 3,904 | USD 3,792 |
| Departure contribution | **−USD 754** | **+USD 275** |

Scenario B contributes more despite carrying 14 fewer passengers. It has not yet been shown to cover route fixed costs, aircraft ownership, or all company overheads. The positive USD 275 is a result within the stated contribution boundary.

This example does not imply that raising fares preserves demand. A pricing decision must model the demand response. It demonstrates why occupancy alone cannot rank the two outcomes.

## 4. Calculate a decision-specific break-even load factor

Under a simple linear model with constant revenue and cost per passenger:

**Break-even passengers = (flight-level cost − other net contribution) ÷ (net fare + net ancillary revenue − passenger-related cost).**

Divide break-even passengers by available seats for the corresponding break-even occupancy. The passenger margin must be positive, and the cost and revenue boundaries must match.

For Scenario B, with no other contribution:

- Passenger margin: USD 78 + USD 5 − USD 8 = **USD 75**.
- Break-even passengers: USD 3,400 ÷ USD 75 = **45.33**.
- Break-even occupancy: 45.33 ÷ 70 = **64.76%**.

Because passengers are discrete, at least 46 would be required to exceed that contribution break-even point under the assumptions.

For Scenario A, the passenger margin is USD 42. Break-even occupancy becomes USD 3,400 ÷ (70 × USD 42) = **115.65%**. Filling the remaining seven seats at the same margin cannot fix the result. The plan needs a different fare mix, cost, capacity, or other contribution.

If the passenger margin is zero or negative, report that the model has no feasible passenger-volume break-even at those assumptions. Do not present a misleading ratio.

## 5. RASK and CASK need matching definitions

[IATA's air-traffic metrics guide](https://www.iata.org/en/publications/newsletters/iata-knowledge-hub/understanding-air-traffic-metrics/) defines available seat kilometres, revenue passenger kilometres, and passenger load factor. For a network, passenger load factor is RPK divided by ASK; an unweighted average of route occupancy percentages can give the wrong result.

Unit revenue and cost then require a declared scope:

- **Passenger yield:** passenger revenue divided by RPK.
- **Passenger RASK:** passenger revenue divided by ASK.
- **Total RASK:** the defined total operating revenue divided by ASK.
- **CASK:** the defined operating cost divided by ASK.

An airline's own reporting definitions should govern its comparisons. [China Southern's published reporting glossary](https://www.csair.cn/en/about/investor/qitabaogao/2023/resource/ea7fa4af230785b93e6371f5d2874a22.pdf) provides a primary-source example of capacity, traffic, and yield definitions.

With matching passenger-revenue definitions, passenger RASK equals passenger yield multiplied by passenger load factor. Total RASK includes other revenue when defined that way. It should not be substituted into the passenger identity without adjustment.

Stage length matters. Comparing a short regional sector's CASK directly with a long sector can obscure the effect of spreading departure-related costs over different distances. Compare both trip economics and unit economics.

## 6. Positive departure contribution can coexist with a route loss

Return to Scenario B. If an additional USD 600 per departure represents route-specific fixed costs and allocated expenses in a broader view, the result changes from +USD 275 to **−USD 325**.

That does not automatically mean immediate cancellation improves the airline's cash result. Determine which of the USD 600 would disappear if the route stopped and over what period. Reallocating an unchanged head-office cost to another route does not create a saving.

Equally, repeatedly excluding aircraft and support commitments can make an unsustainable network look attractive. A route that contributes toward committed costs today may still fail a renewal or fleet-expansion decision.

Present the bridge between contribution and broader result. Management should be able to see the amount, nature, and avoidability of each additional cost, rather than choosing whichever accounting view supports a preferred conclusion.

## 7. Evaluate both directions and the whole season

Directional imbalance is common in leisure and regional markets. One strong outbound does not establish a viable round trip. Include the aircraft's complete rotation, necessary positioning, and the costs created by an outstation overnight.

Use monthly or departure-level assumptions where seasonal demand varies. Peak-season strength should be weighted by the number of actual departures it supports. Adding unweighted monthly profit percentages does not produce an annual route result.

Stress the booking assumptions. Does the forecast use achieved fares from high-demand weeks across the whole season? Does it assume the same demand at a less convenient time? Does a proposed frequency increase spread existing passengers across more departures?

Subsidies and incentives require a separate line. Identify their duration, conditions, collection timing, and the route's result after support ends. An unconfirmed payment should remain an assumption, with a scenario excluding it.

## 8. Test network value and aircraft opportunity cost

A feeder can improve another route's economics, as discussed in the [China–ASEAN hub framework](/posts/cross-border-hub-china-asean-global/). Measure that effect incrementally, including seats displaced on the onward service. Do not assign the same network benefit to several feeder business cases.

Then compare the proposed use of the aircraft with a feasible alternative. A departure contributing USD 275 may be less attractive than another use contributing USD 450, if both compete for the same aircraft window and the alternatives have been costed consistently.

Time matters as well as money. Use block time, required ground time, maintenance access, and crew constraints when comparing rotations. A high contribution per block hour can still produce a poor daily outcome if the flight leaves a large unusable gap.

Higher utilisation is valuable when the additional flying earns adequate incremental contribution and remains operationally credible. It is not an independent justification for a loss-making sector.

## 9. Use sensitivity to choose an action

For Scenario B, keeping its assumptions otherwise unchanged:

| Change | Effect on departure contribution |
|---|---:|
| Net fare falls USD 10 for all 49 passengers | −USD 490 |
| Occupancy rises 10 percentage points: 7 additional passengers at USD 75 margin | +USD 525 |
| Avoidable flight cost rises USD 200 | −USD 200 |

These are isolated arithmetic changes, not demand forecasts. In practice, fare and load factor interact. A scenario that improves both should explain why: better timing, a new sales segment, a partner agreement, or another supported mechanism.

Translate the analysis into a decision and review date. A retiming proposal should name the demand it expects to recover. A frequency reduction should quantify cost savings and lost contribution. A trial extension should specify what evidence would justify continuing.

## Closing

A useful route review connects occupied seats with net revenue, decision-relevant costs, seasonality, and alternative uses of the aircraft. It can explain why a full flight loses money and why a positive flight contribution may still fall short of a sustainable route.

The objective is an explicit operating decision supported by a consistent model. Load factor remains useful, but it earns its place alongside the rest of that model.

---

*Sources were checked on 2 November 2026. All financial examples are constructed illustrations in USD, not current fares, operator cost estimates, or forecasts. Actual decisions require the carrier's own revenue, cost, demand, and operational evidence.*
