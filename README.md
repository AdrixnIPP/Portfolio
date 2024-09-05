# Adrien LAMBERT
👋 Hi! I'm a Data Analyst skilled in Python, R, SQL and Power BI. My goal is to use Data Analytics and AI techniques to generate value from data.

# [Projet 1 : Algorithme de Matching des Données Clients (Salesforce)](https://adrixnipp.github.io/Portfolio/)

## Contexte et Objectif

L'objectif principal de ce projet était de **centraliser les données clients** issues de différentes sources (Salesforce, Marketo, Webshop, distributeurs, etc.) afin d'améliorer la **connaissance client** et d'optimiser le **ciblage des campagnes marketing**. En raison de la diversité des formats et des appellations dans ces bases de données, le défi consistait à développer un algorithme de matching capable de **minimiser les faux positifs** tout en trouvant un maximum de correspondances pertinentes.

### Enjeux

- **Unification des données** clients provenant de systèmes variés (Salesforce CRM, outils de marketing automation, plateformes de vente, etc.).
- **Qualité des données** et gestion des doublons ou variations de formats.
- **Optimisation du ciblage marketing** à partir d'une meilleure vue d'ensemble des clients.

## Approche Méthodologique

### 1. **Cadrage du Projet**
   - **Prise de lead** sur le projet en collaboration avec un stagiaire, avec la répartition des tâches et le suivi des différentes phases de l'implémentation.
   - **Définition du besoin business** : assurer une correspondance précise entre les différentes bases clients pour améliorer les performances des campagnes marketing.

### 2. **Technologies et Algorithmes**
   - **Librarie Python utilisées** :
     - [FuzzyWuzzy](https://github.com/seatgeek/fuzzywuzzy) pour la correspondance floue des chaînes de caractères.
     - [RecordLinkage](https://recordlinkage.readthedocs.io/en/latest/) pour la gestion des correspondances entre enregistrements dans différentes bases de données.
   - **Expérimentation** et développement dans un environnement **Jupyter Notebook** pour faciliter la visualisation et la manipulation des données.

### 3. **Phases d'Implémentation**
   - **Préparation des données** : Nettoyage et normalisation des données provenant de diverses sources pour améliorer la qualité des correspondances.
   - **Algorithme de matching** : Développement de l'algorithme en utilisant des techniques de correspondance floue et d'appariement de champs multiples (noms, emails, numéros de téléphone, etc.).
   - **Évaluation de la précision** : Ajustement du seuil de correspondance pour optimiser le compromis entre le nombre de clients appariés et la minimisation des faux positifs.

## Résultats

- **903 clients matchés sur 1000** avec un **seuil de précision de 95%**.
- L'algorithme a permis d'unifier les données clients de façon significative, améliorant ainsi la vue d'ensemble des données pour le marketing ciblé.
- **Améliorations futures** : Optimiser la détection des faux positifs pour augmenter le taux de match sans sacrifier la précision.

## Défis Techniques

- **Qualité des données** : Nécessité de manipuler des données brutes provenant de systèmes hétérogènes.
- **Apprentissage de nouvelles librairies** : Intégration de FuzzyWuzzy et RecordLinkage pour répondre aux exigences du projet.

## Environnement de Travail

- **Technologies** : Python, Jupyter Notebook, PowerPoint pour les présentations.
- **Équipe** : Collaboration avec un stagiaire, répartition des tâches, et gestion de projet agile.
- **Communication** : Présentation régulière de l'avancement du projet et des résultats, en adaptant le niveau technique en fonction des interlocuteurs (stakeholders, équipe marketing).

## Prochaine Étape

- **Amélioration continue** : Expérimenter de nouvelles techniques pour détecter et corriger les faux positifs tout en augmentant la couverture des correspondances de données clients.

---

> Ce projet met en avant mes compétences en **data unification**, en **développement d'algorithmes de matching**, et en **gestion de projet** dans le domaine de la **data science appliquée au marketing**. Le gain en qualité de la donnée a permis d'améliorer le ciblage marketing et de fournir des insights précis pour les équipes commerciales.

[Voir le code sur GitHub](#) | [Retour à l'accueil du Portfolio](#)
