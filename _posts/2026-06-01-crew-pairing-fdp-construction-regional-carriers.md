---
title: "Crew Pairing and Flight Duty Period Construction for Regional Carriers"
date: 2026-06-01
categories: [Aviation, Operations]
tags: [crew pairing, flight duty period, fdp, fatigue management, frms, icao annex 6, regional aviation, schedule planning]
description: "A practitioner's guide to flight duty period (FDP) construction and crew pairing for regional airline operations, covering the ICAO Annex 6 framework, the practical distinction between FDP and duty time, FDP extension techniques, and how single-aircraft rotations actually get constrained by crew limits."
---

There is a recurring blind spot in commercial route planning, especially in regional aviation: the route is designed, the slots are negotiated, the aircraft is assigned, and only then does someone realise that the flight duty period (FDP) of the proposed schedule exceeds what a single crew can legally fly. The schedule gets rebuilt. Sometimes the route gets dropped. Sometimes a second crew gets added, with cost implications that were not in the original business case. None of this is necessary. FDP is not a mysterious safety constraint that emerges late in the process; it is a calculable input that should sit alongside aircraft performance and slot availability as a Day One planning constraint.

This article walks through what an FDP actually is, how it differs from related concepts (duty time, block hours), how the international framework works, the techniques for extending FDP when a route genuinely requires it, and how single-aircraft regional rotations are most often constrained by crew rules rather than by aircraft capability.

## 1. The framework: ICAO Annex 6 and national variations

The international starting point for crew flight and duty time rules is **ICAO Annex 6, Part I** (Operation of Aircraft, International Commercial Air Transport — Aeroplanes), particularly the fatigue management provisions added through the major 2011 amendment and updated since. The key documents in the framework:

- **Annex 6 Part I, Chapter 4.10**: prescriptive fatigue management requirements at the SARP level
- **Annex 6 Part I, Appendix 7**: Fatigue Risk Management System (FRMS) requirements, introduced in 2008
- **Annex 6 Part I, Attachment A**: Guidance material for developing prescriptive limits

The critical thing to understand about the ICAO framework is what it does **not** do. ICAO has consistently declined to specify global numerical limits on flight time or duty time. As ICAO's own published material puts it, identifying global hour limits "proved impossible" because operational contexts vary too widely across regions, aircraft types, and route structures. What ICAO does is establish the **principle** that each state must have a defined scheme, the **structure** that such a scheme must include (flight time limits, FDP limits, rest requirements, cumulative limits), and the **option** to use FRMS as an alternative to prescriptive rules.

The actual numerical limits come from each national civil aviation authority. The result is that an airline operating across multiple jurisdictions navigates a patchwork of slightly different numbers, even though the underlying concepts are universally consistent.

Major reference frameworks that regional carriers commonly benchmark against:

- **EASA FTL (EU Regulation 965/2012, Subpart FTL)**: a science-based prescriptive scheme widely studied
- **FAA 14 CFR Part 121 Subpart Q/R/S**: US scheduled and supplemental operations
- **CAAM Malaysia CAD 1901**: a publicly available, well-documented ASEAN reference
- **National regulations** of each operating jurisdiction (Cambodia, Vietnam, Thailand, Indonesia, etc., each with its own published scheme)

For a regional carrier operating into multiple ASEAN states, the operator's home-state scheme controls, but any flight into a foreign state must also respect that state's rules where they apply (typically through the FAOC operations specification).

## 2. Three concepts that are not the same

A frequent source of confusion is the conflation of three related but distinct concepts:

**Flight Time (Block Time)** is the time from the aircraft first moving under its own power for the purpose of flight, until it comes to rest at the end of the flight. This is the "wheels off to wheels on plus taxi" period. It is the most narrowly defined of the three concepts, and the easiest to measure (it appears in every journey log).

**Flight Duty Period (FDP)** is the period that begins when a crew member is required to report for a duty that includes a flight (or a series of flights) and ends at engines-off of the final flight. FDP includes report time before the first flight, all flight time, all ground time at intermediate stops, and the post-flight engine shutdown moment. It does **not** typically include post-flight administrative time, which falls under the broader "duty period."

**Duty Period (or simply Duty)** is the broadest measure: the time from when the crew member is required to report for any duty (flight, training, administrative, standby that becomes duty, positioning) until they are free from all duties. Duty includes FDP plus any non-flying duties on either side.

The relationship is hierarchical: **Flight Time ⊂ FDP ⊂ Duty Period**.

A regional pilot operating a typical day might have:
- Report time: 0700
- First flight wheels-off: 0800
- Last flight wheels-on: 1730
- Post-flight admin complete: 1830

The flight time depends on actual block performance across all sectors of the day. The FDP is from 0700 to 1730 (10:30 hours). The duty period is from 0700 to 1830 (11:30 hours).

Almost every regulatory limit is expressed against FDP, not against duty period or flight time alone. When a network planner asks "is this rotation legal?", the operational answer almost always reduces to "what is the maximum FDP for the conditions, and what is the FDP we are scheduling?"

## 3. What drives the maximum FDP

Maximum FDP is not a single number. It varies based on a small set of inputs that every regulatory scheme captures, with broadly similar structure:

**Report time (circadian factor).** A crew reporting at 0700 has a higher maximum FDP than the same crew reporting at 0200. The lowest FDP limits apply to reports during the **Window of Circadian Low (WOCL)**, typically defined as 0200 to 0600 local time. The body's physiological alertness is lowest in this window, and the prescriptive schemes reduce maximum FDP accordingly. This is the single largest variable.

**Number of sectors.** A crew flying two sectors in a duty has a higher maximum FDP than the same crew flying six sectors, because each sector adds workload (briefings, approaches, takeoffs, landings) without proportionally increasing rest. Most schemes reduce maximum FDP by approximately 30 minutes per sector beyond the first two.

**Acclimatisation status.** A crew operating from their home base in their home time zone is "acclimatised" and gets full FDP limits. A crew that has crossed multiple time zones recently may be in an "unknown acclimatisation" state, with reduced FDP. The thresholds for what constitutes acclimatisation vary by scheme (typically 2 to 4 hours of time zone difference).

**Augmented crew.** Operations with more than the minimum required crew (typically two pilots for narrowbodies, three or four for long-haul widebodies) qualify for extended FDP limits, because in-flight rest becomes possible.

To make this concrete, here is the maximum FDP table for non-augmented (unaugmented) crew under **FAR Part 117, Table B**, the current US standard applicable to all Part 121 passenger operations since 2014:

| Report time (acclimated) | 1-2 seg | 3 seg | 4 seg | 5 seg | 6 seg | 7+ seg |
|---|---|---|---|---|---|---|
| 00:00-03:59 | 9 | 9 | 9 | 9 | 9 | 9 |
| 04:00-04:59 | 10 | 10 | 10 | 9 | 9 | 9 |
| 05:00-05:59 | 12 | 12 | 12 | 11.5 | 11 | 10.5 |
| 06:00-06:59 | 13 | 12 | 12 | 11.5 | 11 | 10.5 |
| 07:00-11:59 | **14** | 13 | 13 | 12.5 | 12 | 11.5 |
| 12:00-12:59 | 13 | 13 | 13 | 12.5 | 12 | 11.5 |
| 13:00-16:59 | 12 | 12 | 12 | 11.5 | 11 | 10.5 |
| 17:00-21:59 | 12 | 11 | 11 | 10 | 9 | 9 |
| 22:00-22:59 | 11 | 10 | 10 | 9 | 9 | 9 |
| 23:00-23:59 | 10 | 10 | 9 | 9 | 9 | 9 |

*Source: 14 CFR Part 117, Table B. CCAR-121 R8 Section 121.485 Table B has a similar structure with three time bands (05:00-11:59, 12:00-23:59, 00:00-04:59) and four sector groupings (1-4, 5, 6, 7+); EASA Reg 965/2012 Subpart FTL uses a comparable but distinct table. The specific values applicable to any operation depend on the operator's home-state regulation.*

The structural logic is consistent across schemes: maximum FDP is highest for daytime reports with few sectors, decreases progressively as either the report time moves into night hours or the sector count rises, and is lowest for early-morning reports that cross the WOCL. Augmented crew operations under Part 117 Table C allow substantially longer FDPs (up to 19 hours with four pilots and Class 1 rest facility), discussed below.

A high-sector early-morning regional schedule (six sectors starting at 07:00) can run into a 12-hour FDP cap under Part 117. Most regional schedules planned without an FDP check fall within these limits naturally, but specific patterns — early starts with many sectors, or late starts that cross into the WOCL — can quietly exceed limits unless someone is paying attention.

## 4. How to extend FDP when a route requires it

If the schedule analysis shows the planned FDP exceeds the basic limit, three extension mechanisms exist under most regulatory schemes. Each comes with its own conditions and cost implications.

**Augmented crew (in-flight relief).** Adding a third pilot for narrowbody operations, or operating with a designated cruise relief pilot, allows part of the crew to rest in flight and substantially extends maximum FDP. Under FAR Part 117 Table C, the augmented FDP limits depend jointly on the rest facility class and the number of pilots in the augmented crew. For a peak-time report (07:00-12:59):

- **Class 1 rest facility** (lie-flat bunk, separate from flight deck and cabin, temperature- and light-controlled, isolated from noise): up to 17 hours with 3 pilots, **19 hours with 4 pilots**
- **Class 2 rest facility** (cabin seat allowing flat or near-flat sleeping position, curtain-separated from passengers): up to 16.5 hours with 3 pilots, 18 hours with 4 pilots
- **Class 3 rest facility** (cabin or flight deck seat reclining at least 40 degrees with leg and foot support): up to 15 hours with 3 pilots, 15.5 hours with 4 pilots

For regional narrowbody operations, augmented crew typically means adding a third pilot in the cockpit, with the relief pilot rotating into the operational seat during a defined cruise period. This is the standard mechanism for long single-day rotations that exceed unaugmented FDP. Note that Class 1 facilities are rare on narrowbody aircraft; most regional augmented operations use Class 2 or Class 3 rest facilities, which reduces the available FDP extension.

**Split duty.** Part 117 Section 117.15 permits a split-duty rest opportunity during an unaugmented FDP, with strict conditions: the rest must be provided between 22:00 and 05:00 local time, must be at least 3 hours in a suitable accommodation, must be scheduled before the FDP begins, must be provided only after the first flight segment, and the combined FDP and rest must not exceed 14 hours. Properly scheduled split duty allows the rest time to be excluded from the FDP calculation, effectively extending the operational window. The conditions are restrictive: split duty is not a planning tool for routine schedules, but a real option for specific patterns where a long ground time at an intermediate station coincides with the night hours.

**Discretion (commander's discretion under unforeseen circumstances).** When unforeseen operational circumstances arise (weather diversions, technical delays, ATC holds), most schemes allow the FDP to be extended at the captain's and certificate holder's discretion. Under Part 117 Section 117.19, the FDP may be extended by up to 2 hours, and any extension over 30 minutes requires reporting to the regulator and corrective action. Critically, this discretion may not be used to exceed the cumulative FDP limits in Section 117.23(c). This is a contingency mechanism, not a planning tool. Schedules built to require commander's discretion routinely are not legally schedulable; the discretion exists for actual operational disruptions, not for planned operations near the edge of limits.

## 5. Rest requirements and cumulative limits

FDP is one side of the equation. The other side is rest. Most regulatory schemes specify rest in two ways:

**Pre-duty rest.** Minimum rest period before reporting for a duty. Typical minima:
- At home base: at least the length of the preceding duty or 12 hours, whichever is greater
- Away from home base: at least the length of the preceding duty or 10 hours, whichever is greater (with required minimum sleep opportunity of around 8 hours)

The rest must allow for an 8-hour sleep opportunity, which accounts for travel time to and from the accommodation, meal time, and physiological needs.

**Cumulative limits.** Beyond single-duty FDP, schemes impose cumulative limits on flight time and on duty time across rolling and calendar periods. Two authoritative reference schemes illustrate the typical structure, using different reference periods:

**FAR Part 117** (US, current rule for all Part 121 passenger operations since 2014), Section 117.23, uses rolling consecutive-hour windows:
- Flight time: **≤ 100 hours in any 672 consecutive hours** (28 days)
- Flight time: **≤ 1,000 hours in any 365 consecutive calendar day period**
- FDP: **≤ 60 hours in any 168 consecutive hours** (7 days)
- FDP: **≤ 190 hours in any 672 consecutive hours** (28 days)

**CCAR-121 R8** (China, large aeroplane commercial operations), Section 121.487, uses calendar-period windows:
- Flight time: **≤ 100 hours in any calendar month**
- Flight time: **≤ 900 hours in any calendar year**
- FDP: **≤ 60 hours in any 7 consecutive calendar days**
- FDP: **≤ 210 hours in any calendar month**

The two schemes converge on the most operationally meaningful numbers: roughly 100 hours of flight time per month and 900 to 1,000 hours per year. Duty-period ceilings are typically set substantially higher than the flight-time ceilings, reflecting that duty includes report time, turnaround time, and ground time that does not appear in flight time.

The difference between rolling windows (Part 117) and calendar windows (CCAR) matters in roster construction. A rolling 672-hour window means the limit is checked continuously and any 28-day stretch must comply, which is more demanding to track but harder to game. A calendar-month window allows higher utilisation in the second half of one month immediately followed by the first half of the next, but the implementation cost is simpler. Network planners should know which window their home regulation uses, because it shapes how aggressive the monthly schedule can be at the boundary between months or 28-day periods.

These cumulative limits are why a regional carrier's roster planning is not just "can each individual duty fit within FDP?" but also "across the 28-day or calendar-month roster, do we have enough qualified crew to absorb the total flying without anyone breaching cumulative limits?" Crew planning becomes a multi-dimensional optimisation problem rather than a single-duty check.

## 6. The single-aircraft regional rotation problem

This is where the theory meets practice for many regional carriers. A typical single-aircraft regional pattern might involve operating six to eight sectors in a day from a base, with multiple short turns at outstations and a return to base in the evening. The aircraft is utilised highly. The crew, however, may be running into FDP constraints before the aircraft does.

Consider a hypothetical regional pattern:
- Report at 08:00
- Eight sectors covering ~8.5 hours of total block time
- Multiple intermediate turnarounds of 45-60 minutes each
- Last engines-off at 22:30

The FDP from 08:00 report to 22:30 engines-off is 14:30. Under FAR Part 117 Table B, the maximum FDP for an 08:00 report (in the 07:00-11:59 window) with 7+ flight segments is 11.5 hours. The planned schedule exceeds the regulatory limit by 3 hours and is not legally schedulable as planned. The same operation under CCAR-121 R8 Table B (which uses broader time bands) gives a maximum FDP of 11 hours for an 08:00 report with 7+ sectors — almost the same constraint. Both regulators reach the same conclusion: this duty cannot be flown by an unaugmented crew.

The planner has three options:

**Option 1: Restructure the schedule.** Reduce the number of sectors, change the start time, or split the operation across two days. This is the cleanest solution but may not be commercially viable if the route requirements are fixed.

**Option 2: Add augmented crew.** A third pilot, with appropriate in-flight rest provisions, can extend the FDP enough to operate the planned schedule. The cost implication is significant: an additional pilot day-rate, additional positioning costs, and the broader fleet impact of needing more pilots in the pool.

**Option 3: Dual crew rotation.** Two complete crews swap mid-rotation, each operating part of the day. This is operationally complex and requires the swap point to be at a base or outstation where the second crew is available. For a single-aircraft operation, this means crew positioning costs.

The right answer depends on the route economics and how often the constraint applies. A pattern that hits the FDP wall once a week (one day per pattern type that exceeds limits) is typically best handled with augmented crew or dual crew on that specific day, while other days run normal crew. A pattern that hits the FDP wall every day requires fundamental schedule restructuring.

What network planners should never do is build the schedule first and discover the FDP problem second. The FDP envelope should be a Day One input to the network design, sitting alongside aircraft range, slot availability, and turnaround time.

## 7. FRMS: the alternative to prescriptive limits

For operators that find the prescriptive limits commercially restrictive, ICAO Annex 6 Appendix 7 establishes the **Fatigue Risk Management System (FRMS)** as an alternative compliance pathway. FRMS allows an operator to deviate from prescriptive FDP limits, but only if the operator demonstrates through data, scientific principles, and continuous monitoring that the alternative limits maintain equivalent safety.

FRMS is not a workaround. It is a substantially more demanding regulatory regime than prescriptive limits. An FRMS-approved operator must:

- Document fatigue hazards systematically
- Collect crew alertness data (sometimes including biometric data)
- Apply scientifically validated fatigue prediction models
- Continuously monitor FRMS effectiveness and adjust limits based on data
- Submit to enhanced regulatory oversight

For most regional carriers, the cost and complexity of full FRMS implementation outweighs the operational flexibility gained. FRMS is more commonly seen in long-haul operators where the prescriptive limits are genuinely binding on commercial operations and the data infrastructure to support FRMS is justified by the scale. Regional carriers typically stay within prescriptive limits and treat FDP as a planning constraint.

## 8. Practical takeaways for the regional schedule planner

For anyone designing single-aircraft or small-fleet regional rotations, four working rules:

**Rule 1: Map the FDP envelope before the first schedule iteration.** Know the maximum FDP for each combination of report time and sector count under your home-state regulations. This should be a one-page reference for the network planning team, not a knowledge that lives only with the chief pilot.

**Rule 2: The constraining day shapes the entire rotation.** In a 7-day single-aircraft rotation, the day with the longest FDP usually drives the crew requirement for the whole pattern. Find the worst day first, solve crew constraints for it, then check that the solution works for the other days.

**Rule 3: Augmented crew is a tool, not a punishment.** Adding a third pilot on the most demanding day of a rotation is sometimes the lowest-cost solution to FDP overruns. It is also often the simplest, requiring no schedule restructuring or commercial trade-offs. Treat it as one option among several, not as an admission of planning failure.

**Rule 4: Document FDP at the planning stage.** Every published rotation should have a documented FDP analysis showing the planned FDP for each day, the applicable maximum, and any extension mechanisms used. This is good practice for safety oversight, and it is essential evidence if the schedule is ever questioned by the regulator or in a post-incident review.

## Closing

Crew limits are not a constraint that should be discovered late in route planning. They are inputs that determine which routes can be flown, with which crew complement, on which schedule, with which cost structure. A regional carrier whose schedule planners understand FDP at the same fluency as they understand block time, fuel uplift, and slot availability operates with a real efficiency advantage over carriers where FDP is treated as a downstream compliance check.

The aircraft can usually do more than the crew can. Whether that is the actual binding constraint depends entirely on how the schedule is designed. Design it with crew limits as a Day One input, and the constraint becomes a designed-around feature rather than a discovered-late problem.

---

*This article describes the international framework for flight and duty time limitations as established by ICAO Annex 6 Part I. Numerical limits cited are illustrative reference values based on typical prescriptive schemes; specific limits applicable to any operation depend on the operator's home-state regulations and the regulations of states into which the operation flies. Operators and crew should rely only on the current published regulations of the applicable civil aviation authority and on the operator's own Operations Manual.*
