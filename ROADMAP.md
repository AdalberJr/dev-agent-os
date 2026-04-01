# Roadmap

## Phase 1 — Foundation
- [x] Rollenmodell definieren
- [x] Workflow definieren
- [x] Quality / Security / Release Gates definieren
- [x] Kern-Templates anlegen
- [x] Basis-Standards dokumentieren

## Phase 2 — Operationalization
- [ ] Rollenspezifische Prompt-Profile ergänzen
- [ ] Übergabeprotokolle zwischen Rollen schärfen
- [ ] Beispiel-Projektfluss dokumentieren
- [ ] Review- und Security-Checklisten erweitern
- [ ] Done/Not-Done Beispiele ergänzen

## Phase 3 — Stack Standards
- [ ] Next.js Standard
- [ ] Supabase Standard
- [ ] API / Backend Standard
- [ ] Mobile App Standard
- [ ] CI/CD Standard

## Phase 4 — Automation
- [ ] Sub-Agent-Orchestrierung standardisieren
- [ ] Ticket-to-Review Flows als Routine definieren
- [ ] Security-Baseline je Projekttyp ausarbeiten
- [ ] Release Readiness Template erweitern

## Phase 5 — Maturity
- [ ] Decision Log pflegen
- [ ] Reale Projektbeispiele referenzieren
- [x] Anti-Patterns sammeln (aus AI Sales Copilot v0.1)
- [x] Scorecards / Bewertungsraster hinzufügen

---

## Anti-Patterns (aus erstem Testprojekt)

Diese Anti-Patterns wurden im ersten realen Projektdurchlauf identifiziert:

- **Expo Stack manuell zusammenbauen** → immer `npx create-expo-app` nutzen
- **Research ohne echten Vergleich** → mindestens 2 Optionen mit Tradeoffs
- **Security Gate nur auf Papier** → Cross-User-Test ist Pflicht
- **Tickets als Phasen statt Aufgaben** → jedes Ticket braucht Done-Kriterium
- **AI im Namen ohne AI im MVP** → Claims müssen erfüllbar sein
- **Session-Persistenz als Nice-to-have** → bei Mobile Apps immer Phase 1
