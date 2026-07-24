# Coffee Sales Forecast 

## Projektübersicht

Dieses Projekt demonstriert die Grundlagen des **Machine Learning** mit Python und **scikit-learn**. Ziel des Projekts ist die Entwicklung eines einfachen Prognosemodells zur Vorhersage zukünftiger monatlicher Umsätze eines Cafés auf Basis historischer Verkaufsdaten.

Das Projekt wurde im Rahmen einer Weiterbildung im Bereich **Data Analytics** durchgeführt und zeigt den vollständigen Workflow eines Machine-Learning-Projekts – von der Datenaufbereitung über das Training eines Modells bis hin zur Interpretation der Ergebnisse und der Ableitung betriebswirtschaftlicher Empfehlungen.

---

# Projektziele

- Analyse historischer Umsatzdaten
- Visualisierung langfristiger Umsatzentwicklungen
- Entwicklung eines Machine-Learning-Modells
- Prognose zukünftiger Monatsumsätze
- Bewertung der Modellqualität
- Interpretation der Ergebnisse aus betriebswirtschaftlicher Sicht
- Erläuterung der Grenzen und Risiken von Prognosen

---

# Datensatz

Der Datensatz enthält monatliche Umsätze einer Café-Kette.

**Zeitraum:** 2022–2024

**Anzahl der Beobachtungen:** 36 Monate

**Enthaltene Variablen:**

- Monat
- Umsatz (UAH)

---

# Verwendete Technologien

- Python
- Google Colab
- pandas
- NumPy
- Matplotlib
- scikit-learn
- Lineare Regression

---

# Machine-Learning-Modell

Im Projekt wird die **Lineare Regression** eingesetzt – einer der grundlegenden Algorithmen des überwachten Machine Learnings.

Das Modell lernt den Zusammenhang zwischen dem Zeitverlauf und dem monatlichen Umsatz und nutzt diesen Trend, um zukünftige Umsätze zu prognostizieren.

---

# Projektablauf

### 1. Datenimport

- Import der benötigten Bibliotheken
- Laden des Datensatzes

### 2. Explorative Datenanalyse (EDA)

- Untersuchung der Datenstruktur
- Visualisierung der historischen Umsatzentwicklung
- Identifikation langfristiger Trends

### 3. Datenvorbereitung

- Erstellung der Trainingsdaten
- Vorbereitung der Eingangsvariablen für das Machine-Learning-Modell

### 4. Modelltraining

Training eines Modells der Linearen Regression mit **scikit-learn**.

### 5. Modellbewertung

Vergleich der prognostizierten Werte mit den historischen Daten.

### 6. Umsatzprognose

Erstellung einer Prognose für die ersten sechs Monate des Jahres 2025.

### 7. Zusätzliche Prognose

Erstellung einer Prognose für einen einzelnen zukünftigen Monat (Februar 2026).

### 8. Interpretation der Ergebnisse

Bewertung der Prognose sowie Erläuterung der Grenzen des Modells und Ableitung betriebswirtschaftlicher Schlussfolgerungen.

---

# Prognoseergebnisse

### Prognose für Juni 2025 (Monat 42)

**31.539 UAH**

### Zusätzliche Prognose für Februar 2026 (Monat 50)

**35.213 UAH**

Die Ergebnisse zeigen einen kontinuierlichen Wachstumstrend der Umsätze.

Gleichzeitig nimmt die Zuverlässigkeit der Prognosen mit zunehmendem Prognosehorizont ab.

---

# Zentrale Erkenntnisse

Die Analyse zeigt einen langfristig positiven Umsatztrend.

Wesentliche Erkenntnisse:

- Die historischen Umsätze weisen einen kontinuierlichen Wachstumstrend auf.
- Die Lineare Regression bildet den allgemeinen Trend zuverlässig ab.
- Saisonale Schwankungen werden vom Modell nicht berücksichtigt.
- Mit zunehmendem Prognosezeitraum steigt die Unsicherheit der Vorhersagen.

---

# Grenzen des Modells

Die Prognose sollte nicht als exakte Vorhersage verstanden werden.

Die wichtigsten Einschränkungen des Modells sind:

- Die Lineare Regression setzt ein konstantes Wachstum über die Zeit voraus.
- Saisonale Schwankungen werden nicht berücksichtigt.
- Externe wirtschaftliche und geschäftliche Einflussfaktoren fließen nicht in das Modell ein.
- Das Modell wurde lediglich auf 36 historischen Beobachtungen trainiert.
- Die Prognosegenauigkeit nimmt mit wachsendem Prognosehorizont ab.

## Warum werden langfristige Prognosen ungenauer?

### Fehlerakkumulation

Jedes Vorhersagemodell besitzt eine gewisse Ungenauigkeit. Mit jedem weiteren Prognosezeitraum summieren sich diese Fehler, wodurch die Prognosegenauigkeit sinkt.

### Unvorhersehbare Veränderungen

Die Zukunft wird von zahlreichen Faktoren beeinflusst, die das Modell nicht berücksichtigen kann. Dazu gehören beispielsweise wirtschaftliche Krisen, Veränderungen im Konsumverhalten, neue Wettbewerber, erfolgreiche Marketingkampagnen oder andere unerwartete Ereignisse.

### Veraltete Datengrundlage

Das Modell wurde ausschließlich mit historischen Daten trainiert. Verändern sich Marktbedingungen oder Kundenverhalten im Laufe der Zeit, kann das Modell diese Entwicklungen insbesondere bei langfristigen Prognosen nicht mehr zuverlässig abbilden.

**Fazit:**

Je länger der Prognosehorizont ist, desto größer werden Unsicherheit und Fehlerrisiko. Langfristige Prognosen sollten daher stets als Orientierungshilfe und nicht als exakte Vorhersage verstanden werden.

---

# Geschäftsempfehlungen

Die Prognose eignet sich als erste Orientierung für Budgetplanung und Unternehmenssteuerung.

Strategische Entscheidungen sollten jedoch zusätzlich folgende Faktoren berücksichtigen:

- saisonale Schwankungen;
- Marketingkampagnen;
- wirtschaftliche Rahmenbedingungen;
- Wettbewerbssituation;
- Veränderungen im Kundenverhalten.

Für langfristige Planungen sollten Prognosemodelle regelmäßig mit aktuellen Daten aktualisiert und neu trainiert werden, um Veränderungen der Marktbedingungen zeitnah zu berücksichtigen.

---

# Repository-Struktur

```
python_project/
│
├── coffee_forecast.ipynb
├── coffee_sales.csv
└── README.md
```

---

# Demonstrierte Kompetenzen

- Python
- pandas
- NumPy
- Matplotlib
- Machine Learning
- Lineare Regression
- Umsatzprognosen
- Explorative Datenanalyse (EDA)
- Datenvisualisierung
- Interpretation analytischer Ergebnisse
- Ableitung betriebswirtschaftlicher Handlungsempfehlungen
- Kommunikation datenbasierter Entscheidungen

---

# Projektergebnis

Dieses Projekt demonstriert den vollständigen Ablauf eines grundlegenden Machine-Learning-Projekts – von der Datenaufbereitung über das Training eines Prognosemodells bis hin zur Interpretation der Ergebnisse und der Ableitung fundierter betriebswirtschaftlicher Handlungsempfehlungen.

Es zeigt, wie technische Kenntnisse in Python und Machine Learning mit analytischem Denken und betriebswirtschaftlichem Verständnis kombiniert werden können, um datenbasierte Entscheidungen zu unterstützen und Prognosen kritisch zu bewerten.
