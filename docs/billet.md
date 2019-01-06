# Vanilla JS 2018

## Cartouche d'identification

 - Manifestation : CodeursEnSeine 2018
 - Lieu : Kindarena - Rouen
 - Conférence : Vanilla JS 2018
 - Horaire de la conférence : 11h
 - Durée de la conférence : 50 mins
 - Conférencier(s) :
   - Matthieu Lux ([Twitter](https://twitter.com/Swiip), [Github](https://github.com/Swiip))
 - Audience : ~150 personnes
 - Auteur du billet : Jonathan Hervieux
 - Mots-clés : Javascript, Application Web, Web Components, Virtual DOM, State Management, Web Workers 
 - URL de l'illustration : ![VanillaJS](https://infobeep.info/wp-content/uploads/2017/12/Vanilla-JS-is-most-power-and-lightweight-cross-platfrom-framework.jpg)
   - quelques sources : http://vanilla-js.com, https://ourcodeworld.com/articles/read/62/js-frameworks-vs-vanillajs-use-or-not-use-a-framework-

## Support
 - [Lien vers le support (diapos) présenté en conférence](https://docs.google.com/presentation/d/e/2PACX-1vR8WYVUG87OgoKDxQ-XGCv1Y_YgZt-F27GLsWYuLUVl907FniM5g-pnaWa3PktYsYE0DZdhWRi4_3LC/pub?slide=id.g41faf9c008_0_110)
 - Nombre de diapos du support : 137
 - Plan du support : pas précis, le fil rouge est le projet personnel présenté.

## Résumé

Aujourd'hui, le développement Web paraît impossible sans l'utilisation des frameworks et des outils les plus populaires tels que [React.js](https://reactjs.org/) ou [Webpack](https://webpack.js.org/). La grande question de cette conférence est donc de savoir s'il est possible et viable de se lancer dans un projet sans frameworks. Le but n'est pas de remettre en question le rôle des frameworks, qui sont un gain de temp essentiel pour mettre en production une application rapidement, mais de chercher à (ré-)apprendre le fonctionnement d'un navigateur et des bases qui font fonctionner nos frameworks favoris. Cette grande redécouverte est présentée à travers un projet personnel dont le but est de coder le jeu [2048](https://fr.wikipedia.org/wiki/2048_(jeu_vid%C3%A9o)) en VanillaJS et dont les 3 règles sont : coder tout soi-même, utiliser les dernières nouveautés des navigateurs, le projet doit fonctionner sur au moins deux navigateurs.

Ainsi, le conférencier présente tour à tour les technologies Vanilla qui remplacent celles couramment utilisées. Au lieu de Webpack, il s'agira de directement utiliser le protocole HTTP/2 et sa fonctionalité de push permettant une gestion intelligente des dépendances. La deuxième technologie à remplacer est [Babel](https://babeljs.io/), qui permet la rétro-compatibilité avec les vieux navigateurs. Dans le cadre de ce projet, le conférencier explique qu'il n'est tout simplement pas nécessaire d'utiliser cette technologie car les navigateurs récents (Chrome, Firefox sauf Internet Explorer) sont comptatibles avec les dernières nouveautés. Enfin, les frameworks javascripts sont ici remplacées par les dernières API internes au langage javascript : les Web Components, Custom Elements, le langage HTML enrichi (balises template etc...), et les HTML imports.

Globalement, VanillaJS est verbeux. Pourtant, cela fonctionne ! La principale difficulté est donc le temps qu'il faut consacrer à réapprendre une toute nouvelle API (inconnue pour ceux qui utilisent déjà les frameworks récents) et de réécrire à la main les fonctionnalités basiques de ces frameworks. De plus, la comptabilité avec les navigateurs est quelque chose qui n'est pas certaine, les implémentations entre les navigateurs étant différentes.

## Architecture et facteur qualité
...
