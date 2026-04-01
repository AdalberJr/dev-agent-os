# Quality Gate

## Ziel
Sicherstellen, dass eine Umsetzung fachlich korrekt, technisch sauber und wartbar ist.

## Verantwortlich
- Review / QA Agent

## Mindestanforderungen

- Anforderungen und Akzeptanzkriterien erfüllt
- keine offensichtlichen Funktionsfehler
- sinnvolle Fehlerbehandlung vorhanden
- lesbare Struktur und Benennung
- keine unnötige Komplexität
- relevante Doku aktualisiert
- UI-/UX-Flows nachvollziehbar

## Einstufung

### Blocker
Release oder Merge darf nicht erfolgen.

Beispiele:
- Kernfunktion funktioniert nicht
- falsche Business-Logik
- kritische Edge Cases nicht behandelt
- Regression in bestehendem Verhalten

### Major
Soll vor Release behoben werden.

Beispiele:
- schlechte Wartbarkeit
- inkonsistente UX
- unklare Zustandslogik
- wichtige Fehlerfälle fehlen

### Minor
Kann nachgelagert verbessert werden.

Beispiele:
- kleinere Aufräumarbeiten
- Copy-Verbesserungen
- Refactoring mit niedrigem Risiko

## Output-Format

- Status: Pass / Pass with Issues / Fail
- Blocker
- Major Issues
- Minor Issues
- Empfehlung
