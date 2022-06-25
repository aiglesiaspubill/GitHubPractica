11)	Deshacer el último commit 
(perdiendo los cambios realizados en el 
working copy) 
Git reset - - hard HEAD~1 
12)	Rehacer el último commit (el que 
acabamos de deshacer) 
Git reflog para buscar el HASH del 
commit
Git reset HASH  voy hasta el commit con 
HEAD y STYLED
Git status compruebo el estado de mis 
áreas
Git restore git-nuestro.md  recupero el 
archivo con los cambios
13)	Hacer un merge con ‘master’ 
(styled absorbe a master) 
Git merge main  absorbo la rama main
19)	Hacer un merge de “htmlify” en 
“styled” (styled absorbe a htmlify) 
Git checkout styled 
Git merge htmlify 
21)	Desde “master”, hacer un merge 
con “styled” 
Git checkout main
25)	Dibujar el diagrama
Archivo en la rama main 
26)	Hacer un merge “no fast-forward” 
de “title” en “master” (master absorbe a 
title) 
Git merge - -no-ff title

27)	Deshacer el merge (sin perder los 
cambios del working copy)
git reset HEAD~1
28)	Descartar los cambios
Git restore git-nuestro.md
29)	Eliminar la rama “title”
Git Branch -D title
30)	Rehacer el merge que hemos 
deshecho
Git reflog
git merge 434becc
32)	Volver al commit inicial cuando 
se creó el poema
Git reflog
Git reset 83818ac
33)	Volver al estado final, cuando 
pusimos título al poema
Git reset 434becc

