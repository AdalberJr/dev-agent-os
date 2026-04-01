# Decision Log

## 2026-04-01 — Multi-Agent statt Ein-Agent-Generalist

### Entscheidung
Das System basiert auf spezialisierten Rollen statt auf einem einzigen Allzweck-Agenten.

### Begründung
- bessere Fokusfähigkeit
- klarere Übergaben
- höhere Prüfqualität
- geringere Vermischung von Planung, Umsetzung und Kontrolle

### Konsequenz
Dokumente, Templates und Prozesse müssen rollenbasiert aufgebaut sein.

---

## 2026-04-01 — Security als Pflichtspur

### Entscheidung
Security ist kein optionaler Nachgedanke, sondern ein eigener Pflichtbestandteil im Prozess.

### Begründung
- viele schwerwiegende Fehler entstehen durch fehlende frühe Prüfung
- QA ersetzt keine Security-Perspektive
- starke Systeme brauchen klare Risk Gates

### Konsequenz
Security Gate ist fester Bestandteil vor Release und bei sensibler Architektur schon früh einzubinden.

---

## 2026-04-01 — Learnings aus erstem Testprojekt (AI Sales Copilot)

### Erfahrung
Erster vollständiger Durchlauf von Idee bis laufendem Supabase-Backend mit Expo Mobile App.

### Kritische Learnings
- Expo-Stack nie manuell zusammenbauen — immer `npx create-expo-app` als Startpunkt
- Research Memo muss mindestens 2 echte Optionen mit Tradeoffs enthalten
- Security Gate ist operativ (testen!), nicht nur theoretisch (dokumentieren)
- Tickets brauchen messbare Akzeptanzkriterien, nicht nur Phasenbeschreibungen
- AI im Produktnamen bedeutet AI muss im MVP funktionieren
- Session-Persistenz bei Mobile Apps gehört in Phase 1

### Konsequenz
Diese Punkte fließen als Standards in künftige Projekte ein.

---

## 2026-04-01 — Professionelles Basismodell vor Automatisierung

### Entscheidung
Zuerst werden Rollen, Standards und Übergaben definiert. Erst danach wird operative Automatisierung aufgebaut.

### Begründung
- Automatisierung ohne Standards skaliert Chaos
- starke Agentensysteme brauchen definierte Inputs/Outputs
- Qualität entsteht durch Systemdesign, nicht durch Agentenzahl

### Konsequenz
Das Repo dient zuerst als Source of Truth und wird danach operativ erweitert.
