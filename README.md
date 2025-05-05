📊 Analyse des Ventes E-commerce – Version Freemium
Ce projet propose une solution d’analyse commerciale pour les petits commerçants ou e-commerces. Il adopte un modèle freemium, avec :

Une version gratuite incluant les fonctionnalités de base

Une version premium (à venir) pour des analyses avancées, automatisées et téléchargeables

✅ Fonctionnalités – Version Gratuite
🔍 Chiffre d'affaires (CA) global

🛒 Top produits par revenus

👤 Top clients

🕒 Analyse temporelle :

CA mensuel

CA par jour de la semaine

CA par heure

⚠️ Alertes : produits à faible stock

📉 Détection de produits marginaux (<1% CA)

🛌 Identification des clients dormants (1 seule commande)

📊 Graphiques simples (Seaborn, Matplotlib)

⏳ Historique limité à 30 derniers jours

📈 Analyse commerciale automatisée
À partir d’un simple fichier CSV, le script exécute une analyse stratégique des ventes :

🔹 Statistiques générales
Chiffre d'affaires total

Panier moyen par client

Moyenne, médiane, écart-type

Coefficient de variation (volatilité)

🔹 Segmentation client et produit
Top 10 produits par CA

Top 10 clients

🔹 Alerte dépendance
Sur-dépendance à un seul produit ou client détectée automatiquement

🔹 Fidélisation & diversification
Analyse de concentration des revenus

Suggestions : diversification produit, fidélisation client

🔹 Détection comportementale
Clients dormants

Produits marginaux

🔢 Données attendues
Le fichier d’entrée est un CSV avec au minimum les colonnes suivantes :

Colonne	Description
InvoiceDate	Date de commande (format datetime)
Description	Nom du produit
Quantity	Quantité vendue
UnitPrice	Prix unitaire
CustomerID	Identifiant client
Country	Pays

🗂 Structure du projet
bash
Copier
Modifier
├── Untitled.ipynb         # Notebook local de test
├── requirements.txt       # Dépendances Python
└── README.md              # Ce fichier
