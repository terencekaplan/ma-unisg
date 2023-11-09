# Maschinelle Lerntechniken zur Erkennung verdächtiger Finanztransaktionen

Dieses Repository enthält alle Jupyter-Notebooks für die Masterarbeit: "Maschinelle Lerntechniken zur Erkennung verdächtiger Finanztransaktionen: Eine ökonomische Analyse am Beispiel eines synthetischen Datensatzes der IBM".

# Inhalt der Repositorys

- feature_creation.ipynb: Dieses Notebook beinhaltet den Programmcode zur Beschreibung des Datensatzes sowie den vollständigen Code zur Erstellung aller weiteren Features.
- selection_preprocessing.ipynb: In diesem Notebook findet sich der Code für die Datenmanipulationen. Weiter ent-hält das Notebook den Code sowie Darstellungen für den RF, welcher zur Selektion der Variablen dient. Auch die Vorbehandlungen der Daten sind hier ausgeführt.
- model_comparison.ipynb: Das Notebook beginnt mit der Analyse der selektierten Variablen. Auch hier wird die Vorbehandlung der Daten wiederholt, bevor die Modelle trainiert werden. Abgerundet wird das Notebook mit den Resultaten.
- sensitivity_analysis.ipynb: Dieses Notebook bezeichnet analog den vorherigen Notebooks sämtliche Schritte der Datapipeline. Dabei werden im Vorfeld aber jene Transaktionen aus dem vollständigen Datensatz herausgefiltert, bei welchen die Bank 10 beteiligt ist.

# Verwendete Daten

Auf Kaggle lässt sich der synthetisierte Datensatz von Erik Altman (IBM) herunterladen. Der folgende Link verweist zur direkten Internetseite: https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml

Auf der entsprechenden Seite werden unterschiedliche Datensätze gelistet. Diese Arbeit verwendet die bereitgestellte CSV-Datei: «HI-Small_Trans.csv». Der Datensatz wurde am 28. Februar 2023 abgerufen.

