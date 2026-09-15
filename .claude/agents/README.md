# 🤖 The Agency – Kuratiertes Agenten-Set (52 Spezialisten)

Dieses Verzeichnis enthält **52 spezialisierte Subagents** für Claude Code, ausgewählt aus
[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (The Agency, MIT-Lizenz).
Schwerpunkte: **Web-/App-Design, digitale Unternehmensfunktionen (Betrieb & Steuerung) sowie Finanzen, Steuern, Recht & Compliance**.

---

## 🧠 Was ist ein Subagent?

Ein Subagent ist eine `.md`-Datei mit einer festen Rolle/Persönlichkeit und einem eigenen System-Prompt.
Claude Code kann Aufgaben an so einen Spezialisten **delegieren** – der Subagent arbeitet in seinem eigenen
Kontextfenster und gibt dir nur das Ergebnis zurück. Vorteile:

- **Fokus** – jeder Agent ist Experte für genau ein Feld (SEO, Datenschutz, Backend …).
- **Sauberer Kontext** – die Detailarbeit landet nicht in deinem Hauptchat.
- **Wiederverwendbar & versioniert** – liegt im Repo, ist im Team teilbar.

Jede Datei hat oben einen YAML-Kopf mit `name` (Slug, klein + Bindestriche) und `description`
(daran erkennt Claude, *wann* delegiert werden soll) – darunter der eigentliche Prompt.

---

## ▶️ Wie benutze ich sie?

Es gibt drei Wege:

**1. Explizit per Name** (zuverlässigste Methode):
```
Nutze den design-ui-designer Agenten, um einen Screen für die Login-Seite zu entwerfen.
Lass den security-appsec-engineer diesen Auth-Code auf Schwachstellen prüfen.
Frag den finance-tax-strategist, wie ich die Umsatzsteuer für digitale Produkte in der EU handhabe.
```

**2. Automatisch** – beschreib einfach dein Ziel; Claude wählt anhand der `description` passende Agenten:
```
Ich brauche eine Landingpage für meine App und einen Plan, wie ich sie im Store bewerbe.
```

**3. Übersicht & Verwaltung** – Slash-Befehl in Claude Code:
```
/agents
```
Damit siehst/erstellst/bearbeitest du alle Agenten (Projekt + global).

> **Wichtig:** In Claude Code auf dem Web wird der Agenten-Ordner beim **Session-Start** eingelesen.
> Wenn die Agenten in dieser laufenden Session noch nicht auftauchen, **starte die Session neu** (bzw. `git pull` lokal).

---

## 📚 Die 52 Agenten nach Kategorie

### 🎨 Design (Web & App) — 8
- **`design-ui-designer`** — Visuelle Design-Systeme, Komponenten-Bibliotheken, pixelgenaue UIs.
- **`design-ux-architect`** — UX-Architektur, CSS-Systeme & saubere Frontend-Grundlagen für Entwickler.
- **`design-ux-researcher`** — Nutzerforschung, Usability-Tests, datengetriebene Design-Entscheidungen.
- **`design-brand-guardian`** — Markenidentität, Konsistenz, Brand Guidelines.
- **`design-visual-storyteller`** — Visuelle Narrative, Infografiken, Multimedia-Content.
- **`design-inclusive-visuals-specialist`** — Kulturell akkurate, barrierefreie & inklusive Visuals.
- **`design-ui-finish-gate-reviewer`** — Prüft UIs vor dem Release auf „generisch/austauschbar".
- **`design-image-prompt-engineer`** — Detaillierte Prompts für KI-Bildgenerierung.

### 💻 Engineering (Web-/App-Entwicklung & Betrieb) — 14
- **`engineering-frontend-developer`** — Modernes Frontend, React/Vue/Angular, UI-Umsetzung.
- **`engineering-backend-architect`** — Skalierbares Backend, APIs, Datenarchitektur.
- **`engineering-software-architect`** — Systemdesign, DDD, Architektur-Patterns, tech. Strategie.
- **`engineering-mobile-app-builder`** — Native iOS/Android & Cross-Platform-Apps.
- **`engineering-mobile-release-engineer`** — App-Signing, Provisioning, fastlane, Store-Releases.
- **`engineering-rapid-prototyper`** — Ultraschnelle Prototypen & MVPs.
- **`engineering-code-reviewer`** — Konstruktive Code-Reviews (Korrektheit, Wartbarkeit, Security).
- **`engineering-devops-automator`** — CI/CD, Infrastruktur-Automatisierung, Cloud-Betrieb.
- **`engineering-database-optimizer`** — Schema-Design, Query-Optimierung, Indexierung, Performance.
- **`engineering-api-platform-engineer`** — Öffentliche/Partner-APIs, OpenAPI/gRPC, Versionierung.
- **`engineering-technical-writer`** — Entwickler-Doku, API-Referenzen, READMEs, Tutorials.
- **`engineering-privacy-engineer`** — Datenschutz im Code: PII-Erkennung, Datenminimierung.
- **`engineering-payments-billing-engineer`** — Zahlungsanbindung (Stripe/Adyen/PayPal), Abo-/Billing-Flows.
- **`engineering-cms-developer`** — Drupal/WordPress: Themes, Plugins, Content-Architektur.

### 📦 Product — 3
- **`product-manager`** — Ganzheitliches Produktmanagement über den gesamten Lebenszyklus.
- **`product-sprint-prioritizer`** — Sprint-Planung, Feature-Priorisierung, Ressourcen.
- **`product-feedback-synthesizer`** — Nutzer-Feedback sammeln & in Handlungsempfehlungen übersetzen.

### 📋 Projektmanagement — 2
- **`project-manager-senior`** — Wandelt Specs in Aufgaben um, behält Projektkontext.
- **`project-management-studio-producer`** — Übergreifende Orchestrierung von kreativen/technischen Projekten.

### 📣 Marketing — 5
- **`marketing-growth-hacker`** — Schnelle Nutzergewinnung durch datengetriebene Experimente.
- **`marketing-seo-specialist`** — Technisches SEO, Content-Optimierung, Linkaufbau.
- **`marketing-content-creator`** — Content-Strategie & -Erstellung für Multi-Plattform-Kampagnen.
- **`marketing-social-media-strategist`** — Strategie für LinkedIn, X/Twitter & Co.
- **`marketing-app-store-optimizer`** — App Store Optimization (ASO) & Conversion.

### 🤝 Sales — 2
- **`sales-deal-strategist`** — MEDDPICC-Qualifizierung, Wettbewerbsposition, Win-Planung.
- **`sales-pipeline-analyst`** — Pipeline-Gesundheit, Deal-Velocity, Forecast-Genauigkeit.

### 🏢 Business, Recht & Betrieb — 8
- **`business-strategist`** — Wettbewerbsanalyse, Markteintritt, Geschäftsmodelle.
- **`specialized-chief-of-staff`** — Koordination für Gründer/Führung; Prozesse, Priorisierung.
- **`operations-manager`** — Prozesse mit Lean/Six Sigma, Kapazität & Systemdenken.
- **`chief-financial-officer`** — Kapitalallokation, Treasury, Finanzplanung, M&A.
- **`customer-success-manager`** — Onboarding, Health-Scores, QBRs, Churn-Prävention.
- **`hr-onboarding`** — Mitarbeiter-Onboarding, Doku, Compliance-Tracking.
- **`legal-document-review`** — Prüfung von Verträgen, Prozess- & Immobiliendokumenten.
- **`data-privacy-officer`** — DSGVO/CCPA-Compliance-Programme, DPO-Aufgaben.

### 💰 Finanzen & Steuern — 4
- **`finance-tax-strategist`** — Steueroptimierung, Compliance über mehrere Länder, Verrechnungspreise.
- **`finance-bookkeeper-controller`** — Buchhaltung, Abstimmungen, Controlling.
- **`finance-fpa-analyst`** — Budgetierung, Abweichungsanalyse, Finanzplanung.
- **`finance-financial-analyst`** — Finanzmodelle, Forecasting, Szenarioanalyse.

### 🔒 Security — 3
- **`security-architect`** — Threat Modeling, Secure-by-Design, Trust-Boundaries.
- **`security-appsec-engineer`** — Sichere SDLC, Secure Code Review, Threat Modeling.
- **`security-compliance-auditor`** — SOC 2, ISO 27001, HIPAA, PCI-DSS Audits.

### 🛟 Support & Compliance — 3
- **`support-support-responder`** — Kundensupport, Problemlösung, Nutzererlebnis.
- **`support-legal-compliance-checker`** — Prüft Betrieb/Datenverarbeitung/Content auf Rechtskonformität.
- **`support-analytics-reporter`** — Rohdaten → verwertbare Business-Insights.

---

## 🧩 Beispiel-Workflows (Agenten kombinieren)

**Neue Web-App von 0 auf 1:**
`product-manager` → `design-ux-researcher` → `design-ui-designer` → `engineering-frontend-developer` + `engineering-backend-architect` → `engineering-code-reviewer` → `security-appsec-engineer`

**App-Launch & Vermarktung:**
`marketing-app-store-optimizer` + `marketing-growth-hacker` + `marketing-content-creator` + `marketing-social-media-strategist`

**Rechts- & Finanz-Setup für ein digitales Unternehmen:**
`data-privacy-officer` (DSGVO) + `legal-document-review` (Verträge/AGB) + `finance-tax-strategist` (Steuern) + `finance-bookkeeper-controller` (Buchhaltung) + `security-compliance-auditor` (Zertifizierungen)

---

## 💡 Tipps für den besten Einsatz

1. **Sei konkret.** Statt „mach die Seite schöner" → „Nutze `design-ui-designer` und entwirf ein Card-Layout für die Preisübersicht, mobile-first."
2. **Kette Agenten.** Erst planen (`product-manager`), dann designen, dann bauen, dann prüfen (`engineering-code-reviewer`, `security-appsec-engineer`).
3. **Ein Agent = ein Job.** Für mehrere Themen mehrere Agenten nacheinander statt einen Alleskönner.
4. **`/agents`** nutzen, um Rollen anzupassen (Modell, erlaubte Tools) – z. B. Review-Agenten auf Lesezugriff beschränken.
5. **Rechts-/Steuerthemen sind Orientierung, keine Rechtsberatung.** Bei verbindlichen Fragen Fachperson hinzuziehen.

---

## ➕ Weitere Agenten hinzufügen

Das Original hat 230+ Agenten. So holst du weitere dazu:

```bash
git clone https://github.com/msitarzewski/agency-agents.git
# gewünschte Datei kopieren, z.B.:
cp agency-agents/testing/testing-api-tester.md .claude/agents/
```

> ⚠️ **Format-Hinweis:** Die Original-Dateien haben im `name`-Feld einen Klartext-Namen
> (z. B. `name: UI Designer`). Claude Code verlangt aber **Kleinbuchstaben + Bindestriche**
> (`name: design-ui-designer`) und **überspringt** ungültige Dateien. Passe das `name`-Feld
> nach dem Kopieren an den Dateinamen an (genau wie bei den 52 Agenten hier).
>
> Alternativ für eine **globale** Installation auf deinem eigenen Rechner
> (unter `~/.claude/agents/`) das offizielle Skript nutzen:
> `./scripts/install.sh --tool claude-code`

---

*Quelle: [The Agency](https://github.com/msitarzewski/agency-agents) · Lizenz: MIT · Kuratiert & für Claude Code angepasst.*
