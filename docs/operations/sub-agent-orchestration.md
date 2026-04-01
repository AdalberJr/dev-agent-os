# Sub-Agent Orchestration

## Ziel
Spezialisierte Agenten gezielt einsetzen, ohne Chaos zu erzeugen.

## Grundregeln

- Ein Lead-Agent behält die Gesamtverantwortung
- Sub-Agents bekommen eng umrissene Aufgaben
- Keine parallelen Schreibkonflikte im selben Bereich
- Erst planen, dann delegieren
- Ergebnisse werden nie blind übernommen

## Empfohlene Delegationsmuster

### Pattern 1 — Research First
Lead -> Research -> Architect -> Build -> QA -> Security -> Ops

### Pattern 2 — Spec First
Lead -> Architect -> Build -> QA -> Security -> Ops

### Pattern 3 — UX-sensitive Feature
Lead -> Design/UI + Architect -> Build -> QA -> Security -> Ops

### Pattern 4 — Hotfix
Lead -> Build -> QA -> Security -> Ops

## Nicht erlaubt

- mehrere Build-Agents ohne klare Dateigrenzen gleichzeitig auf dieselben Dateien
- Review durch denselben Agenten, der gerade gebaut hat, wenn unabhängige Prüfung gewünscht ist
- Security komplett auslassen bei ernsthaften Projekten

## Freigabeprinzip
Jede delegierte Arbeit kommt zurück in den Lead-Kontext und wird dort bewertet oder weitergereicht.
