# nba-prediction-ml
 Projet Machine Learning pour prédire le gagnant NBA

## Source des Données : 
https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats?select=End+of+Season+Teams.csv 

## Structure du Projet

projet_nba/
├── data/                  # Données brutes et traitées
│   ├── raw/               # Données brutes collectées
│   ├── processed/         # Données nettoyées/prêtes pour le ML
│   └── external/          # Données complémentaires (scouting, historiques)
├── notebooks/             # Notebooks Jupyter pour l'analyse exploratoire
├── src/                   # Code source du projet
│   ├── data/              # Scripts de traitement des données
│   ├── models/            # Scripts d'entraînement et de prédiction des modèles
│   ├── features/          # Scripts de feature engineering
│   └── visualization/     # Scripts de visualisation des données
├── tests/                 # Tests unitaires et d'intégration
├── .github/workflows/     # Configuration CI/CD (GitHub Actions)
├── .gitignore             # Fichiers à ignorer par Git
├── requirements.txt       # Dépendances Python
└── README.md              # Documentation du projet
