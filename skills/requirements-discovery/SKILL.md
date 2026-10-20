---
name: requirements-discovery
description: Clarify a plan through a focused requirements interview, synthesize known context into a specification, or draft questions for stakeholders. Use for unresolved product decisions, scope, acceptance criteria, and handoff artifacts; do not interview again when the user asks only for synthesis.
---

# Requirements discovery

Turn the available context into a useful decision or artifact without inventing
agreement. Overlapping source interview entry points are consolidated here.

## Select the requested mode

- **Interview/stress test:** map the goal, constraints, users, alternatives, and
  consequential decisions. Ask a small coherent batch whose prerequisites are
  already known. Offer recommendations with tradeoffs where useful, without
  wording questions to steer agreement. Let answers shape subsequent questions.
  Stop when the requested decision is sufficiently specified, or the user's
  time/scope budget is reached; do not interrogate every possible branch.
- **Specification:** synthesize existing conversation, code evidence, glossary,
  and accepted decisions. Do not restart an interview when synthesis was requested.
  Separate unresolved choices from settled requirements and carry them visibly
  into the draft. The [source spec structure](references/r/023.md)
  is an optional template; its tracker/publication instructions do not apply.
- **Questionnaire:** identify the recipient's role and knowledge, the facts or
  decisions needed, and why the user cannot answer them alone. Draft direct,
  single-idea questions in priority order; group by theme when helpful. Include
  answer stubs and brief context where needed. Producing the draft does not send it.

## Ground the requirements

Resolve available factual questions from supplied evidence or authorized tools
rather than asking the user to perform avoidable research. Distinguish observed
facts, assumptions, preferences, constraints, and user-owned decisions. Ask only
for missing information that materially changes the outcome; progress independent
work while an answer is pending. Never interpret silence as approval.

Inspect real examples, failure cases, access boundaries, quality requirements,
and existing integration contracts. Keep the user's chosen product and constraints;
challenge a proposed solution through evidence without silently changing scope.
Do not invent stakeholder priorities, measurements, owners, dates, or commitments.

## Produce an actionable artifact

For a spec, include the problem, intended behavior, relevant user stories or
scenarios, acceptance criteria, implementation decisions, testing approach,
exclusions, and unresolved questions. Scale detail to the task. Prefer existing
public seams; flag materially new contracts for a real decision when needed.
Use stable concepts and useful examples rather than exhaustive speculative detail.

Deliver in the requested format and destination, or return the draft in chat.
Do not create a local file, issue, label, or tracker status merely because an
upstream example prescribed it. Saving or publishing follows current authorization;
there is no mandatory tracker setup or sibling plugin dependency.

## Optional references

The [reference index](references/README.md) preserves the interview, sharpening,
specification, and questionnaire sources for detail and provenance. Source tool
names, global local-only rules, automatic publication, and repeated-confirmation
requirements are historical examples. This hub and the actual task determine
scope; artifact completion alone is not permission to implement or send it.
