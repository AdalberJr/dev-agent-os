# Next.js Standard

## Ziel
Ein robuster Standard für produktive Webprojekte mit Next.js.

## Einsatz
Geeignet für:
- Landingpages mit Wachstumspfad
- SaaS MVPs
- Dashboards
- interne Tools
- content-nahe Webanwendungen

## Bevorzugte Grundstruktur

- App Router bevorzugen
- klare Trennung von UI, Server-Logik und Datenzugriff
- Komponenten nach Verantwortung strukturieren
- gemeinsame Utilities zentral halten
- kein chaotisches Vermischen von Fetching, Rendering und Business-Logik

## Empfehlungen

### Frontend
- React mit klaren, kleinen Komponenten
- Tailwind nur mit konsistenten Patterns
- wiederverwendbare UI-Bausteine früh definieren
- Form- und Error-States bewusst behandeln

### Server
- serverseitige Logik nicht unnötig in den Client ziehen
- sensible Operationen serverseitig ausführen
- Actions / Route Handlers bewusst und sparsam einsetzen
- keine Secret-Nutzung im Client-Bundle

### Datenzugriff
- Datenzugriff kapseln
- keine verstreuten DB-Zugriffe über die ganze App
- klare Trennung zwischen Query-Logik und Darstellung

### Auth
- serverseitige Session-/Role-Prüfung
- Client-Checks nur als UX, nicht als Sicherheitsgrenze

## Mindeststandards

- sinnvolle Error-States
- Loading-/Empty-States vorhanden
- mobile Nutzbarkeit mitdenken
- keine unnötige Client-Komponente wenn Server-Komponente reicht
- klare Env-Dokumentation
- SEO/Metadata bewusst setzen, wenn öffentliches Produkt

## Anti-Patterns

- große God Components
- Business-Logik quer im UI verteilt
- direkte Secret-Nutzung im Frontend
- unstabile Copy-Paste-Fetch-Muster
- fehlende Trennung von public/private Routen
