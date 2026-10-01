1. Contexte

RetailCo est une entreprise fictive spécialisée dans la distribution de produits à travers plusieurs canaux de vente : magasins, e-commerce et ventes B2B.

L'entreprise génère des données liées aux ventes, aux clients, aux produits, aux stocks et aux activités commerciales. Ces données proviennent de différentes sources et ne sont pas centralisées dans une solution unique d'analyse.

La direction souhaite mettre en place une solution permettant de centraliser, structurer et analyser ces données afin d'obtenir une vision globale de l'activité commerciale et d'améliorer la prise de décision.

2. Problématique

RetailCo dispose de nombreuses données, mais leur dispersion rend difficile l'obtention d'une vision globale et fiable de la performance de l'entreprise.

La direction souhaite notamment pouvoir suivre les ventes et la rentabilité, comprendre le comportement des clients, analyser la performance des produits, surveiller les stocks, comparer les prix avec le marché et anticiper l'évolution future des ventes.

Le projet vise donc à construire une solution décisionnelle permettant de transformer ces différentes données en informations fiables et exploitables.

3. Objectifs

Le projet a pour objectifs de :

Centraliser les données provenant de différentes sources.
Suivre l'évolution des ventes et de la rentabilité.
Analyser les clients, les produits et les stocks.
Évaluer le positionnement tarifaire de RetailCo par rapport au marché.
Prévoir l'évolution future des ventes.
Fournir des indicateurs et tableaux de bord permettant d'aider à la prise de décision.
4. Utilisateurs
Utilisateur	Besoin
Directeur commercial	Suivre ventes, performance et rentabilité
Responsable Marketing/CRM	Analyser clients et fidélisation
Responsable Stock	Surveiller stocks et ruptures
Direction générale	Vision globale de l'activité
5. Besoins métier
Ventes
Analyser le chiffre d'affaires par période.
Comparer les ventes entre différentes périodes.
Identifier les produits et catégories les plus performants.
Analyser les ventes par région et canal.
Rentabilité
Calculer le profit.
Calculer la marge.
Identifier les produits les plus et moins rentables.
Clients
Identifier les clients à forte valeur.
Analyser la fréquence et la récence des achats.
Identifier les clients inactifs ou à risque.
Segmenter les clients.
Stocks
Suivre les niveaux de stock.
Identifier les produits proches de la rupture.
Identifier les situations de surstock.
Identifier les produits à faible rotation.
Prix / marché
Collecter des prix externes.
Comparer les prix de RetailCo avec ceux observés sur le marché.
Identifier les écarts de prix.
Prévisions
Analyser les tendances historiques.
Prévoir les ventes futures.
Utiliser les prévisions pour aider à la planification.
6. Fonctionnalités

La solution devra permettre :

Dashboard Executive
Dashboard Sales
Dashboard Customer Intelligence
Dashboard Inventory
Dashboard Competitive Pricing
Dashboard Forecasting
Analyse RFM des clients
Calcul des principaux KPI
Contrôles de qualité des données
Génération d'alertes sur certains niveaux de stock
7. Données nécessaires
Domaine	Données
Ventes	commandes, dates, produits, quantités, prix, remises
Produits	produit, catégorie, sous-catégorie, coût, prix
Clients	client, région, segment, historique
Stock	quantité disponible, seuil de réapprovisionnement
Commercial	commercial, région, objectif
CRM	interactions, dates, statut
Marché	produit, prix observé, disponibilité, date
Calendrier	jour, mois, trimestre, année
8. KPI

Les principaux indicateurs seront :

Ventes

Chiffre d'affaires
Nombre de commandes
Quantité vendue
Panier moyen
Croissance des ventes

Rentabilité

Profit
Marge %
Profit par produit

Clients

Nombre de clients actifs
CA par client
Fréquence d'achat
Récence
Segmentation RFM

Stock

Stock disponible
Valeur du stock
Produits en rupture
Produits sous seuil
Produits en surstock

Prix

Prix RetailCo
Prix marché
Écart de prix
Écart %
9. Architecture et solution proposée

La solution suivra une architecture de type :

Sources
   ↓
Ingestion
   ↓
Raw Data
   ↓
Staging / Transformation
   ↓
Data Warehouse
   ↓
Data Model / SQL
   ↓
Power BI
   ↓
Business Insights
Les données pourront provenir de plusieurs sources simulées :

données transactionnelles représentant un ERP ;
données CRM ;
données de stock ;
données externes de prix.

Python sera utilisé notamment pour la préparation des données, l'analyse, la collecte de données externes et les modèles prédictifs.

SQL Server sera utilisé pour le stockage, la transformation et la construction du Data Warehouse.

Power BI sera utilisé pour la visualisation et l'analyse décisionnelle.
10. Livrables

À la fin du projet, nous aurons :

un Data Warehouse SQL Server ;
des processus ETL ;
des contrôles de qualité des données ;
un modèle de données décisionnel ;
plusieurs dashboards Power BI ;
une analyse RFM ;
un modèle de prévision des ventes ;
une collecte de données externes ;
une automatisation d'alerte ;
une documentation technique et fonctionnelle ;
un dépôt GitHub documenté.
11. Critères de réussite

Le projet sera considéré comme réussi si :

les différentes sources sont correctement intégrées ;
les données sont nettoyées et structurées ;
les KPI sont calculés correctement ;
le Data Warehouse permet une analyse cohérente ;
les dashboards répondent aux besoins métier définis ;
les prévisions sont évaluées avec des métriques adaptées ;
les résultats sont documentés et reproductibles.
12. Limites et hypothèses

RetailCo est une entreprise fictive créée dans le cadre de ce projet portfolio.

Les systèmes ERP et CRM seront donc simulés à partir de données publiques et/ou synthétiques.

Les données externes utilisées pour l'analyse des prix seront considérées comme une source pédagogique permettant de démontrer le processus d'intégration de données externes.

Le projet ne prétend pas reproduire l'architecture réelle d'un ERP comme SAP ou d'un CRM comme Salesforce.
