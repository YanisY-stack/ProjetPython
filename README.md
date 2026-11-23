
# Écarts salariaux femmes-hommes dans le secteur privé français (1996-2024)

*Auteur : Yanis Yvray & Jawad MAHRAOUI (2026).*

> **Sujet**
>
> Ce projet étudie les inégalités de rémunération entre les femmes et les hommes dans le secteur privé français entre 1996 et 2024.
>
> **Problématique :** Comment les écarts salariaux femmes-hommes ont-ils évolué sur cette période et dans quelle mesure varient-ils selon la catégorie socioprofessionnelle et le niveau de salaire ?

> **Données**
>
> Le projet repose sur des données agrégées de salaires mensuels nets, distinguées selon :
>
> - Le sexe ;
> - La catégorie socioprofessionnelle (cadres, professions intermédiaires, employés et ouvriers) ;
> - La position dans la distribution des salaires (D1, Q1, médiane, Q3, D9, P95 et P99) ;
> - L'année (1996-2024).

> **Modèles économétriques**
>
> Trois régressions linéaires sont estimées :
>
> 1. **Évolution temporelle :** mesure la tendance de l'écart salarial moyen entre les femmes et les hommes.
> 2. **Analyse par CSP :** étudie les différences d'écarts salariaux selon la catégorie socioprofessionnelle, à l'aide d'interactions entre le sexe et la CSP.
> 3. **Analyse par quantiles :** examine l'évolution de l'écart salarial selon la position dans la distribution des salaires.

> **Principaux résultats**
>
> Les résultats montrent que :
>
> - L'écart salarial moyen diminue entre 1996 et 2024, passant d'un écart initial estimé à -22,82 % à un écart prédit d'environ -14,1 % en 2024.
> - L'écart varie selon la CSP : il atteint -22,11 % chez les cadres, contre -7,37 % chez les employés.
> - Il augmente avec le niveau de salaire : de -6,28 % au premier décile à -34,98 % au 99e centile.
>
> Les résultats mettent ainsi en évidence la persistance et l'hétérogénéité des inégalités salariales.

> **Reproduction du projet**
>
> **Installation**
>
> ```bash
> pip install -r requirements.txt
> ```
>
> **Lancement**
>
> Ouvrir le notebook `Regression_salaire_femme_CSP.ipynb`, qui regroupe le traitement des données, les estimations économétriques et l'interprétation des résultats.

> **Structure du repo**
>
> - `data` : données utilisées pour l'analyse ;
> - `Regression_salaire_femme_CSP.ipynb` : notebook principal ;
> - `requirements.txt` : dépendances Python nécessaires à l'exécution du projet.
