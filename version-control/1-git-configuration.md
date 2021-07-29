# Git Configuration ⚙️

#### Instalación

- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

#### Configuración Básica
Cuenta global de mi usuario para que en el historico de cada proyecto figure a mis datos:

- git config --global user.name "Matías Beltramone"
- git config --global user.email "mbeltramone@gmail.com"

Esta configuración aplica como bien dice el flag, a todos los proyectos que esten en la usuario de la computadora que estoy utilizando y esta instalado git.

Configuración de mi usuario realizada: `$ head -n 3 ~/.gitconfig`

```
[user]
name = Matias Beltramone
email = mgbeltramone@gmail.com
```

#### Configuración de un repositorio en nuestro local

Creamos una carpeta: `$ mkdir workflows-and-methodologies`

Inicializamos una carpeta con git para que quede versionada: `$ git init`

Visualizamos que paso sobre esa carpeta: `$ ls -la`, se creo una carpeta `.git` (por lo que esta instalado git como versionador de nuestra carpeta), es decir, vemos que se convirtio en un repositorio.

#### Clonando Repositorios

Otro camino que tenemos disponible es clonar o hacer una copia de un repositorio que ya existe en `Github` por ejemplo.

`$ git clone git@github.com:matiasbeltramone/workflow-and-methodologies.git`

En cualquiera de los dos caminos tomados terminamos con lo mismo, es decir, una carpeta que es nuestro reposotorio y mediante `git` tiene un control de versiones en sí misma.

Nosotros tomamos a Github como ejemplo de plataforma de hosting de los mismos porque es una de las más usadas a nivel mundial, pero existen otras disponibles como: GitLab, Bitbucket, etc.
