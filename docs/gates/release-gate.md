# Release Gate

## Ziel
Sicherstellen, dass ein Stand technisch, operativ und organisatorisch bereit für Auslieferung ist.

## Verantwortlich
- Deploy / Ops Agent
- optional gemeinsam mit Security Agent

## Mindestanforderungen

- Build ist reproduzierbar
- benötigte Env-Variablen sind dokumentiert
- Zielumgebung ist klar definiert
- Rollback oder Recovery ist bedacht
- Logs/Monitoring sind vorhanden oder bewusst entschieden
- bekannte Restrisiken sind dokumentiert

## Prüffelder

- Build erfolgreich
- Deploy-Prozess dokumentiert
- Staging/Production sauber getrennt
- Secrets korrekt gesetzt
- Debug/Test-Flags geprüft
- DB-Migrations bedacht
- Domain / Routing / SSL / Plattformsettings geprüft
- Monitoring / Error Tracking vorhanden oder bewusst deferred

## Output-Format

- Status: Ready / Ready with Risks / Not Ready
- offene Punkte
- Restrisiken
- Freigabeempfehlung
