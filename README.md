
# Shop Sphere

## Projektbeschreibung

Shop Sphere ist ein analytisches Ausbildungsprojekt, das auf den Daten eines globalen Online-Marktplatzes basiert, der Produkte aus sieben Kategorien in fünf Weltregionen verkauft.

Ziel des Projekts war es, den vollständigen Data-Analytics-Prozess zu durchlaufen:

- Daten mit SQL extrahieren und aufbereiten;
- Geschäftsanalysen durchführen;
- interaktive Dashboards in Tableau erstellen;
- Schlussfolgerungen und Handlungsempfehlungen für das Management formulieren.

Das Projekt basiert auf Daten aus den Jahren **2022–2024**.

# Geschäftsanforderungen

Das Management wollte Antworten auf folgende Fragestellungen erhalten:

- Wie effizient wird das Marketingbudget eingesetzt?
- Welche Marketingkanäle erzielen den höchsten ROI?
- Stimmen die ROI-Ergebnisse mit dem langfristigen Kundenwert (LTV) überein?
- Wie kann das Marketingbudget optimiert werden?
- Welche Produktkategorien sind tatsächlich profitabel?
- Welche Kategorien erzeugen lediglich die Illusion hoher Umsätze?
- Welche Kategorien besitzen Entwicklungspotenzial?
- Fördern Rabatte die Kundenbindung?
- Welchen Anteil am Gesamtumsatz erzielen die wertvollsten Kunden?
- Welche Ergebnisse liefert der A/B-Test des Checkout-Prozesses?
- Für welche Kundengruppen ist die neue Checkout-Version besonders effektiv?

# Verwendete Tools

- SQL (SQLite)
- Tableau Public

# Im Projekt demonstrierte Kompetenzen

Im Rahmen des Projekts wurden folgende Data-Analytics-Kompetenzen angewendet:

- SQL (CTE, JOIN, Aggregate Functions, Window Functions, CASE WHEN)
- Analyse von Geschäftskennzahlen (KPIs)
- Berechnung von ROI und LTV sowie Pareto-Analyse
- Analyse des Kundenverhaltens
- Analyse von Produktkategorien
- A/B-Testing
- Datenvisualisierung mit Tableau
- Erstellung interaktiver Dashboards
- Ableitung datenbasierter Handlungsempfehlungen

# Repository-Struktur

```text
Shop-Sphere/
│
├── Data/
├── SQL_Queries.pdf
├── Report.pdf
├── README.md
└── Presentation/
```

# Hinweis zur Datenstruktur

Für die korrekte Ausführung der SQL-Abfragen in SQLite wurden zwei Spalten umbenannt:

- `acquisition_channel` → `acquisition_chan`
- `attributed_revenue` → `attributed_reven`

Diese Umbenennungen wurden ausschließlich aufgrund der Einschränkungen von SQLite hinsichtlich der Spaltennamen vorgenommen und haben weder die Datenstruktur noch den Dateninhalt verändert.

# Durchgeführte Analysen

Im Rahmen des Projekts wurden folgende Analysen durchgeführt.

### 1. Analyse der Marketingeffizienz

- ROI der Marketingkanäle
- Verteilung des Marketingbudgets
- Vergleich von ROI und LTV
- Empfehlungen zur Umverteilung des Marketingbudgets

### 2. Analyse der Produktkategorien

Vergleich der Produktkategorien hinsichtlich:

- Umsatz
- Marge
- Retourenquote

Identifiziert wurden:

- Kategorien, die lediglich hohe Umsätze vortäuschen;
- Kategorien mit hoher Profitabilität und Entwicklungspotenzial.

### 3. Kundenanalyse

Untersucht wurden:

- Einfluss von Rabatten auf Wiederholungskäufe;
- durchschnittliche Anzahl der Bestellungen;
- Beitrag der Top-5-%-Kunden zum Gesamtumsatz;
- Regionen und Akquisitionskanäle der wertvollsten Kunden.

### 4. A/B-Testing

Analyse des Checkout-Experiments.

Verglichen wurden:

- durchschnittlicher Bestellwert der Gruppen A und B;
- Neukunden;
- Bestandskunden.

Zusätzlich wurde ein möglicher statistischer Effekt untersucht, bei dem das Gesamtergebnis unterschiedliche Verhaltensweisen einzelner Kundengruppen verdeckt.

# Visualisierung

Zur Präsentation der Ergebnisse wurden interaktive Dashboards in Tableau erstellt.

Die Dashboards ermöglichen die Analyse von:

- Effizienz der Marketingkanäle;
- Kundenverhalten;
- Wirksamkeit von Rabatten;
- Produktkategorien;
- Retouren;
- zentralen Geschäftskennzahlen.

**Tableau Public:**

https://public.tableau.com/app/profile/olga.lytvynenko/viz/ShopSphere_17848336784920/MarketingPerformance?publish=yes

# Projektkennzahlen

Im Rahmen der Analyse wurden untersucht:

- 5 Datentabellen
- ca. 12.300 Bestellungen
- mehr als 26.000 Bestellpositionen
- 3.000 Kunden
- Daten aus den Jahren 2022–2024
- 5 Weltregionen
- 7 Produktkategorien

# Wichtigste Ergebnisse

Die Analyse führte zu folgenden Erkenntnissen:

- Identifikation der effizientesten und ineffizientesten Marketingkanäle;
- Vergleich von ROI und LTV der Kunden;
- Empfehlungen zur Optimierung des Marketingbudgets;
- Identifikation von Kategorien mit hohem Umsatz, aber geringer tatsächlicher Profitabilität;
- Identifikation von Produktkategorien mit hohem Wachstumspotenzial;
- Analyse des Einflusses von Rabatten auf Wiederholungskäufe;
- Ermittlung des Umsatzanteils der Top-5-%-Kunden;
- Analyse der Ergebnisse des A/B-Tests und Ableitung von Empfehlungen zur Einführung der neuen Checkout-Version.

# Geschäftsempfehlungen

Auf Grundlage der Analyse wurden Empfehlungen formuliert für:

- die Optimierung des Marketingbudgets;
- die Umverteilung der Investitionen zwischen Marketingkanälen;
- die Weiterentwicklung der profitabelsten Produktkategorien;
- die Bindung der wertvollsten Kunden;
- die Verbesserung der Rabattstrategie;
- die Einführung der Ergebnisse des A/B-Tests für ausgewählte Kundensegmente.
