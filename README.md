# Modellierung der jährlichen erwarteten KfZ-Schadenhöhe 

## Virtual Environment & Packages
Zur Installation der virtual environment und der benötigten packages führen Sie bitte folgende Befehle im Terminal aus:

```BASH
pyenv local 3.11.9
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Daten

Bitte laden Sie die folgenden beiden Datensätze herunter und speichern diese im Ordner `data`: 
* https://www.openml.org/d/41214
* https://www.openml.org/d/41215

## Ergebnisse
Die Ergebnisse befinden sich in folgendem Jupyter-Notebook:

**claim_prediction.ipynb** 

Zum Öffnen des Jupyter Notebooks im Browser lassen Sie bitte folgenden Befehl laufen und wählen Sie das entsprechende Notebook aus:

```BASH
jupyter lab
```
