# 🤖 Où va l'argent dans l'IA ? — Analyse des investissements mondiaux (2015–2025)

> **Projet portfolio Data · Analyse complète des investissements privés et publics en intelligence artificielle**

---

## 📌 Présentation

L'intelligence artificielle est l'un des secteurs les plus dynamiques de l'économie mondiale. Ce projet analyse l'évolution des investissements mondiaux en IA entre **2015 et 2025**, en identifiant les pays les plus attractifs, les secteurs les plus financés et les tendances qui façonnent l'avenir de l'écosystème IA.

---

## ❓ Problématique

> **Quels pays attirent le plus d'investissements en intelligence artificielle et comment cette dynamique a-t-elle évolué depuis 2015 ?**

Questions secondaires :
- Comment les investissements ont-ils évolué au fil des années ?
- Quels secteurs de l'IA bénéficient des financements les plus importants ?
- Quel impact l'essor de l'IA générative a-t-il eu sur les investissements ?
- Quels pays émergent comme nouveaux pôles d'innovation ?

---

## 🗂️ Structure du projet

```
ai-investments-analysis/
│
├── index.html                          ← Dashboard interactif (GitHub Pages)
├── README.md                           ← Ce fichier
│
├── notebooks/
│   └── analyse_investissements_IA.ipynb ← Notebook Google Colab complet
│
├── data/
│   └── (données extraites manuellement des sources ci-dessous)
│
└── outputs/
    ├── graphique_1_evolution.png
    ├── graphique_2_pays.png
    ├── graphique_3_secteurs.html
    ├── graphique_4_carte.html
    └── graphique_5_gouvernements.png
```

---

## 🔑 Résultats clés

| Indicateur | Valeur |
|---|---|
| Investissement mondial 2025 | **$581 Md** (+130% vs 2024) |
| Part des États-Unis | **49%** ($286Md) |
| IA Générative 2024 | **$33.9Md** (+18.7% vs 2023) |
| TCAM mondial (2015–2024) | **+40%/an** |
| Ratio US / Chine | **×23** en 2025 |
| Top secteur | **Infrastructure IA** ($80Md) |

---

## 📊 Visualisations

1. **Évolution temporelle** — Line chart Monde / USA / Chine (2015–2025)
2. **Top pays** — Horizontal bar chart investissement 2024
3. **Répartition sectorielle** — Donut chart interactif (Plotly)
4. **Carte mondiale** — Choroplèthe (Plotly)
5. **Engagements gouvernementaux** — Bar chart 2025

---

## 🛠️ Outils utilisés

| Outil | Usage |
|---|---|
| Python 3.11 | Langage principal |
| Pandas | Manipulation des données |
| NumPy | Calculs statistiques (TCAM, ratios) |
| Matplotlib | Graphiques statiques exportés en PNG |
| Plotly | Graphiques interactifs (HTML) |
| Chart.js | Dashboard web interactif |
| Git & GitHub | Versioning et déploiement |
| GitHub Pages | Hébergement du dashboard |

---

## 🚀 Comment exécuter

### Option 1 — Dashboard web (aucune installation)
Ouvrir directement `index.html` dans un navigateur  
**ou** visiter : `https://[votre-pseudo].github.io/ai-investments-analysis`

### Option 2 — Notebook Python (Google Colab)
1. Aller sur [colab.research.google.com](https://colab.research.google.com)
2. Fichier → Ouvrir → GitHub → coller l'URL du dépôt
3. Ouvrir `notebooks/analyse_investissements_IA.ipynb`
4. Runtime → Exécuter tout

---

## 📚 Sources de données

| Source | URL | Données extraites |
|---|---|---|
| Stanford HAI AI Index 2025 | [hai.stanford.edu](https://hai.stanford.edu/ai-index/2025-ai-index-report) | Investissements privés par pays et secteur |
| Our World in Data | [ourworldindata.org/artificial-intelligence](https://ourworldindata.org/artificial-intelligence) | Séries temporelles mondiales |
| Statista | [statista.com](https://www.statista.com/statistics/1472716) | Rankings par pays 2024 |
| Quantumrun | [quantumrun.com](https://www.quantumrun.com) | Projections 2025 |

---

## ⚠️ Limites de l'étude

- Les investissements militaires chinois (~$184Md sur 2000–2023) ne sont **pas inclus** dans les données privées
- La R&D interne des GAFAM (non divulguée séparément) est **exclue**
- Les chiffres 2025 sont des **estimations consolidées**, non des données auditées définitives

---

## 👤 Auteur

**[Votre nom]**  
Étudiant(e) en Data Analytics  
[LinkedIn](#) · [GitHub](#)

---

*Projet réalisé dans le cadre d'un portfolio Data — 2025*
