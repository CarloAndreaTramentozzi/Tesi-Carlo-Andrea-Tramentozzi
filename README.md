# Bachelor Thesis – Object-Oriented Programming in Tree-Based Financial Models

This repository contains my Bachelor thesis for the BSc in Computer Science (L-31).

The thesis focuses on the design and implementation of tree-based financial models
using object-oriented programming and dynamic programming techniques.

## Thesis information
- Candidate: Carlo Andrea Tramentozzi
- Degree: BSc in Computer Science (L-31)
- University: Università degli studi di Verona
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

## Contribution to finmath-lib

Part of the work developed during this thesis and the associated internship
was integrated into the open-source quantitative finance library
[finmath-lib](https://github.com/finmath/finmath-lib).

The contribution focuses on the implementation of tree-based financial
models and products, following the object-oriented architecture
discussed in the thesis.

The corresponding code is now part of the tree model module of the library:

https://github.com/finmath/finmath-lib/tree/main/src/main/java/net/finmath/tree

More details on the specific classes related to this work are provided
in `contributions/finmath-lib.md`.


