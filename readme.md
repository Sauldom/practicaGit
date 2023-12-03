Esta es la practica de git para keepconding

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  git reset --hard HEAD~1
  Es el comando que deshace el ultimo commit y lo que hay en la working copy
 
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
   git reset --hard hash del commit
   lo he descubierto con git reflog

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  al hacer el merge no me da ningun conflicto
  no deberia porque la rama que absorve tiene los mismos commits, la rama main no ha sido
  cambiada en ningun momento
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  porque la rama que absorve no tiene esos commits integrados
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  no deberia es como hacer un fastworward estamos moviendo el puntero hacia arriba 
- ¿Qué comando o comandos utilizaste en el paso 25?
  git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  yo creo que si porque todas las modificaciones de main ya estan contenidas en title
  solo subiriamos los punteros
- ¿Qué comando o comandos utilizaste en el paso 27?
- git rest HEAD~1
  para no modificar la working copy
- ¿Qué comando o comandos utilizaste en el paso 28?
- use git status y con git restore deshice los cambios que estaban a la espera 
- ¿Qué comando o comandos utilizaste en el paso 29?
  git branch -d title
  hice antes un git branch para asegurarme
  y como habia cosas colgadas ejecute un git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
  use git reset --hard hash que saque con reflog
  pero como soy un manco me equivoque de hash y lo hice otra vez
  comprobe que la rama title no estaba con git branch
  y luego comprobe con git log 
- ¿Qué comando o comandos usaste en el paso 32?
  git checkout hash del primer commit
- ¿Qué comando o comandos usaste en el punto 33?
  hice git checkout hash de la posicion anterior lo saque con reflog