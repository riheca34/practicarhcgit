
¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, Porque este baja el puntero de HEAD una posición y ademas es como si hiciera rm, quitar el fichero, y volver al original.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset 714ce8d, que era el comit para dejarlo como estaba.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
no, porque dejamos a rama como estaba y desaciendo los cambios.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
no, porque una vez creada la rama htmlify, hicimos una modidicacion y un commit y no realizamos ningun
cambio en la rama
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
no, de igual forma al seguir el grafo sin hacer cambios en las ramas, cada una por su cuenta, no hay conflictos.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
si, porque las otras ramas creadas en el proyecto ya estaban 'mergeadas' en master, al partir de master la rama 
tittle, no hay vifurcaciones.
- ¿Qué comando o comandos utilizaste en el paso 27?
git checkout al commit anterior al merge. --no es correcta, cambiar
- ¿Qué comando o comandos utilizaste en el paso 28?
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D tittle
- ¿Qué comando o comandos utilizaste en el paso 30?
git checkout master, 
- ¿Qué comando o comandos usaste en el paso 32?
git checkout 51edf4e, que es el commit inicial.
- ¿Qué comando o comandos usaste en el punto 33
git checkout 456f615 HEAD@{4}: commit: añadiendo titulo personal que es el commit donde añadimos el titulo

