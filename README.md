# Étude de santé publique — Python & FAO

> Cartographier la sous-nutrition mondiale et identifier ses causes structurelles à partir des données FAO.

**Stack** · Python · Pandas · Matplotlib · Jupyter

---

## Contexte

Mission d'analyse pour la FAO visant à mieux comprendre la répartition de la sous-alimentation dans le monde. Le projet croise 4 datasets publics (population, disponibilité alimentaire, aide alimentaire, sous-nutrition) pour produire des indicateurs pays et identifier les zones les plus vulnérables.

## Méthodologie

1. **Collecte et nettoyage** — fusion de 4 fichiers CSV, gestion des valeurs manquantes et des unités
2. **Calcul d'indicateurs** — proportion de sous-alimentés, disponibilité calorique, aide reçue par habitant
3. **Analyse géographique** — cartographie mondiale de la sous-nutrition
4. **Corrélations** — lien entre production alimentaire disponible et niveau de malnutrition

## Résultats clés

- Zones les plus vulnérables identifiées : Afrique subsaharienne et Asie du Sud
- Mise en évidence d'un écart structurel entre disponibilité alimentaire et besoins nutritionnels réels
- Corrélation entre PIB/habitant et taux de sous-alimentation (r = -0.6)

## Contenu du repo

| Fichier | Description |
|---------|-------------|
| `notebook.html` | Notebook interactif complet (visualisable dans un navigateur) |
| `notebook.pdf` | Version PDF du notebook |
| `presentation.pptx` | Présentation des résultats |

---

*Formation Data Analyst — OpenClassrooms × ENSAE · Projet 3*
