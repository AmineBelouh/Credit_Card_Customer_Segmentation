# Credit_Card_Customer_Segmentation

## Description du projet

Ce projet de **Data Science** a pour objectif d'analyser le comportement des clients utilisant des cartes de crédit et de les **segmenter en différents groupes** selon leurs habitudes financières.

La segmentation est réalisée à l'aide de techniques de **clustering non supervisé**, principalement l’algorithme **K-Means**.
L’objectif est d’identifier des profils de clients afin d’aider à la **prise de décision business** (marketing ciblé, gestion du risque, offres personnalisées).

---

## Dataset

Le dataset utilisé contient des informations sur l'utilisation des cartes de crédit par différents clients, notamment :

* Balance du compte
* Montant des achats
* Avances de cash
* Limite de crédit
* Fréquence des achats
* Paiements effectués
* Nombre de transactions

Ces variables permettent d'analyser le comportement financier des clients.

---

## Fichiers du projet

```
├── CC GENERAL.csv
├── code.ipynb
├── datasetExplination.ipynb
├── whyNotDBSCAN.ipynb
└── presentationProjectAI.pdf
```

### Contenu des fichiers

```code.ipynb``` 
Notebook principal contenant :

* nettoyage des données
* normalisation
* réduction de dimension avec PCA
* clustering avec K-Means
* visualisation des clusters
* interprétation des résultats

```datasetExplination.ipynb```   
Explication des variables du dataset et de leur signification.

```whyNotDBSCAN.ipynb```   
Analyse expliquant pourquoi l’algorithme **DBSCAN** n’a pas été retenu pour ce projet et comparaison avec **K-Means**.

```presentationProjectAI.pdf```   
Présentation du projet, de la méthodologie et des résultats obtenus.

---

## Méthodologie

Les principales étapes du projet sont :

1. Exploration du dataset
2. Nettoyage des données
3. Normalisation des variables
4. Réduction de dimension avec PCA
5. Clustering avec K-Means
6. Visualisation et interprétation des clusters

---

## Objectifs du projet

* Comprendre le comportement des clients
* Identifier différents profils d’utilisation des cartes de crédit
* Aider à la prise de décision pour des stratégies marketing

---

## Technologies utilisées

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Auteur

Projet réalisé dans le cadre d'un projet d'analyse de données et de machine learning.
