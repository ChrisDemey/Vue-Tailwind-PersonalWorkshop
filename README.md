# Vue.js & Tailwind

#### <a href="En.md">English version</a>

![Tailwind and Vue logo](assets/img/tailwindvue.jpeg)
Ce mini-workshop a pour but de montrer les étapes à suivre afin de créer les bases d'un projet Vue.js couplé avec le framework Tailwindcss.

### VueJS

Il s'agit d'un framework Javascript. Jusqu'ici je pense que tout le monde suit. Mais nous n'allons pas trop nous attarder sur les détails.

Si vous voulez de la bonne documentation, quoi de mieux que le site de <a href="https://fr.vuejs.org/index.html">Vue</a>!

Et pour ceux qui ne se sont pas encore familiariser avec Vue, voici le <a href="https://github.com/jeandavidwuilquot/VueJS-workshop">workshop</a> d'un ancien BeCodien qui explique les bases de ce framework. Allez-y! Et revenez quand vous serez prêts.

Pour les autres, on passe à la suite.

Ici nous n'allons pas utiliser de CDN mais passer par le CLI (Command Line Interface). Mais ne vous inquiétez pas tout se passera bien.

#### Configurer et créer un projet Vue
Tout d'abord on va installer le package de Vue afin d'utiliser les commandes requises (Ceci dit avec le workshop donné plus haut ça devrait déjà être fait!). Ouvrez un terminal et tapez:
```
$ npm install -g @vue/cli
```
Maintenant, toujours avec le terminal, allez où vous voulez pour créer votre premmier projet qu'on va appeler my-app (vive l'originalité) et tapez:
```
$ vue create my-app
```
Vous allez avoir un choix qui va s'afficher dans le terminal. 
- **'default'** : inclut de base babel et eslint.
- **'manually select features'** : permet de choisir ce dont vous avez besoin pour votre projet.

Choisissons ***Manually select features***.

Ensuite, nous allons laisser ***Babel*** et ***Linter / Formatter*** cochés. Ce sera uniquement pour la base, mais libre à vous de choisir ce dont vous avez besoin en plus. (cochez et décochez avec la barre d'espace).

Concernant linter, je choisis ***ESLint + Standard config***, mais à chacuns ses choix.
Ensuite ***Lint on save*** est un must.
Et enfin, le plus important! Choisissez ***In dedicated config files***. Ceci est absolument nécessaire pour la suite.

### TailwindCSS

Qu'est-ce donc que cette chose là? Il s'agit d'un framework CSS sans toucher une ligne de CSS.
Les aficionados de Bootstrap s'y retrouveront assez vite, mais pour les plus curieux, voici le <a href="https://tailwindcss.com/">site</a>.

Ici notre but ultime, si vous ne l'avez pas compris, c'est de faire un projet Vue **SANS TOUCHER UNE LIGNE DE CSS**. Ce qui pourrait paraître fou pour certains, mais vous allez voir, la magie va opérer ;)

#### Installation et configuration

Comme pour Vue, ouvrez à nouveau votre terminal, ou bien revenez-y. Mais vous devrez revenir à la racine du projet créé précédemment. Puis mettez cette ligne de commande:
```
$ vue add tailwind
```
Lors de l'installation un fichier **tailwind.config.js** sera créé, mais avec un choix:
- **'none'** : ne créé pas le fichier.
- **'minimal'** : créé le fichier en version minimal. Permet de personnaliser uniquement ce dont vous avez besoin du framework.
- **'full'** : créé la version full de ce fichier. Et ceci permet de personnaliser l'entièreté de Tailwind dans votre projet.

Mais le mieux, pour commencer en tout cas, c'est choisir l'option ***minimal***. Pas besoin d'importer ce que l'on n'aura pas besoin d'utiliser.

Et...... **FINI!!!**

Maintenant à vous de jouer et de (re)découvrir **Vue.js** et **Tailwindcss**.