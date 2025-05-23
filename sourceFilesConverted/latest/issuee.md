## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/issuee'>here</a>

## Explanation
An [ACDC](authentic-chained-data-container) is optionally issued to the Issuee. When present, the Issuee identifier ([AID](autonomic-identifier)) appears at the top level of the attribute section or in the attribute list at the top level of the attribute aggregate section of the ACDC.

Each ACDC MUST have an [Issuer](issuer) and MAY have an [Issuee](issuee). The set of [ACDC](ACDC)s so disclosed in a presentation exchange MUST be chained. This set of chained ACDCs define a [directed acyclic graph](directed-acyclic-graph) that MUST have at least one vertex and MAY have zero or more edges pointing to other vertices.