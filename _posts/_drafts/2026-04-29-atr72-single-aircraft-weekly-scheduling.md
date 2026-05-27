---
title: "Single-Aircraft ATR 72-600 Weekly Scheduling: A Day-Pattern Framework"
date: 2026-04-29 08:00:00 +0700
categories: [Aviation, Network Planning]
tags: [atr 72-600, scheduling, regional aviation, network planning, fdp, southeast asia]
description: "A practical framework for building a weekly schedule for a single ATR 72-600 in Southeast Asian operations, with realistic block times, six reusable day patterns, and FDP discipline."
---

Operating a single ATR 72-600 across a multi-country regional network is a constraint puzzle, not a spreadsheet exercise. You have one airframe, one base, fixed minimum ground times, regulatory FDP ceilings, and a market that wants frequency at viable times. Getting all of that into seven days of revenue flying — without ferry legs, without crew duty overruns, and without sacrificing commercial appeal — takes more than dragging blocks around in GanttView.

This article walks through a practical day-pattern framework for single-aircraft ATR 72-600 scheduling. It assumes a single hub, daily overnight at base, all sectors revenue, 60-minute minimum ground turns, and a 14-hour FDP cap consistent with ICAO-aligned regulators. Numbers used below are illustrative planning values typical of Southeast Asian operations.

## 1. Why day patterns beat ad-hoc sector building

If you build a single-aircraft week sector by sector, you end up chasing your tail. Each new sector forces you to revisit the previous one. Block times shift, ground times collide with curfews, and FDP creeps over the line on Thursday before you noticed.

Day patterns reverse the problem. Instead of optimizing 40+ sectors directly, you design **4 to 6 reusable rotations** — each one starts and ends at base on the same day — and then assemble the week from those building blocks.

The benefits compound:

- **Crew predictability.** Pilots and flight attendants see the same shapes repeat. Briefings become routine.
- **Maintenance window stability.** Engineering knows when the aircraft is at base and for how long.
- **Failure recovery.** When weather or AOG disrupts a day, swapping in a known shorter pattern is far easier than rebuilding.
- **Commercial discipline.** You can defend each pattern's economics independently rather than averaging the whole week.

## 2. Block-time discipline: plan for what actually happens

Single-aircraft schedules are unforgiving. A 10-minute slip on sector 2 cascades through every remaining sector that day. Building with optimistic block times is the single most common cause of schedule collapse.

For an ATR 72-600 operating in Southeast Asia, useful planning block times (door-to-door, including standard taxi):

| Sector type | Typical distance | Planning block |
|---|---|---|
| Short domestic | < 200 nm | 0:50 – 1:05 |
| Cross-border subregional | 250 – 350 nm | 1:25 – 1:45 |
| Regional reach | 400 – 500 nm | 1:50 – 2:15 |
| Long regional | 500+ nm | 2:20 – 2:35 |

These should be **published block times that match historical actuals**, not airframe performance brochures. If your last 90 days of OFP data show an average 1:48 on a 1:35 published block, the published block is wrong, not the crews.

Add **60 minutes minimum ground turn** at outstations. The ATR is technically capable of a 25–30 minute turn, but for revenue planning you need buffer for late inbound, slot deviation, ground equipment availability, and immigration/customs holds at international sectors. Save the 30-minute turn capability for irregular ops recovery.

## 3. Construction logic: hard constraints first

Before you draw a single rotation, write down the constraints that cannot move:

1. **First departure** from base not before the catchment supports it (typically 09:00 local for short-haul leisure-mix routes; 06:00 if connecting bank logic dictates).
2. **Last arrival** at base not after the curfew or crew rest reset point (commonly 23:00 local).
3. **Daily block** ≥ 7:00 to justify the asset's daily operating cost.
4. **FDP** ≤ 14:00 per duty period (verify against your specific MCAR/CAA limits).
5. **All sectors revenue** — no positioning legs in a single-aircraft plan, ever. If you need to position, the network is wrong.

Then choose your **anchor sectors** — the long radials that determine each day's shape. For a single ATR with a base in the regional center, anchors typically fall into three categories:

- **Out-and-back to your furthest profitable city** (~2 hours block each way). Eats most of the day; high yield required.
- **Double-header to your busiest hub** (twice in one day). Frequency play; works only when the city pair supports two distinct demand windows.
- **Triangulation** (base → A → B → base). Highest aircraft productivity per day, but only viable when the A–B leg has genuine O&D, not just a connection-of-convenience.

## 4. Six day patterns that work

Here are six rotation shapes I've found viable for a SEA-based single ATR. Block times shown are illustrative single-leg values; substitute your own actuals.

### Pattern A — Long Triangle (highest productivity)

```
Base → SAI (1:05) → HAN (1:45) → SAI (1:45)
     → SGN (1:35) → SAI (1:30) → Base (1:05)
```

Total block: ~8:45. Six sectors. RTB around 22:45 with a 13:30 block start. **Highest productivity pattern**, but tight on FDP — verify against your specific duty calculation including report and debrief time.

### Pattern B — Hub Double-Up

```
Base → SAI (1:05) → SGN (1:35) → SAI (1:30)
     → Base (1:05) → BKK (1:30) → Base (1:30)
```

Total block: ~8:15. Touches base mid-day, which gives operations a check-in point and creates a natural connecting bank for inbound passengers.

### Pattern C — Single Out-and-Back + Local

```
Base → SGN (0:50) → Base (0:55) → SAI (1:05)
     → Base (1:05) → CXR (1:40) → Base (1:45)
```

Total block: ~7:20. Lower utilization day. Useful for slot-constrained Sundays or when commercial demand drops on certain days of the week.

### Pattern D — All-Domestic

```
Base → SAI (1:05) → KOS (1:15) → SAI (1:15)
     → KOS (1:15) → Base (0:50)
```

Total block: ~5:40. Low utilization. Use this as your **maintenance-friendly day** — short turn time at base in the evening leaves engineering room for line checks.

### Pattern E — Short International + Mixed

```
Base → SGN (0:50) → Base (0:55) → KOS (0:50)
     → BKK (1:25) → KOS (1:25) → Base (0:50)
```

Total block: ~6:15. Reaches Bangkok via a domestic connection, useful when direct base–BKK economics don't work but KOS–BKK does.

### Pattern F — Mid-Range Triangle

```
Base → SAI (1:05) → VTE (2:15) → SAI (2:15)
     → Base (1:05)
```

Total block: ~6:40. Only four sectors. Good Wednesday or Thursday option when crew need a recovery day from a heavier Tuesday.

## 5. The FDP trap on high-block days

If a pattern gives you 9 hours or more of block, you must audit FDP cold-bloodedly. With 60-minute turns, a 60-minute report time, and 30-minute debrief, the math is roughly:

```
FDP ≈ Report (1:00) + Σ(block + ground time) + Debrief (0:30)
```

Worked example: a Saturday pattern flying base → SAI → SGN → SAI → base → DAD → base, with six sectors totaling 9:50 block and five intermediate ground turns:

- Report: 1:00
- Block total: 9:50
- Ground turns: 5 × 1:00 = 5:00
- Debrief: 0:30
- **FDP total: ~16:20**

That is a serious overrun against a 14:00 cap. The fixes, in order of preference:

1. **Drop a sector.** Cleanest answer. Reshape the pattern so it fits.
2. **Augmented crew.** Add a third pilot to extend the FDP cap. Cost goes up, training records get more complex.
3. **Split duty.** Insert a ground rest period that resets the FDP clock. Practical only if you have crew accommodation at an outstation.
4. **Move to a different day pattern.** Sometimes the "high-yield Saturday" is just not feasible with one airframe. Accept it.

What you do **not** do is publish the schedule and "see how it goes." FDP overruns are how you lose your AOC.

## 6. Competitive timing without frequency

A single ATR cannot match an A320 operator on frequency. It competes on timing.

If your competitor flies a daily rotation departing at 13:00 on a key route, do not fly 12:50. You'll split the same demand pool and lose on aircraft size. Fly **09:30** to capture early business and outbound day-trippers, or **16:00** for the late-afternoon connecting bank. Run the OAG schedule for the city pair, identify the gaps in the published timetable, and aim your aircraft into them.

This is also where blue-ocean routes come in. Sectors that no incumbent operates daily — secondary city pairs, off-hub triangulations, weekend-only leisure routes — are exactly where a single ATR with a flexible day-pattern bank can build defensible yield.

## 7. The seventh day matters more than the first

You will be tempted to fill the seventh day of the week with overflow routes that didn't fit elsewhere. Resist.

A single-aircraft weekly schedule needs at least one **lower-utilization day** for:

- **Maintenance opportunity.** A-checks, line maintenance windows, deferred defect catch-up.
- **Irregular operations buffer.** When Tuesday's typhoon strands the aircraft at an outstation, Sunday's slack is what lets you recover by Monday.
- **Crew rest pattern stability.** Predictable lighter days protect against duty-cycle fatigue accumulation across the month.

A 6:00–7:00 block day on Saturday or Sunday is healthier for the operation than seven consecutive 9:00 days that crumble after one weather event.

## Closing

Day patterns are a way of compressing thousands of scheduling variables into a small set of repeatable shapes. Build your six patterns first, audit each one against FDP and ground-time discipline, then assemble the week.

Three rules to keep in your head while you build:

1. **Published block times must match historical actuals**, not brochure performance.
2. **FDP audits are non-negotiable** — audit cold, never optimistically.
3. **Schedule resilience matters more than peak utilization** for a single aircraft.

The operator who flies 7×7 hours reliably beats the operator who plans 7×9 hours and delivers 5×9 + 2×0. The market remembers cancellations; it forgets the days you were on time.

---

*This article reflects general scheduling practice for single-aircraft regional operations. Specific FDP limits, ground time minima, and operational requirements vary by jurisdiction and operator AOC — always verify against your applicable MCAR/CAR and your company's operations manual before publishing a schedule.*
