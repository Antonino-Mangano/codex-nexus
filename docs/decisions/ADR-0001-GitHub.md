# ADR-0001: Use GitHub as the Project Repository

## Status

Accepted

## Date

2026-07-17

---

## Context

Codex Nexus is designed as a modular, privacy-first knowledge platform.

A reliable system for storing source code, documentation, project history, and collaboration is required.

The project needs:

- Version control
- Transparent development history
- Backup of project assets
- Possibility of future collaboration
- Integration with modern development workflows

---

## Decision

GitHub has been selected as the primary repository platform for Codex Nexus.

The repository will contain:

- Source code
- Documentation
- Architecture Decision Records (ADRs)
- Development roadmap
- Future contribution guidelines

Git will be used for local version control, while GitHub will serve as the central remote repository for collaboration, documentation, and project history.

---

## Rationale

GitHub provides:

- Mature version control infrastructure
- Industry-standard workflows
- Issue tracking and project management tools
- Excellent documentation support
- Possibility to build an open-source community in the future

The repository also acts as a historical record of Codex Nexus development.

---

## Consequences

### Positive

- Clear project history
- Easier collaboration
- Professional development workflow
- Strong ecosystem and community support

### Negative

- Dependence on an external platform
- Public exposure must be carefully managed if the project becomes open source

---

## Alternatives Considered

- GitLab
- Self-hosted Git server

These alternatives remain viable options should future project requirements change.

GitHub was selected because it provides the best balance of accessibility, collaboration features, documentation support, and community visibility for the current stage of Codex Nexus.

---

## Related Documents

- README.md
- THE_CODEX.md
- VISION.md
- ARCHITECTURE.md

---

## Alignment with THE CODEX

This decision supports the following principles:

- Build with care.
- Design to last.
- Documentation is part of the product.
- Stay modular.

---

## Decision Owner

**Founder:** Antonino Mangano

**AI Development Partner:** Astra
