# Tools

The **tools** directory contains utilities that help validate
documentation written using OpenSTE rules.

These tools help maintain consistency and detect violations of writing
guidelines or vocabulary rules.

------------------------------------------------------------------------

## Purpose

Validation tools help:

-   detect complex sentences
-   identify restricted vocabulary
-   enforce writing rules
-   improve documentation quality

------------------------------------------------------------------------

## Possible Tool Types

Examples of tools that may exist in this directory:

-   documentation linters
-   vocabulary validators
-   grammar rule checkers
-   documentation format validators

------------------------------------------------------------------------

## Example Use Case

A linter could detect sentences that exceed a recommended length:

    Sentence exceeds recommended length (25 words)

Another tool may detect non-approved terminology:

    Word "initiate" is not recommended. Use "start".

------------------------------------------------------------------------

## Example Structure

Typical tool files may include:

    linter/
    vocabulary_checker/
    rule_validator/

------------------------------------------------------------------------

## Contributing

You can contribute by:

-   developing validation tools
-   improving rule detection
-   adding integrations with documentation platforms
-   improving performance and accuracy
