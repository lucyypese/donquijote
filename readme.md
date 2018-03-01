# Práctica GIT

### Pérez Sierra, Luca


<p>- ¿Qué comando utilizaste en el paso 11? ¿Por qué? </p>
git reset --hard HEAD~1
Este es el reset que pierde también lo que hay en el Working Copy. El 1 es el nº de commits que vamos atrás.</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? </p>
<p>git reset --hard HEAD@{1}
Este reset rehace, al contrario que el anterior reset. Y al igual, el 1 es el nº de commits que vamos adelante.</p>

<p>- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? </p>
<p>No.</p>

<p>- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? </p>
<p>Sí.
Auto-merging don-quijote.md
CONFLICT (content): Merge conflict in don-quijote.md
Automatic merge failed; fix conflicts and then commit the result.
Las dos ramas estaban actuando sobre el mismo archivo, así que para resolverlo había que borrar el archivo de hmltify, añadir al git los cambios del archivo y hacer un commit.</p>

<p>- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? </p>
<p>No.</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 25? </p>
<p>git log --graph</p>

<p>- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? </p>
<p>No. Porque se necesita hacer una fusión que cree un commit para representar ésta, que esté a parte pero sin dejar de separarse.</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 27? </p>
git reset HEAD~1</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 28? </p>
<p>git reset --hard</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 29? </p>
<p>git branch -D title</p>

<p>- ¿Qué comando o comandos utilizaste en el paso 30? </p>
<p>Con git reflog vemos el identificador del merge, y ponemos git reset f21d082.</p>

<p>- ¿Qué comando o comandos usaste en el paso 32? </p>
<p>Git reflog para ver el nº identificador del commit:
0d424f4 HEAD@{22}: commit (initial): Creo el poema
Y git reset 0d424f4.</p>

<p>- ¿Qué comando o comandos usaste en el punto 33? </p>
<p>git reset --hard e810159</p>


