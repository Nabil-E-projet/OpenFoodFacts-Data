# Projet – Analyse des données nutritionnelles (Open Food Facts)

## Objectif

Préparer un dataset issu d'Open Food Facts pour construire un système d’auto-complétion à destination d’un organisme de santé publique. Le but est de faciliter la saisie de données nutritionnelles par les utilisateurs via des suggestions pertinentes.

## Démarche

### 1. Préparation des données
- Chargement des données avec Pandas.
- Sélection des colonnes clés pour l’analyse.
- Suppression des doublons via la colonne `code`.

### 2. Nettoyage
- Analyse des valeurs manquantes.
- Traitement par imputation (SimpleImputer, régressions linéaires).
- Suppression ou correction des valeurs aberrantes (médiane, boxplots).

### 3. Exploration
- Analyse univariée (ex : `fat_100g`, `energy_100g`).
- Analyse bivariée (corrélations, heatmap).
- Analyse multivariée (ACP, ANOVA).

## Résultats

- Mise en évidence de corrélations fortes (`fat_100g` ↔ `saturated-fat_100g`).
- Réduction importante des valeurs manquantes.
- Dataset cohérent et complet, prêt pour être utilisé dans un système de suggestion.

## Conclusion

Les données sont exploitables pour alimenter une application d’auto-complétion. La méthode est conforme au RGPD, car aucune donnée personnelle n’a été traitée. Le projet est techniquement et éthiquement réalisable.
