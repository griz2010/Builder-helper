# Idea-to-Build Toolkit

Prompts and templates for turning an idea into a project brief, a build
plan, and a tested result. You can use them on your own or with an AI
assistant. The files work with any text editor.

## Who this is for

- **People starting a project:** write down what you want to build and
  decide what to do first.
- **AI assistants:** ask for missing details, help build the project,
  and report what they checked.

## The files

| File | What it's for |
| --- | --- |
| [README.md](README.md) | This overview. |
| [PROJECT_BRIEF.md](PROJECT_BRIEF.md) | A template for the brief and plan. |
| [MASTER_PROMPT.md](MASTER_PROMPT.md) | A prompt for the planning interview. |
| [BUILD_HANDOFF_PROMPT.md](BUILD_HANDOFF_PROMPT.md) | A prompt for building and testing. |
| [WORKFLOW.md](WORKFLOW.md) | Instructions and review checklists. |

## Quick start — humans

1. Open `WORKFLOW.md` and follow Step 1: write down your idea in a few
   sentences, right inside `PROJECT_BRIEF.md`.
2. If you're using an AI assistant for planning, copy the prompt from
   `MASTER_PROMPT.md` into it. If not, fill in the template yourself.
3. Work through the brief section by section. Write **Unknown** where
   you do not have an answer yet.
4. Check your work with the checklists in `WORKFLOW.md`.
5. When the plan is approved, start building: follow Step 6 in
   `WORKFLOW.md`, pasting the prompt from `BUILD_HANDOFF_PROMPT.md` into
   your assistant if you use one.
6. Run the acceptance checks and ask someone who did not build the
   project to review the result.

## Quick start — AI agents

Read all five files. Follow `MASTER_PROMPT.md` to interview the user and
draft the brief. Get their approval before building. Then follow
`BUILD_HANDOFF_PROMPT.md`: resolve blocking questions, build in small
steps, test the result, report evidence and limitations, and request an
independent review before release. Do not invent answers for the user.

## Ground rules

1. Mark missing information **Unknown**. Label assumptions.
2. Use only the sections that apply to your project.
3. Explain technical terms when your reader may not know them.
4. Report what you tested and what remains untested.

## Credit and license

Created and maintained by **griz2010**, with AI assistance.

The documentation and prompts in this repository are licensed under
[Creative Commons Attribution 4.0 International](LICENSE.md) (CC BY 4.0).
You may share and adapt them if you credit griz2010, link to the license,
and indicate your changes.

