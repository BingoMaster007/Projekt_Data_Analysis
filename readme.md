## Datensatz

Quelle:  
Tiwari, S. (2019). Consumer complaints dataset for NLP. Kaggle  
https://www.kaggle.com/datasets/shashwatwork/consume-complaints-dataset-fo-nlp/data

### Speicherung des Datensatzes

Der Datensatz sollte heruntergeladen und die ZIP-Datei im im selben Directory wie das Projekt entpackt und unter dem Namen complaints_processed.csv abgelegt werden. (siehe Projektstruktur)

## Installation
1. Repository clonen
2. requirements.txt installieren:
pip install -r requirements.txt
3. spaCy installieren:
python -m spacy download en_core_web_sm
4. Pfade definieren
5. Ausführen

## Projektstruktur

```
project/
├── data/
│   ├── complaints.zip
│   └── complaints_processed.csv
├──Projekt_Data_Analysis.ipynb
├──requirements.txt
├──README.md
├── .gitignore
