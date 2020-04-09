# Portée

- La portée local l'emporte sur une portée plus générale
  - `<style>p{color:blue;}</style>`
  - `<p style="color: red;">mon text</p>`
  - > Mon text sera de couleur rouge
- Lors d'une imbrication de balises les enfants prennent le style de leurs parents s'ils n'ont pas leurs propre style
  - `<p style="color: red;"><b>mon texte</b></p>`
