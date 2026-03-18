# Analyse Multidimensionnelle de la Pollution (Périgueux)

## Présentation
Étude statistique de la qualité de l'air à Périgueux basée sur des relevés météorologiques et des concentrations de polluants ($O_3, NO, NO_2$). Ce projet vise à comprendre l'influence des facteurs climatiques sur la pollution atmosphérique.

## Méthodologie & Analyses
* **Exploration de données** : Analyse descriptive et traitement des valeurs manquantes.
* **Analyse en Composantes Principales (ACP)** : Réduction de dimension avec `FactoMineR` pour identifier les corrélations entre variables (température, rayonnement, polluants).
* **Modélisation** : Construction d'un modèle de prédiction de l'Ozone ($O_3$) en fonction des conditions météo.
* **Visualisation** : Graphiques avancés avec `ggplot2` et matrices de corrélation.

## Technologies
* **Langage** : R
* **Librairies** : FactoMineR, ggplot2, corrplot, dplyr
