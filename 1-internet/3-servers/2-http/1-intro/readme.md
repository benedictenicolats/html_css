# Serveur web

## Synonyme

- router
- request router
- multiplexer
- mux
- servemux
- server
- http router
- http request router
- http multiplexer
- http mux
- http servemux
- http server

> Vous pouvez imaginez un server web comme un restaurant. Le client demande (requete) au serveur un plat et le serveur lui apporte (reponse).

Un serveur web utilise le protocole http (HyperText Transfer Protocol) une fois la connection tcp/ip effectuée. Pour naviguer sur un site nous utilisons un URL (Uniform Resource Locator) qui contient plusieurs informations :

Analyse de http://monsiteinternet.com/article-239

- http : C’est le protocole qui va être utilisé par le navigateur pour accéder au serveur et lui adresser ces demandes.
- monsiteinternet.com : C’est l’adresse du serveur. (Je vous rappelle que pour savoir où pointe le serveur, l’ordinateur va faire une requête DNS)

Et si on parle de la ressource à récupérer ou à accéder, on va parler de URI (Uniform Resource Identifier)

> article-239 : C’est la ressource que l’on veut récupérer sur le serveur.

Cette ressource peut-être une page, mais cela pourrait être bien autre chose tel que:

- une image : http://monsiteinternet.com/tcpip.png
- de la musique : http://monsiteinternet.com/potcast_web.mp3
- un fichier à télécharger : http://monsiteinternet.com/cours_web.pdf
- etc...

Et le port où est il?

Le port par défaut pour accéder à un serveur http, le port est le 80. Nous pouvons bien entendu changer le port part default à condition d'informer le client.
