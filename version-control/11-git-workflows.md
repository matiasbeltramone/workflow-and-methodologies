#### Organización de los Flujos de Trabajo
Hablamos de flujos de trabajo en términos de gestión de PRs.

- Labels
- Github Project
- PR Status

#### Labels

![Screenshot from 2020-05-28 08-01-26](https://user-images.githubusercontent.com/22304957/83133592-7a54e780-a0b9-11ea-9349-2b46261a9e3d.png)

Workflow:

![flujo](https://user-images.githubusercontent.com/22304957/83133852-d6b80700-a0b9-11ea-80ce-a51212378be5.png)

Es importante darse cuenta que cuando un reviewer nos pide cambios a realizar debe haber una convención de equipo a nivel de que tipo de comentarios son obligatorios realizar
para que esto se integre a la rama principal, o si ciertos comentarios si bien se pueden tomar como feedback solamente y pueden mergearse de la misma manera sin replantearse lo que nos comentaron.

Comentarios del tipo:
- Yo lo hubiera hecho de otra manera. (Sin romper las convenciones que tenemos de equipo, paradigma de programación, estilos, etc). Que respecto a esto es genial aprendemos algo nuevo pero puede ir igual a producción.
- Otro tipo es el esto va a romper algo en producción por tal y tal motivo.

##### GitHub Projects
Tablero kanban que tiene ciertas automatizaciones, revisarlas ya que puede ser interesante, siempre que no tengamos algún Trello / Jira que ya lo usemos para este fin.

Después dentro de los Projects podemos tener diferentes milestones que nos permiten segmentarlos en días o sprints por ejemplo.

##### Draft Pull Request
Es una feature más sencilla en la cuál cuando creamos un PR podemos crearlo en "Modo Draft", basicamente esto simboliza que estamos trabajando.
Si bien no estaría listo para revisión, le estamos dando a nuestros compañeros un margen de que puedan ir viendo lo que hacemos y en ciertos casos que nos marquen algún error temprano el cuál nos permite
que no se lleve hasta el final.
