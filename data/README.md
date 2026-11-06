# Données

Les fichiers CSV ne sont **pas inclus** dans ce dépôt : ils proviennent de la base **FAOSTAT** (FAO) et ont été fournis dans le cadre du projet de formation. Vérifiez les conditions d'utilisation de FAOSTAT avant de redistribuer des données.

Pour exécuter le notebook, placez dans ce dossier les quatre fichiers suivants :

| Fichier | Colonnes principales |
|---|---|
| `population.csv` | `Zone`, `Année`, `Valeur` (population, en milliers d'habitants) |
| `dispo_alimentaire.csv` | `Zone`, `Produit`, `Origine`, quatre colonnes de disponibilité par personne, dix colonnes de quantités en milliers de tonnes |
| `aide_alimentaire.csv` | `Pays bénéficiaire`, `Année`, `Produit`, `Valeur` (en tonnes) |
| `sous_nutrition.csv` | `Zone`, `Année` (intervalles de 3 ans), `Valeur` (en millions de personnes) |

Source d'origine : FAOSTAT, <https://www.fao.org/faostat/>.
