# EDS_AI_JJ

## Projektkontext
Dieses Repository enthält ein Studienprojekt im Modul **EDS_AI** an der Hochschule Luzern (HSLU).  
Ziel des Projekts ist die automatische Klassifikation von Musikgenres auf Basis von Audiodaten
mithilfe von **neuronalen Netzen**.

Das Projekt ist öffentlich zugänglich und richtet sich primär an Studierende sowie interessierte
Dozierende mit Grundkenntnissen in **Artificial Intelligence** und der Anwendung von **TensorFlow**.

---

## Datengrundlage
Als Datensatz wird der **GTZAN Genre Dataset** verwendet:

- 10 Musikgenres  
- 100 Titel pro Genre  
- 30 Sekunden pro Titel  

Jeder Track wird in **10 Segmente à 3 Sekunden** unterteilt, wodurch insgesamt **9’990 Samples**
entstehen (eine fehlerhafte Datei wurde ausgeschlossen).

Der Originaldatensatz kann auf Kaggle heruntergeladen werden:  
👉 https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

---

## Repository-Struktur

```text
├── Genre_Classification.ipynb   # Hauptnotebook (Analyse & Vergleich)
├── FFNN.ipynb                   # Feedforward-Modell
├── preprocess_gtzan.ipynb       # Feature-Extraktion & Preprocessing
├── bad_files.txt                # Liste beschädigter Audiodateien
├── Musikbeispiel/               # Beispiel-Audiodatei für Visualisierungen
  └── hiphop.00099.wav              
├── data_gtzan_mfcc.zip*         # aufbereitete GTZAN Daten
├── README.md
└── .gitignore
```
*Die aufbereiteten Daten wurden in ein .json Format gespeichert. Der Upload dieser Datei ist zu gross für mein Git Repo. 
Sollte eine gezippte Version der Datei data_gtzan_mfcc.json nicht im Repo auffindbar sein, besteht die Möglichkeit dies mit dem Notebook "preprocess_gtzan.ipynb" zu reproduzieren. 
Alternativ kann ich die Datei im persönlichen Austausch bereitstellen.

---

## Software Versionen für das Hauptnotebook
to do

---

## Lizenz & Quellen

Das Notebook `preprocess_gtzan.ipynb` basiert auf Code aus einem externen
GitHub-Repository und wurden für die Datenaufbereitung des GTZAN Datensets verwendet.

Originalquelle:  
https://github.com/musikalkemist/AudioSignalProcessingForML

Lizenz: MIT License


