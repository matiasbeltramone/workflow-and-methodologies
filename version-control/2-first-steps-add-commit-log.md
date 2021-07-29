#### Primeros pasos

Creamos un archivo para mostrar un flujo de trabajo normal: `$ touch README.md`

- Vemos el estado de nuestro repositorio local: `$ git status`
- Agregamos al stage el archivo creado: `git add README.md`
- Confirmamos nuestros cambios con un mensaje de lo que hicimos: `git commit -m "message"`
- Podemos ver todos nuestros puntos en el histórico marcados: `$ git log (igual que google docs que nos muestra las versiones)`

En esos pasos anteriores podemos notar un conjunto de 4 comandos en total, los cuáles nos acompañaran durante el resto de nuestras vidas como programadores.

#### Git Status
Este comando simplemente lo que busca es mostrarnos en que estado se encuentra nuestro repositorio actual, en que rama nos encontramos actualmente (ya hablaremos de ramas en otro apartado)
cuál es el estado de nuestros archivos en la carpeta que ya se encuentren bajo el control de git y que archivos todavía no se encuentran bajo el control del mismo(seguramente archivos nuevos).

Estados posibles:
 - Working Directory
 - Staging Area
 - Remote Repository

#### Git Add
Cuando queremos que git nos tome cambios de un archivo nuevo creado u alguna modificación sobre alguno que ya se encuentra bajo el control de git lo que hacemos es el uso de este comando, es decir, `git add file_name`
eso agrega a nuestro área intermedia el archivo con el estado nuevo en cuestión y lo deja a la espera de que realicemos el commit.

#### Git Commit
Cuando agregamos uno o varios archivos mediante el comando `git add` lo que queda a la espera es que se realice un nombreamiento de estos cambios, es decir, como si fuera una marca en nuestra línea de tiempo, para
poder identificar que es lo que paso durante esos cambios por ejemplo `git commit -m "Initial Configuration"` normalmente el flag -m nos permite ingresar una cadena para nombrarlo.

#### Git Log
Una vez terminados los dos pasos anteriores si escribimos en nuestra consola `git log` vamos a poder observar nuestra lista de commits anteriores con su hash correspondiente.
Si su hash correspondiente... esto que identifica a cada punto marcado en la historia y que es lo que nos permite poder volver atrás, irnos a un punto especifico por un rato, o simplemente extraer un commit especifico a otra parte.

#### Herramientas gráficas:
Todos los comandos mencionados anteriormente entre otros que vamos a ir viendo, son los comandos nativos que podemos ejecutar en la consola o shell para realizar ciertas acciones,
pero también existen herramientas gráficas por si no nos gusta tener que acordarnos a detalle los comandos con sus flags (debo decir que prefiero la consola al menos en mi caso), estas nos facilitan su uso algunas de ellas son:

- Sourcetree
- Gitkraken
- IDE de turno como podrían ser la familia de JetBrains que incluye su propio Gestor de control de versiones para manejarlo de manera sencilla.
