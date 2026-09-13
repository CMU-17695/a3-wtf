# 17-695 A3: wtf at a fixed commit

This repository is a copy of [wtf](https://github.com/wtfutil/wtf) for assignment A3 of CMU 17-695 (Design Patterns, Fall 2026).
It is pinned at upstream commit [`bb838c1`](https://github.com/wtfutil/wtf/commit/bb838c1ccb0f0f3223690df44afdec663d622881).
Do not update it to a newer upstream version.
wtf is copyright its authors and licensed under the Mozilla Public License 2.0; see [LICENSE.md](LICENSE.md).

The assignment handout on the course website is the source of truth for what to do and what to submit.
This file only records what this copy is.

## Verifying the copy

`git archive bb838c1 | shasum -a 256` on the upstream repository and on this one both give:

```text
c441c6fb30560e601a146667cbbf772db71483287555dd9aa207e041265011ef
```

## Building

You do not need to build or run wtf for the assignment.
The assignment is a design review of a proposal to change how the application constructs its modules.
Start at `app/widget_maker.go`.
