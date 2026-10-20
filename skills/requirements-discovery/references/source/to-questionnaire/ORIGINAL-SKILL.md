> Archived source reference, repackaged by Leotus-Richard on 2026-10-20. This is not an active skill or execution policy. Use the domain hub for current task scope and available capabilities; host commands, integrations, local-only rules, identity rules, and publishing steps below are historical examples. Modifications: discovery filename and local links normalized where needed, machine paths replaced where present; source substance retained.

---
name: to-questionnaire
description: "Turn a decision blocked on knowledge in someone else's head into a local discovery questionnaire draft; never send or publish it."
metadata:
  version: "1.0.0"
  profile: "local-task-toolkit"
  invocation: "task-specific"
  integration-status: "portable-instructions-host-untested"
---

# To Questionnaire

## Scope

Read `references/local-execution-contract.md` at task start. This skill is task-specific and local-only. Do not activate remote integrations, persistent modes, hooks or unrelated implementation. The result is a local Markdown draft; never send it, publish it or claim it was delivered.

## Workflow

1. Interview the user only about the send, which they can always answer: the recipient's role, expertise and relationship, in one exchange. Use grilling when the send needs real interrogation.
2. In one exchange, capture the specific decisions or facts the user cannot resolve alone and needs back.
3. Draft questions aimed at the gap between what the recipient knows and what the user needs, ordered most-important-first and grouped by `##` theme beyond a handful.
4. Write the draft to `to-questionnaire-<slug>.md` in the current directory and report the path. Every need named in step 2 is covered by a question; each question is one idea with an answer stub and an optional one-line rationale only where it could be misread.

## Default output

A local `to-questionnaire-<slug>.md` discovery questionnaire draft with purpose, context, how-to-answer, themed questions and a closing catch-all.

## Failure boundary

Report the missing input or capability; do not invent recipient knowledge, answer on their behalf or broaden the task.

## Conditional skill dependencies

- `grilling`: read the installed sibling skill when the send must be interrogated before drafting.

Use the host's actual skill loader, or read the current domain hub (historical dependency syntax removed) from this installed directory. Do not guess host tool names. Install the dependency closure shown in manifest.json if these siblings are absent.

## Upstream resources

The full original skill and its questionnaire template are preserved under `references/upstream/`. Read `references/upstream/ORIGINAL-SKILL.md` when its detailed template is relevant. Its slash-command invocation is a source-specific example, not permission to execute remote delivery. Follow this hub and the local execution contract when those instructions conflict.

## Provenance

Adapted from [mattpocock:to-questionnaire](https://github.com/mattpocock/skills/blob/5beb35b040e3de97e54fa9e386d7e42d15c295c2/skills/productivity/to-questionnaire/SKILL.md). The original MIT notice is bundled. This is a local-only adaptation, not an endorsement or a claim of native host support.
