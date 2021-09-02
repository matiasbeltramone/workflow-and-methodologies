### 👇 Fetch vs Pull
Creamos desde GitHub una rama mediante un PR (simulamos ser un compañero de trabajo)

Ejecutamos en nuestro local: `git branch -a` pero notamos que no hay nada nuevo.

Git es un sistema de versiones distribuido por lo tanto cada usuario tiene en su computadora, su propia version del repositorio,
y esto lo hace independiente de si tenemos conexión al remoto o no.

Esto genera la necesidad de un `sync` con las ramas del remoto contra las de nuestro local.

Traer las ramas del remoto mediante: `git fetch origin`, esto nos trae las referencias nuevas que tenemos de ramas que se
han creado y subido al remoto.

Hacemos alguna prueba de índices: realizamos un merge del PR que habíamos abierto contra master, en el cuál simplemente podemos hacer un cambio a nuestro archivo README.md.

Vamos a master y mostramos nuestro fichero README.md que tenemos en el local.

Ejecutamos un: `git pull` y esto inmediatamente hace las cosas del `fetch` pero también nos trae los cambios que se
realizaron, es decir, movió el índice al lugar más actualizado.

El pull primero hace un fetch que nos dice existe una nueva referencia en el `origin/master`.

Luego hace un "merge", es decir, unifica el `origin/master` con `master` (local), para agregar este commit que
se realizo en el master de nuestro local.

_Tip: `git fetch -ap` lo que hace es todas las ramas que esten en remoto y que ya no existan las limpia.
(Puede ser del origin que es github y además de un fork que haya realizado algún compañero)._

