#### 👯‍ Alias de Git
Configurar los alias en nuestro archivo de configuración: `nano ~/.gitconfig`

Agregamos:
```
[alias]
  st = status
```
Hacemos la prueba en consola en lugar del: `git status usamos git st`

Agregamos uno mas complejo ya que siempre hacemos un add -A & commit:

```
[alias]
  c = !git add -A && git commit
```

El signo `!` nos obvia de poner el comando git, y así no da problemas con doble comandos.

Más avanzado:
```
[alias]
  reset-permissions = !git diff -p -R --no-color | grep -E "^(diff|(old|new) mode)" --color=never | git apply
```

_En este comando en particular se usa la potencia del bash_

Lo que hace por arriba es que el output del `diff``se lo pasa gracias al pipe `|` a la expresión regular de la derecha, que basicamente se queda con las diferencias que hacen referencia a `mode` es decir, a los permisos del archivo.

¿Cuando lo solemos usar? Muchas veces haciendo pruebas de que algo no nos funciona solemos tirar algun: `chmod 777 -R` y destrozamos todo el proyecto, con esto nos ayuda a revertir esos cambios de una manera sencilla, o en otras ocasiones cuando unos usan Linux y otros Windows, se hacen conflictos de permisos.
