# Security Baseline

## Ziel
Ein nicht verhandelbarer Sicherheits-Mindeststandard für ernsthafte Projekte.

## 1. Access Control
- serverseitige Autorisierung für geschützte Aktionen
- Rollen und Rechte explizit definieren
- Client-seitige Checks nie als echte Sicherheitsgrenze behandeln

## 2. Input Safety
- Eingaben validieren
- erwartete Formate klar definieren
- Injection-, XSS- und Missbrauchsvektoren aktiv prüfen

## 3. Secrets
- Secrets nur über sichere Konfiguration / Env
- niemals im Repo oder Frontend-Bundle
- minimal nötige Rechte vergeben

## 4. Data Handling
- Datensparsamkeit
- keine unnötigen sensiblen Logs
- klare Besitz- und Zugriffsregeln
- Export-/Admin-Funktionen besonders hart prüfen

## 5. Dependencies
- keine unnötigen Packages
- etablierte Libraries bevorzugen
- bekannte Risiken und Wartbarkeit betrachten

## 6. Deployment
- Debug-/Dev-Modi in Produktion deaktivieren
- Umgebungen sauber trennen
- Domains, Zugriffspfade und öffentliche Flächen bewusst prüfen

## 7. Monitoring
- Fehler sichtbar machen
- sicherheitsrelevante Ereignisse nachvollziehbar halten
- aber ohne Secrets oder sensible Payload-Leaks

## 8. Review Rule
- keine ernsthafte Auslieferung ohne Security Review

## Mindestfrage vor Release
Was wäre der realistischste Angriff oder Missbrauch hier — und haben wir ihn ausreichend erschwert?
