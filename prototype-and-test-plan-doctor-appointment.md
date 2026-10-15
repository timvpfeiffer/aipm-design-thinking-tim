# Prototype and Test Plan: Booking a GP Appointment

Builds on [define-and-ideate-doctor-appointment.md](define-and-ideate-doctor-appointment.md) and [journey-map-doctor-appointment.md](journey-map-doctor-appointment.md).

**Evidence status:** No real tests have been run. Sections 4 and 5 are templates to fill in after real sessions. Nothing here is a finding yet.

## 1. Learning question

> Is waiting on hold during work really what stops working adults from booking a GP appointment, and does a callback request remove that barrier?

**Assumptions under test:**
- A1: Working adults avoid or delay booking because phone booking clashes with work.
- A2: Requesting a callback at a chosen time feels easier than calling.
- A3 (trust): People believe the callback will actually happen.

## 2. Prototype

**Idea tested:** Callback service (idea 2 from the ideation file).

**Fidelity:** Low. A paper flow or a few sketched screens, with a facilitator playing the "system". No code, no visual polish.

**Why this fidelity (Notebook 4):** The question is whether the *journey* makes sense and whether people trust it, not whether they can find a button. A paper flow is enough, and polish would distract.

**Flow (4 screens or cards):**
1. "Need an appointment?" with the options **Call now** or **Request a callback**
2. Callback form: name, phone number, preferred time window (e.g. 12–13h, after 17h), reason (optional, short)
3. Confirmation: "We'll call you between 17:00 and 18:00 on Thursday."
4. Reminder message: "Your callback is today, 17:00–18:00. Can't talk? Tap to change the time."

**Facilitator role:** Shows one card at a time and answers only with "What would you do next?" Does not explain the intended action.

## 3. Test plan

| Element | Plan |
|---|---|
| **Participants** | 3–5 working adults (25–40) who have booked, or avoided booking, a GP appointment in the last year. Real people, not AI-simulated. |
| **Why relevant** | They match the actor in the journey map. |
| **Setting** | 15 minutes, in person or by video, one person at a time. |
| **Task (neutral)** | "Imagine you have had back pain for two weeks and you work 9 to 5. Show me how you would get an appointment, using this." |
| **Observe** | Where they hesitate, what they tap or point to first, whether they find the callback option on their own, whether they ask if the callback is reliable, and what they say out loud. |
| **Follow-up questions** | 1. "What would you do next?" (at each card) 2. "Tell me about the last time you tried to book. What happened?" 3. "What, if anything, would stop you from using this?" |
| **What would change the design** | If most people say hold time was not their problem, revisit the problem frame and the POV. If people do not trust the callback, add reassurance or test another idea. If people want to pick a slot directly, test online booking (idea 1). |

**Avoid:** asking "Do you like it?", describing the callback idea before the task, or counting polite approval as evidence.

## 4. Session notes template

Copy one table per participant.

**Participant:** P1 | **Real / simulated:** Real | **Context:** (age range, job, last booking)

| Observation (what happened or was said) | Interpretation (what it may mean) | Decision |
|---|---|---|
| | | |

## 5. Synthesis template

| Assumption | Evidence for | Evidence against | Sample size | Confidence | Next action |
|---|---|---|---|---|---|
| A1: Phone booking clashes with work | | | | | |
| A2: Callback feels easier | | | | | |
| A3: People trust the callback | | | | | |

**Confidence guide:** one person is an anecdote, 3 or more with the same behaviour is a hint, and anything less than that stays an assumption.

## 6. Iteration

After the tests, decide:
- **Keep** what the evidence supports.
- **Change** the prototype, HMW question, persona, journey map or problem statement where the evidence contradicts them.
- **Do not change yet:** (note what you deliberately leave alone, and why)

If the test challenges the problem frame, update the evidence and revisit the POV before adding any feature.

## 7. Responsible AI note

AI may help word the tasks, spot ambiguous questions or play a sceptical reviewer. Any AI role-play must be labelled **simulation** and kept separate from real observations in section 4.
