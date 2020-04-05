# Chemin relatif vs chemin absolu

## Chemin relatif

```
dossier/page.html
```

La cible (page.html) va être cherchée dans le sous-répertoire "dossier".

```
./dossier/page.html
```

`./` : signifie que la page est cherchée à partir du répertoire courant.

```
../dossier/page.html
```

`../` : signifie que la page est cherchée à partir du répertoire parent (on remonte d'un niveau).

Il est tout à fait possible de remonter plusieurs répertoires. Pour cela il faudra cumuler les `../` et ainsi pour remonter de deux niveaux, il sera possible d'écrire `../../dossier/page.html`.
