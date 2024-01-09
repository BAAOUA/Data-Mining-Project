# Data-Mining-Project

## Dataset
Données sur les trajets en taxi à New York - Données publiques de Google
Cet ensemble de données est un sous-ensemble de l'ensemble de données publiques Google BigQuery - Nyc yellow taxi trips contenant **10 000 000** lignes de données aléatoires. Cet ensemble de données a été extrait et téléchargé dans le but d'expérimenter et d'apprendre des modèles de régression pour la prédiction des prix. Il y a également beaucoup de place pour le nettoyage des données, les valeurs aberrantes dans les données, et beaucoup de données avec lesquelles travailler pour une formation, des tests et une validation de modèles plus réalistes.

Les données sont accessibles au public à l'adresse suivante : https://www.kaggle.com/datasets/neilclack/nyc-taxi-trip-data-google-public-data


# Présentation des Algorithmes de Machine Learning : LightGBM, CatBoost et XGBoost
Les algorithmes de gradient boosting, tels que LightGBM, CatBoost et XGBoost, sont des techniques avancées de machine learning particulièrement efficaces pour la modélisation prédictive. Chacun de ces algorithmes présente des caractéristiques uniques et des avantages spécifiques.
## **LightGBM :**
**Light Gradient Boosting Machine (LightGBM)** est un framework de boosting basé sur l'histogramme, développé par Microsoft. Ses principales caractéristiques incluent :
*	Optimisation de l'histogramme : LightGBM utilise un découpage en histogramme pour accélérer le processus de construction de l'arbre, ce qui le rend plus rapide que les méthodes traditionnelles.
*	Parallel Learning : La capacité de LightGBM à effectuer un apprentissage en parallèle rend l'algorithme particulièrement efficace pour les ensembles de données volumineux.
*	Gestion des valeurs manquantes : LightGBM gère efficacement les valeurs manquantes sans avoir besoin de les prétraiter.
CatBoost :
CatBoost est un algorithme de gradient boosting développé par Yandex, conçu pour fonctionner de manière optimale avec des données catégorielles. Ses principales caractéristiques sont :
*	Traitement automatique des données catégorielles : CatBoost peut traiter automatiquement les variables catégorielles sans nécessiter un encodage préalable.
•	Optimisation de la profondeur des arbres : CatBoost utilise une stratégie d'optimisation automatique de la profondeur des arbres, ce qui facilite son utilisation sans trop de paramétrage.
•	Robustesse au surajustement : CatBoost intègre des mécanismes pour lutter contre le surajustement, ce qui en fait un choix robuste pour divers scénarios.
XGBoost :
Extreme Gradient Boosting (XGBoost) est un algorithme de boosting largement utilisé et maintenu par la communauté open source. Ses principales caractéristiques comprennent :
•	Régularisation intégrée : XGBoost intègre des techniques de régularisation L1 et L2 pour éviter le surajustement.
•	Système de cartes d'arbres : XGBoost utilise un système de cartes d'arbres pour améliorer la performance en permettant la parallélisation du processus d'apprentissage.
•	Gestion des données manquantes : XGBoost gère efficacement les valeurs manquantes, ce qui facilite le travail avec des ensembles de données incomplets.
Comparaison et Choix :
•	Performance : Les performances peuvent varier en fonction des données spécifiques, mais en général, ces algorithmes offrent des performances élevées.
•	Gestion des données catégorielles : CatBoost excelle dans le traitement des variables catégorielles, tandis que LightGBM et XGBoost nécessitent souvent un prétraitement.
•	Vitesse : LightGBM est réputé pour sa vitesse, ce qui le rend idéal pour les ensembles de données volumineux. CatBoost et XGBoost sont également rapides, mais peuvent nécessiter un peu plus de temps dans certains cas.
•	Facilité d'utilisation : CatBoost est souvent considéré comme plus convivial en raison de son traitement automatique des variables catégorielles et de ses paramètres par défaut bien réglés.
