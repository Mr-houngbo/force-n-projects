#  Laptop Price Prediction

Projet de Data Science visant à prédire le prix de vente de laptops à partir de leurs caractéristiques techniques.

##  Contenu

- `NOTRE_PRODUCTION_Projet_1_mentorat_FORCE_N.ipynb` : notebook complet du projet.
- `requirements.txt` : dépendances à installer.
- `README.md` : ce fichier.

##  Objectif

Utiliser un jeu de données de configurations de laptops pour :

- Nettoyer et préparer les données
- Réaliser des visualisations exploratoires
- Extraire des caractéristiques pertinentes
- Construire un modèle de prédiction de prix

##  Technologies utilisées

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- gdown

##  Modèle

Modèle utilisé : `LinearRegression` (scikit-learn)  
Évaluation : MAE, RMSE, R²

##  Exécution

1. Clone le repo :
   ```bash
   git clone <url-du-repo>
   cd <nom-du-dossier>
2. Crée un environnement :
   ```bash
   python -m venv venv
   source venv/bin/activate  # ou venv\Scripts\activate sous Windows  
3. Installe les dépendances :
   ```bash
   pip install -r requirements.txt
4. Lance le notebook :
   ```bash
   jupyter notebook
