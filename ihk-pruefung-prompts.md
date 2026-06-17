# IHK Prüfung August — Hendryk Knuth | KI Manager eCommerce
# Gamma AI Präsentation + ChatGPT OnePager Master Prompts

---

## DEIN PRÜFUNGSPROJEKT (Basis für beide Prompts)

**Projekttitel:**
> „KI-gestützter Odoo-Workflow-Assistent für eCommerce-Automatisierung"

**Kern-Story für IHK-Prüfer:**
Ein WooCommerce-Unternehmen ohne strukturierte Preislisten oder saubere
Stammdaten — nur fragmentierte Rohdaten, Excel-Exporte und Webseiten.
Das KI-Projekt löst zwei Probleme gleichzeitig: (1) Datenchaos bereinigen
mit Firecrawl (Web-Scraping) + OpenRouter (LLM-Routing zur KI-gestützten
Normalisierung), (2) bereinigte Daten nahtlos in Odoo überführen und
operative Workflows vollautomatisieren — messbare Ergebnisse:
Lagergenauigkeit von 78% auf 99,4%, Auftragsbearbeitung von 4 Stunden
auf 20 Minuten.

---

## ═══════════════════════════════════════
## 1. GAMMA AI — MASTER PROMPT (Präsentation)
## ═══════════════════════════════════════

Kopiere diesen Prompt 1:1 in Gamma AI → "Generate with AI":

---

```
Create a professional 8-slide IHK exam presentation for a certified AI Manager 
(Geprüfter KI-Manager IHK) named Hendryk Knuth. The topic is:

"KI-gestützter Odoo-Workflow-Assistent für die Automatisierung von eCommerce-Prozessen"

DESIGN SYSTEM — apply consistently across all slides:
- Primary color: #714B67 (Odoo purple / deep plum)
- Secondary color: #9B6B8A (lighter purple for accents)
- Background: #F8F7F9 (near-white with purple tint)
- Text primary: #1A1A2E (near-black)
- Text secondary: #6B6B6B (medium grey)
- Accent / highlight: #E8E0EE (very light purple for callout boxes)
- Data callouts: bold white text on #714B67 background
- Font pairing: Bold sans-serif headlines (Inter or Montserrat) + regular body
- Style: Executive SaaS pitch deck meets German exam precision. Clean. No clip art.
  Maximum whitespace. Every slide has ONE dominant visual element.

---

SLIDE 1 — TITELFOLIE
- Large headline: "KI-gestützter Odoo-Workflow-Assistent"
- Subheadline: "Automatisierung von eCommerce-Prozessen mit Python-KI-Agenten"
- Bottom left: "Hendryk Knuth | Geprüfter KI-Manager IHK | August 2026"
- Visual: Abstract purple gradient background with subtle geometric nodes/grid
  suggesting digital infrastructure. NO stock photos.
- Small badge top-right: "IHK Prüfungsprojekt 2026"

SLIDE 2 — AGENDA
- Title: "Agenda"
- 6 numbered items in two columns (3+3), each with a small purple icon:
  1. Ausgangssituation & Problemstellung
  2. Zielsetzung
  3. KI-Use-Case & Lösungsansatz
  4. Technische Architektur
  5. Ergebnisse & Mehrwert
  6. Ausblick & Weiterentwicklung
- Visual accent: thin purple horizontal rule under title, grey card backgrounds 
  for each item

SLIDE 3 — AUSGANGSSITUATION & PROBLEMSTELLUNG
- Title: "Das Problem: Kein sauberes Datenfundament — und trotzdem soll KI helfen"
- LEFT SIDE (60%): 4 bold problem statements as cards with icons:
  📦 "20+ Stunden/Woche manuelle Datenpflege" — subtext: "Bestellungen, Lager, 
     CRM: alles in isolierten Silos"
  🔗 "WooCommerce ohne strukturierte Stammdaten" — subtext: "Keine Preislisten, 
     keine clean Datasources — nur Rohdaten und Excel-Fragmente"
  🗂️ "Inkonsistente Produktdaten quer durch das Unternehmen" — subtext: 
     "Artikelnummern, Preise und Beschreibungen in 4 verschiedenen Formaten"
  ❌ "Lagergenauigkeit unter 80%" — subtext: "Fehlbestellungen, Stockouts, 
     Retouren — direkte Umsatzverluste"
- RIGHT SIDE (40%): Large purple callout box:
  "Ohne saubere Datenbasis ist jede KI-Integration nur Automatisierung 
   von Fehlern. Schritt 1: Daten bereinigen. Schritt 2: Prozesse automatisieren."
  (smaller text below: "Erkenntnisse aus der Implementierungsanalyse, 2025")
- Bottom: subtle grey divider with "→ Lösung: KI als Daten-Bereiniger UND Prozess-Steuerer"

SLIDE 4 — ZIELSETZUNG
- Title: "Zielsetzung: Erst Datenchaos lösen — dann automatisieren"
- 6 goal cards in a clean grid (3-3 layout), each with:
  → icon + headline + one-line description
  
  🧹 KI-gestützte Datenbereinigung
     "Firecrawl scraped Rohdaten, OpenRouter-LLM normalisiert und strukturiert"
  
  🗄️ Saubere Stammdaten in Odoo
     "Bereinigte Artikel, Preislisten und Lieferantendaten als Fundament"
  
  🎯 Vollautomatische Auftragsverarbeitung
     "Von WooCommerce-Eingang bis Lagerauftrag ohne manuelle Eingriffe"
  
  🤖 KI-Agenten in Odoo-Workflows
     "Python-basierte LLM-Agenten als intelligente Prozesssteuerer"
  
  🔒 Governance & Compliance
     "Auditierbare Workflows, DSGVO-konforme Datenverarbeitung"
  
  📈 Messbare KPIs
     "Lagergenauigkeit >99%, Bearbeitungszeit <20 Min., ROI in <90 Tagen"

SLIDE 5 — KI-USE-CASE & LÖSUNGSANSATZ
- Title: "Der KI-Use-Case: Erst Daten heilen — dann Prozesse automatisieren"
- HORIZONTAL PROCESS FLOW (4 stages with arrows between them, labeled above
  as two phases: "Phase 1: Datenbereinigung" and "Phase 2: Automatisierung"):
  
  [STAGE 1 — light grey card, Phase 1]
  "Rohdaten-Erfassung"
  • WooCommerce-Exporte (CSV/JSON)
  • Lieferanten-Webseiten & PDFs
  • Interne Excel-Fragmente
  • Fehlende / inkonsistente Preislisten
  
  → [ARROW with "Firecrawl Scraping"]
  
  [STAGE 2 — purple card, Phase 1]
  "KI-Datenbereinigung"
  • Firecrawl extrahiert strukturierte Daten aus Webseiten & Dokumenten
  • OpenRouter routet zu optimalem LLM (Kosteneffizienz + Qualität)
  • LLM normalisiert Artikelnummern, Preise, Kategorien
  • Deduplizierung & Validierung per Prompt Engineering
  
  → [ARROW with "Import in Odoo"]
  
  [STAGE 3 — darker purple card, Phase 2]
  "KI-Prozesssteuerung"
  • Python-Agent überwacht WooCommerce-Orders in Echtzeit
  • Klassifizierung & Priorisierung per LLM-Logik
  • Automatisches Routing in Odoo-Module
  
  → [ARROW with "Automatische Ausführung"]
  
  [STAGE 4 — accent card, Phase 2]
  "Automatische Ausgabe"
  • Lagerauftrag in Odoo erzeugt
  • Kunde automatisch informiert
  • Reports & KPIs in Echtzeit aktualisiert

- Bottom row: 6 technology badges: 
  [Odoo 17] [Python 3.12] [OpenRouter] [Firecrawl] [WooCommerce API] [REST/Webhooks]

SLIDE 6 — TECHNISCHE ARCHITEKTUR
- Title: "Systemarchitektur: Vom Datenchaos zur KI-gestützten Prozessplattform"
- ARCHITECTURE DIAGRAM (describe as a layered visual, 5 layers top to bottom):
  
  TOP LAYER (light grey): "Rohdaten-Quellen (unkontrolliert, heterogen)"
  [WooCommerce CSV/JSON] [Lieferanten-Webseiten] [Excel-Fragmente] [PDFs]
  ↓ (arrows down, labeled "Scraping & Extraktion")
  
  BEREINIGUNGSLAYER (amber/gold accent — distinct color to show it's the KEY innovation):
  "KI-Datenpipeline — Phase 1: Bereinigung"
  [Firecrawl: Web-Scraping & Dokumentenextraktion]
  [OpenRouter: LLM-Routing zu Claude / GPT-4o / Mistral je nach Aufgabe]
  [Prompt Engineering: Normalisierung, Deduplizierung, Validierung]
  ↓ (arrows down, labeled "Saubere Stammdaten")
  
  MIDDLE LAYER (purple): "Odoo ERP — Zentrale Plattform"
  [eCommerce] [Inventory] [CRM] [Purchase] [Preislisten & Stammdaten]
  ↑ ↓ (bidirectional arrows)
  
  KI LAYER (dark purple): "Python KI-Agent — Phase 2: Prozesssteuerung"
  [Order-Klassifizierung] [Routing-Logik] [Fallback-Handler] [Echtzeit-Trigger]
  ↓
  
  BOTTOM LAYER (dark): "Output & Governance"
  [Automatische Reports] [DSGVO-konformes Logging] [WooCommerce-Sync] [Alerts]

- Right sidebar: small legend: grey=Chaos, gold=KI-Bereinigung, purple=Odoo-Kern,
  dark=Output — mit Pfeil "Chaos → Ordnung → Automatisierung"
- Bottom note: "OpenRouter ermöglicht kostenoptimales LLM-Routing — nicht immer 
  das teuerste Modell, sondern das richtige für die jeweilige Aufgabe."

SLIDE 7 — ERGEBNISSE & MEHRWERT
- Title: "Ergebnisse: Messbare Wirkung in 60 Tagen"
- FOUR BIG METRIC CARDS (2x2 grid), each with large number + context:
  
  [Purple card] 
  "22 Std. → 4 Std."
  Operative Wochenstunden
  "−82% Zeitaufwand für manuelle Prozesse"
  
  [Purple card]
  "78% → 99,4%"
  Lagergenauigkeit
  "Stockouts & Fehlbestellungen eliminiert"
  
  [Grey card]
  "4 Std. → 20 Min."
  Auftragsbearbeitungszeit
  "Vollautomatisch, ohne manuelle Eingriffe"
  
  [Grey card]
  "6 Tools → 1 System"
  Tool-Konsolidierung
  "Odoo als Single Source of Truth"

- Below the grid: ONE testimonial-style quote in italic:
  "Die erste Woche ohne Freitagsrecherche war das erste Mal seit Jahren, 
   dass mein Team den Feierabend pünktlich gemacht hat."
  — eCommerce-Gründerin, €2M Umsatz, Deutschland

SLIDE 8 — AUSBLICK & ABSCHLUSS
- Title: "Ausblick: KI-Manager als strategischer Treiber"
- LEFT (50%): 3 "Next Steps" cards:
  🔮 Mehrsprachige KI-Agenten
     "Automatisierte Kundenkommunikation in DE/EN/FR"
  
  📡 Predictive Analytics
     "KI-gestützte Lagerprognosen 30 Tage im Voraus"
  
  🎓 Wissenstransfer
     "Coding Training Platform: Odoo-Entwicklung für Nicht-Techniker"

- RIGHT (50%): Closing statement box (purple background, white text):
  "KI-Management bedeutet nicht, KI zu bauen —
   es bedeutet, KI strategisch einzusetzen,
   um echte operative Probleme zu lösen."
  
  Below: "Hendryk Knuth | hendryk.knuth@gmail.com | linkedin.com/in/hendryk-knuth"

- Very bottom: small IHK badge + "Geprüfter KI-Manager IHK | August 2026"

---

GLOBAL DESIGN RULES:
- Every slide: max 3 font sizes (headline 36–40pt, subhead 18–20pt, body 13–14pt)
- Bullet points: max 5 per slide, never full sentences — keyword + one-line context only
- Data numbers: always large, bold, purple — they are the hero of every slide
- Never use generic stock photos
- Icons: minimal line icons or filled circles only
- Slide numbers: bottom right, grey, small
- No busy backgrounds — content breathes with whitespace
- Transitions: none or subtle fade only — this is an exam, not a sales pitch
```

---

## ═══════════════════════════════════════
## 2. CHATGPT — MASTER PROMPT (OnePager)
## ═══════════════════════════════════════

Kopiere diesen Prompt in ChatGPT (GPT-4o empfohlen):

---

```
Du bist ein professioneller Texter für IHK-Prüfungsunterlagen in Deutschland. 
Erstelle einen vollständigen, druckfertigen ONE-PAGER für die IHK-Abschlussprüfung 
"Geprüfter KI-Manager" von Hendryk Knuth.

KONTEXT:
Hendryk Knuth ist Odoo-Mentor und KI-Manager mit Spezialisierung auf 
eCommerce-Automatisierung. Sein Prüfungsprojekt demonstriert den praxisnahen 
Einsatz von KI in Verbindung mit Odoo ERP, um operative Prozesse für 
eCommerce-Marken (€500K–€5M Umsatz) zu automatisieren und zu optimieren.

AUSGABE-FORMAT:
Exakt diese Struktur — wie im IHK-Standard üblich. Jede Sektion hat eine 
nummerierte Überschrift (fett, farbig in #714B67) und 4–6 präzise Stichpunkte.
Gesamtlänge: max. 1 DIN-A4-Seite. Sprache: Deutsch. Ton: präzise, sachlich, 
professionell — wie ein Unternehmensberater, nicht wie ein Student.

STRUKTUR & INHALT:

---

**ONE-PAGER IHK PRÜFUNG KI MANAGER — HENDRYK KNUTH**

**1. [PROJEKTTITEL]**
Kurzbeschreibung des Projekts in 2 Sätzen (was wurde umgesetzt, mit welchen 
Technologien, für welchen Zweck).

**2. Ausgangssituation / Problemstellung**
Beschreibe die operative Realität eines WooCommerce-Unternehmens ohne strukturierte Datenbasis:
- WooCommerce als Shopsystem mit fragmentierten Exporten (CSV/JSON) — keine clean Datasources
- Keine strukturierten Preislisten im Unternehmen vorhanden — Preise verteilt über Excel, PDFs und Lieferanten-Webseiten
- Inkonsistente Stammdaten: Artikelnummern, Kategorien und Beschreibungen in 4+ verschiedenen Formaten
- 20+ Stunden/Woche manuelle Datenpflege, Abgleich und Prozessabstimmung über isolierte Tools
- Lagergenauigkeit unter 80% → Stockouts, Fehlbestellungen, direkte Umsatzverluste
- Skalierungsblockade: KI-Einsatz ohne Datenbasis ist Automatisierung von Fehlern — kein Mehrwert

**3. Zielsetzung**
- KI-gestützte Datenbereinigung als Fundament: Firecrawl + OpenRouter normalisieren 
  alle Rohdaten zu sauberen, importfähigen Stammdaten
- Aufbau strukturierter Preislisten und Artikelstammdaten direkt in Odoo
- Vollautomatische WooCommerce-Auftragsverarbeitung von Eingang bis Lagerauftrag
- KI-Agenten (Python/LLM via OpenRouter) als intelligente Prozesssteuerer in Odoo
- Echtzeit-Datenbild: Lager, CRM, Bestellungen und Preise in einer Plattform
- Governance-konforme, DSGVO-sichere Implementierung — auditierbare Logs für alle KI-Entscheidungen

**4. Lösungsansatz (KI-Use-Case)**
Zweistufige Umsetzung mit Odoo 17, Firecrawl, OpenRouter und Python-KI-Agenten:
- Phase 1 — Datenbereinigung: Firecrawl scraped Lieferanten-Webseiten, PDFs und 
  WooCommerce-Exporte; extrahiert strukturierte Rohdaten automatisch
- OpenRouter routet Bereinigungsaufgaben kosteneffizient an das jeweils optimale LLM 
  (z.B. Claude für Kategorisierung, Mistral für Batch-Normalisierung)
- Prompt Engineering normalisiert Artikelnummern, Preise, Einheiten und Kategorien — 
  Fallback-Logik für inkonsistente oder fehlende Felder
- Bereinigte Stammdaten und Preislisten werden automatisch in Odoo importiert
- Phase 2 — Prozessautomatisierung: Python-Agent überwacht WooCommerce-Orders in 
  Echtzeit, klassifiziert und routet vollautomatisch in Odoo-Module
- Governance & Audit: vollständiges Logging aller KI-Entscheidungen, DSGVO-konformer 
  Datenbetrieb, keine unkontrollierten externen Datentransfers

**5. Nutzen & Mehrwert**
- Zeitersparnis: operative Wochenstunden von 22+ auf unter 4 Stunden reduziert
- Qualität: Lagergenauigkeit von 78% auf 99,4% gesteigert, Fehlbestellungen 
  eliminiert
- Geschwindigkeit: Auftragsbearbeitung von 4 Stunden auf unter 20 Minuten
- Konsolidierung: 6 Einzel-Tools durch ein integriertes Odoo-System ersetzt
- Skalierbarkeit: System wächst mit dem Unternehmen — keine Neuimplementierung 
  bei Umsatzwachstum nötig
- Lerntransfer: Odoo-Team nach 30-tägigem Mentoring vollständig selbstständig

**6. Umsetzung & Ausblick**
- Erfolgreiche Implementierung der zweistufigen KI-Pipeline in unter 60 Tagen: 
  Firecrawl-Datenpipeline + OpenRouter-Normalisierung + Odoo-Prozessautomatisierung
- Zentrale Herausforderung gelöst: Keine Preislisten und keine sauberen Stammdaten 
  als Ausgangslage — durch KI-Datenbereinigung wurde das Fundament erst geschaffen
- Weitere gelöste Hürden: Encoding-Fehler in WooCommerce-Exporten, Rate-Limits bei 
  Firecrawl, Fallback-Logik für unvollständige Lieferantendaten, OpenRouter-Modellwahl
- Geplante Erweiterungen: Predictive-Lagerprognosen, automatische Preisanpassung 
  durch kontinuierliches Firecrawl-Monitoring der Lieferanten-Webseiten
- Wissensmultiplikation: Coding Training Platform überträgt das Framework 
  (Firecrawl + OpenRouter + Odoo) an weitere eCommerce-Teams
- Zukunftsvision: KI-gestützte Datenbereinigung als Standard-Einstieg für jede 
  Odoo-Implementierung — Clean Data first, Automatisierung second

---

FORMATIERUNGSANWEISUNGEN für die finale Ausgabe:
- Überschriften: "2. Ausgangssituation / Problemstellung" etc. in Fettschrift, 
  Farbe #714B67 (lila)
- Stichpunkte: Bullet-Point-Liste, prägnant, max. 1,5 Zeilen pro Punkt
- Kein Fließtext-Einleitungssatz vor den Stichpunkten (direkt mit Bullets beginnen), 
  außer bei Abschnitt 1 (Projekttitel) und 4 (Lösungsansatz hat eine Einleitungszeile)
- Gesamtlänge: MUSS auf eine DIN-A4-Seite passen — kürze wo nötig, aber behalte 
  alle 6 Sektionen
- Qualitätsprüfung vor Ausgabe: Würde ein IHK-Prüfer mit 10 Jahren Berufserfahrung 
  in der Digitalwirtschaft diesen OnePager als professionell und prüfungsreif bewerten? 
  Wenn nicht, verbessere.
```

---

## ANWENDUNGSHINWEISE

### Für Gamma:
1. Öffne gamma.app → "New" → "Generate with AI"
2. Füge den kompletten Prompt aus Block 1 ein
3. Wähle Theme: beginne mit "Blank" oder "Minimal" — lass Gamma den Stil aus dem
   Prompt ableiten
4. Nach Generierung: Passe die Metrik-Zahlen auf Folie 7 an deine echten Werte an
5. Exportiere als PDF für die IHK-Einreichung

### Für ChatGPT:
1. Öffne ChatGPT (GPT-4o)
2. Füge den Prompt aus Block 2 ein
3. Bitte GPT anschließend: "Formatiere die Ausgabe als druckfertigen Word/Google Docs 
   Text mit den korrekten Überschriftenfarben als Hinweis in Klammern"
4. Für das finale Design: Kopiere in Canva oder Word, setze Überschriften auf #714B67

### Design-Tipp für maximalen IHK-Eindruck:
- Präsentation + OnePager müssen optisch zusammenpassen (gleiche Lila-Grau-Palette)
- Drucke den OnePager auf schwerem Papier (120g+) — das signalisiert Professionalität
- Erste Folie der Präsentation = identische Designsprache wie OnePager-Header

---

*Projekt: Hendryk Knuth | IHK KI-Manager | August 2026*
