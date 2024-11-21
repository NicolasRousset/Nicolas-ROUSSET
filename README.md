# Portfolio d'Analyse de Données

Bienvenue sur mon portfolio ! Je suis **Nicolas ROUSSET**, **Ingénieur en Gestion des Données et Suivi de la Qualité de l'Eau** chez Haut-Bugey Agglomération.

Mes missions incluent l'ETL des données de différentes sources, le calcul de KPIs et la création de tableaux de bord dynamiques destinés à l'ensemble du service.
Je manipule au quotidien des logiciels comme Excel, AirByte, DBT et PowerBI pour extraire, nettoyer, transformer et présenter des données issues de différentes sources (SQL Server, PostgreSQL, API pour les données externes).

Ce portfolio présente mes projets réalisés dans le domaine de la gestion de l'eau potable, ainsi que mes compétences en outils et techniques d'analyse de données.

---

## 🛠️ **Compétences**
- **Langages** : SQL
- **Outils** :
  - BDD : Microsoft SQL Server, PostGreSQL, Excel
  - RDBMS : SSMS, pgAdmin4
  - ELT : Airbyte + DBT
  - Visualisation : PowerBI

---

## 📊 **Projets**
### 1️⃣ **Suivi des indicateurs de qualité de l’eau**

- **Description** : Intégration et analyse des résultats mensuels des analyses de qualité de l'eau reçus d'un laboratoire d'analyse dans le cadre du contrôle sanitaire national.
Chaque mois, je reçois deux fichiers :
  - La liste des analyses : Ce fichier contient les métadonnées des analyses (dates, communes, etc.).
  - Les résultats des analyses : Détaille les résultats pour chaque paramètre analysé, au format SISE-EAUX.

- **Données brutes** :
  - Liste des analyses :
  ![Donnees_brutes](Projets/Donnees_brutes2.PNG)
  - Résultat des analyses :
  ![Donnees_brutes](Projets/Donnees_brutes.PNG)

- **Méthodologie** :
  - Import et transformation des données : Les fichiers sont combinés dans Power BI en utilisant la colonne "id échantillon" comme clé de jointure.
  - Décodage des codes SISE-EAUX : Des tables de correspondance sont utilisées pour transformer les codes SISE-EAUX en libellés compréhensibles.
  - Création de rapports dynamiques : Je crée des tableaux de bord dans Power BI où l'utilisateur peut sélectionner les communes et les paramètres à afficher pour visualiser les résultats d'analyses de manière claire et dynamique.

- **Outils utilisés** : PowerQuery + PowerBI

![Schema_modele](Projets/Schema_modele.PNG)


- **Résultat** :
Le rapport final permet aux utilisateurs d'avoir accès à l'ensemble de l'historique des analyses du contrôle sanitaire sur le périmètre de notre collectivité.
Les utilisateurs peuvent filtrer et examiner les analyses de qualité de l'eau pour chaque commune et chaque paramètre, facilitant ainsi la prise de décision et le suivi de la conformité de l'eau potable.

📄 [Voir le rapport complet Power BI](Projets/Controle_Sanitaire.pdf)


---

### 2️⃣ **Suivi des consommations par secteur**
- 📄 [Lien vers le tableau de bord Power BI](https://votre-lien-power-bi)
- 📷 ![Exemple de visualisation](Images/consommations-secteurs.png)
- **Description** : Modélisation des données de consommation pour détecter les anomalies et optimiser la gestion des secteurs.
- **Méthodologie** :
  - Jointures SQL pour relier compteurs et débits journaliers.
  - Calcul des entrées/sorties par secteur.
  - Création de graphiques dynamiques pour faciliter l’analyse.

---

## 🌐 **Contactez-moi**
- 💼 **LinkedIn** : [Mon profil LinkedIn](https://www.linkedin.com/in/nicolas-rousset-73313467/)
- 🌍 **GitHub** : [Mon GitHub](https://github.com/NicolasRousset)

