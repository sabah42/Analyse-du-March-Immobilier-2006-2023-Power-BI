# Analyse du Marché Immobilier (2006-2023) - PowerBI 
## Table des matières
- [Description du projet](#description-du-projet)
- [Contenu du projet](#contenu-du-projet)
- [ Objectifs du projet](#objectifs-du-projet)
- [Étapes principales](#étapes-principales)
 -[Nettoyage des données (Power Query)](#nettoyage-des-données-(power-query))
 -[Modélisation (DAX)](#modélisation-(DAX))
 -[Visualisations](#visualisations)
- [ Principaux insights](#principaux-insights)
- [Recommandations](#recommandations)
- [Compétences utilisées](#compétences-utilisées)
##  Description du projet
Ce projet Power BI analyse l’évolution du marché immobilier entre 2006 et 2023 à partir des ventes de biens immobiliers (dataset “Real Estate Sales” – data.gov).

L’objectif du projet était de comprendre les tendances du chiffre d’affaires, les comportements de vente, ainsi que la répartition géographique des transactions. 
## Contenu du projet
**Data/**  
Données utilisées pour l’analyse (source : data.gov).

**Rapport Power BI (PDF)/**
Aperçu complet du tableau de bord

**Fichier PBIX /**
Version modifiable du rapport

**Images/**
Captures d’écran du tableau de bord

## Objectifs du projet

- Étudier l’évolution des ventes et du chiffre d’affaires immobilier.
- Analyser les différences entre les types de biens (résidentiel, commercial, etc.).
- Identifier les villes les plus dynamiques.
- Comprendre la saisonnalité et les tendances avant/après 2020.
## Étapes principales
### Nettoyage des données (Power Query)

- Suppression ou correction des valeurs manquantes
- Regroupement des anciens types résidentiels (Single Family, Two Family…)
- Création de colonnes :
   - Année de vente
   - Durée sur le marché
   - Période ("Avant 2020" / "Après 2020")
- Suppression des doublons
- Correction des problèmes de géolocalisation

 ### Modélisation (DAX)

- Création d’une table calendrier
- Mesures :
  - Chiffre d’affaires
  - Nombre de ventes
  - Ratio de vente
  - Croissance d’une année à l’autre
- Table indépendante pour afficher toutes les années

  ### Visualisations

- Page 1 : Analyse 2020–2023 (marché diversifié)
- Page 2 : Analyse 2006–2023 (marché résidentiel)
- KPI : CA, ventes, ratio, valeur estimée
- Graphiques : évolution du chiffre d'affaires, répartition, cartes géographiques, top ventes

## Principaux insights

- Pic du marché en 2021, puis baisse dès 2023.
- La majorité du chiffre d’affaires provient des biens résidentiels.
- Les biens se vendent en moyenne en moins d’un an.
- Forte saisonnalité : hausse des ventes en été.
- Greenwich est la ville la plus rentable.

## Recommandations
Sur la base de cette analyse, voici quelques recommandations que j’ai formulées :

- Investir dans les biens résidentiels : ce segment génère la majorité du chiffre d’affaires et reste le plus stable.
- Cibler les villes les plus performantes, notamment Greenwich, qui domine le marché sur toute la période.
- Profiter des périodes hautes, comme l’été, pour lancer ou renforcer les opérations commerciales.
- Surveiller l’évolution du marché post-2020, car la diversification peut modifier les tendances futures.
- Analyser régulièrement les types de biens pour voir lesquels gagnent ou perdent en attractivité.

## Compétences utilisées

- Power BI Desktop
- Power Query (nettoyage et transformation)
- DAX (mesures et calculs avancés)
- Modélisation relationnelle
- Storytelling visuel & KPI interactifs


