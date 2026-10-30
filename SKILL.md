---
name: api-doc-standard
description: Create or review concise Chinese API documentation organized by business feature page, with clear request and response contracts. Use when drafting, restructuring, or reviewing API docs.
---

# API Documentation Standard

Produce documentation that lets a caller understand which capability to use, how to call it, and how to interpret the result. Organize each page around a business feature.

## Page scope

- Give each page one cohesive feature or caller workflow. Include its related routes on that page, with a separate request and response section for each route.
- Give independent capabilities separate pages when that makes the documentation easier to navigate.
- Preserve confirmed project terminology and conventions. Record each decision at the scope where it applies; establish a project-wide convention when it is confirmed to apply across features.

## Contract quality

- Describe the confirmed caller-visible contract. Check the relevant requirements/design against the project schema, route, or implementation where available. Record discrepancies between the confirmed contract and observed behavior so they can be resolved explicitly.
- Include the details a caller needs to construct a valid request and understand the response: path and method, request format, authorization when relevant, fields, types, required conditions, and meaningful constraints.
- Explain enum values, defaults, missing/null/empty behavior, side effects, and error handling only where they affect how callers use the feature.
- Keep examples consistent with the field descriptions. Use a complete ordinary request and success response; add failure or boundary examples when they clarify an important contract.
- For high-risk operations, state a minimal reproducible verification and expected result.

Use the [feature page template](references/feature-page-template.md) as a starting point. Select and adapt sections to the feature so each section helps callers construct requests or interpret responses.
