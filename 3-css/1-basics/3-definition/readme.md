# Définition

## style local

- Directement dans une balise
- Paramètre style
- Concerne uniquement cette balise
- Exemple
  - <p style="color:red;">Mon texte</p>

## style global

- Dans l'en-tête de la page HTML
- Concerne toute la page
- Balise `<style> // css </style>`
- Exemple
  ```html
  <style>
    p {
      color: red;
    }
    img {
      width: 100%;
    }
  </style>
  ```

## style externe

- Dans un fichier externe (.css)
- Concerne toutes les pages associées
- Balise `<link></link>` dans l'en-tête de la page HTML
- rel="stylesheet" : type de lien
- Href="monfichier.css": fichier cible
- Exemple
  - `<link rel="stylesheet" href="monfichier.css">`
