# ADR-0001: Use GitHub as the Project Repository

## Status
Accepted

## Date
2026-07-17

## Context

Codex Nexus is designed as a modular, privacy-first knowledge platform.
A reliable system for storing source code, documentation, project history, and collaboration is required.

The project needs:
- Version control
- Transparent development history
- Backup of project assets
- Possibility of future collaboration
- Integration with modern development workflows

## Decision

GitHub has been selected as the primary repository platform for Codex Nexus.

The repository will contain:
- Source code
- Documentation
- Architecture decisions
- Development roadmap
- Future contribution guidelines

Git will be used locally for version tracking and GitHub will act as the central remote repository.

## Rationale

GitHub provides:
- Mature version control infrastructure
- Industry-standard workflows
- Issue tracking and project management tools
- Possibility to build an open-source community in the future

The repository also acts as a historical record of Codex Nexus development.

## Consequences

Positive:
- Clear project history
- Easier collaboration
- Professional development workflow

Negative:
- Dependence on an external platform
- Public exposure must be carefully managed if the project becomes open source

## Related Documents

- README.md
- vision.md
- architecture.md
