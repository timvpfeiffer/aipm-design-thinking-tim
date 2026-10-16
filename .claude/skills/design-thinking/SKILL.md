---
name: design-thinking
description: Guides Design Thinking work (Empathise, Define, Ideate, Prototype, Test) with evidence discipline. Use when creating or reviewing discovery artefacts such as evidence logs, personas, journey maps, problem statements, HMW questions, idea selections, prototypes or test plans, and for requests about user research, customer interviews, understanding users or prototype feedback. Keeps evidence, interpretation and assumptions separate, treats AI-generated users as simulations, and asks for human approval at decision points.
---

# Design Thinking

This skill describes a method and its guardrails. It contains no project-specific
answers. Use only the evidence the group supplies.

## Default order

Empathise → Define → Ideate → Prototype → Test, then iterate. The order is a
default, not a staircase. New evidence can send the work back to any earlier
mode. When it does, say which artefact must be updated.

## Method

**Empathise**
- Establish the person, goal and context.
- Keep an evidence log. Label every claim as direct evidence, behavioural
  evidence, interpretation or assumption.
- Build personas and journey maps only from supplied evidence. Include open
  questions where evidence is weak.

**Define**
- Cluster related observations and name the need or tension behind each cluster.
- Write a POV, a problem statement and HMW questions.
- The problem statement must be user-centred, specific, grounded in evidence,
  open to more than one response and bounded by constraints. It must not contain
  a solution. HMW questions must not contain a solution either.

**Ideate**
- Generate many ideas first, using techniques such as brainstorming, mind
  mapping, SCAMPER, "What if..." prompts and borrowing from other domains.
- Hard rule: do not score, rank or criticise ideas during generation. Select in a
  separate, later step.
- Select by user value, learning value, feasibility and risk. Prefer the idea
  that teaches the most about an important assumption.

**Prototype**
- Start from a learning question and name the assumptions under test.
- Choose the lowest fidelity that can answer the question. Do not add polish
  that the question does not need.

**Test**
- Write a test plan: learning question, participants and why they are relevant,
  a neutral task, what to observe, follow-up questions and what evidence would
  change the design.
- Prefer observing behaviour over asking whether someone likes the idea. Do not
  explain the solution. Ask "What would you do next?"
- Record observation, interpretation and decision separately.

**Iterate**
- State what changes, what is deliberately not changed yet and which earlier
  artefact (persona, journey map, HMW, problem frame) must be updated.
- Do not turn one reaction into a requirement. Note sample size, context and
  confidence.

## Guardrails

1. Use only evidence the group supplies. Never invent research, quotes,
   statistics or participants. If evidence is missing, say so and list it as
   "evidence needed".
2. Label every claim as direct evidence, behavioural evidence, interpretation or
   assumption. Treat unlabelled claims as assumptions.
3. Keep ideation and selection separate (hard rule).
4. Ask for approval before committing to a concept, choosing a problem frame or
   editing a prototype.
5. Treat AI-generated personas, users and reactions as simulations. Label them
   "simulation" and keep them apart from real observations. They are never
   evidence.
6. Record every suggestion as accepted, edited or rejected in the decision log.
7. Do not put project-specific content into this skill.
8. Do not turn one reaction into a requirement.
9. Do not add polish beyond the learning question.

If a request would break a guardrail (for example, "invent three customer
quotes"), flag the conflict and offer an alternative, such as a clearly labelled
simulation. Do not silently comply or silently refuse.

## Approval gates

Stop and ask for explicit approval at these points. Never continue on your own.

| Gate | When | Present |
|---|---|---|
| G1 Challenge | Before starting, if no challenge is chosen | Candidate challenges with person, goal and context |
| G2 Problem frame | After clustering, before the final POV and problem statement | Clusters, evidence labels, proposed POV and problem statement |
| G3 Concept | After ideation and scoring, before prototyping | Shortlist, scores, recommendation and reasoning |
| G4 Prototype | Before creating or changing a prototype | What will be built, fidelity and the learning question |
| G5 Iteration | After test results are supplied | Observation / interpretation / decision table and what to change or leave alone |

At each gate the human can accept, edit or reject. Work between gates is routine
drafting.

## Decision log

Keep one `decision-log.md` in the project root. Write each entry directly after
the human's reply. The log is append-only: never rewrite earlier entries. A later
change gets a new entry.

Fields: ID and date, gate, suggestion, outcome (accepted / edited / rejected),
the human's change or reason, evidence link (or "none: assumption").

## Artefacts

Read [templates.md](templates.md) before creating any artefact. Every artefact
starts with an evidence status line. Save location and file names are chosen by
the human each time.
