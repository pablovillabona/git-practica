# Respuestas práctica del curso

## Ejercicio 1:

> 1) git reset HEAD~1, para volver el HEAd al nodo anterior en la rama 
styled

> 2) git reflog, para recuperar el anterior commit.

> 3) No, styled absorbe a main y al ser un merge fastforward la rama y 
HEAd se quedan en el último commit.

> 4) No, styled absorbe a htmlify y al ser un merge fast forward  no causa 
conflicto.

> 5) No, main absorbe styled y al ser un merge fast forward la rama styled 
y HEAD pasan al último commit de main.

> 6) git graph

> 7) Si, perdiendo los cambios de la rama title.

> 8) git reset HEAD~1

> 9) git restore git-nuestro.md

> 10) git branch -D title

> 11) git reflog + git reset --hard con el codigo del 
ultimo commit que queremos recuperar.

> 12) git checkout + codigo del commit del primer poema

> 13) git checkout main 
