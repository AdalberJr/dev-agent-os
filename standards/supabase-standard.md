# Supabase Standard

## Ziel
Supabase kontrolliert, sicher und wartbar einsetzen.

## Einsatz
Geeignet für:
- MVPs
- SaaS-Produkte
- Auth + Postgres + Storage Kombinationen
- schnelle produktive Backends

## Grundregeln

- Datenmodell zuerst denken, nicht erst nachträglich
- Row Level Security bewusst planen
- Policies nicht nebenbei zusammenklicken und vergessen
- Service Role nur serverseitig und gezielt nutzen
- Storage, DB und Auth als getrennte Sicherheitsflächen behandeln

## Datenbank

- klare Tabellenverantwortung
- sprechende Spaltennamen
- Timestamps / Ownership sauber definieren
- Migrationen nachvollziehbar halten
- keine wilden Schema-Änderungen ohne Doku

## Auth

- serverseitige Prüfung für geschützte Operationen
- Rollen-/Rechtekonzept früh definieren
- User-Metadaten nicht blind vertrauen

## RLS / Policies

- Standard: deny by default denken
- jede Policy braucht klare Begründung
- Policies auf Lesen, Schreiben, Updaten, Löschen bewusst trennen
- nicht nur Happy Path testen

## Storage

- Bucket-Zugriffe bewusst definieren
- private und öffentliche Assets klar trennen
- Upload-Regeln und Ownership bedenken

## Mindeststandards

- dokumentierte Tabellen und Kernbeziehungen
- dokumentierte Policies für sensible Daten
- keine Service-Role im Client
- Trennung von anonym, authentifiziert und Admin sauber bedacht

## Anti-Patterns

- alles über Service Role lösen
- RLS deaktivieren aus Bequemlichkeit
- komplexe Business-Regeln nur im Frontend absichern
- unsichtbare manuelle DB-Änderungen in Produktion
