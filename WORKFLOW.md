# Workflow

Eight steps from idea to a reviewed result. The time estimates are
examples; adjust them to your project.

```
idea → capture → interview → brief review → plan → plan check → build → test → audit → done
```

## Step 1 — Capture the idea (10 minutes)

Write your idea in `PROJECT_BRIEF.md`, section 1, in your own words.
A few rough sentences are enough to start.

**Check:** someone who knows nothing about your situation could roughly
understand what you want.

## Step 2 — Interview (30–90 minutes)

Either paste the prompt from `MASTER_PROMPT.md` into an AI assistant and
answer its questions, or work through the remaining Part A sections
yourself, one at a time.

**Check:** every Part A section is either filled in or explicitly marked
Unknown / not applicable.

## Step 3 — Review the brief

Re-read Part A with fresh eyes, then run this checklist:

- [ ] The summary is 2–4 sentences and current.
- [ ] Goals and non-goals are stated separately.
- [ ] Success criteria can be checked.
- [ ] Scope lists at least one thing that's *out*.
- [ ] Every assumption and open question is written down, not just felt.
- [ ] Nothing is filled in with a guess presented as fact.

If an item fails, revise the brief before planning.

## Step 4 — Build the plan

Fill in Part B of `PROJECT_BRIEF.md`:

1. **Approach** — a few sentences on how you'll build it and in what order.
2. **Milestones** — each needs an observable "done when" condition, not
   just a name.
3. **Acceptance checks** — the short list of checks, written so a
   stranger could run them, that must pass before this counts as done.
4. **Next actions** — 1–3 small, concrete steps you could start today.
5. **Deferred work** — list ideas to consider later.
6. **Review checkpoint** — when you'll come back and re-read all this.

With an AI assistant, this is step 5 of the master prompt. It should
propose a plan; you approve or correct it.

## Step 5 — Sanity-check the plan

- [ ] The first next action is doable today and by you (or a named person).
- [ ] Each milestone's "done when" could be judged by someone else.
- [ ] Steps that depend on an open question are marked as such.
- [ ] The plan's level of detail fits the project's size.
- [ ] You believe the first milestone is reachable. If not, cut scope.

## Step 6 — Build in small increments

Start the build. With an AI assistant or coding agent, paste the prompt
from `BUILD_HANDOFF_PROMPT.md` into it; working alone, use that page as
your working agreement.

- Clarify blocking unknowns before building; settle the rest with a
  recorded assumption.
- Build one milestone or next action at a time. Make each increment
  runnable and testable.
- Keep the documents current as you go: tick next actions, log decisions
  in Part A's Decisions made, update open questions as they're answered.
- When scope changes, re-run the Step 3 checklist. At each review
  checkpoint, re-read both parts and revise.

**Check:** after every increment you can point at something that runs
and say how you'd know it works.

## Step 7 — Test and collect evidence

Run the acceptance checks from Part B. Record the commands or steps used
and the results observed.

- Record what was verified, what remains untested, and any limitations.
- Match the amount of testing to the project's size and risks.

**Check:** every success criterion in Part A is demonstrated, explicitly
untested, or out of scope — with the evidence written down somewhere you
can find it again.

## Step 8 — Audit before publishing

Before release, get an independent check. Give a person or agent who
did not build the project the brief, acceptance checks, and build
report. Have them run the checks, review the evidence and limitations,
and write down their findings.

- Fix what the audit finds, or record it as a known limitation with a
  reason.
- After fixes, re-check only what changed.
- Before sharing, remove secrets and private details from the result,
  documents, examples, and build report.

**Check:** the audit ran the acceptance checks cold, questioned the
build report, and every finding is fixed or recorded.

## Troubleshooting

| Symptom                              | Try this                                                    |
| ------------------------------------ | ----------------------------------------------------------- |
| Stuck on a section                   | Write Unknown and move on; it becomes an open question.     |
| Interview feels endless              | Ask for fewer, bigger questions; small project ≠ big brief. |
| Plan feels abstract                  | Make the first next action smaller and specific.            |
| Keep changing the scope              | Move new ideas to Deferred work, not into scope.            |
| Don't trust a claim in the brief     | Move it to Assumptions until verified.                      |
| AI assistant invented details        | Correct it, and re-state the "never invent facts" rule.     |
| Build keeps stalling                 | Reduce the size of the next increment.                      |
| Can't tell if it really works        | Write the acceptance check first, then build until it passes. |
| Assistant reports "done"             | Ask for evidence: what it ran, what that showed, what wasn't checked. |

## When to stop planning

Stop when Part A records the known facts, Part B has concrete first
steps, and each open question has a way to resolve it. Revise the plan
as the work produces new information.

## When it's done

Done means the acceptance checks pass, someone independent has reviewed
the result, and the limitations are recorded.

