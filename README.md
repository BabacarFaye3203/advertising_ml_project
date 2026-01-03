Prédiction des Ventes (Advertising Analysis)
Ce projet utilise l'apprentissage automatique (Machine Learning) pour analyser l'impact des dépenses publicitaires sur les ventes. À partir de données historiques d'investissements publicitaires dans différents médias (TV, Radio, Journaux), le modèle prédit le volume des ventes attendu.



📊 Aperçu des Données
Le jeu de données contient les colonnes suivantes :

TV : Budget publicitaire investi à la télévision.

Radio : Budget publicitaire investi à la radio.

Journaux : Budget publicitaire investi dans la presse écrite.

Ventes (Cible) : Le nombre d'unités vendues.



🚀 Fonctionnalités du Projet
Exploration de données (EDA) : Visualisation des relations entre les budgets publicitaires et les ventes à l'aide de matplotlib et seaborn.

Prétraitement : Mise à l'échelle des caractéristiques (Feature Scaling) avec MinMaxScaler.

Modélisation : Utilisation de la Régression Linéaire (LinearRegression) pour modéliser les prédictions.

Évaluation : Mesure de la performance du modèle via les métriques suivantes :

MSRE (Mean Squered Error)

MAPE (Mean Absolute Percentage Error)




📈 Résultats
Après optimisation et feature engineering, le modèle a atteint des performances de haute précision :

MAPE : ~0.059 (soit une erreur moyenne d'environ 6%).

MSE : ~0.00057.




🛠️ Installation et Utilisation
Prérequis
Python 3.12.8

Bibliothèques : pandas, matplotlib, seaborn, scikit-learn

Installation
Bash

git clone https://github.com/BabacarFaye3203/advertising_ml_project.git
cd advertising_ml_project
pip install pandas matplotlib seaborn scikit-learn
Exécution
Ouvrez le fichier advertising.ipynb dans Jupyter Notebook ou VS Code pour reproduire l'analyse.

