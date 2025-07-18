# MLOps Workshop: KI Summer Summit 2025

## 🚀 Von der Idee zum Deployment mit MLflow

Dieses Repository enthält die Materialien für den MLOps-Workshop des KI Summer Summit 2025, geleitet von **Ahmad Salah** und **Kaywan Barazani** von [SprintEins Stuttgart](https://sprint.ins).

### 📚 Inhalt

- **Präsentationen**
  - `ki-summer-summit.pptx` - Hauptpräsentation für den Workshop
  - `MLOps_Einführung_-_KI_Summer_Summit_Stuttgart(1).pptx` - Einführung in MLOps

- **Jupyter Notebooks**
  - `ki-summer-summit.ipynb` - Hauptnotizbuch mit dem vollständigen Workshop
  - `hands-on.ipynb` - Praktische Übungen
  - `hands-on_local_mlflow.ipynb` - Übungen für lokale MLflow-Nutzung
  - `test.ipynb` - Detaillierte MLOps-Hands-On-Anleitung mit dem Iris-Datensatz

### 🎯 Workshop-Ziele

In diesem Workshop lernen die Teilnehmer:

1. Das Problem chaotischer ML-Experimente zu verstehen
2. Die vier Kernkomponenten von MLflow effektiv einzusetzen:
   - **Tracking**: Parameter, Metriken & Artefakte protokollieren
   - **Models**: Modelle in einem Standardformat verpacken
   - **Model Registry**: Modelle zentral verwalten und versionieren
   - **Deployment**: Modelle als Service bereitstellen

3. Einen vollständigen MLOps-Workflow praktisch umzusetzen:
   - Experiment Tracking
   - Modellvergleich und -auswahl
   - Modellregistrierung
   - Deployment als REST-API

### 🛠️ Voraussetzungen

- Python 3.7+
- Jupyter Notebooks
- Installierte Pakete:
  - mlflow
  - scikit-learn
  - pandas
  - matplotlib
  - seaborn

Installation der Pakete:
```bash
pip install mlflow scikit-learn pandas matplotlib seaborn
```

### 🔬 Hands-On Workshop

Die Teilnehmer arbeiten mit dem klassischen Iris-Datensatz und durchlaufen den gesamten MLOps-Workflow:

1. Training eines Random-Forest-Modells ohne MLOps (um das Problem zu demonstrieren)
2. Training mit MLflow Tracking (strukturierter Ansatz)
3. Experimentierphase mit verschiedenen Hyperparametern
4. Auswertung der Ergebnisse in der MLflow UI
5. Registrierung des besten Modells in der Model Registry
6. Bereitstellung des Modells als REST-API

### 🌐 MLflow Server

Während des Workshops wird ein zentraler MLflow-Server verwendet, auf den alle Teilnehmer zugreifen. Nach dem Workshop können die Teilnehmer auch einen lokalen MLflow-Server starten:

```bash
mlflow ui
```

### 📊 Datenset

Wir verwenden den klassischen Iris-Datensatz:
- 150 Blumen
- 4 Merkmale (Kelchblatt-/Blütenblattlänge & -breite)
- 3 Arten (Setosa, Versicolor, Virginica)

### 👨‍💼 Mitwirkende

- **Ahmad Salah** - DevOps/MLOps Engineer @ SprintEins Stuttgart
- **Kaywan Barazani** - DevOps/MLOps Engineer @ SprintEins Stuttgart

### 📞 Kontakt

Für weitere Informationen:
- [SprintEins Stuttgart](https://sprint.ins)
