# SHOE: Footwear Sector Ontology

License: Apache 2.0 Based on ISO 19952 Status: Early Development

## Overview
SHOE is an open semantic data dictionary for the footwear industry, designed to support
the implementation of the EU Digital Product Passport (DPP) under the Ecodesign
for Sustainable Products Regulation (ESPR).

Each concept in this dictionary is assigned a persistent URI, enabling machine-readable
references via the dictionaryReference attribute as specified in NWIP N 458
(CEN/CLC/JTC 24).

## Reference Standards
- UNE-EN ISO 19952:2005 — Footwear. Vocabulary
- CEN/CLC/JTC 24 — Semantic interoperability for the Digital Product Passport
- NWIP N 458 — Dictionary referencing: Concepts and principles

## Repository Structure
SHOE-core.ttl       Core classes: Footwear, Component, Material, Actor
SHOE-components.ttl  Upper, Outsole, Insole, Lining, Heel...
SHOE-materials.ttl   Leather, Textile, Synthetic, Polymer...
SHOE-sustainability.ttl Recycled content, carbon footprint, circularity

## Namespace
https://w3id.org/footwear#

## Alignment
This ontology is designed to align with Schema.org, GS1 Web Vocabulary,
ECLASS, and IEC CDD to ensure cross-sector interoperability.

## Status & Roadmap
- [x] Repository setup
- [x] Core namespace and SHOE-core.ttl
- [ ] Full ISO 19952 term coverage
- [ ] Alignment with Schema.org Product
- [ ] SPARQL endpoint

## License
This project is licensed under the **Apache License, Version 2.0**. It is intended to be used as an open industry standard to promote global digital transformation.

## Contact
Initiated by aamat@inescop.es, researcher at INESCOP.
Maintained by INESCOP — Footwear Technology Centre, Spain.
Contributions from manufacturers, standardization bodies and
technology providers are welcome.
