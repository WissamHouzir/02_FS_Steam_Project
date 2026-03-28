# Steam_Project
# 🎮 Analyse des jeux Steam

## Présentation du projet

Ce projet consiste à analyser un dataset de jeux disponibles sur Steam afin de mieux comprendre les tendances du marché du jeu vidéo.
L’analyse porte sur les éditeurs, les prix, les avis des joueurs, les genres et les plateformes.

L’objectif est d’identifier les facteurs qui influencent le succès d’un jeu en termes de popularité, de satisfaction des joueurs et de revenus.

---

## Objectifs

L’analyse est structurée en trois parties principales :

### 1. Analyse macro

* Quels éditeurs publient le plus de jeux ?
* Comment les prix sont-ils distribués ?
* Quels sont les jeux les mieux notés ?
* Comment le nombre de sorties évolue-t-il dans le temps ?

### 2. Analyse par genre

* Quels sont les genres les plus représentés ?
* Quels genres ont les meilleurs ratios d’avis positifs ?
* Certains éditeurs sont-ils spécialisés dans des genres spécifiques ?
* Quels genres génèrent le plus de revenus ?

### 3. Analyse des plateformes

* La majorité des jeux est-elle disponible sur Windows, Mac ou Linux ?
* Certains genres sont-ils plus présents sur certaines plateformes ?

---

## 🛠️ Outils et technologies

* **Databricks**
* **PySpark**
* Visualisation de données (Databricks)

---

## 📁 Structure du projet

```id="482gs9"
02_FS_Steam_Project/
│
├── 01_Data_Loading_&_Cleaning.html
├── 02_Macro_Analysis.html
├── 03_Genre_Analysis.html
├── 04_Platform_Analysis.html
├── README.md
```

---

## 📈 Principaux résultats

* L’écosystème Steam est largement dominé par les **jeux indépendants (Indie)**.
* **Windows** est la plateforme principale, avec beaucoup plus de jeux que Mac et Linux.
* La majorité des prix se situe entre **10€ et 30€**, ce qui rend les jeux accessibles.
* La popularité (nombre d’avis) n’est pas toujours liée à une meilleure note.
* Les genres les plus représentés sont également les plus rentables.

---

## 📤 Livrables

Les notebooks ont été exportés au format **HTML** afin de permettre une consultation simple des analyses et des visualisations sans nécessiter un accès à Databricks.

### Accès aux notebooks

- Data_Loading_&_Cleaning : [Voir le notebook](./01_Data_Loading_&_Cleaning.html)
- Macro Analysis : [Voir le notebook](./02_Macro_Analysis.html)
- Genre Analysis : [Voir le notebook](./03_Genre_Analysis.html)
- Platform Analysis : [Voir le notebook](./04_Platform_Analysis.html)

---

## 👩‍💻 Auteur

Projet réalisé par Wissam Houzir dans le cadre d’une formation en data Science chez Jedha, paris.

---
