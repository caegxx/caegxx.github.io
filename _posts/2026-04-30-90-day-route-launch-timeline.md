---
title: "How a Route Actually Gets Launched: A 90-Day Timeline"
date: 2026-04-30 16:00:00 +0700
categories: [Aviation, Network Planning]
tags: [route launch, network planning, schedule planning, project management, regional aviation, operations]
description: "A practitioner's walkthrough of the full 90-day timeline from board approval to first commercial flight for a new airline route, covering seven parallel workstreams, critical decision gates, and the dependencies that most often cause launches to slip."
---

The travel press tends to write about new routes as if they appear by magic. "Airline X announces new route to Y, first flight on date Z." The framing implies the airline decided one morning and the route happened by the end of the quarter. That framing is wrong by roughly an order of magnitude. A new commercial route is the product of three to four months of coordinated work across seven parallel workstreams, each with its own external dependencies, statutory deadlines, and failure modes.

This article walks through what a realistic 90-day launch looks like from the inside. It is a generic framework, applicable to any regional carrier launching a new international route into a coordinated airport. Specific timelines compress or extend based on the regulatory regime, the airport's coordination level, the carrier's prior experience on similar routes, and the season. The 90-day envelope is roughly the minimum; many launches take 120 days or more.

## The headline view

The complete timeline, with all seven workstreams running in parallel:

![90-day route launch timeline showing seven parallel workstreams with critical milestones](/assets/img/route-launch-timeline.svg)

Three critical milestones anchor the calendar: **Decision Lock** at around Day 15, when the launch becomes commitment rather than evaluation; **Sales Open** at around Day 45-50, when the route enters public schedules and tickets go on sale; and **First Flight** at Day 90. Everything else is the work required to connect these three points.

## Day 0 to 15: Decision lock

The clock starts on the day the carrier's board or executive committee approves the route in principle. This approval is rarely the start of the analysis. It is the end of months of network planning, route economic modelling, competitive analysis, and traffic-rights diligence. By Day 0, the schedule planner already knows what the daily one-way demand is, what the competitive timing window looks like, what the unit costs are, and what the break-even load factor is.

What happens between Day 0 and Day 15 is **commitment**. Specifically:

- **Final commercial approval.** Pricing structure (fare basis, fare classes, RBD allocation), revenue management setup, expected load factor by month, ancillary revenue assumptions.
- **Fleet assignment.** Which aircraft, which sub-fleet, which days of the week, which rotation. The aircraft must be free on the proposed days, which means the rotation has to integrate with the rest of the network without breaking anything else.
- **Capacity declaration check.** Verify that the proposed slot times fit within the published capacity declarations of both endpoints. This is a hard check; if the airport simply does not have capacity at the proposed time, no amount of negotiation creates it.
- **Designation status check.** Confirm that the carrier is designated under the relevant bilateral air services agreement to operate this city pair. If not, designation has to happen before regulatory approvals can move (and designation can take months on its own, which often pushes the timeline beyond 90 days).

By Day 15, all of these have to be locked. Changing the proposed schedule, aircraft type, or pricing structure after Day 15 forces re-work on every downstream workstream, which is why this gate is treated as a hard freeze.

That said, the 15-day envelope assumes the carrier is actually capable of locking the decision on schedule. In practice, this step can stretch indefinitely. Many proposed routes spend months stuck in decision-lock limbo, with the executive committee deferring final sign-off pending one more market study, one more competitive update, one more partner negotiation, or one more management reshuffle. Routes that get stuck here often never launch at all. The 90-day clock formally starts when the decision is genuinely locked; if the lock keeps slipping, every downstream workstream slips with it, and the launch date becomes a moving target with no anchor.

## Day 15 to 60: The parallel push

This is the longest and most complex phase, and it is the phase where launches go wrong. Seven workstreams now run simultaneously, each with its own external dependencies. Project management discipline becomes the single most important success factor.

![Seven parallel workstreams during route launch showing coordination links and hard dependencies](/assets/img/route-launch-workstreams.svg)

The seven workstreams:

**1. Commercial and pricing.** Fare structures get filed with the relevant publisher, revenue management systems are loaded with forecasts, agency commission terms are finalised, and corporate accounts are notified.

**2. Regulatory and permits.** This is the most variable workstream by jurisdiction. It includes:
- Foreign Air Operator Certificate (FAOC) or its local equivalent
- Scheduled flight approvals
- Frequency authorisation under the bilateral ASA
- Customs and immigration clearance pre-coordination at the destination
- Environmental and noise clearances if applicable

For an experienced operator on a familiar regulator, this can take 30 days. For a first-time operation into a jurisdiction with conservative civil aviation authorities, it can take 90 days or more, which is why this workstream often defines the overall timeline.

**3. Slot and airport coordination.** For Level 3 airports under the WASG framework, this means submitting SCR messages to the coordinator and negotiating slot times. The slot times must align with the broader rotation, and adjustments here cascade into the operations workstream. For Level 2 airports, SMA exchanges with the facilitator. For Level 1 airports, direct coordination with the airport operations team.

**4. Operations and crew.** Route study (procedures, alternates, emergency airfields, fuel uplift planning), crew route familiarisation for first-time destinations, OFP template build, performance database update, MEL/CDL review for the route environment.

**5. Ground handling.** Standard Ground Handling Agreement (SGHA) with the destination station, ramp services contract, passenger services scope, fuelling agreement, de-icing if relevant, lost-baggage handling protocol. For a first-time station, also station manager appointment, training, and equipment positioning.

**6. Distribution and GDS.** Schedule filing with OAG, distribution into the GDS systems (Sabre, Amadeus, Travelport), internet booking engine integration, interline agreements activation if applicable, code-share filing if applicable.

**7. Marketing and sales.** Pre-launch teaser, trade press placement, inaugural flight planning, key account briefings, ad placement schedule.

Each workstream has internal complexity, but the hard problem is the **dependencies between them**. The diagram above shows the four most common blockers.

The most consequential cross-workstream dependency: **regulatory approval blocks distribution**. The schedule cannot be filed with the GDS for public sale until the regulator confirms the operating permit is in hand. If the permit is delayed, sales open is delayed. If sales open is delayed past the practical pre-booking window, the inaugural flight launches with poor load factor and the route economics suffer from Day 1.

The second consequential dependency: **slot confirmation blocks the OFP build**. Crews cannot finalise route procedures until the actual slot times are known, because slot times determine fuel uplift requirements, alternate airport selection, and crew duty timing.

## Day 30 to 60: The decision gates

This is where the launch either consolidates or starts to slip. Two gates dominate this window:

![Critical decision gates for slot and permits, with failure path consequences](/assets/img/route-launch-decision-gates.svg)

The diagram shows the two gates and their failure consequences. The pattern is asymmetric: **gate failures are not symmetric in cost**.

**Slot denial** at a Level 3 airport typically forces a re-time within the available capacity window (acceptable, with minor commercial impact) or a defer to the next scheduling season, which is six months. Six-month deferrals kill many routes outright because the underlying market conditions, competitive position, and management appetite all change in six months.

**Permit delay** is harder. By Day 60, the carrier has typically already opened sales. A delay forces either pushing the first flight (refunding sold tickets, absorbing rebooking cost, taking the public reputation hit) or operating at risk with a permit pending (which is acceptable in some jurisdictions and absolutely not acceptable in others).

The professional approach to both gates is the same: **plan for failure from Day 0**. Have a backup slot time identified before the primary is even submitted. Have a contingency plan for permit delay before the application is filed. The cost of contingency planning is small. The cost of being surprised at Day 50 is large.

## Day 50 to 90: The customer-facing phase

By Day 50, the route is on sale. The remaining 40 days are operational rather than planning, but they are not low-effort:

- **Booking curve monitoring.** Revenue management watches the early load factor build. Pricing adjustments may be triggered.
- **Inaugural flight planning.** Trade press invitations, ribbon-cutting, photographer scheduling, dignitary management.
- **Operational rehearsal.** First-day procedures briefing for ground staff, OCC, crew. A successful first flight requires every team member to know exactly what happens at every step.
- **Service recovery preparation.** If the first flight has a problem (delay, diversion, equipment swap), the rebooking and communication protocol is set up in advance, not improvised.

The first flight itself is the smallest part of the work. By Day 90, every detail has been rehearsed multiple times.

## What most often goes wrong

Across many route launches in regional Southeast Asian operations, three patterns of failure recur:

**Pattern 1: Optimistic regulatory timelines.** New entrants assume that because the regulator has processed similar applications in the past, this one will move at the same pace. Often it does not, and the delay is discovered too late to adjust the launch date.

**Pattern 2: Slot times that look fine in isolation but break the rotation.** A schedule planner secures a slot at Day 50, only to discover at Day 70 that the slot time forces the aircraft into an FDP violation on the day-after rotation. By that point, the slot is allocated, and adjusting it means giving up the slot and re-applying.

**Pattern 3: GDS filing errors discovered after sales open.** The schedule gets filed with a wrong equipment code, wrong flight number sequence, or wrong day-of-week mask. The errors are caught by an agent in another country who sees inconsistent fares, and the carrier finds out from the agent's complaint. Fixing it requires re-filing and a public correction.

All three of these are preventable with project management discipline. None of them are preventable with hope.

## Three rules for the schedule planner

For any planner running a route launch:

**Rule 1: One person owns every workstream.** A route launch with seven workstream owners and no single project manager will slip. The project manager does not need to do the work of each workstream, but must hold the integrated plan and the dependency map.

**Rule 2: Build the timeline backwards from First Flight.** Pick the target Day 90, then map every required milestone back to its earliest start date. The plan is wrong if any workstream has slack less than five working days; that workstream is your single point of failure.

**Rule 3: Pre-mortem before kick-off.** On Day 0, gather the workstream owners and ask one question: "What goes wrong here?" Write down every answer. Use the answers to build the contingency plans for each gate. The pre-mortem takes two hours. It saves weeks of recovery work later.

## Closing

A route launch is a project. It rewards project management discipline, structured dependency tracking, and pre-planned contingencies. It punishes optimism, ad hoc coordination, and surprise.

For the 90-day envelope to hold, everything has to be running in parallel from Day 15. The regulator has to be already engaged. The slot request has to be in. The ground handling tender has to be live. The crew route study has to be progressing. The marketing brief has to be drafted. By Day 60, all gates have to be passed. By Day 50, sales have to be open.

The first flight, when it finally happens, is the easiest part. Everything before it is where the work lives. Understanding that gap, and planning for it, is what separates a route launch that lands on time from one that slips into next season.

---

*This article describes a generic 90-day route launch framework based on industry-standard practice for regional carrier operations into coordinated international airports. Specific timelines and process steps vary substantially by jurisdiction, regulator, and operator. Practitioners should adapt this framework to their specific operational context, MCAR/CAR requirements, and the published timelines of the relevant civil aviation authorities and airport coordinators.*
