# Car Sales Dashboard – Power BI 🚗

## Aperçu du dashboard
Ce dashboard interactif Power BI permet de suivre et d’analyser les ventes automobiles simulées à travers deux pages principales : **Overview** et **Details**.  

- La page **Overview** montre les KPIs clés et les tendances globales des ventes.  
- La page **Details** permet d’explorer chaque transaction simulée pour comprendre les performances par concessionnaire, modèle et couleur.  

### Overview
Voici un exemple de la page Overview, avec les principaux indicateurs et graphiques YTD et MTD :  


![Overview](https://github.com/melissa-aliouche/PowerBI-Car-Sales-Dashboard/blob/main/images/overview.PNG)


### Details
La page Details montre les transactions simulées avec tous les détails (modèle, carrosserie, couleur, montant, concessionnaire et date) :  


![Details](https://github.com/melissa-aliouche/PowerBI-Car-Sales-Dashboard/blob/main/images/details.PNG)


---

## Contexte du projet
Ce projet a été réalisé dans le cadre d’un exercice de simulation visant à illustrer la conception d’un tableau de bord analytique sous Power BI.  
Les données utilisées sont fictives et ont été créées uniquement à des fins de démonstration et de visualisation.  

L’objectif principal est de montrer comment Power BI peut être utilisé pour analyser et suivre les ventes automobiles à travers des indicateurs clés et des visualisations interactives.

---

## 🎯 Objectif du projet
Le tableau de bord permet de :  

- Suivre la performance des ventes automobiles simulées.  
- Analyser les tendances mensuelles et annuelles.  
- Identifier les facteurs de performance (région, marque, couleur, style de carrosserie, etc.).  
- Mettre en avant les capacités de modélisation, d’analyse et de visualisation dans Power BI.

---

## ⚙️ Indicateurs clés (KPIs)

### 1. Vue d’ensemble des ventes
- **YTD Total Sales** : ventes cumulées à l’année  
- **MTD Total Sales** : ventes cumulées au mois  
- **YOY Growth** : croissance annuelle simulée des ventes  
- **Écart YTD / PTYD** : comparaison entre la période actuelle et celle de l’année précédente  

### 2. Prix moyen des ventes
- **YTD Average Price** : prix moyen annuel  
- **MTD Average Price** : prix moyen du mois en cours  
- **YOY Growth in Average Price** : évolution annuelle du prix moyen  
- **Écart YTD / PTYD du prix moyen**  

### 3. Volume des voitures vendues
- **YTD Cars Sold** : voitures vendues cette année  
- **MTD Cars Sold** : voitures vendues ce mois-ci  
- **YOY Growth in Cars Sold** : croissance simulée du volume des ventes  
- **Écart YTD / PTYD du nombre de voitures vendues**  

---

## 📊 Visualisations du tableau de bord

### 1. YTD Sales Weekly Trend
Graphique en courbes représentant la tendance hebdomadaire des ventes YTD.

### 2. YTD Total Sales by Body Style
Diagramme circulaire montrant la répartition des ventes par type de carrosserie (SUV, Hatchback, Sedan, Passenger, Hardtop).

### 3. YTD Total Sales by Color
Diagramme circulaire illustrant la contribution des couleurs (Pale White, Black, Red).

### 4. YTD Cars Sold by Dealer Region
Carte géographique interactive affichant les ventes par région de concessionnaire (ex. Austin, Scottsdale, Greenville, etc.).

### 5. Company-Wise Sales Trend
Tableau récapitulatif (grid) présentant la performance de chaque marque (Acura, BMW, Chevrolet, etc.), incluant :  
- Le prix moyen  
- Les ventes totales YTD  
- Le pourcentage du total des ventes  

### 6. Détails des ventes
Tableau détaillé affichant toutes les transactions simulées :  
- Modèle de voiture  
- Type de carrosserie  
- Couleur  
- Montant des ventes  
- Concessionnaire / région  
- Date

---

## 🧭 Fonctionnalités interactives
- Filtres dynamiques par type de carrosserie, nom du concessionnaire, transmission, moteur, etc.  

Voici un exemple d’un filtre appliqué pour le type de carrosserie **Passenger** :  


![Filtre Body Style](https://github.com/melissa-aliouche/PowerBI-Car-Sales-Dashboard/blob/main/images/filtre.PNG)


- Navigation entre les vues **Overview** et **Details** via un menu latéral.  
- Actualisation automatique possible si connecté à une base de données réelle.  

---

## 🧩 Outils et technologies utilisés
- **Power BI Desktop** pour la création du dashboard  
- **Excel** (source de données simulées)  
- **DAX (Data Analysis Expressions)** pour les calculs (YTD, MTD, YOY, différences, etc.)  
- **Visuals Power BI** : cartes, graphiques en ligne, diagrammes circulaires, tableaux  


