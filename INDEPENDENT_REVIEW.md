# Independent Review

LIFT's modules are synthetic role-reviewed drafts. They have not yet passed the
independent-human gate in the [golden-module criteria](MODULES.md).

This protocol lets a person attempt one bounded task without author coaching
and report what was usable, confusing, inaccessible, or unsafe.

## What independent means here

An independent reviewer:

- is a real person, not a generated role or AI panel;
- did not author the module being reviewed;
- attempts the task before asking an author for interpretation;
- can stop without explanation;
- does not need to disclose an employer, role, identity, or personal record;
- reports limitations and conflicts that materially affect the review.

Independence does not imply subject-matter expertise, representativeness, legal
authority, or endorsement.

## AI assistance

An AI-generated panel, review, report, or completed form is not
independent-human evidence.

A reviewer may use an accessible or translation aid on public LIFT text when
they disclose the aid and still make the attempted judgments themselves.

For the independent gate:

- author explanation or AI interpretation of the module before the attempt
  counts as coaching, except disclosed mechanical translation or accessibility
  transformation;
- generated findings do not count as the reviewer's findings;
- identifiable or confidential context must not be submitted to a public AI
  service;
- assistive use and its limitations belong in the report.

## Safety before participation

Do not submit:

- a completed LIFT profile or score;
- employer, team, manager, colleague, customer, or project names;
- private workplace conversations or documents;
- protected, health, leave, immigration, compensation, or investigation data;
- confidential links, screenshots, recordings, or logs;
- evidence that could expose another person;
- a report that participation was required.

Use a [synthetic scenario](review/SCENARIOS.md) when possible.

If you use your own context privately, report only how the module behaved. Keep
the underlying facts and completed record private.

## Smallest useful review

Choose:

1. one module;
2. one task from that module;
3. one synthetic scenario or public example;
4. one report.

Do not review all modules in one pass.

Recommended first review:

```text
Module: 00, M/S/E Foundation
Task: produce one evidence-linked dimension judgment
Scenario: A, current advocacy
Stop after: one dimension, one next question, and the ethical-use check
```

## Review loop

```text
Select
  -> Attempt
  -> Explain
  -> Stress
  -> Sanitize
  -> Report
  -> Disposition
```

### 1. Select

Record:

- module and commit or version;
- attempted task;
- scenario or public example;
- relevant reviewer perspective;
- material conflict or prior author coaching;
- assistive or AI use.

Perspective is context, not a reviewer score.

### 2. Attempt

Use only the public instructions.

Record:

- where you started;
- whether you completed, partially completed, or stopped;
- fields or terms you skipped;
- the first point that required guessing;
- the smallest change that would have helped.

Do not send the completed LIFT record.

### 3. Explain

In your own words, explain:

- what the module helps inspect;
- what evidence it requires;
- what conclusion it does not support;
- when use should stop or route elsewhere.

This tests the instruction boundary, not memory or agreement.

### 4. Stress

Check at least these failure paths:

- missing evidence becomes a midpoint score;
- warmth, visibility, or title becomes advocacy;
- a structural barrier becomes personal blame;
- a private reflection becomes a shared personnel record;
- a score becomes an employment decision;
- a next action becomes visibility theater or unsafe confrontation;
- inaccessible format or language prevents use.

For Modules 09-10 also check:

- compelled disclosure;
- centralized individual scores;
- secondary use;
- retention without purpose;
- public-AI submission;
- false security claims about Markdown.

### 5. Sanitize

Before reporting:

- remove names and organizations;
- replace private facts with a synthetic description;
- remove completed scores and profiles;
- remove copied private messages;
- check combinations of facts for re-identification;
- state when sanitization weakens the finding.

Do not submit material merely because it is important. Some evidence should
remain private.

### 6. Report

Use [REVIEW_REPORT.md](review/REVIEW_REPORT.md) or the GitHub independent-review
issue form.

A useful finding includes:

```text
Severity:
Artifact and section:
Attempted task:
Observed problem:
Consequence:
Evidence from the attempt:
Smallest closure condition:
```

Suggested severity:

| Severity | Meaning |
|---|---|
| critical | permits prohibited use, serious privacy exposure, retaliation, discrimination, or unsafe action |
| major | blocks independent use or materially changes interpretation |
| minor | creates avoidable friction without changing the safety boundary |

### 7. Disposition

Maintainers record:

- `accept`: revise the artifact;
- `clarify`: request only public-safe information;
- `defer`: name the evidence or owner needed;
- `decline`: explain why the finding does not change LIFT;
- `remove`: delete or restrict unsafe submitted content.

The reviewer does not need to agree with the disposition. Dissent remains
visible when it can be published safely.

## Unsafe submission handling

If a report includes private, identifying, protected, confidential, or
otherwise unsafe content, maintainers should:

1. avoid quoting or copying the unsafe content;
2. restrict further discussion by locking the issue when available;
3. redact editable content immediately;
4. delete the issue or attachment when redaction is insufficient and the
   platform permits deletion;
5. ask the contributor to resubmit only a sanitized finding;
6. retain at most a non-identifying note that content was removed;
7. use the platform's security or privacy escalation path when exposure
   remains.

Do not preserve unsafe content merely to maintain a complete review history.

## Evidence states

| State | Meaning |
|---|---|
| `unreviewed` | no admissible independent-human attempt is recorded |
| `attempted` | an independent person attempted a bounded task |
| `usable with findings` | the task was completed without coaching and findings remain |
| `independently usable` | the task was completed without coaching and no critical or major usability or safety finding remains |
| `golden` | all repository golden criteria are met, not only independent usability |

These states apply to the reviewed module and task, not to LIFT as a whole.

One reviewer cannot establish:

- population-wide usability;
- accessibility across needs and formats;
- fairness across workplaces;
- causal career outcomes;
- legal or policy compliance;
- psychometric validity;
- safe employment-decision use;
- endorsement.

## Golden-gate evidence

A review can satisfy the independent-practitioner criterion for a bounded
module task only when:

1. the reviewer meets the independence boundary;
2. the attempt used a named public commit or version;
3. the task was completed without author coaching;
4. the reviewer can explain the module's evidence and misuse boundaries;
5. no completed personal record was submitted;
6. no critical or major actionable finding remains;
7. the sanitized report and maintainer disposition are public;
8. dissent and limitations remain visible.

Other golden criteria still apply.

## Accessibility

Markdown is not a participation requirement.

Reviewers may use an accessible equivalent format. Report:

- format used;
- navigation or reading barriers;
- cognitive load;
- language or terminology barriers;
- whether tables, code blocks, or scoring notation were usable;
- whether another format is required.

Do not infer that no accessibility finding means the artifact is accessible.

## Coercion and compensation

Do not call a review independent when:

- a manager requires a report;
- refusal could affect employment;
- the reviewer is asked to reveal a personal score;
- the author directs the attempt in real time;
- compensation depends on a positive finding.

Compensation for time does not automatically invalidate review. Record the
relationship and who defined the task.

## Public record

Admitted reports are indexed under
[context/independent-reviews/](context/independent-reviews/README.md).

The index must show:

- reviewed module and task;
- commit or version;
- evidence state;
- unresolved findings;
- limitations;
- maintainer disposition.

It must not become a reviewer leaderboard or testimonial page.
