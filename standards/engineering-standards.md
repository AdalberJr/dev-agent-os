# Engineering Standards

## Ziel
Ein konsistenter Qualitätsrahmen für Softwarearbeit.

## Grundregeln

- erst denken, dann bauen
- keine Implementierung ohne klares Ziel
- kleine, prüfbare Änderungen bevorzugen
- bestehende Konventionen respektieren
- Doku dort aktualisieren, wo Wissen entsteht

## Code

- sprechende Namen statt kryptischer Abkürzungen
- Logik nicht unnötig in UI-Komponenten verstecken
- Funktionen und Module mit klarem Zweck
- keine doppelten Patterns ohne Grund
- Fehlerfälle bewusst behandeln
- Defaults defensiv wählen

## Architektur

- lose Kopplung wo sinnvoll
- klar definierte Verantwortlichkeiten
- Wachstumspfad mitdenken, aber nicht overengineeren
- externe Services bewusst auswählen

## Qualität

- jede größere Änderung braucht Review
- Definition of Done pro Ticket klar festhalten
- Regressionen aktiv mitdenken
- Randfälle nicht ignorieren

## Betrieb

- `.env.example` oder dokumentierte Env-Liste
- trennscharfe Umgebungen
- nachvollziehbarer Build-/Deploy-Weg
- keine geheimen manuellen Schritte ohne Doku
