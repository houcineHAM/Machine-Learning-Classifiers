# Machine Learning Classifiers

## 📝 Description  
Ce projet regroupe trois classifieurs de machine learning :  
- **Arbre de Décision** : Modèle basé sur des règles de décision sous forme d’arbre, permettant de classifier les données en suivant des branches logiques.  
- **k-Plus Proches Voisins (K-Nearest Neighbours, KNN)** : Algorithme qui classe un point en fonction des classes majoritaires parmi ses k plus proches voisins.  
- **Naive Bayes** : Modèle probabiliste basé sur le théorème de Bayes, supposant l’indépendance entre les caractéristiques.  

Chaque algorithme est implémenté dans un fichier distinct, avec un jeu de données pour entraîner et évaluer les modèles.  

---

## 📂 Contenu du projet  
- **decision_tree_classifier.py** : Implémentation du classifieur basé sur l'Arbre de Décision.  
- **k_nearest_neighbours_classifier.ipynb** : Implémentation du classifieur K-Nearest Neighbours.  
- **naive_bayes_classifier.ipynb** : Implémentation du classifieur Naive Bayes.  
- **car_evaluation.csv** : Jeu de données utilisé pour le Naive Bayes.  

---

## ⚙️ Prérequis  
- Python 3.x  
- Bibliothèques nécessaires :  
  - numpy  
  - pandas  
  - sklearn  
  - matplotlib (pour la visualisation)  

Pour installer les dépendances :  
```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## 🚀 Utilisation  

1. **Arbre de Décision**  
   - Exécute le script principal :  
     ```bash
     python decision_tree_classifier.py
     ```
   - Analyse les résultats affichés :  
     - Visualisation de l’arbre de décision.  
     - Rapport de classification et matrice de confusion pour évaluer les performances.  

2. **K-Nearest Neighbours**  
   - Ouvre le notebook :  
     ```bash
     jupyter notebook k_nearest_neighbours_classifier.ipynb
     ```
   - Suis les étapes :  
     - Chargement des données.  
     - Entraînement du modèle avec différents k.  
     - Évaluation avec la matrice de confusion et la courbe des erreurs en fonction de k.  

3. **Naive Bayes**  
   - Ouvre le notebook :  
     ```bash
     jupyter notebook naive_bayes_classifier.ipynb
     ```
   - Suis les étapes :  
     - Chargement du fichier **car_evaluation.csv**.  
     - Prétraitement des données.  
     - Entraînement du modèle Naive Bayes.  
     - Visualisation des résultats : score d’exactitude, matrice de confusion, et analyse des erreurs.  

---

## 📊 Résultats  
Chaque modèle est évalué en utilisant des métriques comme :  
- La précision (accuracy).  
- La matrice de confusion.  
- Le rapport de classification.  

Les résultats permettent de comparer les performances des trois algorithmes sur le même jeu de données.  

---



