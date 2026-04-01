# Security Gate

## Ziel
Sicherstellen, dass keine grundlegenden Sicherheitsmängel in Architektur, Code oder Betrieb übersehen werden.

## Verantwortlich
- Security Agent

## Mindestanforderungen

- serverseitige Autorisierung für geschützte Aktionen
- Eingaben validiert und bereinigt
- keine Secrets im Code oder Client-Bundle
- sensible Daten werden nicht unnötig gespeichert oder geloggt
- sichere Standardkonfigurationen
- Abhängigkeiten bewusst gewählt
- unnötige Angriffsfläche reduziert

## Prüffelder

### Auth & Access
- Wer darf was?
- Gibt es fehlende Rollen-/Rechteprüfungen?
- Werden serverseitige Checks statt nur Client-Checks genutzt?

### Input / Output
- Gibt es Input-Validierung?
- Gibt es Risiko für Injection, XSS, unsichere Serialisierung?

### Data Handling
- Werden personenbezogene oder sensible Daten minimiert?
- Sind Logs sauber?
- Ist Datenzugriff begrenzt?

### Secrets & Config
- `.env` statt Hardcoding
- keine Tokens in Repos oder Client-Code
- saubere Umgebungs-Trennung

### Dependencies
- unnötige Packages vermeiden
- bekannte Risiken beobachten
- Supply-Chain-Risiken mitdenken

### Ops Surface
- Debug-Modi deaktivieren
- exponierte Endpunkte bewusst prüfen
- minimale Berechtigungen verwenden

## Einstufung

### Critical
Kein Merge / kein Release.

### High
Vor Release beheben.

### Medium
Zeitnah beheben und tracken.

### Low
Dokumentieren / später bereinigen.

## Output-Format

- Status: Pass / Pass with Risks / Fail
- Critical Findings
- High Findings
- Medium Findings
- Low Findings
- Residual Risk Summary
- Empfehlung
