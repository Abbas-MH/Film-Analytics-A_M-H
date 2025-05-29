# Film-Analytics-A_M-H
phase 2 du projet cinedata

# 🎬 Phase 2 – Data Analyst : Exploration & Visualisation

Cette seconde phase du projet CineData met en œuvre des compétences avancées en **data analysis**, **visualisation** et **développement d’applications interactives**.  
Elle s’appuie sur l’API développée en phase 1 pour proposer une **exploration approfondie des données films** et la **création d’outils analytiques** orientés métier.

---

## 🎯 Objectifs de la phase

- **Analyser les données via une API Python (SDK intégré)**
- **Construire une Data App avec Streamlit**
- **Livrer une expérience utilisateur interactive et professionnelle**

---

## 📊 Analyse exploratoire des données (EDA)

- Requête dynamique des données via le **SDK `moviesdex`** (connecté à l’API REST FastAPI).
- Étude des **tendances de notation**, genres les plus populaires, préférences utilisateurs.
- Construction de **notebooks Jupyter professionnels**, intégrant des graphiques (`seaborn`, `matplotlib`, `plotly`) et des explications lisibles.

> 📁 Livrable :  
> `movie_data_analysis.ipynb`

---

## 🧠 Environnement technique : Jupyter Notebook

- Notebooks organisés par étapes d’analyse (nettoyage, visualisation, exploration).
- Visualisations intégrées dans l’interface, avec interprétations claires.
- Outil adapté pour les présentations techniques ou non techniques.

---

## 💡 Création d’une application Streamlit

L’analyse est ensuite valorisée via une **application web interactive** construite avec **Streamlit** :

- **Navigation multi-pages** (accueil, exploration, statistiques...).
- **Graphiques dynamiques** intégrés à l’interface (plotly, matplotlib).
- **Fonctionnalités interactives** : filtres par genre, recherche par note ou popularité.
- **Connexion directe à l’API** pour affichage en temps réel des données.

> 📁 Livrable :  
> `streamlit_app/`  
> Fichier principal : `movielens_app.py`

---

## 🎞️ Intégration d’un enrichissement OMDb (affiches & liens IMDb)

- Génération automatique de **liens vers les affiches de films** et leur page IMDb via l’API OMDb.
- Script de traitement : `get_movie_poster.py`
- Fichier enrichi final : `output/links_enriched.parquet`

---

## 🛠️ Stack technique mobilisée

| Compétence                  | Outils / Technologies            |
|----------------------------|----------------------------------|
| Récupération de données    | SDK Python, API REST, FastAPI    |
| Analyse exploratoire       | pandas, seaborn, matplotlib      |
| Visualisation interactive  | plotly, Streamlit                |
| Notebook interactif        | Jupyter, Markdown, VSCode        |
| Web App Data               | Streamlit (multi-pages, widgets) |
| Appels API externes        | OMDb API                         |
| Gestion de projet          | Git, GitHub                      |

---

## ✅ Livrables finaux

- ✅ Notebooks Jupyter d’exploration et visualisation
- ✅ Application Streamlit fonctionnelle et connectée à l’API
- ✅ Fichier enrichi avec affiches de films
- ✅ Code structuré, documenté, prêt à être déployé

---

## 📌 Résumé

Cette phase démontre ma capacité à :
- Transformer des données brutes accessibles par API en **analyses visuelles compréhensibles**.
- Concevoir une **expérience utilisateur complète** : depuis l’ingestion des données jusqu’à leur présentation web.
- Mobiliser des outils de **visualisation moderne** pour raconter une histoire métier à partir de données structurées.

---
## 🔄 Lancer l’application Streamlit

*👉 Avant de démarrer l’application, **assurez-vous que l’API est en fonctionnement**.*  
L’URL de l’API ainsi que les instructions de lancement se trouvent dans le fichier `README.md` du dossier `api`, situé dans `backend-movie-A_m-h`.

Une fois l’API lancée, assurez-vous d’être dans le dossier streamlit avec le terminal. Vous pouvez ensuite exécuter l’application Streamlit à l’aide de la commande suivante :

```bash
streamlit run movielens_app.py
