<!-- ELUCENIA technical documentation · h2fpef · de · no clinical/professional/rights approval -->

# H₂FPEF-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/h2fpef)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Heavy: BMI \> 30 kg/m² (2)

`obesidade`

### Hypertensive: 2 oder mehr Antihypertensiva (1)

`anti`

### F: paroxysmales oder persistierendes Vorhofflimmern (3)

`fa`

### Pulmonal: systolischer Pulmonalarteriendruck \> 35 mmHg in der Echokardiografie (1)

`hp`

### Elder: Alter \> 60 Jahre (1)

`idade`

### Filling: E/e' \> 9 in der Echokardiografie (1)

`ee`

## Fassung der Methode

H2FPEF/Reddy 2018: 6 Faktoren, 0–9; 2 BMI/3 Vorhofflimmern

## Dokumentierte Formel

Adipositas (BMI \> 30) = 2 · ≥ 2 Antihypertensiva = 1 · Vorhofflimmern = 3 · systolischer Pulmonalarteriendruck \> 35 mmHg = 1 · Alter \> 60 = 1 · E/e' \> 9 = 1. Gesamt 0 bis 9.

## Grenzen und Population

H2FPEF wurde bei Personen mit ungeklärter Dyspnoe entwickelt, die zur invasiven hämodynamischen Belastungsuntersuchung überwiesen wurden, im Vergleich von HFpEF und nichtkardialen Ursachen. Der Score hilft bei der Entscheidung über weitere Abklärung; er bestätigt HFpEF nicht allein und darf nicht automatisch auf jede Dyspnoeursache übertragen werden. Population, Ejektionsfraktion und echokardiografische Definitionen müssen zur Methode passen.

## Referenzen

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Niedrige Wahrscheinlichkeit für HFpEF (0 bis 1)

Nicht-kardiale Ursachen der Dyspnoe abklären.


### 2

Mittlere Wahrscheinlichkeit (2 bis 5)

Ergänzend Belastungs-Echokardiographie (diastolisch) oder Belastungskatheteruntersuchung; natriuretische Peptide helfen.


### 3

Mittlere Wahrscheinlichkeit (2 bis 5)

Ergänzend Belastungs-Echokardiographie (diastolisch) oder Belastungskatheteruntersuchung; natriuretische Peptide helfen.


### 4

Hohe Wahrscheinlichkeit für HFpEF (6 bis 9)

HFpEF wahrscheinlich: behandeln und spezifische Ätiologien abklären (Amyloidose, hypertrophe Kardiomyopathie).

