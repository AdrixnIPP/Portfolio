# Adrien LAMBERT - Data Analyst & Consultant en Data Science
👋 Hi! I'm a Data Analyst skilled in Python, R, SQL and Power BI. My goal is to use Data Analytics and AI techniques to generate value from data.
              [LinkedIn](https://www.linkedin.com/in/adrienlambert1) | adrien.lmbrt.1999@gmail.com | +33 6 65 44 28 70 | Permis B

## 🎓 Formation
- **2019-2022** : ENSTA Paris, Membre de l’Institut Polytechnique de Paris
  - Diplôme d’ingénieur en systèmes complexes (GPA: 3.5)
  - Cours principaux : Mathématiques Appliquées, Statistiques, Deep Learning, Management de l’Innovation.
 
- **2017-2019** : Université Paris-Saclay
  - DUT Mesures Physiques (Mention Très Bien - GPA : 4.0)

---

## 💼 Expériences Professionnelles

### Forvis Mazars Group - **Data Analyst Consultant** (Depuis 11/2023)
- **Contexte** : Réalisation de missions d'audit externe et de contrôle interne dans des secteurs variés (Industrie, Services, Immobilier, Banque, Assurance).
- **Outils** : Alteryx, QlikSense, Power BI, Python
- **Missions réalisées** :
  - Automatisation des processus d’analyse de données avec Python et Power BI.
  - Développement d’un outil de détection de fraude pour les audits internes.
  - Enseignement de cours de Data Analytics à l'Université Paris-Dauphine.

---

### Unilever Group - **Data Specialist** (01/2023 - 11/2023)

#### **Projet 1 : Algorithme de Matching des Données Clients**
- **Contexte** : Unification des données clients provenant de diverses sources (Salesforce, Marketo, Webshop) pour optimiser le ciblage marketing.
- **Approche technique** :
  - Utilisation des bibliothèques Python : `FuzzyWuzzy` et `RecordLinkage` pour le matching de données.
  - Implémentation dans un environnement **Jupyter Notebook**.
  - Algorithme basé sur la correspondance floue des noms, adresses, et emails des clients.
 
```python
from fuzzywuzzy import fuzz
from recordlinkage import Compare

# Exemple de matching entre deux bases de données clients
compare = Compare()
compare.string('name', 'name', method='jarowinkler', threshold=0.85)
compare.exact('email', 'email')
features = compare.compute(dfA, dfB)

matches = features[features.sum(axis=1) > 1.5]  # Ajuster le seuil pour optimiser les résultats
```

- **Résultats** : 903 clients matchés sur 1000 avec un score de précision de 95%.

#### **Projet 2 : Dashboard Power BI - DN Tracker**
- **Contexte** : Création d’un dashboard pour le suivi quotidien de la distribution numérique (DN) des produits Unilever.
- **Technologies utilisées** : Power BI, Power Query, Excel, SAP
- **Résultats** : Amélioration de la prise de décision stratégique grâce à la visualisation des KPI en temps réel.

![Exemple de dashboard Power BI](path/to/dashboard-image.png)

---

### Thales Group - **AI & Data Science Apprentice** (09/2020 - 09/2022)

#### **Projet : Algorithmes d’IA pour la Guerre Électronique**
- **Contexte** : Application de techniques de clustering et de détection d’anomalies aux signaux radar.
- **Technologies utilisées** : Python, Scikit-learn, HDBSCAN, GMM
- **Exemple de code** : Clustering d'impulsions radar avec HDBSCAN.

```python
from hdbscan import HDBSCAN

# Clustering des données radar
clusterer = HDBSCAN(min_cluster_size=10)
cluster_labels = clusterer.fit_predict(radar_data)

# Visualisation des clusters
import matplotlib.pyplot as plt
plt.scatter(radar_data[:, 0], radar_data[:, 1], c=cluster_labels)
plt.title('Clustering d\'impulsions radar')
plt.show()
```

- **Résultats** : Amélioration significative de la classification des signaux radar et détection d’anomalies fiables.

---

## 🛠️ Compétences Techniques
- **Langages** : Python (avancé), SQL (intermédiaire), R (intermédiaire)
- **Data Science** : Scikit-Learn, Pandas, NumPy, TensorFlow
- **Visualisation** : Power BI, Seaborn, Matplotlib, Plotly
- **Outils Cloud** : Microsoft Azure, Databricks
- **Systèmes** : Windows, MacOS, Linux

---

## 🌍 Langues
- **Français** : Langue maternelle
- **Anglais** : Courant
- **Espagnol** : Intermédiaire

---

## 🏅 Loisirs
- **Sport** : Triathlon (IRONMAN Nice 2024), Rugby (Racing Club de France)
- **Musique** : Guitare (9 ans d'auditions et de concerts)

---

## 📈 Projets Open Source (Ajouté à GitHub)
- **Attribution Marketing Multi-Touch** : Modélisation des canaux marketing pour optimiser le budget des campagnes.
- **Optimisation de la Durabilité** : Analyse des données d’émissions de CO2 pour aider les entreprises à réduire leur empreinte carbone.
- **Prédiction du Churn** : Modèle de machine learning pour prédire l’attrition client avec visualisation interactive sous Power BI.
- **Projet d'analyse du Tour de France basé sur des techniques d'apprentissage automatique**

![tdf_image](https://github.com/AdrixnIPP/TourDeFrance/assets/121221811/656fcaeb-a31f-4d52-8ff5-4ccaddd308d2)

[Voir le code sur GitHub](https://github.com/adrienlambert)
```

### Éléments supplémentaires :
- **Images** : Intègre des captures d'écran de tes dashboards Power BI.
- **Visualisations interactives** : Tu peux ajouter des GIFs ou des vidéos montrant l'interaction avec les dashboards.
- **Liens vers GitHub** : Crée un repository dédié pour chaque projet avec du code et des notebooks.

> Ce projet met en avant mes compétences en **data unification**, en **développement d'algorithmes de matching**, et en **gestion de projet** dans le domaine de la **data science appliquée au marketing**. Le gain en qualité de la donnée a permis d'améliorer le ciblage marketing et de fournir des insights précis pour les équipes commerciales.

[Voir le code sur GitHub](#) | [Retour à l'accueil du Portfolio](#)
