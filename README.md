# 📊 Power BI Complaints Dashboard

## 🎯 À propos du projet
J’ai réalisé ce petit projet Power BI afin de simuler un suivi de performance des plaintes dans un contexte organisationnel.

L’objectif était de reproduire un cas concret de reddition de comptes, avec des indicateurs simples mais pertinents pour la prise de décision.

---

## 🧱 Données
Le jeu de données représente des plaintes clients avec des informations comme :
- la date
- la région
- le type de produit
- le statut (traité ou en cours)
- le délai de traitement

Les données ont été générées pour créer un scénario réaliste d’analyse.

---

## ⚙️ Préparation des données (Power Query)
J’ai utilisé Power Query pour :
- ajouter des colonnes comme le mois et l’année
- créer une catégorie de performance basée sur le délai :
  - Rapide (≤ 7 jours)
  - Moyen (8 à 14 jours)
  - Lent (> 14 jours)
- nettoyer et structurer les données

---

## 🧮 Indicateurs (DAX)
J’ai ensuite créé quelques indicateurs clés :
- le nombre total de plaintes
- le nombre de plaintes traitées
- le taux de traitement
- le délai moyen

Ces indicateurs permettent d’avoir une vision rapide de la performance.

---

## 📊 Tableau de bord
Le dashboard permet :
- de visualiser les KPI principaux
- de suivre l’évolution des plaintes dans le temps
- d’analyser les données par région
- d’évaluer la performance de traitement
- d’interagir avec les données grâce à des filtres

---

## 🛠️ Outils utilisés
- Power BI
- DAX
- Power Query

---

## 🚀 Pourquoi ce projet
Ce projet m’a permis de mettre en pratique :
- la transformation de données
- la création d’indicateurs
- la conception d’un tableau de bord orienté utilisateur
