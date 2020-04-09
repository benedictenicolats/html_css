# Responsive

> Un site web vise, grâce à différents principes et techniques, à offrir une consultation confortable sur des écrans de tailles très différentes. L'utilisateur peut ainsi consulter le même site web à travers une large gamme d'appareils (ordinateur, smartphone, tablettes, télévision…) avec le même confort visuel et sans avoir recours au défilement horizontal ou au zoom avant/arrière sur les appareils tactiles notamment, manipulations qui peuvent parfois dégrader l'expérience utilisateur, tant en lecture qu'en navigation.

Les requêtes média (media queries) permettent de modifier l'apparence d'un site ou d'une application en fonction du type d'appareil (impression ou écran par exemple) et de ses caractéristiques (la résolution d'écran ou la largeur de la zone d'affichage (viewport) par exemple).

## Syntaxe

Une requête média se compose d'un type de média optionnel et d'une ou plusieurs expressions de caractéristiques de média. Plusieurs requêtes peuvent être combinées entre elles grâce à des opérateurs logiques. Les requêtes média ne sont pas sensibles à la casse.

Une requête média vaut true si le type de média correspond à l'appareil utilisé pour l'affichage du document et si toutes les expressions relatives aux caractéristiques sont vraies. Les requêtes qui utilisent des types de média inconnus valent toujours false.

### types de média

- all
  - Correspond pour tous les appareils.
- print
  - Correspond aux matériaux paginés et aux documents consultés en aperçu avant impression. Pour plus d'informations, voir l'article sur les média paginés.
- screen
  - Correspond aux appareils dotés d'un écran.
- speech
  - Correspond aux outils de synthèse vocale.

### opérateurs logiques

- and
  - L'opérateur and permet de combiner plusieurs requêtes média en une seule. Pour que la requête résultante soit vraie, il faut que chacune des sous-requêtes soit vraie. Cet opérateur est également utilisé afin de relier des caractéristiques média avec des types de média.
- only
  - L'opérateur only est utilisé afin d'appliquer un style uniquement si l'intégralité de la requête est vérifiée. Il permet d'empêcher les anciens navigateurs d'appliquer les styles concernés. Si on utilise pas only, un ancien navigateur interprètera screen and (max-width: 500px) comme screen uniquement (appliquant ainsi le style à tous les écrans). Si l'opérateur only est utilisé, la requête doit nécessairement contenir un type de média.
- not
  - L'opérateur not est utilisé afin d'obtenir le résultat opposé d'une requête média (il renvoie true si l'opérande renvoie false). S'il est utilisé dans une liste de requêtes séparées par des virgules, il ne nie que la requête sur laquelle il est appliqué. Si l'opérateur not est utilisé, la requête doit nécessairement contenir un type de média.
