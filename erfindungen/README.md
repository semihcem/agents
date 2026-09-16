# 🔬 Erfindungs-Radar (dauerhaft)

Ein selbstlaufendes Agenten-Duo, das **fortlaufend nach neuen, wirtschaftlich nutzbaren Erfindungen** sucht.

## Wie es funktioniert

```
        ⏰ Routine (täglich)
                │
                ▼
   🔎 invention-scout  →  findet 5 neue Erfindungs-Kandidaten
                │           (recherchiert Neuheit + Monetarisierung)
                ▼
   🧐 invention-verifier →  prüft hart: existiert das schon? machbar? profitabel?
                │           verwirft Duplikate/Luftschlösser
                ▼
   📁 erfindungen/inventions.md  →  speichert nur Bestätigte (Score ≥ 16/25)
                │
                ▼
        📌 commit + push (bleibt dauerhaft im Repo)
```

## Die Agenten
- **`invention-scout`** — sucht neue Erfindungen; verwirft alles, was es schon gibt oder womit man kein Geld verdienen kann.
- **`invention-verifier`** — gegenprüft (Produkt-/Patent-Recherche, Machbarkeit, Wirtschaftlichkeit) und **schreibt** die bestätigten in [`inventions.md`](./inventions.md).

## „Dauerhaft" – der Mechanismus
Ein einzelner Agent läuft nicht von allein endlos. Das „dauerhaft" kommt über eine **zeitgesteuerte Routine**
(standardmäßig **täglich**), die jeweils eine frische Session startet, Scout → Verifier laufen lässt, die
Ergebnisse anhängt und committet. Taktung änderbar (stündlich–täglich) — sag einfach Bescheid.

## Regeln (was NICHT gespeichert wird)
- Dinge, die es schon gibt (auch nicht leicht umbenannt) → verworfen mit Beleg.
- Ideen ohne Zahlungswille / ohne Markt → verworfen.
- Physikalisch/rechtlich/ethisch Unmögliches → verworfen.

> Alle Angaben sind Recherche-Einschätzungen ohne Gewähr — keine Rechts-/Patent-/Anlageberatung.
> Vor einer echten Umsetzung immer eigene Patent-/Marktrecherche & ggf. Fachberatung.
