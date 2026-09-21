# Open Steward

**Keep software open, understandable, and alive.**

Software should remain ours to run, understand, repair, and pass on.

Open Steward is an independent software stewardship project. It creates small, useful tools, rescues important open-source software that has lost active maintenance, and sustains long-lived infrastructure with conservative engineering.

## Create · Rescue · Sustain

### Create

Build software that stays inspectable, portable, and useful without requiring a permanent dependency on a vendor or hosted service.

### Rescue

Find valuable open-source software that has lost active maintenance, understand its history and compatibility constraints, restore reproducible testing, and help it return to active stewardship.

### Sustain

Maintain software people already depend on. Prefer compatibility, evidence, tests, and small defensible changes over unnecessary rewrites.

## Current work

| Project | Role | What is happening |
| --- | --- | --- |
| [jq-lite](https://github.com/kawamurashingo) | Create | Building a small JSON-processing tool in Perl. |
| [CPAN Rescue](https://github.com/kawamurashingo/cpan-rescue) | Rescue | Investigating and adopting CPAN distributions that need active stewardship. |
| [DBD::ODBC](https://github.com/kawamurashingo/DBD-ODBC) | Rescue / Sustain | Adoption requested. Modern Linux CI restored and a DBI compatibility regression has a tested patch ready. |
| [Devel::CallChecker](https://github.com/kawamurashingo/Devel-CallChecker) | Sustain | Rescued and released as 0.010 in 2026. |

## Principles

- **Ownable.** Software should remain runnable without asking a permanent gatekeeper for permission.
- **Understandable.** Source, behavior, dependencies, and maintenance decisions should be inspectable.
- **Repairable.** Old software is not disposable merely because its original maintainer moved on.
- **Compatible.** Stewardship means respecting the users and systems that already depend on the software.
- **Transferable.** Good stewardship leaves enough tests, documentation, and history for the next person to continue.

## Why Open Steward?

The software world is increasingly built around services we do not control and systems we cannot fully inspect. AI makes software creation faster, but it does not make long-term ownership, maintenance, or independence less important.

Open Steward starts from a different premise:

> Software should remain ours to run, understand, repair, and pass on.

This is not a campaign against AI. AI can be a powerful tool for software archaeology, testing, maintenance, and creation. The goal is to use modern tools while preserving human agency and an open software commons.

## Status

Open Steward is beginning with Perl and CPAN because that ecosystem contains decades of useful, battle-tested software—and because long-lived software deserves active stewardship.

The work is public. Results matter more than slogans.
