
## README
Projektanleitung: Plant Disease Classification
Dieses Projekt dient zur Klassifikation von Pflanzenkrankheiten anhand von Bilddaten mithilfe klassischer ML-Modelle, künstlicher neuronaler Netze (ANN) und Convolutional Neural Networks (CNN).

Die Analyse und das Training erfolgen exemplarisch für drei Pflanzengruppen: Apfel, Mais (Corn) und Tomate.


### 1️ Projekt herunterladen

Klone oder lade das Repository direkt über GitHub herunter:


       git clone https://github.com/dein-nutzername/plant-disease-classification.git

### 2️ Bibliotheken installieren

Stelle sicher, dass pip installiert ist. Navigiere dann im Projektordner und führe folgenden Befehl aus, um alle benötigten Bibliotheken zu installieren:

         pip install -r requirements.txt

### 3️ Datensatz herunterladen und einfügen

Der für diese Arbeit verwendete Datensatz wurde manuell von Mendeley Data heruntergeladen:

PlantVillage Dataset – Mendeley Data

Anleitung zur Integration:

Lade den Datensatz herunter und entpacke ihn.

Verschiebe den Ordner PlantVillage in das Projektverzeichnis unter:

**Projektstruktur**

plant-disease-classification/
├── data/PlantVillage/                    # Data 
├── plant_disease_modeling.ipynb          # Analyse & Modellierung für Apfel
├── requirements.txt                      # Alle benötigten Python-Bibliotheken
└── README.md                             # Diese Projektbeschreibung

#### 4️ Notebooks ausführen

Die Analyse erfolgt in den folgenden Jupyter-Notebooks:

plant_disease_modeling.ipynb

Öffne die gewünschten .ipynb-Dateien mit Jupyter Lab oder Jupyter Notebook und führe die Zellen nacheinander aus.