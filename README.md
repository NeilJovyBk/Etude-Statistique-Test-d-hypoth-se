# 📊 Comprendre les données clients par la statistique

## ✍️ Auteur  
**Minko NEIL-JOVY**

---

## 📌 Présentation

Ce projet propose une **étude statistique** des relations entre différentes **variables qualitatives, quantitatives et ordinales** issues de plusieurs jeux de données.  
Il s’appuie sur des méthodes statistiques rigoureuses, des visualisations (`ggplot2`) et des tests d’hypothèses pour évaluer les liens et corrélations entre variables.

---

## 🧰 Fonctionnalités principales

L’étude comprend plusieurs axes :

1. **Variables Qualitatives vs Qualitatives (Quali-Quali)**  
   - Tableaux de contingence  
   - Graphiques empilés  
   - Test du Chi²  
   - Coefficient de Cramer (V)  
   - *Exemple : lien entre tranche d’âge et plateforme de réseau social*

2. **Variables Quantitatives vs Quantitatives (Quanti-Quanti)**  
   - Nuages de points  
   - Corrélations de Pearson, Spearman, Kendall  
   - Tests de significativité  
   - *Exemple : relation entre revenus et dépenses publicitaires*

3. **Variables Ordinales vs Ordinales**  
   - Test du Chi²  
   - Corrélations ordinales (Spearman, Kendall)  
   - V de Cramer  
   - *Exemple : satisfaction client vs probabilité de recommandation*

4. **Variables Qualitatives vs Quantitatives (Quanti-Quali)**  
   - Boxplots  
   - Tests de Student, Welch, Wilcoxon, ANOVA, Kruskal-Wallis  
   - *Exemple : différence de montant d’achat selon le groupe marketing*

---

## 📊 Jeux de données utilisés

- `base_de_donnees_media_sociaux.csv`  
- `data_marketing.csv`  
- `recommandation_satisfaction.csv`  
- `donnees_marketing.csv`  
- `donnees_marketing_3_groupes.csv`

---

## 📦 Librairies R utilisées

- `ggplot2` – Visualisation des données  
- `vcd` – Statistiques d’association (Chi², Cramer’s V)  
- `car` – Test de Levene  
- `tidyverse` – Manipulation et traitement de données

---

## 📁 Structure du projet

- `Quali-Quali/` → Tests d’indépendance, visualisations croisées  
- `Quanti-Quanti/` → Corrélations, nuages de points  
- `Ordinal-Ordinal/` → Tests Chi² et corrélations ordinales  
- `Quali-Quanti/` → Comparaison de moyennes par groupes (paramétriques et non-paramétriques)

---
