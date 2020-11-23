Création d'un blog personnel de veille technologique dans le cadre du cours **LabVeilTech** à la HEIG-VD

# Hugo
Création d'un site statique grace à [Hugo](https://gohugo.io/).  
`brew install hugo`  
`hugo version`  
`hugo new site mon-site-de-veille`

# Choix du thème
Choix du thème [Codex](https://themes.gohugo.io/hugo-theme-codex/).
![](https://d33wubrfki0l68.cloudfront.net/3c9146b977bbef91f92600d0669a7548b764e7e0/360fe/hugo-theme-codex/screenshot-hugo-theme-codex_hu2e503dcb16114be293da4f05196c31ac_32296_1500x1000_fill_catmullrom_top_2.png)
`git submodule add https://github.com/jakewies/hugo-theme-codex.git themes/hugo-theme-codex`

## Pourquoi ?
* Site minimaliste
* Adapté pour un blog
* Possibilité d'ajouter des tags pour rechercher facilement les articles qui parlent d'un thème
* Ajout facile d'articles avec la [syntaxe Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

# Structure du site
## But
Mon but est de regrouper sur cette plateforme la base données d'articles sur l'UX que je m'étais déjà créée (actuellement sur Google Docs).  
Je désire pouvoir stocker et retrouver des liens sur des articles très facilement, ainsi que pouvoir en écrire d'autres.

## Structure actuelle
Le site est composé de trois parties :

* **About** : courte description du site
![](https://www.zupimages.net/up/20/48/g1dv.png)
* **Blog** : post sur l'UX
![](https://www.zupimages.net/up/20/48/lyhs.png)
* **Links** : fonctionne comme une base de données avec des liens sur des articles intéressants. Il y a un post pour chaque catégories (UX Writing, UX Design, UI, etc.).
![](https://www.zupimages.net/up/20/48/w3wt.png)

Suivant la quantité d'information, je pense créer un onglet de navigation pour chaque sous-domaine UX.
