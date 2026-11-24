# Écarts salariaux femmes-hommes dans le secteur privé français (1996-2024)

*Auteurs : Yanis Yvray & Jawad MAHRAOUI (2026).*

## Sujet

Ce projet étudie l'évolution et la structure des inégalités de rémunération entre les femmes et les hommes dans le secteur privé français entre 1996 et 2024.

**Problématique :** Comment les écarts salariaux hommes-femmes ont-ils évolué sur cette période et dans quelle mesure varient-ils selon le secteur d'activité, la catégorie socioprofessionnelle et le niveau de salaire ?

## Données

Le projet repose sur des données agrégées de salaires mensuels nets exprimés en euros constants (tous temps de travail confondus), distinguées selon :

1. Le sexe ;
2. Le secteur d'activité (regroupé en 4 grandes catégories : Industrie et Énergie, Construction, Services marchands, Services non marchands et aux ménages) ;
3. La catégorie socioprofessionnelle (cadres, professions intermédiaires, employés et ouvriers) ;
4. La position dans la distribution des salaires (D1, Q1, médiane, Q3, D9, P95 et P99) ;
5. L'année (1996-2024).

## Méthodologie

L'étude contient deux parties :

1. **Statistiques descriptives :** suivi de l'écart salarial moyen en euros constants, comparaison par grands secteurs d'activité et par CSP, et analyse de la dispersion des salaires (ratio P90/P10 et comparaison des quantiles P10 et P90 selon le sexe).
2. **Modèles économétriques :** estimation de trois régressions linéaires
   - **Évolution temporelle :** tendance linéaire de l'écart salarial moyen entre 1996 et 2024 ;
   - **Analyse par CSP :** interactions entre le sexe et la CSP avec effets fixes annuels ;
   - **Analyse par quantiles :** interactions entre le sexe et la position dans la distribution des salaires avec effets fixes annuels.

## Principaux résultats

- **Baisse tendancielle de l'écart de salaire moyen homme-femme:** l'écart observé recule de 22,3 % en 1996 à 13,0 % en 2024 (soit de 583 € à 377 € mensuels en euros constants), avec une accélération après 2015. Le modèle linéaire estime un écart initial de -22,82 % en 1996 qui se réduit en moyenne de 0,38 % par an (environ -14,1 % prédit en 2024).
- **Disparités sectorielles :** l'écart diminue dans tous les grands secteurs, particulièrement dans l'Industrie et Énergie (de 21,0 % à 9,1 %). La Construction se distingue avec un écart devenu négatif (-2,0 % en 2024).
- **Hétérogénéité par CSP :** l'écart moyen estimé est le plus marqué chez les cadres (-22,11 %), devant les ouvriers (-16,69 %), les professions intermédiaires (-13,76 %) et les employés (-7,37 %).
- **Effet de plafond de verre (quantiles) :** l'écart augmente nettement avec le niveau de rémunération, passant de -6,28 % au premier décile (D1) à -12,97 % à la médiane et jusqu'à -34,98 % au 99e centile (Top 1 %). La dispersion interne (ratio P90/P10) reste également plus forte chez les hommes (3,07 contre 2,65 chez les femmes en 2024).

## Limites

Les données utilisées étant agrégées et tous temps de travail confondus, elles ne permettent pas de contrôler les caractéristiques individuelles (diplôme, ancienneté, métier exact, temps partiel). Les résultats mesurent donc des écarts observés entre groupes et non un effet causal direct du sexe sur la rémunération.

## Ordre d'exécution

1. **Nettoyage des données :** ouvrir le fichier de nettoyage des données et lancer le code en premier afin de générer le jeu de données nettoyé.
2. **Statistiques descriptives :** ouvrir et tout excécuter 
3. **Modélisation économétrique :** ouvrir et tout exécuter
