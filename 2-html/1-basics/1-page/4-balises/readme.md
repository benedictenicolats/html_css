# Les balises

- Certaines balises s'ouvrent et se ferment pour encapsuler du code (balise avec portée)
  - `<body>` la balise ouvrante body
  - `</body>` la balise fermante du body
  - Le code compris entre ces deux balises sera "contenu" par les balises body, on dit que body est un container (conteneur)
- D'autre balise ne sont pas des conteneurs
  - `<img>` la balise image ne contient pas de code html
- Le HTML contient environ 140 balises qui fournissent au navigateur des indications sur le sens d'un élément.
  - https://developer.mozilla.org/fr/docs/Web/HTML/Element

# Paramètres d'une balise

Certaines balises HTML peuvent avoir des paramètres:

- Un paramètre modifie le comportement de la balise
- Les paramètres se placent entre les `< >` de la balise
  - `<a href="https://google.com">`
    - La balise `<a>` avec un paramètre href dont la valeur est https://google.com (le lien cible de la balise `<a>`)
  - `<a href="https://google.com" target="_blank">`
    - La balise `<a>` garde le paramètre href et nous lui ajoutons le paramètre target avec la valeur \_blank (qui ouvre le lien dans un nouvel onglet)
