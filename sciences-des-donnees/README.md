# Sciences des données (Python)

Travaux pratiques du M2 Mathématiques : Science des données, Université Sorbonne Paris Nord, 2026-2027.
Les énoncés appartiennent à l'enseignant, ce dépôt contient uniquement mon code et mes analyses.

## Contenu

- **[TP1](TP1/TP1.ipynb)** : introduction à scikit-learn
  - importation des bibliothèques
  - manipulation d'un jeu de données
  - téléchargement et importation de données
  - génération de données et affichage

- **[TP2](TP2/TP2.ipynb)** : visualisation de données
  - normalisation de données (standardisation et MinMax)
  - visualisation de données
  - réduction de dimension : PCA et LDA

- **[TP3](TP3/TP3.ipynb)** : descente de gradient
  - descente de gradient en dimension 1
  - descente de gradient pour la régression linéaire

- **[TP4](TP4/TP4.ipynb)** : classification
  - plus proches voisins
  - classifieur bayésien naïf

- **[TP5](TP5/TP5.ipynb)** : analyse de jeux de données
  - description et visualisation des données
  - K-means
  - comparaison de plusieurs algorithmes de clustering
  - comparaison de plusieurs algorithmes de classification

## Lancer le code

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r ../requirements.txt
jupyter notebook
```