# Nexus Scholar

Nexus Scholar is a public research-software workspace for systematic literature review tooling, scholarly search, citation-network analysis, screening workflows, and reproducible research artifacts.

The work here is mostly Laravel/PHP backend engineering: reusable packages, command-line workflows, graph tooling, reference-management infrastructure, and hosted-product foundations for researchers who need review workflows that can be inspected later.

## Start Here

If you are evaluating the work, start with these repositories:

- [`core`](https://github.com/nexus-scholar/core) - reusable PHP/Laravel package for systematic-review workflows: search, deduplication, screening, full-text artifacts, citation graphs, exports, and audit trails.
- [`nexus-cli`](https://github.com/nexus-scholar/nexus-cli) - Laravel Artisan workspace for running review workflows from the command line and preserving local evidence.
- [`nexus-web`](https://github.com/nexus-scholar/nexus-web) - Laravel/Inertia web application surface for hosted Nexus Scholar workflows.
- [`graph-core`](https://github.com/nexus-scholar/graph-core) - reusable PHP graph data structures used by the citation-network work.
- [`graph-algorithms`](https://github.com/nexus-scholar/graph-algorithms) - PHP graph algorithms package and successor to earlier graph experiments.
- [`refmanager`](https://github.com/nexus-scholar/refmanager) - bibliographic import/export support across RIS, BibTeX, CSL-JSON, and EndNote XML.

## What This Workspace Is Trying To Prove

Systematic reviews need more than search results. A serious review workflow should preserve where records came from, how duplicates were handled, which screening criteria were used, how human decisions were made, what graph or export artifacts were generated, and what changed over time.

The public Nexus Scholar repositories focus on that infrastructure:

- provider boundaries that keep search sources traceable;
- deduplication records that explain why papers were merged;
- screening workflows tied to criteria, reasons, and reviewer decisions;
- citation graphs treated as inspectable artifacts, not only visualizations;
- reference-management and export paths that can be audited;
- CLI commands and generated files that make demos reproducible.

## Research Direction

The broader research lane includes plant-disease AI, computer vision, and academic workflow automation. Public material is kept deliberately conservative: enough to show direction, tooling, and evidence discipline, without exposing unpublished methods, supervisor-sensitive thesis details, or claims that still need formal validation.

This workspace also contains older prototypes and research-adjacent repositories. When a repository is experimental, superseded, or archived, treat it as historical context rather than the current product surface.

## Public Boundary

The reusable core, CLI workflows, graph packages, reference tooling, documentation, and safe evidence artifacts are public so developers and researchers can inspect the system.

Hosted-product details, private roadmap decisions, credentials, client data, unpublished thesis methods, and sensitive experiment planning stay out of public repositories.

That boundary is intentional: public work should clarify the system without turning the research or product process into an unfiltered archive.

## Related Links

- Public site and writing: [mouadh.org](https://mouadh.org)
- Personal GitHub account: [mbsoft31](https://github.com/mbsoft31)
- Nexus Scholar organization: [github.com/nexus-scholar](https://github.com/nexus-scholar)
