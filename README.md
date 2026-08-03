# Programming Paradigms Lab

A curated collection of programming exercises that compares how the same ideas are expressed across C, Java, Ruby, Racket, and Prolog.

> [!NOTE]
> This repository is a work in progress. The initial project structure is in place, but the first executable comparison has not been added yet.

## Purpose

The lab turns selected coursework into small, independently runnable examples with consistent inputs, documented behavior, and automated tests. Rather than presenting unrelated assignments, it focuses on the tradeoffs each language makes around:

- iteration and recursion;
- mutation and memory management;
- static and dynamic typing;
- functional list processing;
- pattern matching and declarative queries;
- short-circuit evaluation; and
- testing and error handling.

## Planned comparisons

| Area | Languages | Focus |
| --- | --- | --- |
| Matrix operations | C | Allocation, validation, iteration, and manual memory management |
| Zero-row detection | Java and Ruby | Explicit loops compared with collection-oriented operations |
| Evaluation order | Java | Short-circuit behavior through focused examples |
| List operations | Racket | Recursion, nested lists, sets, and predicates |
| List predicates | Prolog | Recursion, unification, and declarative queries |

## Planned structure

```text
programming-paradigms-lab/
├── c/
│   └── matrix/
├── java/
│   ├── evaluation/
│   └── zero-row/
├── ruby/
│   └── zero-row/
├── racket/
│   └── list-operations/
├── prolog/
│   └── list-predicates/
├── docs/
│   └── comparison.md
└── tests/
```

## Roadmap

1. Rebuild the C matrix example with safe allocation and support for rectangular matrices.
2. Add tests for valid, invalid, empty, negative, and incompatible inputs.
3. Standardize the Java and Ruby zero-row examples around one input/output contract.
4. Add tested Racket and Prolog list operations with defined empty-list behavior.
5. Document the cross-language tradeoffs and provide one command for running every example.
6. Add continuous integration for all five language toolchains.

## Project standards

Each example should be:

- authored or substantially rebuilt for this repository;
- small enough to study independently;
- runnable from documented commands;
- tested for normal and edge-case behavior; and
- connected to a meaningful cross-language comparison.

Third-party exercises, instructor-provided code, course PDFs, archives, and unrelated media are intentionally excluded.

## Current status

Repository setup and documentation are underway. The first implementation milestone is the corrected and tested C matrix example.
