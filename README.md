☕ Dashboard Ventes de Café – Excel
📌 Contexte du projet

Ce projet simule l’analyse des ventes d’une entreprise virtuelle spécialisée dans la vente de grains de café.

Les données utilisées représentent :

des commandes clients

des informations produits (type de café, taille, prix, profit)

des données clients (pays, fidélité, coordonnées)

Les ventes concernent trois pays :

États-Unis

Irlande

Royaume-Uni

Les données sont réparties sur plusieurs tables (Orders, Customers, Products) et doivent être consolidées avant analyse.

L’objectif est de transformer ces données brutes en un dashboard interactif permettant de piloter la performance commerciale.

🎯 Objectifs

Consolider des données multi-tables

Nettoyer et transformer les données

Créer des indicateurs clés de performance (KPIs)

Concevoir un tableau de bord interactif sous Excel

🛠 Outils & Fonctions utilisées

Excel

XLOOKUP

INDEX / MATCH

IF (fonctions conditionnelles)

Tables structurées (Ctrl + T)

Pivot Tables

Pivot Charts

Timeline

Slicers

Formats personnalisés

🔎 Étapes du projet
1️⃣ Data Gathering

Les données étaient réparties sur trois tables :

Orders (Commandes)

Customers (Clients)

Products (Produits)

Les informations manquantes ont été récupérées via :

XLOOKUP → données clients (nom, email, pays, fidélité)

INDEX + MATCH → données produits (type de café, taille, prix unitaire)

2️⃣ Transformation des données

Calcul de la colonne Sales (Unit Price × Quantity)

Remplacement des abréviations (ROB → Robusta, etc.)

Mise en forme des dates

Formatage des tailles (kg)

Formatage des montants en USD

Suppression des doublons

Conversion du dataset en table structurée

3️⃣ Création des KPIs

Trois analyses principales :

📈 Total Sales Over Time (par type de café)

🌍 Sales by Country

🏆 Top 5 Customers

4️⃣ Interactivité

Ajout de filtres dynamiques :

Timeline (filtrage par date)

Slicers :

Roast Type

Size

Loyalty Card

Tous les éléments sont connectés pour filtrer dynamiquement l’ensemble du dashboard.

📊 Résultat

Un dashboard interactif permettant :

d’analyser les ventes par période

d’identifier les pays les plus performants

d’identifier les clients stratégiques

de filtrer par type de produit et fidélité


Spécialisation en Data Analysis
