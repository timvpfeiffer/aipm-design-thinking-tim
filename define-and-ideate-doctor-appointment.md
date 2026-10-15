# Define and Ideate: Booking a GP Appointment

Builds on [journey-map-doctor-appointment.md](journey-map-doctor-appointment.md).

**Evidence status:** The journey map contains only assumptions. Everything below is a **hypothesis** until it is checked against real evidence.

## 1. Clusters and tensions

| Cluster | Journey phases | Need or tension behind it | Type |
|---|---|---|---|
| Doubt before acting | 1 Realise | "Is this serious enough to book?" Uncertainty delays action. | Assumption |
| Effort to get a slot | 2 Find, 3 Choose | Booking depends on office hours, while the user is at work. | Assumption |
| Uncertainty after booking | 4 Confirm, 5 Prepare and go | "Did it work?" and "What if I can't make it?" | Assumption |

**Most important cluster (current guess):** Effort to get a slot. It has the largest assumed pain point (phase 3).

## 2. Point of View (POV)

> A working adult with a non-urgent health issue needs to book an appointment outside their working hours without waiting on hold, because we assume that phone lines are busy in the morning and conflict with work.

**Status:** Hypothesis. The "because" is not yet backed by evidence.

## 3. Problem statement

Working adults with a non-urgent health issue struggle to book a GP appointment that fits around work, because the main booking routes seem to depend on office hours.

Checklist:
- User-centred, no solution inside: yes
- Specific enough to investigate: yes
- Grounded in observed behaviour: **not yet** (needs evidence)
- Open to several solutions: yes
- Constraints: non-urgent cases only, existing practice systems

## 4. How Might We questions

1. How might we help a working adult book an appointment when they cannot make phone calls during work hours?
2. How might we help someone feel sure that their booking went through?
3. How might we help someone who is unsure whether their issue is "serious enough" take the first step?
4. How might we make rescheduling as easy as booking?

None of these names a solution.

## 5. Ideas (diverge)

Generated for HMW 1 and 2, with judgement deferred.

| # | Idea | Technique |
|---|---|---|
| 1 | Online booking available 24/7 | What if... office hours did not matter? |
| 2 | Callback service: leave a number and the practice calls you back at a time you choose | Substitute (waiting on hold becomes a callback) |
| 3 | Text message booking: reply with a preferred time | Adapt (from hair salons) |
| 4 | Chat assistant that offers free slots | Combine (search and booking) |
| 5 | One-tap confirmation message with a calendar entry | Combine |
| 6 | Reminder with a "reschedule" link | Modify |
| 7 | Book through an employer or occupational health service | Put to another use |
| 8 | Remove the need to choose a doctor: first available slot wins | Eliminate |
| 9 | Let the doctor propose a slot after a short symptom form | Reverse |

## 6. Selection (converge)

Scores run from 1 (low) to 3 (high). They are rough personal judgements, not evidence.

| Idea | User value | Learning value | Feasibility | Risk (3 = low risk) | Total |
|---|---|---|---|---|---|
| 1 Online booking 24/7 | 3 | 2 | 2 | 3 | 10 |
| 2 Callback service | 3 | 3 | 3 | 3 | 12 |
| 3 Text message booking | 2 | 2 | 3 | 2 | 9 |
| 4 Chat assistant | 2 | 2 | 1 | 1 | 6 |
| 5 One-tap confirmation | 2 | 2 | 3 | 3 | 10 |
| 9 Doctor proposes slot | 2 | 3 | 2 | 2 | 9 |

**Pick to learn from first:** Idea 2 (callback service). It could be tested cheaply, for example by faking the callback by hand, and it tests the most important assumption: that waiting on hold during work is the real problem.

**Risk notes:** Callback excludes nobody who can already use a phone. Online-only ideas may exclude people who are less comfortable with digital tools.

## 7. User story

> As a working adult with a non-urgent issue, I want to request a callback at a time that suits me, so that I can book an appointment without waiting on hold during work.

**Evidence attached:** None yet (assumption).
**Learning question:** Is waiting on hold during work hours really what stops working adults from booking?

## 8. Next step

Check the key assumption with real evidence before building a prototype. Options are asking 3–5 people about their last booking, or looking at reviews or complaints about booking at local practices.
