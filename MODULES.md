# LIFT Modules

LIFT is developed one bounded module at a time.

## Golden-module loop

```text
Frame
  -> audit private source
  -> classify every material claim
  -> rewrite from first principles
  -> test with synthetic examples
  -> review with .roles
  -> record learning
  -> revise or retire claims
```

A module is **golden** when:

1. its audience, problem, and behavioral outcome are explicit;
2. no private workplace material or identifying provenance remains;
3. every material claim has an evidence label;
4. scoring rules are reproducible from observable evidence;
5. uncertainty, counterevidence, equity, and misuse risks are visible;
6. examples are public, synthetic, or transformed and clearly labeled;
7. no critical or major role finding remains;
8. dissent and defers have destinations;
9. at least one independent practitioner can use it without author coaching;
10. the module records what changed during its learning loop.

Golden does not mean permanently correct. New evidence can reopen a module.

## Roadmap

| Module | Working title | Central question | Status |
|---:|---|---|---|
| 00 | M/S/E foundation | What are the three advocacy layers, and what does a score mean? | role-reviewed draft |
| 01 | Honest assessment | How do you score observable evidence without scoring optimism? | role-reviewed draft |
| 02 | Advocacy in action | Which manager behaviors create credit, context, and opportunity? | role-reviewed draft |
| 03 | The management cascade | How do manager pathways amplify or constrain a team? | role-reviewed draft |
| 04 | New-manager transition | What changes when personal output stops being the primary evidence? | role-reviewed draft |
| 05 | Trust and team health | How should upward support and downward experience be reconciled? | role-reviewed draft |
| 06 | Momentum and resistance | Is the evidence path improving, stalled, resetting, or structurally blocked? | role-reviewed draft |
| 07 | Choosing an environment | What can people responsibly inspect before joining a manager or organization? | role-reviewed draft |
| 08 | Transitions | How do manager changes, transfers, and organizational resets affect evidence? | role-reviewed draft |
| 09 | Equity and ethical use | Where do access, bias, power, and misuse invalidate a simple score? | role-reviewed draft |
| 10 | Operating toolkit | What lightweight records support recurring reflection and conversation? | role-reviewed draft |

## Companion layers

Modules remain authoritative for LIFT semantics, scoring, evidence, and ethical
boundaries. Companion layers route or compose those rules without adding a
module, dimension, score, or required workflow.

| Layer | Purpose | Status |
|---|---|---|
| [Reader guides](guides/README.md) | route common questions to the smallest relevant module and record | role-reviewed draft |
| [Stories and metaphors](STORIES_AND_METAPHORS.md) | provide optional bounded illustrations with direct-rule fallbacks | role-reviewed draft |
| [Cross-cutting practices](practices/README.md) | compose modules around evidence burden, collective contribution, correction, and an integrated case | role-reviewed draft |

## Required module artifacts

Each module directory should contain:

```text
README.md
CLAIMS.md
LEARNING.md
examples/
```

Role reviews live under `context/role-reviews/`.
