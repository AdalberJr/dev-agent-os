# Security Scorecard

## Ziel
Eine einfache Risikobewertung für Security-Readiness.

## Bewertungsskala
- 0 = kritisch unzureichend
- 1 = schwach
- 2 = akzeptabel
- 3 = gut
- 4 = stark

## Kriterien

### 1. Auth / Authorization
Sind geschützte Aktionen sauber abgesichert?

### 2. Input Validation
Sind Eingaben ausreichend validiert?

### 3. Secret Hygiene
Werden Secrets sauber behandelt?

### 4. Data Exposure Risk
Gibt es unnötige Exposition sensibler Daten?

### 5. Dependency Risk
Sind Libraries bewusst und vertretbar gewählt?

### 6. Operational Exposure
Sind Deployment- und Laufzeitrisiken ausreichend bedacht?

## Ergebnis
- 20-24 = Stark
- 14-19 = brauchbar, aber mit Risiken
- 8-13 = riskant
- 0-7 = nicht freigabefähig

## Pflichtnotiz
Neben der Punktzahl immer:
- größtes realistisches Risiko
- schwerwiegendste Schwachstelle
- empfohlene Pflichtmaßnahme
