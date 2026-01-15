## 📱 Analyse de Performance : Jeux Mobiles & Monétisation In-App (JESA Games)
 
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)

## 📋 Contexte du projet
 
JESA Games, éditeur de jeux sur terminaux mobiles, a lancé une nouvelle série de produits. L'entreprise dispose de données brutes sur les premiers mois d'exploitation mais manque de visibilité sur ses leviers de croissance.
 
**L'objectif de cette mission** : Transformer les données transactionnelles et comportementales en un tableau de bord décisionnel pour orienter la stratégie commerciale.
 
**Enjeux clés :**
* Identifier les segments de joueurs les plus rentables (Whales vs Free-to-play).
* Analyser la performance géographique des ventes.
* Fournir des recommandations basées sur la data pour augmenter le chiffre d'affaires.
 
## 🛠️ Stack Technique & Méthodologie
 
Ce projet met en œuvre une chaîne de traitement complète (ETL & Visualisation) :
 
* **Outils :** Microsoft Power BI (Desktop), Excel.
* **Data Cleaning (Power Query) :** Nettoyage des tables `TIC`, `GEO` et des données d'achats brutes. Normalisation des formats et gestion des valeurs manquantes.
* **Modélisation de données :** Création d'un schéma en étoile (Star Schema) pour optimiser les performances d'analyse.
* **Calculs (DAX) :** Création de mesures personnalisées pour les KPIs (Chiffre d'affaires total, Panier moyen, Taux de conversion).
 
## 📊 Fonctionnalités du Dashboard
 
Le rapport Power BI (`Mobile_GameInAppPurchase25_vDef.pbix`) permet d'explorer :
 
1.  **Vue d'ensemble (Executive Summary) :** KPIs macro-économiques (CA, Volume de joueurs).
2.  **Analyse Temporelle :** Évolution des téléchargements et des achats mois par mois.
3.  **Segmentation :** Répartition des revenus par type d'achat (Consommables vs Unlockables).
4.  **Cartographie :** Analyse de la pénétration par pays/région.
 
## 🚀 Recommandations Stratégiques
 
Suite à l'analyse des données, les axes de croissance suivants ont été identifiés :
> *Note : Ici, vous pouvez résumer en une phrase une conclusion forte de votre analyse, par exemple : "Le marché X présente un fort taux de conversion mais un faible volume d'acquisition, suggérant un besoin d'augmentation du budget marketing sur cette zone."*
 
## 📂 Structure du Répertoire
 
```text
├── Data/                   # Données sources (CSV, XLSX)
│   ├── Table_Mobile_GameInAppPurchase.csv
│   ├── Table_TIC.xlsx
│   └── Table_GEO.xlsx
├── Reports/                # Rapports finaux
│   ├── Rapport_Mobile_Game_2025.pdf
│   └── Presentation_Strategique.pdf
├── Dashboard_vDef.pbix     # Fichier source Power BI
└── README.md
