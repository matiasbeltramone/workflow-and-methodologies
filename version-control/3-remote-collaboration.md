#### Colaboración Remota (Hostings)

Esta genial hasta ahora podemos versionar nuestro proyecto para nosotros mismos,
pero si quiero colaborar con más personas y que todos colaboremos sobre el mismo proyecto,
necesitamos de un hosting remoto, donde todas las personas puedan realizar
sus colaboraciones.

Hostings:

- Bitbucket
- GitLab
- **GitHub**

#### Creación de Repositorios
Creamos un repositorio de prueba en Github, para subir nuestro código que esta en local.

Nos ofrece dos comandos:

- `git remote add origin git@github.com:matiasbeltramone/workflow-and-methodologies.git`
- `git push -u origin master`

Primero agregamos a nuestro repositorio local, una referencia al hosting remoto, que se identifica con el nombre `origin`. Después que estan linkeados ambos repositorios (local y remoto) subimos los cambios del local al remoto con el `git push`.

_"Origin es el nombre que tiene el repositorio remoto."_

_Remote son los reposotorios remotos que tenemos conectados a nuestro repositorio local, y el origin es el que le damos como nombre convención que usaremos como repositorio central del equipo en este caso el de github._
