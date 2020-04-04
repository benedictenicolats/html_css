# Request & response

Les messages des requetes et des réponses sont similaire. Les deux messages consiste à:

- request/response line
- 0 ou plus lignes pour les headers
- une ligne vide (ie, CRLF)
- un message optionel pour le body (corp)

---

## HTTP request

Request

- request line
- headers
- message optionnel body

Request-Line

- Method SP Request-URI SP HTTP-Version CRLF

exemple de request line:

- GET /path/to/file/index.html HTTP/1.1

---

## HTTP response

Reponse

- status line
- headers
- message optionnel body

Status-Line

- HTTP-Version SP Status-Code SP Reason-Phrase CRLF

exemple de status line:

- HTTP/1.1 200 OK

---

## Headers

[Liste des champs headers](https://en.wikipedia.org/wiki/List_of_HTTP_header_fields)

---

## Pour inspecter

- vous pouvez utilisez google chrome dev tools / network
- vous pouvez utilisez cURL en ligne de commande

```
curl -v google.com
```

## Client/Server Messaging

HTTP est un protocole de request/response sans état qui fonctionne par
échange des messages à travers un transport fiable ou
Couche SESSION "CONNEXION".

Un "CLIENT" HTTP est un programme qui établit une CONNEXION à un serveur
dans le but d'envoyer une ou plusieurs requêtes HTTP.

Un "SERVEUR" HTTP est un programme qui accepte les CONNEXIONS afin de répondre aux requêtes HTTP en envoyant des réponses HTTP.
