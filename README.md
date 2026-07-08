# 📊 Analyse des secteurs d'activité des leads – EIC Canada

## 🎯 Contexte du projet
EIC Canada est une entreprise spécialisée dans le placement de stagiaires internationaux au Canada.

L’entreprise possède :
- une équipe B2C (accompagnement des étudiants)
- une équipe B2B (développement de partenariats entreprises)

Dans le cadre de mon stage au sein de l’équipe B2B, j’ai analysé les données CRM afin d’identifier les secteurs d’activité les plus demandés par les étudiants pour leurs stages.

---

## ❗ Problématique
L’entreprise dispose de nombreuses données issues du CRM HubSpot, mais sans vision claire des secteurs les plus recherchés.

Ce projet vise à répondre à :
- Quels secteurs sont les plus demandés ?
- Où développer de nouveaux partenariats ?
- Existe-t-il des tendances dans le temps ?
- Comment fournir un outil d’aide à la décision aux équipes B2B ?

---

## 🧹 Préparation des données
Les données proviennent d’exports HubSpot (~2 731 enregistrements).

Travail réalisé dans Power Query :
- Nettoyage des colonnes inutiles
- Harmonisation des formats de date
- Suppression des doublons et valeurs incohérentes
- Normalisation des intitulés de postes (minuscule, nettoyage, standardisation)

---

## 🧠 Classification des postes (point clé du projet)
Aucune classification sectorielle n’existait dans les données.

J’ai donc construit une **table de correspondance métier** permettant d’associer chaque poste à un secteur.

### Secteurs définis :
- IT / Software / Développement
- Data / IA
- Marketing / Communication
- Sales / Business Development
- Finance
- Ingénierie
- Media / Journalisme
- Sport / Performance
- Management / Gestion de projet
- Autres

Une logique de mapping (Power Query) a été développée pour automatiser la classification des intitulés.

---

## 🔗 Modélisation des données
- Relation entre table des leads et table de classification (*:1)
- Structuration du modèle dans Power BI pour analyse dynamique

---

## 📊 Visualisations Power BI
- Répartition des leads par secteur
- Analyse des secteurs les plus demandés
- Évolution des secteurs dans le temps
- KPI de suivi des demandes de stage

---

## 📈 Résultats
- Identification des secteurs les plus demandés
- Détection de tendances dans le temps
- Outil d’aide à la décision pour l’équipe B2B
- Amélioration de la stratégie de prospection
- Automatisation du classement des postes

---

## 🛠️ Outils utilisés
- Power BI
- Power Query (M)
- Excel / HubSpot
- Data Cleaning & Data Modeling
- IA générative (aide à la construction du référentiel)

---

## 👤 Auteur
Junior Jemkoue  
Data Analyst / BI Developer

---

## 🚀 Conclusion
Ce projet transforme des données CRM brutes en un outil décisionnel permettant d’orienter la stratégie commerciale de l’entreprise vers les secteurs les plus porteurs.
