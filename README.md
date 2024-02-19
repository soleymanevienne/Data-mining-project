### Projet Analyse des Accidents de la Route

Bienvenue dans la documentation de mon projet d'analyse des accidents de la route.

## Sources de données

Pour ce projet, j'ai utilisé les données provenant de plusieurs sources :

- **Véhicules (veicule)**
- **Victimes (vic)**
- **Lieux (lieux)**
- **Caractéristiques (carac)**

J'ai également consulté plusieurs tutoriels pour m'aider dans mon travail :

- **Assigner un rôle à un utilisateur**
- **Tutoriel d'Ilyes Talbi sur la revue IA**
- **Limitation des régions dans Databricks**
- **Création d'un token avec Databricks**
- **Création d'un endpoint avec Databricks**
- **Markdown Cheat Sheet**
- **GitHub Get Started**
- **Plus d'informations sur la commande GridSearchCV**
-  [affectations de rôle](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal?tabs=delegate-condition).

## Chargement des données

J'ai utilisé Python avec les bibliothèques suivantes pour charger et prétraiter les données :

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

from sklearn.preprocessing import normalize
from sklearn.cluster import KMeans
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.metrics import accuracy_score, confusion_matrix, recall_score, f1_score
```

## Analyse et Modélisation

Après avoir exploré les données, j'ai choisi le modèle d'arbre de décision (DecisionTreeClassifier) pour plusieurs raisons. J'ai créé plusieurs échantillons de données sur lesquels j'ai dû réduire le nombre d'échantillons. J'ai observé que l'arbre de décision présentait des performances cohérentes avec une précision et un F1-score élevés :

### Performances du modèle RandomForestClassifier
- Accuracy: 0.9983
- F1-Score: 0.9983

### Performances du modèle DecisionTreeClassifier
- Accuracy: 0.9983
- F1-Score: 0.9982

### Comparaison des performances
- RandomForestClassifier vs DecisionTreeClassifier :
  - Accuracy: 0.9983 vs 0.9983
  - F1-Score: 0.9983 vs 0.9982

## Conclusion

J'ai choisi le modèle d'arbre de décision (DecisionTreeClassifier) pour sa légère amélioration du F1-score.

![Visualisation](https://github.com/soleymanevienne/Databricks-Accidents-Project/assets/123655159/f677fff4-c8a8-4ba5-a635-e15182b2fd37)

Cette documentation fournit une vue d'ensemble de mon projet, je vous invite à visualiser mon groupe de ressource sur azure et mon databricks par la suite 
