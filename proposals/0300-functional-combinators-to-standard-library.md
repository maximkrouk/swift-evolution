# Functional combinators to Standard library (Draft)

* Proposal: [SE-0300](0300-functional-combinators-to-standard-library.md)
* Authors: [maximkrouk](https://github.com/maximkrouk)
* Review Manager: TBD
* Status: **Awaiting implementation**

## Introduction

Swift is a multy-paradigm language and functional programming becomes more and more popular, so adding functional combinators to the standard library makes sense.

- `Lens`
- `Either`

Swift-evolution thread: [Discussion thread topic for that proposal](https://forums.swift.org/)

## Motivation

- Swift already has `Optional` and `Result` types, which have a similar vibes to generic containers like `Lens` and `Either`
- The second one will solve [the problem of Enum composition](https://forums.swift.org/t/pitch-enum-composition/43598)

## Proposed solution

> Here should be a PR link

## Detailed design

> TBD

## Source compatibility

Changes are additive and have no effect on source compatibility

## Effect on ABI stability

Changes have no effect on ABI stability

## Effect on API resilience

Changes are additive.

## Alternatives considered

[pointfreeco/swift-prelude](https://github.com/pointfreeco/swift-prelude#optics) framework already solves the problem, but I'd like to see this feature in the std lib, because it is generic and may be shared across different code bases, especially when functional programming becomes more and more popular.
