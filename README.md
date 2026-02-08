# Bachelor Thesis – Object-Oriented Programming in Tree-Based Financial Models

This repository contains my Bachelor thesis for the BSc in Computer Science (L-31).

The thesis focuses on the design and implementation of tree-based financial models
using object-oriented programming and dynamic programming techniques.

## Thesis information
- Candidate: Carlo Andrea Tramentozzi
- Degree: BSc in Computer Science (L-31)
- University: [Università degli studi di Verona]
- Supervisors: Sara Migliorni, Alessandro Gnoatto, Andrea Mazzon
- Language of the thesis: Italian

## Abstract
The thesis studies recombining tree models (binomial and trinomial) for pricing
financial derivatives. Particular attention is given to US and EU path-dependet option, software design,
object-oriented abstractions, and dynamic programming techniques to efficiently
handle path-dependent and non-path-dependent products.

An emphasis is placed on memory-efficient data structures and extensible model
hierarchies suitable for real-world quantitative finance libraries.

## Repository structure
- `Thesis/`: PDF of the full thesis (Italian)
- `Abstract/`: English abstract
- `Contributions/`: Description of external code contributions

## External code contribution
Part of the work developed for this thesis resulted in a concrete contribution
to the open-source quantitative finance library **finmath-lib**.

A pull request adding new tree-based financial products and models was submitted
and reviewed by the library maintainers:

👉 https://github.com/finmath/finmath-lib/pull/102

This contribution includes:
- Object-oriented design of tree products
- Integration with existing finmath-lib abstractions
- Production-quality Java code reviewed by domain experts

## Keywords
Quantitative Finance, Tree Models, Object-Oriented Design, Dynamic Programming,
Java, Financial Engineering

