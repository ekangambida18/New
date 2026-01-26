# Analyse Statistique de Facteurs de Risque en Santé

##  I-Contexte du projet

Ce projet présente une **analyse statistique exploratoire** réalisée sur une **base de données simulée**, dans un objectif pédagogique et académique. Il vise à illustrer l’application de méthodes classiques de **biostatistique** à des variables couramment utilisées en épidémiologie et en santé publique.

Le projet s’inscrit dans une démarche de **portfolio GitHub**, mettant en évidence la capacité à structurer une analyse,poser des hypothèses,choisir des tests statistiques appropriés et interpréter les résultats de manière rigoureuse.

---

##  II-Description des données

* **Type de données** : données simulées
* **Taille de l’échantillon** : 200 individus

### Variables étudiées

| Variable             | Type                       | Description                     |
| -------------------- | -------------------------- | ------------------------------- |
| `age`                | Quantitative               | Âge              |
| `sexe`               | Qualitative                | Sexe                 |
| `imc`                | Quantitative/ Catégorisée              | Indice de masse corporelle      |
| `cholesterol`        | Quantitative / Catégorisée | Taux de cholestérol             |
| `diabete`            | Qualitative binaire        | Présence ou absence de diabète  |
| `activite_physique`  | Qualitative                | Niveau d’activité physique      |
| `tension_arterielle` | Quantitative / Catégorisée              | Valeur de la tension artérielle |

Les données ne proviennent pas de patients réels et ne permettent aucune inférence clinique.

---

## III-Méthodologie statistique

###  1-Analyse descriptive

* Statistiques descriptives (moyennes, médianes, dispersions)
* Tableaux de fréquences pour les variables qualitatives
* Visualisations exploratoires

###  2-Analyses inférentielles

Les méthodes statistiques suivantes ont été appliquées selon la nature des variables et les conditions de validité :

* **Corrélation de Pearson** : Etude de la relation entre le Cholesterol et la tension artérielle à traver un exploration de relations linéaires
* **Corrélation de Spearman** : exploration des relations monotones en absence de linéarité
* **Analyse de variance (ANOVA)** : Etude de la realtion entre l'âge et le cholestérol à travers une comparaison de la moyenne d’âge entre groupes de cholestérol
* **Test du Chi-carré** : Etude de la relation entre l'activité physique et l'imc à travers une comparaison des pourcentages
* **Test de Student** : Etude de la relation entre le diabète et la tension artérielle à travers une comparaison des moyennes de la tension artérielle dans les groupes de diabète

Les conditions d’application des tests (normalité, homogénéité des variances, effectifs) ont été vérifiées avant interprétation.

---

## IV-Résultats Principaux

* Les analyses descriptives ont permis de caractériser la population simulée.
* Les tests de corrélation (Pearson et Spearman) n’ont pas mis en évidence de relation statistiquement significative entre les variables quantitatives étudiées.
* Les comparaisons de groupes (ANOVA, test de Student) n’ont montré **aucune différence statistiquement significative**.
* Les tests d’association entre variables qualitatives (Chi-carré) n’ont révélé **aucune association significative**.

---

## V-Interprétation

Les résultats suggèrent l’absence d’association statistiquement significative entre les variables étudiées dans cette base de données simulée. Cette absence de significativité ne permet pas de conclure à une absence de relation dans un contexte réel, mais reflète les caractéristiques et les limites inhérentes aux données simulées.

---

## VI-Limites

* Données entièrement simulées
* Absence de lien causal
* Résultats non généralisables à une population réelle
* Objectif exclusivement pédagogique

---

## VII- Outils utilisés

* **Python**
* Bibliothèques :

  * `pandas`
  * `numpy`
  * `scipy`
  * `matplotlib` / `seaborn`

---

## 👤 Auteur

**Ekanga Mbida Saint Wilfried**
Étudiant en **microbiologie médicale** et **biostatistique**
En cours de certification *Data Analyst Associate*

---

##  Licence

Projet à visée pédagogique et académique.
