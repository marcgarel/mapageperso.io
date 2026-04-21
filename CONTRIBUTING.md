# Guide de Contribution

Ce guide explique comment ajouter du contenu au site.

## Ajouter un article de blog
1. Créez un nouveau dossier dans `blog/posts/` suivant le format `YYYY-MM-DD-titre-court/`.
2. Créez un fichier `index.qmd` dans ce dossier.
3. Remplissez le front-matter (YAML) avec le titre, la date et les catégories.

## Ajouter un projet au portfolio
1. Créez un dossier dans `portfolio/projects/`.
2. Ajoutez un fichier `index.qmd`.
3. Utilisez le format `grid` pour l'affichage (configuré dans `portfolio/index.qmd`).

## Mettre à jour les publications
1. Modifiez le fichier `publications/index.qmd` pour ajouter l'entrée dans le listing YAML.
2. Ajoutez également l'entrée dans `publications/references.bib` pour permettre l'export par les pairs.
