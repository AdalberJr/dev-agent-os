# Release Readiness Scorecard

## Ziel
Bewerten, ob ein Stand operativ auslieferbar ist.

## Bewertungsskala
- 0 = nicht gegeben
- 1 = schwach
- 2 = ausreichend
- 3 = gut
- 4 = stark

## Kriterien

### 1. Build Reproducibility
Ist der Build nachvollziehbar und reproduzierbar?

### 2. Environment Readiness
Sind Env-Variablen, Secrets und Zielumgebung sauber vorbereitet?

### 3. Deployment Clarity
Ist der Deploy-Prozess klar und dokumentiert?

### 4. Recovery / Rollback Thinking
Ist klar, wie auf Probleme reagiert wird?

### 5. Monitoring / Visibility
Sind Fehler und Probleme nach Release sichtbar?

### 6. Risk Documentation
Sind bekannte Restrisiken dokumentiert?

## Ergebnis
- 20-24 = Release-stark
- 14-19 = releasebar mit Auflagen
- 8-13 = wackelig
- 0-7 = nicht bereit

## Pflichtnotiz
Neben der Zahl immer:
- größte operative Schwäche
- wichtigster fehlender Release-Schutz
- empfohlene nächste Maßnahme
