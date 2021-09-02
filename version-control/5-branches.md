#### 🎄 Branches
Nuestro repositorio esta compuesto por un tronco principal (main/master) que puede o no ser la rama que se encuentran funcionando en producción y además podemos tener diferentes bifurcaciones apartir de aquí que son
llamadas ramas, las cuales nos permiten tener copias identicas desde cierto punto en cuestión para seguir trabajando sobre las mismas implementando diferentes requerimientos nuevos, parches, etc.

1. Crear una rama: `git branch testing`
2. Listado de ramas: `git branch`
3. Borrado de ramas: `git branch -d testing`
4. Movernos a un branch: `git switch / checkout testing`

Podemos utilizar un atajo en lugar del `branch & switch`.

`git checkout -b "testing-branches"`

Podemos crear etiquetas en nuestras líneas temporales al igual que los nombres que poníamos a ciertas versiones en google docs, con los tags de github.

- Crear una versión para el historial: `git tag "v1"`
- Listado de tags disponibles: `git tag`
