# Databricks-Accidents-Project
Bonjour sur ce projet je vais vous présenter mon projet d'examen 

nos sources de données ont été des tutorile d'ylies talbi et enfin des echantillon de données sur des accidents 
: veicule 
: vic
: lieux
: carac
![image](https://github.com/soleymanevienne/Databricks-Accidents-Project/assets/123655159/f03e09f9-6dbc-4dce-aabc-c313d244bc8c)
: Assigner un rôle à un utilisateur
: Tutoriel d'Ilyes Talbi de la revue IA
: Limitation des regions dans Databricks
: Création d'un token avec Databricks
: Création d'un endpoint avec Databricks
: Markdown Cheat Sheet
: GitHub Get Started
: Plus d'info sur la commande GridSearchCV
: https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal?tabs=delegate-condition

dans ce respository je vous vous présenter nnotre chargement de données fait sur databricks avec les différents importations nescessaires : 

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

from sklearn.preprocessing import normalize

from sklearn.cluster import KMeans
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import GradientBoostingClassifier
from sklearn.model_selection import train_test_split, GridSearchCV

from sklearn.metrics import accuracy_score, confusion_matrix
from sklearn.metrics import recall_score, f1_score

enfin nous avons décider dans ce projet de me concencentrer sur le modele KNN car grace a ces plusieurs écahntillons creer et sur lesquelle j'ai du baisser leur nombre d'écahntillon de ce fait c'est l'abre de decison qui a le plus de résulat coerahent aveec une précision et f1 score de : 
RandomForestClassifier - Accuracy: 0.9983326822854639
RandomForestClassifier - F1-Score: 0.9982568746715941
DecisionTreeClassifier - Accuracy: 0.9983136272258691
DecisionTreeClassifier - F1-Score: 0.9981669809733357
'n_neighbors' is not present in best_params.

Performance Comparison:
RandomForestClassifier - Accuracy: 0.9983326822854639
DecisionTreeClassifier - Accuracy: 0.9983136272258691

RandomForestClassifier - F1-Score: 0.9982568746715941
DecisionTreeClassifier - F1-Score: 0.9981669809733357
