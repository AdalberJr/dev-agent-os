# Standard Workflow

## Ziel

Ein durchgängiger Ablauf von Idee bis Release mit klaren Qualitäts- und Sicherheitsstufen.

---

## Phase 1 — Intake

### Zweck
Projektziel, Problem, Scope und Erfolgskriterien klären.

### Verantwortlich
- Lead / Orchestrator

### Ergebnis
- klares Zielbild
- grober Scope
- Annahmen / offene Fragen
- gewünschtes Qualitätsniveau

### Output
- Project Brief

---

## Phase 2 — Research

### Zweck
Technologien, APIs, Libraries, Patterns, Wettbewerber und Umsetzungsoptionen bewerten.

### Verantwortlich
- Research Agent

### Ergebnis
- Shortlist von Optionen
- Tradeoffs
- Empfehlung
- Risiken und Abhängigkeiten

### Output
- Research Memo

---

## Phase 3 — Architecture & Planning

### Zweck
Aus dem Ziel und Research eine belastbare technische Lösung machen.

### Verantwortlich
- Architect / Planner
- optional: Security Agent frühzeitig bei sensiblen Themen

### Ergebnis
- Architekturentscheidung
- Datenmodell
- API-Design
- Modulstruktur
- Betriebsannahmen
- Security-Annahmen

### Output
- Architecture Spec
- Definition of Done

---

## Phase 4 — Ticketing / Breakdown

### Zweck
Das Vorhaben in umsetzbare, überprüfbare Arbeitspakete zerlegen.

### Verantwortlich
- Lead / Orchestrator
- Architect / Planner

### Ergebnis
- priorisierte Tickets
- klare Akzeptanzkriterien
- bekannte Risiken pro Ticket

### Output
- Build Tickets

---

## Phase 5 — Build

### Zweck
Features, Integrationen und technische Bausteine umsetzen.

### Verantwortlich
- Build Agent
- optional: Design / UI Agent für UX-/UI-nahe Features

### Ergebnis
- funktionierende Implementierung
- begleitende Doku / Env / Migrations falls nötig

### Output
- Code
- Doku-Updates
- ggf. Tests

---

## Phase 6 — Quality Gate

### Zweck
Prüfen, ob die Umsetzung funktional, nachvollziehbar und wartbar ist.

### Verantwortlich
- Review / QA Agent

### Prüffragen
- erfüllt die Umsetzung die Spezifikation?
- gibt es Bugs oder Edge Cases?
- ist die Struktur nachvollziehbar?
- ist die UX logisch?
- ist die Änderung wartbar?

### Ergebnis
- Freigabe oder Review-Liste

### Output
- Review Report

---

## Phase 7 — Security Gate

### Zweck
Prüfen, ob Architektur, Code und Betriebsannahmen sicher genug sind.

### Verantwortlich
- Security Agent

### Prüffragen
- gibt es Auth-/Autorisierungsprobleme?
- werden Inputs validiert?
- gibt es Secret-Risiken?
- werden sensible Daten unnötig geloggt oder exponiert?
- gibt es Dependency-Risiken?
- sind Rechte und Datenflüsse sauber?

### Ergebnis
- Security-Freigabe oder Blocker

### Output
- Security Review

---

## Phase 8 — Release Gate

### Zweck
Sicherstellen, dass der Stand reproduzierbar und betrieblich sauber auslieferbar ist.

### Verantwortlich
- Deploy / Ops Agent
- bei Bedarf gemeinsam mit Security Agent

### Prüffragen
- sind Umgebungsvariablen sauber dokumentiert?
- ist der Build-/Deploy-Prozess nachvollziehbar?
- ist Staging/Prod sauber getrennt?
- gibt es Monitoring/Logs?
- sind Debug-/Testmodi deaktiviert?

### Ergebnis
- Release freigegeben oder gestoppt

### Output
- Release Checklist

---

## Phase 9 — Post Release

### Zweck
Lernen, stabilisieren, dokumentieren.

### Verantwortlich
- Lead / Orchestrator
- Review / QA Agent
- Deploy / Ops Agent

### Ergebnis
- bekannte Probleme dokumentiert
- nächste Optimierungen identifiziert
- Learnings festgehalten

### Output
- Post-Release Notes
- Decision Log / Learnings
