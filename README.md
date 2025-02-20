# Ensemble Learning (Apprentissage ensembliste)

## Description
Ce projet explore l'apprentissage ensembliste appliqué à la classification d'images de voitures et de bateaux à partir de la base de données **cordelDB**. Les caractéristiques des images ont été extraites en utilisant l'architecture **VGG16** et plusieurs modèles de Machine Learning ont été testés.

## Auteur
**Mohamed EL AOUMARI**  
Email : mohammedelaoumari@gmail.com

## Prérequis
Avant d'exécuter le projet, assurez-vous d'avoir installé les bibliothèques nécessaires.

```bash
pip install -r requirements.txt
```

## Installation et Exécution
1. Clonez ce dépôt :
   ```bash
   git clone <URL_DU_DEPOT>
   ```
2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
3. Ouvrez le fichier `main.ipynb` avec Jupyter Notebook :
   ```bash
   jupyter notebook main.ipynb
   ```
4. Exécutez les cellules dans l'ordre pour importer les données, entraîner les modèles et visualiser les résultats.

## Détails du Projet
- **Données utilisées** : Images issues de la base cordelDB (490 images, classes : voiture & bateau).
- **Extraction des caractéristiques** : Utilisation de **VGG16** pour obtenir une base de 1000 caractéristiques par image.
- **Modèles testés** :
  - **SVM (Support Vector Machine)** avec optimisation des hyperparamètres (C, kernel)
  - **KNN (K-Nearest Neighbors)**
  - **Decision Tree**
- **Visualisation des performances** : Courbes de précision pour chaque modèle.

## Exemples de Code
Séparation des données :
```python
X_train, X_test, y_train, y_test = train_test_split(X, Y, test_size=0.2, random_state=42)
print("X_train:", X_train.shape, "X_test:", X_test.shape)
```


## Contribution
Toute contribution est la bienvenue. Vous pouvez soumettre une pull request ou contacter l'auteur par email.
