PREGUNTAS EJERCICIO 1
- ¿Que comando utilizaste en el paso 
11? ¿Porque? 
"Git reset - - hard HEAD~1"
Vuelvo al paso anterior reescribiendo mi 
working copy

- ¿Que comandos utilizastes en el paso 
12? ¿Porque?  
Git reflog para buscar el HASH del 
commit
Git reset HASH voy hasta el commit con 
HEAD y STYLED
Git status compruebo el estado de mis 
áreas
Git restore git-nuestro.md recupero el 
archivo con los cambios


-El merge del paso 13, causa conflicto? 
Porque? 
Git merge main absorbo la rama main
Hace un merge fast forward y no causa 
conflicto


-El merge del paso 19, causa conflicto? 
Porque? 
Git checkout styled 
Git merge htmlify
Causa conflicto porque tiene modificado 
el archivo git-nuestro.md en las dos 
ramas
 
- Merge del paso 21, causa conflicto? 
Porque? 
Git checkout main
Git merge styled
No causa conflicto porque tienen mismos 
archivos

- Que comando utilizaste en el 
paso 25?
git log --graph
Adjunto imagen en draw.io

- El merge del paso 26. ¿Podria ser fast 
forwars? ¿Porque?
Git merge - -no-ff title
Podria ser fast forward ya que 
no perderiamos los caminos a los 
diferentes commits

- Que comandos utilizastes en el paso 27?
git reset HEAD~1

- Que comandos utilizastes en el paso 28?
Git restore git-nuestro.md

- Que comandos utilizastes en el paso 29?
Git Branch -D title

- Que comandos utilizastes en el paso 30?
Git reflog
git merge 434becc

- Que comandos utilizastes en el paso 32?
Git reflog
Git reset 83818ac

- Que comandos utilizastes en el paso 33?
Git reset 434becc

