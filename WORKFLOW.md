# Workflow

The path from idea to a built, audited result, in eight steps. Each step
says what to do, and most end with a check. Times are rough guides, not
rules — a small project may take a day end to end; a large one, much
longer.

```
idea → capture → interview → brief review → plan → plan check → build → test → audit → done
```

## Step 1 — Capture the idea (10 minutes)

Write your idea in `PROJECT_BRIEF.md`, section 1, in your own words.
Messy is fine. Two sentences beat a blank page.

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
- [ ] Success criteria are checkable, not vibes.
- [ ] Scope lists at least one thing that's *out*.
- [ ] Every assumption and open question is written down, not just felt.
- [ ] Nothing is filled in with a guess presented as fact.

If items fail, fix them before planning. A plan built on a shaky brief
inherits every crack.

## Step 4 — Build the plan

Fill in Part B of `PROJECT_BRIEF.md`:

1. **Approach** — a few sentences on how you'll build it and in what order.
2. **Milestones** — each needs an observable "done when" condition, not
   just a name.
3. **Acceptance checks** — the short list of checks, written so a
   stranger could run them, that must pass before this counts as done.
4. **Next actions** — 1–3 small, concrete steps you could start today.
5. **Deferred work** — park good-but-later ideas so they stop circling.
6. **Review checkpoint** — when you'll come back and re-read all this.

With an AI assistant, this is step 5 of the master prompt. It should
propose a plan; you approve or correct it.

## Step 5 — Sanity-check the plan

- [ ] The first next action is doable today and by you (or a named person).
- [ ] Each milestone's "done when" could be judged by someone else.
- [ ] Steps that depend on an open question are marked as such.
- [ ] The plan fits the project's actual size — no ceremony for a
      weekend build, no hand-waving for a big one.
- [ ] You believe the first milestone is reachable. If not, cut scope.

## Step 6 — Build in small increments

Start the build. With an AI assistant or coding agent, paste the prompt
from `BUILD_HANDOFF_PROMPT.md` into it; working alone, use that page as
your working agreement.

- Clarify blocking unknowns before building; settle the rest with a
  recorded assumption.
- Build one milestone or next action at a time. Each increment ends
  somewhere that runs and can be checked — never half-wired.
- Keep the documents current as you go: tick next actions, log decisions
  in Part A's Decisions made, update open questions as they're answered.
- When scope changes, re-run the Step 3 checklist. At each review
  checkpoint, re-read both parts honestly and revise.

**Check:** after every increment you can point at something that runs
and say how you'd know it works.

## Step 7 — Test and collect evidence

Run the acceptance checks from Part B, plus anything else that would
convince a skeptic: actual commands, actual outcomes.

- Record what was verified and how — and also what was *not* verified,
  plus any known limitations. Both lists matter.
- Match effort to size: an afternoon project needs evidence, not
  ceremony.

**Check:** every success criterion in Part A is demonstrated, explicitly
untested, or out of scope — with the evidence written down somewhere you
can find it again.

## Step 8 — Audit before publishing

Before calling this done — and before showing it to anyone it's meant
for — get an independent check. Hand a person or agent who hasn't
followed the build the brief, the acceptance checks, and the build
report. Have them run the checks cold, challenge every claim in that
report — what was verified, what wasn't, and the limitations — and
write up their findings.

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
| Plan feels abstract                  | Shrink the first next action until it's boringly concrete.  |
| Keep changing the scope              | Move new ideas to Deferred work, not into scope.            |
| Don't trust a claim in the brief     | Move it to Assumptions until verified.                      |
| AI assistant invented details        | Correct it, and re-state the "never invent facts" rule.     |
| Build keeps stalling                 | The increment is too big — cut it in half until it's boring. |
| Can't tell if it really works        | Write the acceptance check first, then build until it passes. |
| Assistant reports "done"             | Ask for evidence: what it ran, what that showed, what wasn't checked. |

## When to stop planning

Stop when Part A is honest, Part B's first steps are concrete, and the
remaining unknowns are written down with a way to resolve each. More
planning than that has diminishing returns — the work itself will teach
you things the plan can't.

## When it's done

Done means the acceptance checks pass with evidence you can point at,
someone independent has audited the result, and the limitations are
written down. Anything short of that is a status, not a finish line.

