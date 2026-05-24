# microfinance-impact-scoring
Analyse d'impact social et modèle de scoring de risque pour un programme de microfinance (400 bénéficiaires). Utilisation de l'ACP, ACM et Régression Logistique.
# 📊 Évaluation d'Impact et Modélisation du Risque (Microfinance)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Complet-green)]()

## Présentation du Projet
Ce projet analyse l'efficacité d'un programme de microfinance portant sur **400 projets**. L'objectif est de mesurer l'impact social (évolution des revenus) et de fournir un outil d'aide à la décision (Scoring de risque) pour sécuriser les futurs octrois de crédits.

## Méthodologie Analytique
Le projet suit une démarche scientifique rigoureuse en 8 étapes :
1. **Nettoyage & Imputation** : Traitement des données manquantes par des méthodes statistiques (Moyennes/Médianes par région et activité).
2. **Analyse Descriptive** : Visualisation des distributions (Âge, Montants, Revenus).
3. **Tests d'Impact** : Validation de la hausse de revenus par **T-test** (Impact significatif de +24%) et **D de Cohen** (Taille d'effet moyenne).
4. **ANOVA & Tukey** : Identification des secteurs d'activité les plus performants (Secteur **Transformation** en tête).
5. **Analyse Multidimensionnelle (ACP)** : Profilage financier des bénéficiaires (découverte du paradoxe de la richesse).
6. **Analyse de Correspondances (ACM)** : Identification des facteurs comportementaux liés au défaut (Tontine, Éducation, Mobile Money).
7. **Modélisation Prédictive** : Comparaison entre **Régression Logistique** et **Random Forest**.
8. **Dashboarding** : Construction d'un score de risque de 0 à 100 et recommandations opérationnelles.

## 📈 Résultats Clés
*   **Impact Social** : Hausse moyenne des revenus de **24%** pour les bénéficiaires.
*   **Facteur Protecteur** : L'éducation (niveau Secondaire) divise le risque de défaut par **2.4**.
*   **Insight Majeur** : Le risque de défaut est décorrélé de la richesse initiale (Axe 1 de l'ACP) mais fortement lié aux habitudes d'épargne (Tontines).

## 📁 Structure du Dépôt
*   `images/` : Contient les visualisations clés (Courbes ROC, Matrices de Confusion, Dashboard d'octroi).
*   `microfinance_analysis_KONATE-Razac.ipynb` : Le code source complet et commenté.
*   `microfinance_axeA.csv` : Le jeu de données utilisé pour l'étude.
*   `TABLEAU_DE_BORD_FINAL_...xlsx` : Le livrable opérationnel pour le bailleur de fonds.

## Outils & Bibliothèques
*   **Traitement** : Pandas, NumPy
*   **Visualisation** : Matplotlib, Seaborn
*   **Statistiques** : Scipy, Statsmodels
*   **Machine Learning** : Scikit-learn, Prince (ACM)

---
**Auteur :** KONATE Razac
*Projet réalisé dans le cadre d'une évaluation de performance de fonds de développement.*
