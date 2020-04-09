# Selecteurs

- Balise inclue dans une autre
  - `div p {color: red;}`
  - `<div><p>mon texte</p></div>`
- Balise fille direct d'une autre
  - `DIV P {color: red;}`
  - `<div><p>mon texte</p></div>`
- Balise multiple
  - `h1, h2, p {color: red;}`
  - `<p>mon texte</p>`

* class
  - Paramètre d'une balise
    - `<p class="description">ma description</p>`
  - `.description{color: red;}`
* id
  - Paramètre d'une balise (unique)
    - `<p id="description">ma description</p>`
  - `#description{color: red;}`

---

## Attributs

- [attribut]
  - Attribut défini
- [attribut="foo"]
  - Attribut dont la valeur est définie à foo
- [attribut~="foo"]
  - Attribut dont la valeur contient foo
- [attribut|="foo"]
  - Attribut dont la valeur commence par foo
- [attribut^="foo"]
  - Attribut dont la valeur commence exactement par foo
- [attribut$="foo"]
  - Attribut dont la valeur finit exactement par foo
- [attribut*="foo"]

  - Attribut dont la valeur contient au moins une fois foo

- Exemple

  - ```css
    input[type='text'] {
      color: red;
    }
    ```

---

## Pseudo-classes

- :hover
  - Elément lorsqu'il est survolé
- :focus
  - Elément lorsqu'il est focus
- :first-letter
  - Première lettre de l'élément
- :before
  - Elément positionné avant
- :after
  - Elément positionné après
- :nth-child(x)
  - X : Xeme enfant
- :nth-last-child(x)
  - X : Xeme enfant en partant de la fin
- :first-child
  - Premier enfant
- :last-child
  - Dernier enfant
- Etc
  - https://www.w3schools.com/css/css_pseudo_classes.asp
