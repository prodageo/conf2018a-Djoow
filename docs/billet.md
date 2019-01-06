# Vanilla JS 2018

## Cartouche d'identification

 - Manifestation : CodeursEnSeine 2018
 - Lieu : Kindarena - Rouen
 - Conférence : Vanilla JS 2018
 - Horaire de la conférence : 11h - 11h50
 - Durée de la conférence : 50 mins
 - Conférencier(s) :
   - Matthieu LUX ([Twitter](https://twitter.com/Swiip), [Github](https://github.com/Swiip))
 - Audience : ~150 personnes
 - Auteur du billet : Jonathan HERVIEUX
 - Mots-clés : Javascript, Application Web, Web Components, Virtual DOM, State Management, Web Workers 
 - URL de l'illustration : ![VanillaJS](https://infobeep.info/wp-content/uploads/2017/12/Vanilla-JS-is-most-power-and-lightweight-cross-platfrom-framework.jpg)
   - quelques sources : http://vanilla-js.com, https://ourcodeworld.com/articles/read/62/js-frameworks-vs-vanillajs-use-or-not-use-a-framework-

## Support
 - [Lien vers le support (diapos) présenté en conférence](https://docs.google.com/presentation/d/e/2PACX-1vR8WYVUG87OgoKDxQ-XGCv1Y_YgZt-F27GLsWYuLUVl907FniM5g-pnaWa3PktYsYE0DZdhWRi4_3LC/pub?slide=id.g41faf9c008_0_110)
 - Nombre de diapos du support : 137
 - Plan du support : pas précis car le support est principalement composé de photographies ; le fil rouge est le projet personnel présenté.

## Résumé

Aujourd'hui, le développement Web sans frameworks ou outils externes (appelé VanillaWEB) tels que [React.js](https://reactjs.org/) ou [Webpack](https://webpack.js.org/) paraît impossible. Le but de cette conférence n'est pas de remettre en question le rôle de ces outils, qui permettent un gain de temps important pour mettre en production une application, mais de chercher à savoir s’il est actuellement viable de se passer d’eux. 

Chaque framework ou outil possède un équivalent Vanilla sur lequel on peut s’appuyer pour développer un équivalent. Ainsi, il est possible d’écrire sa propre librairie Javascript en Vanilla directement à l’aide de l’API du navigateur, qui propose par exemple les Web Components, les Custom Elements, un langage HTML enrichi (balises template etc...) ou encore les HTML imports.

Ainsi, dans l’état actuel, VanillaJS est un moyen de programmer très verbeux, mais cela fonctionne ! La principale difficulté est le temps qu'il faut consacrer à (ré)apprendre les API des navigateurs, puissante mais plus basique que les frameworks. De plus, la compatibilité entre navigateurs est inégale selon la fonctionnalité utilisée, les implémentations de l'API Javascript des navigateurs étant différente. VanillaJS et plus généralement VanillaWEB est donc viable, à condition de proscrire les anciens navigateurs et de prendre le temps d’écrire sa propre librairie Javascript.


## Architecture et facteur qualité

Les facteurs qualité de la norme ISO9126:2001 liés à ce talk sont la Portability (Portabilité), la Maintainability (Maintenabilité) et l'Efficiency (Efficacité). En effet, les frameworks modernes assurent ces trois facteurs, à savoir la portabilité du code javascript entre plusieurs navigateurs mais aussi sa maintenabilité grâce à une écriture simple et lisible. L'efficacité est elle assurée par le framework lui-même qui propose de ne pas "réinventer la roue" pour un gain de temps. 

Concernant VanillaJS, la maintenabilité n'est pas altérée puisqu'il est de la tâche du développeur de coder lisiblement et intelligemment. De plus, VanillaJS propose des fonctionnalités suffissantes pour produire un code modulaire. La portabilité est un point plus sensible : lorsqu'on parle de navigateurs modernes, ce facteur n'est pas problématique, mais il est indéniable que VanillaJS n'est pas supporté par des navigateurs anciens ou non à jour. Enfin, concernant l'efficacité, c'est un point noir de VanillaJS. En effet, même au niveau des performances l'application sera sans aucun doute bien plus optimisée que si elle avait été écrite à l'aide d'un framework, cela se paye au prix d'un temps de développement bien plus élevé. 
