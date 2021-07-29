#### Guardar cambios temporales (Stash)
`$ git stash`: Crea un paquetito de las cosas que tenemos hasta el momento modificadas,
los dejamos en alguna mochilita escondidos como la busqueda del tesoro en el fondo del patio
(Es útil en varias ocasiones por ejemplo:
cuando necesitamos arreglar un hotfix mientras hacemos otra issue,
o si teniamos un commit escribimos algo y rompimos todo el sistema sin saber porque,
tiramos stash y vemos si andaba antes,
comprobando que algo que escribimos rompio el estado actual de la app)

**Solo funciona con archivos trackeados por git (si estaba en working directory no funcionaria)**

- Recuperar último stash: `$ git stash pop`
- Listado de stashes: `$ git stash list`
- Recuperar un stash: `$ git stash pop 1`
