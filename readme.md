# EJERCICIO 1

- ¿Que comando utilizaste en el paso 11?
En el paso 11 utilizo el comando git reset --hard HEAD~1
¿Porque?
porque con ese comando me muevo al commit anterior y ademas modifico el working copy tambien

- ¿Que comando o comandos utilizaste en el paso 12?
Primero utilizo el comando reflog para acceder al historial de todos los commits, busco el que me 
interesa rescatar, anoto el identificador, y a continuacion escribo el comando git reset --hard mas 
el 
identificador.
¿Porque?
porque necesito el reflog para buscar el commit que me intersa rescatar y despues hago un reset 
--hard mas el id para moverme a él, y ademass con hard lo recuperas tambien en el working copy.

- El merge del paso 13, ¿causo algun conflicto?
No, no causó ningun conflicto.
¿Porque?
porque no ha variado nada practicamente ya que estamos en la rama styled que tiene el commit mas 
actual, y en el grafo estan en una lista.

- El merge del paso 19. ¿Causo algun conflicto?
Si, causo un conflicto.
¿Por que?
porque el archico git-nuestro.md en las nismas lineas tiene contenido distinto.

- El merge en el paso 21. ¿Causo algun conflicto?
No, no causo ningun conflicto.
¿Por que?
porque estan dentro de una misma lista, no existe ninguna bifurcacion.

- ¿Que comandos o comando utilizaste en le paso 25?
git log --graph

- El merge en el paso 26 , ¿Podria ser fast-forward?
Si podia haber sido fast-forward.
¿Por que?
porque no existe bifurcacion y estamos en la misma lista.

- ¿Que comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Que comando o comandos utilizastes en el paso 28?
git reflog
git reset --hard "id commit necesario"

- ¿Que comando o comandos utilizastes en el paso 29?
git branch
git branch -D title

- ¿Que comando o comandos utilizastes en el paso 30?
git reset --hard "id commit necesario"

- ¿Que comando o comandos utilizastes en el paso 32?
git reflog
git reset --hard "id commit necesario"

- ¿Que comando o comandos utilizastes en el paso 33?
git reflog
git reset --hard "id commit necesario"

