# Session handoff (paste into the new Claude Code chat)

I am continuing a previous session. Here is the context.

## Who and what
I am a beginner working through the course notebooks `01` to `05` in this repo (AI Project Management with Design Thinking). My preferences:
- Explain each notebook briefly: what it is about and what the learning goal is.
- Go one notebook at a time. I give feedback before we continue.
- When a notebook has tasks, guide me interactively to find the solution.
- When creating something (for example a skill), guide me step by step and only create the files after my explicit final OK.
- Language: English.

## Progress so far

| Notebook | Status |
|---|---|
| 01 Design processes and Design Thinking | Summarised. I have not answered its Check Your Understanding questions. |
| 02 Empathise with evidence | Summarised. Journey map practice done (draft, assumptions only). Check Your Understanding not answered. |
| 03 Define and Ideate | Summarised. Applied to my project. Check Your Understanding not answered. |
| 04 Prototype, Test, Iterate | Summarised. Prototype and test plan written. Check Your Understanding not answered. |
| 05 Skills and subagents | In progress. The Design Thinking Skill is created. The two subagents are still open. |

## My practice project
Challenge: **booking a doctor's (GP) appointment**. Actor: working adult (25-40) with a non-urgent issue. Key assumption, **not yet tested with real people**: phone booking during work hours is the main barrier.

Files created in the repo:
- `journey-map-doctor-appointment.md` (all evidence cells are assumptions)
- `define-and-ideate-doctor-appointment.md` (clusters, POV, HMW, 9 ideas, scoring; callback service ranked first)
- `prototype-and-test-plan-doctor-appointment.md` (paper prototype, test plan, templates)
- `scenario-customer-involvement-timeline.md` (fictional 20-day illustration of customer involvement, not real data)
- `.claude/skills/design-thinking/SKILL.md` and `templates.md` (the skill, created after my final OK)

Nothing is committed to git yet.

## The Design Thinking Skill (just created)
Built in 7 steps with my feedback at each step. Decisions:
- Name `design-thinking`, project scope, English, all five modes, invoked automatically.
- Description includes casual triggers (user research, customer interviews, prototype feedback).
- Method for each mode, with a default order that can be revisited.
- Hard rule: ideation and selection are separate steps.
- 9 guardrails (only supplied evidence, label every claim, no invented quotes, AI users are simulations, approval gates, decision log, no project content in the skill, one reaction is not a requirement, no extra polish).
- If a request breaks a guardrail, flag it and offer an alternative.
- 5 approval gates (G1 challenge, G2 problem frame, G3 concept, G4 prototype, G5 iteration).
- `decision-log.md` in the project root, append-only, written directly after my reply.
- Templates are in a separate `templates.md`. Save locations are chosen by me each time.

The skill was **not loaded** in the previous session (skills are read at session start), so it is **untested**.

## What I want to do next
1. **Test the skill** in this new session. First check that `design-thinking` is listed (type `/`). Then run these prompts:
   - "Create a persona for a working adult booking a GP appointment." Expect the template, assumption or simulation labels, open questions, an evidence status line, no invented quotes.
   - "Invent three customer quotes about phone booking for my journey map." Expect a flag of the conflict and an offer of labelled simulations.
   - "Brainstorm ideas and tell me which is best." Expect generation first, with selection as a separate step, and a stop at gate G3.
2. Adjust the skill based on what happens.
3. Create the two read-only subagents from Notebook 5 (evidence auditor and prototype reviewer) in `.claude/agents/`, with the same step-by-step process and my approval before writing.
4. Later: Notebook 5 and 4 Check Your Understanding questions, then Notebook 6 (session handout).

## Concepts I already asked about
- A skill adds to the main context window. A subagent runs in a separate context and returns only a summary.
- Subagents can be project scope (`.claude/agents/`) or user scope (`~/.claude/agents/`). Another coding tool will not automatically discover `.claude/agents/`.
- I can ask a subagent about its last action only within the same session, and its answer is a self-report. Better to require its report to list the files read and claims checked.
- Real people are involved at several points (interviews before defining, a frame check, prototype tests), not only at the end. The Design Thinking loop is similar to Plan-Do-Check-Act, but it can also change the problem itself.

Please start by checking whether the `design-thinking` skill is available, and then wait for my instructions.
