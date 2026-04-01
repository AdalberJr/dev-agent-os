# Dev Agent OS

Ein professionelles Multi-Agent-Betriebsmodell für starke Web-, App- und Softwareprojekte.

## Ziel

Dieses Repo definiert ein belastbares Setup für die Arbeit mit spezialisierten Agenten/Rollen statt einem einzelnen Generalisten.

Fokus:
- klare Rollen
- saubere Übergaben
- hohe Qualitätsstandards
- verpflichtende Security- und Release-Gates
- reproduzierbare Abläufe

## Kernprinzipien

- Kein Bauen ohne klares Ziel und Scope
- Keine Implementierung ohne Ticket oder Spec
- Keine Freigabe ohne QA-Review
- Kein Release ohne Security- und Ops-Check
- Lieber robuste Standards als Tool-Spielerei
- Modularität vor Chaos
- Dokumentierte Entscheidungen statt implizitem Wissen

## Rollenmodell

1. Lead / Orchestrator
2. Research Agent
3. Architect / Planner
4. Build Agent
5. Review / QA Agent
6. Security Agent
7. Deploy / Ops Agent
8. Design / UI Agent

Details: siehe `docs/roles/`

## Standard-Ablauf

1. Intake / Zielklärung
2. Research
3. Architektur / Spec
4. Ticketing / Breakdown
5. Build
6. QA Review
7. Security Review
8. Deploy / Release Gate
9. Post-Release / Learnings

Details: siehe `docs/workflows/standard-workflow.md`

## Pflicht-Gates

- Quality Gate
- Security Gate
- Release Gate

Details: siehe `docs/gates/`

## Ordnerstruktur

- `docs/roles/` → Rollenprofile
- `docs/workflows/` → Abläufe
- `docs/gates/` → Freigabekriterien
- `templates/` → Übergabe- und Arbeitsvorlagen
- `standards/` → technische und operative Standards

## Einsatz

Dieses Repo ist die Source of Truth für den Dev-Agent-Prozess.
Es soll regelmäßig weiterentwickelt, geschärft und auf echte Projekte angewendet werden.

## Erweiterte Betriebsdoku

- `docs/operations/agent-prompt-profiles.md` → Rollenfokus und Prompt-Profile
- `docs/operations/handoff-protocol.md` → Übergabeformat zwischen Rollen
- `docs/operations/sub-agent-orchestration.md` → Delegationsmuster und Grenzen
- `CONTRIBUTING.md` → Änderungsprinzipien
- `ROADMAP.md` → Ausbaupfad
- `DECISIONS.md` → wichtige Grundsatzentscheidungen
- `CHANGELOG.md` → Verlauf

## Nächste sinnvolle Erweiterungen

- Example Project Lifecycle
- Stack-spezifische Standards (z. B. Next.js, Supabase, Expo)
- CI-Checklisten und Security-Automation
- Bewertungsraster / Scorecards
