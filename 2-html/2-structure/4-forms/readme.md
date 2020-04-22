# Formulaires

- Balise `<form></form>`
- Paramètres
  - name: nom du formulaire
  - method: methode d'envoi des données
    - get : http uri
    - post: http body
  - action: redirection des données
    - example : fichier.php
- Structure le formulaire
- Example
  - Balise `<input>`
  - Balise `<select>`
  - Balise `<textarea>`
- Paramètre name
  - Donne un nom au champ pour pouvoir récupérer la valeur par example en php

---

- Balise `<input>`
- Paramètres
  - Name : nom du champ
  - Type : type de champ
  - Value: valeur par défault
  - Size: taille du champ
  - Maxlength: nombre max de caractères
  - Placeholder: indication (valeur fantome)
  - Readonly: Lecture seul du champ (pas possible de saisir)
  - Disabled: champ désactivé
  - Required: champ obligatoire
  - Pattern: expression régulière à respecter
- Example
  - `<input type="text" name="pays" placeholder="saisissez votre ville">`

* Types
  - Email: adresse email
  - Number: nombre
  - Tel: téléphone
  - Date: date
  - Password: mot de passe
  - Range: slider
  - Color: couleur
  - Checkbox: case à cocher
  - Radio: case à cocher
  - Hidden: champ invisible
  - Button: bouton
  - Submit : bouton validation du formulaire
* Example
  - `<input type="text" name="pays" placeholder="saisissez votre ville">`

---

- Balise `<textarea></textarea>`
- Paramètres
  - Name : nom du champ
  - Rows: nombre de lignes
  - Cols: nombre de colonnes
- Example
  - `<textaerea name="commentaire">Votre commentaire ici</textarea>`

---

- Balise <select></select>
- Paramètres
  - Size: nombre d'éléments visibles
  - Multiple: selection multiple
- Balise <option></option>
  - Options de notre select
  - Paramètre
    - value: valeur de l'option
- Example:
  ```html
  <select name="ville">
    <option value="1">Reims</option>
    <option value="2">Paris</option>
  </select>
  ```
