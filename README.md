# Site Web Personnel Quarto - MicrobioMarine Lab

Ce dépôt contient le code source du site web académique du Dr. Marine Micro, chercheur en microbiologie marine.

## Structure du projet

- `blog/` : Articles de blog et veille scientifique.
- `portfolio/` : Galerie de projets techniques et scientifiques.
- `publications/` : Liste des publications avec export BibTeX.
- `recherche.qmd` : Synthèse des axes de recherche.
- `css/` : Styles personnalisés (thème océan).
- `images/` : Assets visuels et photos.

## Installation et Rendu local

1. **Prérequis** : Installez [Quarto](https://quarto.org/docs/get-started/).
2. **Cloner le dépôt** :
   ```bash
   git clone <url-du-depot>
   cd TestAntygravity
   ```
3. **Rendu local** :
   ```bash
   quarto preview
   ```
4. **Générer le site** :
   ```bash
   quarto render
   ```

## Déploiement

Le site est configuré pour être déployé via GitHub Pages. Le dossier `_site/` (généré par `quarto render`) doit être poussé sur la branche `gh-pages` ou géré par une GitHub Action.
