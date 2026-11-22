# ProjetPython

Projet Python d’analyse des salaires à partir des séries longues DERA.

## Ordre d’exécution

Les notebooks doivent être lancés dans cet ordre :

1. **`Nettoyage_donnees.ipynb`** — lit les fichiers CSV bruts du dossier `Data brutes/`, harmonise les noms et les catégories, puis crée les fichiers nettoyés dans `Data nettoyees/`. Les fichiers bruts ne sont pas modifiés.
2. **`Statistiques_descriptives.ipynb`** — lit le fichier privé nettoyé et produit les tableaux et graphiques descriptifs.
3. **`Regression_salaire_femme_CSP.ipynb`** — lit également le fichier privé nettoyé et estime les régressions sur les écarts salariaux.

Exécute toutes les cellules du notebook de nettoyage avant d’ouvrir les deux notebooks d’analyse. Si `Data nettoyees/` ou le fichier privé nettoyé est absent, relance d’abord le nettoyage.

## Dépendances

Les notebooks utilisent Python et les bibliothèques `pandas`, `numpy`, `matplotlib` et `statsmodels`. Ils peuvent être ouverts dans Jupyter ou VS Code avec la prise en charge des notebooks `.ipynb`.
