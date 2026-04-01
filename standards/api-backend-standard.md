# API / Backend Standard

## Ziel
Ein klarer Standard für Backends, APIs und serverseitige Business-Logik.

## Prinzipien

- serverseitige Logik gehört auf den Server
- Eingaben nie blind vertrauen
- Zuständigkeiten klar trennen
- APIs so bauen, dass Fehler und Grenzen nachvollziehbar sind

## Struktur

- Route / Controller Layer
- Service / Business Logic Layer
- Data Access Layer
- Validation Layer

## Mindeststandards

- Input-Validierung an jedem relevanten Einstiegspunkt
- klare Fehlercodes oder saubere Fehlerantworten
- Auth- und Autorisierungsprüfungen serverseitig
- keine Secrets im Code
- Logging ohne sensible Payloads
- Timeouts / externe API-Fehler mitdenken

## Gute Praxis

- APIs klein und verständlich halten
- Seiteneffekte sichtbar machen
- Idempotenz bedenken, wenn Aktionen mehrfach ausgelöst werden könnten
- externe Integrationen kapseln
- Rate Limits oder Schutz gegen Missbrauch prüfen

## Anti-Patterns

- Business-Logik direkt in Routen verstreuen
- fehlende Validierung
- interne Fehlermeldungen 1:1 nach außen geben
- Admin-Operationen ohne harte Prüfung
- Copy-Paste-Endpunkte ohne gemeinsame Regeln
