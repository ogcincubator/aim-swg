# PROJECT PLAN for AIM specification

## Context

OGC is seeking to improve the process and tooling for creating specifications to create higher quality, machine readable (AI ready) specifications with less effort and greater review efficiency and effectiveness.

AIM as a complex modular standard with a strong semantic base, explicitly re-using other OGC and industry standards makes it a perfect test case.

The reusable "Cross domain model" collection of base ontologies has already been factored out into building blocks.

This "project plan" lays out a proposed methodology for consideration by the AIM SWG.

## Outline

| # | Step | Who |
| :------------ | :----------- | :------------ |
| 1 | Commit to the [Building Blocks approach](#approach) | AIM SWG |
| 3 | Update TTL content and documentation text in repo to match current state of AIM implementations | AIM SWG |
| 4 | Choose target namespaces | AIM SWG + OAB |
| 5 | Draft an [AI prompt](skills/refactor.md) to define desired outcome | SWG + OGC advice |
| 6 | Use [LLM skills](https://github.com/ogcincubator/ogc-llm-skills) to refactor content into Building Blocks | SWG + OGC advice |
| 7 | Set up Building Blocks based Specification generation tooling  | OGC |
| 8 | Complete Specification text content | SWG |
| 9 | Use [LLM skills](https://github.com/ogcincubator/ogc-llm-skills) to define sub-domain specific profiles  | SWG + OGC advice |
| 10 | Complete examples for core + profiles  | SWG |
| 11 | Create transforms to map AIM to other standards  | SWG + OGC advice |
| 12 | Create JSON schema + JSON-LD payload specifications for OGC API implementation  | SWG + OGC advice |

## Approach

The Building Blocks approach is being formalised by OGC as a framework for creating standards.

Documentation is here: https://ogcincubator.github.io/bblocks-docs/

Please review, and identify where gaps exist.

The main known gap is the OGC's own governance arrangements for Building Blocks and infrastructure - however this is not a barrier to implementing the design approach.

A key factor to remember is the power of a test-driven approach with examples.
