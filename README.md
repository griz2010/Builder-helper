# Idea-to-Build Toolkit

Five plain Markdown files that guide you from a rough idea to a
written project brief, an implementation plan, and on to a built,
tested result. No software to install, no account needed, no specific
AI provider required.

## Who this is for

- **A person with an idea** — no project-management background assumed. If you
  can fill in a form, you can use this.
- **An AI assistant** — the files are written so a chatbot or coding agent can
  read them and run the process with you.

## The files

| File                      | What it's for                                                          |
| ------------------------- | ---------------------------------------------------------------------- |
| `README.md`               | This overview. Start here.                                              |
| `PROJECT_BRIEF.md`        | The fill-in template. Ends up holding the brief **and** the plan.       |
| `MASTER_PROMPT.md`        | A copy-paste prompt that asks any AI assistant to run the planning interview. |
| `BUILD_HANDOFF_PROMPT.md` | A copy-paste prompt that asks an AI assistant — or you — to build, test, and report with evidence. |
| `WORKFLOW.md`             | Step-by-step instructions and checklists for the whole journey.         |

## Quick start — humans

1. Open `WORKFLOW.md` and follow Step 1: write down your idea in a few
   sentences, right inside `PROJECT_BRIEF.md`.
2. If you're using an AI assistant for planning, copy the prompt from
   `MASTER_PROMPT.md` into it. If not, fill in the template yourself.
3. Work through the brief section by section. It is fine — expected, even —
   to write **Unknown** in places you don't have answers yet.
4. Check your work with the checklists in `WORKFLOW.md`.
5. When the plan is approved, start building: follow Step 6 in
   `WORKFLOW.md`, pasting the prompt from `BUILD_HANDOFF_PROMPT.md` into
   your assistant if you use one.
6. You're done when the acceptance checks pass with evidence, and someone
   who didn't do the building has audited the result.

## Quick start — AI agents

Read all five files, then act in two stages. First as the facilitator
described in `MASTER_PROMPT.md`: interview the user in small batches,
draft each section, get the user's confirmation, fill `PROJECT_BRIEF.md`
in place. Then, once the plan is approved, as the builder described in
`BUILD_HANDOFF_PROMPT.md`: clarify blocking unknowns, build in small
verifiable increments, test meaningful behavior, report evidence and
limitations, and ask for an independent audit before anything is
published. Keep the rules below. If the user is unavailable, stop and
ask — do not invent their answers.

## Ground rules

1. **Honesty about unknowns.** "Unknown" is always a valid answer.
  Nothing in these files should be filled with a guess presented as a fact.
2. **Provider-neutral.** The toolkit is designed to work with any AI
   assistant, or with none at all. No file assumes a particular vendor,
   model, or tool.
3. **Plain language.** Jargon gets a one-line definition or gets cut.
4. **Right-sized.** A weekend project needs less detail than a team effort.
  Shorten the template rather than padding it.
5. **Evidence over assertion.** "Done" means someone ran it and saw it
   work — or the report says plainly what wasn't checked.

