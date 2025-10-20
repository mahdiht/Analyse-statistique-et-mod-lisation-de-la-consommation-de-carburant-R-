# 🚗 Analyse statistique et modélisation de la consommation de carburant (R)

## 📘 Description du projet
Ce projet a pour objectif d’étudier la **consommation de carburant de différents véhicules** à partir de leurs caractéristiques techniques, en utilisant des **méthodes statistiques classiques et multivariées**.  
L’analyse porte sur la variable **mpg (miles per gallon)** et vise à modéliser la consommation en fonction de plusieurs variables explicatives, puis à compléter cette modélisation par une **Analyse en Composantes Principales (ACP)**.

## 🎯 Objectifs
- Explorer et visualiser les relations entre les variables du jeu de données.
- Construire un **modèle de régression multiple** pour expliquer la consommation.
- Sélectionner les variables les plus pertinentes et comparer les modèles obtenus.
- Étudier la **robustesse du modèle** face à des individus extrêmes.
- Réaliser une **ACP** pour réduire la dimension du jeu de données et visualiser les corrélations.
- Comparer la **régression classique** et la **régression sur composantes principales (PCR)**.
- Discuter les **avantages et limites** des approches utilisées.

## 🧠 Méthodologie
Le projet suit une démarche complète d’analyse de données :
1. **Étude descriptive** : visualisation des distributions, corrélations et tendances globales.
2. **Régression multiple initiale**, puis **sélection de variables** basée sur les corrélations et les performances.
3. **Analyse d’un individu extrême** pour tester la stabilité du modèle.
4. **Analyse en Composantes Principales (ACP)** avec visualisation des individus et des variables.
5. **Régression sur ACP** et **comparaison** avec le modèle classique.
6. **Discussion** sur la qualité de la modélisation et l’interprétation des résultats.

## 🧰 Outils et packages utilisés
- **Langage** : R  
- **Bibliothèques principales** :  
  `tidyverse`, `ggplot2`, `stats`, `FactoMineR`, `factoextra`, `broom`, `knitr`, `rmarkdown`

## 📊 Jeu de données
Le projet utilise le jeu de données **mtcars**, intégré à R, qui contient les caractéristiques techniques de 32 véhicules :  
- Cylindrée, puissance, poids, rapport poids/puissance, etc.  
- Variable cible : **mpg (miles per gallon)** – indicateur de la consommation de carburant.

## 📈 Résultats
- Le modèle réduit permet d’obtenir une meilleure interprétation des variables influençant la consommation.  
- L’ACP met en évidence des corrélations fortes entre certaines variables mécaniques.  
- La régression sur composantes principales (PCR) offre une alternative robuste face à la multicolinéarité.  

## 🔍 Conclusion
Ce projet illustre la complémentarité entre **modélisation statistique** et **analyse multivariée** pour comprendre les déterminants de la consommation de carburant.  
L’utilisation de **RMarkdown** garantit la **traçabilité**, la **reproductibilité** et une **présentation claire** des analyses.

---

### 👨‍💻 Auteur
**Mahdi HADJ TAIEB**  
Étudiant en Master 2 Data Science – École Polytechnique / ENSTA Paris  
📧 mahdi.hadj-taieb@polytechnique.edu  

