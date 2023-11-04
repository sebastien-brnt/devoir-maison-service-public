# Devoir maison N°1 Sébastien B. - Service Public

**Lien vers le rendu :** [https://sitecube.fr/dm-service-public/](https://sitecube.fr/dm-service-public/)

**Lien vers le Git du projet :**  https://github.com/sebastien-brnt/devoir-maison-service-public

## Structures des fichiers

- index.html
- assets
    - css
        - style.css
    - img
        - images nécessaires à la créations..
    

## Actions notables sur le HTML

- Autours des blocs, “nos astuces” et “nos actualités”, remplacement des `<div>` par des `<section>`
- Remplacement de la value “Rechercher” par un **placeholder** dans la recherche du header
- Ajout des **alt** sur les images
- Dans le footer, remplacement de la première `<div>` par un `<nav>`, étant donné que c’est un menu de navigation
- Ajout de `<h2>` aux balises `<article>`
- Remplacement de la `<div>` autours du texte “Découvrez ci-dessous ce que vous pouvez faire dans la rubrique « Mon tableau de bord ».” par une balise `<p>`
- Dans la section Mon tableau de bord, ajout de balises `<article>` autours des éléments
- Remplacement de la balise section qui englobait le `<main>` et `<aside>` par une `<div>` car le `<main>` ne doit pas être contenu dans une `<section>`
- Suppression du `<span>` au niveau du logo footer

## Utilisation du framework Bootstrap

- Import de la partie “grid” de Bootstrap via le lien cdn ([https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap-grid.min.css](https://cdn.jsdelivr.net/npm/bootstrap/dist/css/bootstrap-grid.min.css))
- Utilisation des classes de Bootstrap container, row, col pour la structure.
- Utilisation de la classe Bootstrap gx pour modifier les gap dans les colonnes.
- Utilisation de classes tels que  my, ps, pe, mb, pt, pt, pb… pour modifier des marges et padding.
- Utilisation de la classe Bootstrap d-flex pour mettre des élément en display flex.

Le reste du projet a été fait en pure css.

## Utilisation de variables CSS :

J’ai utilisé les variables CSS pour maintenir une cohérence dans les couleurs à travers tout le projet. L’utilisation de ces variables permet également une meilleure clarté et maintenabilité.

## Utilisation de flex :

Pour ce projets j’ai opté pour l’utilisation de flex et non de grid. Ce choix a été soutenu par l’utilisation du framework Bootstrap, étant donné que celui-ci utilise flex, je trouve cela plus cohérent de rester sur la même base pour l’entièreté du projet.
