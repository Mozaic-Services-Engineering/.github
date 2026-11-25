---
name: Bug
about: A defect, filed in the repository that owns the fix.
title: "[Bug][Capability] "
type: Bug
---

<!--
Format: §10.7 Bug in the GitHub Issue and Project Operating Model
https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#107-bug
Where it lives: §5.1 (the repository that owns the fix, which may differ from where the symptom appears)
https://github.com/Mozaic-Services-Engineering/mozaic-platform-docs/blob/main/docs/engineering/operating-model/consultancy-on-tap/github-issue-and-project-operating-model.md#51-location-rules

Title: replace "Capability" with the Owning capability, then add the outcome phrase.
Set capability, priority (the severity decision), readiness, effort and security profile
as Issue Fields, not in this body. Do not restate a severity level here.
Link the parent Feature (when truthful) and dependencies natively.
Keep the headings below as written and in this order. Suspected boundary, Proposed fix
and Dependencies and hand-off are optional: delete them if unused rather than writing "N/A".
-->

## Impact

<!-- Who or what is affected, how badly, and any workaround. -->

## Environment

<!-- Environment, application, version or commit, and the surface where the symptom appears. -->

## Observed and expected behaviour

**Observed:**

**Expected:**

## Reproduction evidence

<!-- Numbered steps, plus logs, request IDs or screenshots. If not yet reproducible, say so and give the evidence that exists. -->

## Suspected boundary

<!-- Optional: the component or contract suspected, with the evidence. Present it as suspected until proven. -->

## Proposed fix

<!-- Optional: a known or suggested fix direction. Non-authoritative: the implementing Task's Implementation boundary is the authority. -->

## Acceptance criteria

<!-- Checkboxes (- [ ]) for the corrected behaviour, including what must not regress. -->

## Validation

<!-- The regression test that fails before the fix and passes after, plus any UAT check. Where such a test is not practical, give the reason and the before-and-after evidence that replaces it. -->

## Dependencies and hand-off

<!-- Optional: prerequisites and the safe hand-off state. -->

## Authority

Creation does not authorise implementation.
