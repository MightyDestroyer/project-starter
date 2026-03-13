# CLAUDE.md

## Projekt

- **Name:** [Projektname]
- **Beschreibung:** [Kurzbeschreibung — was macht dieses Projekt?]
- **Stack:** [z. B. TypeScript, Next.js, PostgreSQL]
- **Repo:** [GitHub-URL]

## Quick Links

| Service | URL |
|---------|-----|
| GitHub | [Repo-URL] |
| Governance Wiki | https://mightydestroyer.github.io/governance/ |
| Governance Repo | https://github.com/MightyDestroyer/governance |

<!-- Lokale Services (falls zutreffend): -->
<!-- | Grafana | http://localhost:3000 | -->
<!-- | Prometheus | http://localhost:9090 | -->
<!-- | Health Check | http://localhost:8080/healthz | -->

## Governance

Dieses Projekt folgt den MightyDestroyer Governance-Prinzipien.

- [Kernprinzipien](https://github.com/MightyDestroyer/governance/blob/main/standards/principles.md) — 11 Prinzipien, alle verbindlich.
- [AI Guardrails](https://github.com/MightyDestroyer/governance/blob/main/standards/ai-guardrails.md)
- [Security Guidelines](https://github.com/MightyDestroyer/governance/blob/main/standards/security-guidelines.md)
- [Coding Principles](https://github.com/MightyDestroyer/governance/blob/main/standards/coding-principles.md)

Operative Regeln (Naming, Commits, Eskalation) werden durch Cursor Rules in `.cursor/rules/` durchgesetzt.

## Architektur

<!-- Kurze Beschreibung der Projektarchitektur: -->
<!-- - Welche Services/Module gibt es? -->
<!-- - Wie kommunizieren sie? -->
<!-- - Welche Datenbanken/Stores werden genutzt? -->

## Build & Run

```bash
make dev       # Entwicklung
make build     # Build
make test      # Tests
make lint      # Lint
```

## Kontext-Dateien

| Datei | Zweck | Pflicht? |
|-------|-------|----------|
| `CLAUDE.md` | Diese Datei — Projekt-Kontext | Ja |
| `README.md` | Projektueberblick, Setup | Ja |
| `MEMORY.md` | Persistenter Kontext ueber Sessions | Empfohlen |
| `docs/project-bible.md` | Sprint-Protokoll, ADRs, Entscheidungen | Empfohlen |

## Session-Workflow

### Start

1. CLAUDE.md lesen (diese Datei).
2. MEMORY.md lesen (falls vorhanden).
3. Uebergabe-Dokument der letzten Session lesen (falls vorhanden).
4. Scope der aktuellen Aufgabe klaeren.

### Ende

1. Doku aktualisieren (README, MEMORY.md, ADRs).
2. Uebergabe-Dokument erstellen (falls relevanter Kontext).

## Projektspezifische Regeln

<!-- Hier projektspezifische Anweisungen einfuegen -->

## ADRs

Architektur-Entscheidungen werden unter `docs/adrs/` dokumentiert.

---

*Generiert aus [MightyDestroyer/project-starter](https://github.com/MightyDestroyer/project-starter)*
