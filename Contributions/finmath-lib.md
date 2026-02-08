# Contribution to finmath-lib

During the development of this thesis, part of the proposed design and
implementation was contributed to the open-source quantitative finance
library **finmath-lib**.

## Pull Request
- Repository: https://github.com/finmath/finmath-lib
- Pull request: https://github.com/finmath/finmath-lib/pull/102

## Description
The contribution introduces new tree-based financial products and model
extensions, designed following object-oriented principles.

The code includes:
- New product abstractions
- Integration with existing tree models
- Java classes authored by me (annotated with `@author`)

The pull request demonstrate production-level coding standards and domain-specific design
choices.

## Relation to the thesis
The contribution directly reflects the concepts discussed in Chapters Non-Path-Dependet option 
of the thesis, in particular:
- Object-oriented design of financial products
- Differences between Path-Dependent and Non-Path-dependent options
- Dynamic programming and backward induction
- Difference of space and complexity in this type of implementation
- Efficient recombining tree structures through matrix and not object with pointers
