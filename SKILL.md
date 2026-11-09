---
name: api-doc-standard
description: Create, organize, or review concise Chinese API documentation using project contract sources, feature pages, and publication rules.
---

# API Documentation Standard

Help callers choose a capability, construct a valid request, and interpret its results. Provide API document completeness checks and a default feature-page structure.

## Authority and carriers

Use the project's authoritative contract sources, document carriers, template, and publication workflow. User instructions take precedence over general defaults. Keep maintained sources and complete published pages distinct.

Express confirmed caller-visible behavior. Confirmed requirements and design define the target contract; same-version declarations and actual entry points establish current behavior. For a new operation, document the confirmed target and state its implementation and validation status. Resolve material behavioral choices in the authoritative contract before finalizing the page.

Use project-approved, redacted data in sources, examples, and published pages. Represent authentication credentials with placeholders, and handle publishing credentials in the authorized tool context.

Apply [contract checks](references/contract-checklist.md) to each authoring, organizing, reviewing, or publishing task according to its maintained source and final output.

## Task routing

- **Create or organize:** Follow the project template. For page structure delegated to this skill, organize one cohesive feature or caller workflow per page, with separate request and response sections for related routes.
- **Review:** Report discrepancies with their source, confirmation status, and caller impact.
- **Publish or synchronize:** Read [publication checks](references/publication-checklist.md) and use the repository's configured workflow and existing authorization.

The [feature page template](references/feature-page-template.md) is the complete-page default. Local supplements follow the repository's carrier rules. Read supporting references according to the requested operation and deliver the specified document sources and output.
