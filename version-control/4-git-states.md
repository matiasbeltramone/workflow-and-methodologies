#### Estado de nuestros archivos

Tenemos 3 estados posibles de nuestros archivos:

1. Working Tree
2. Staging
3. Remote

Si creamos un archivo nuevo, no está en track por git, está en el "working tree" por lo que utilizamos
el comando `git add file_name` para que se agregue al "staging area".

Desde el momento que un archivo esta trackeado por git, podemos utilizar todos los comandos que tiene disponibles, importante recordar claramente
que dentro del "working tree" excepto por el comando `git add` que nos agrega el archivo al `staging area` lo demás es probable que no funcione para nuestro archivo no seguido.

El remoto es el que esta centralizado en Github por ejemplo y que todos hacemos subidas y bajadas del mismo para mantenernos actualizados sobre los cambios de nuestro proyecto.
