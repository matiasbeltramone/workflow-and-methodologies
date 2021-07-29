#### Revertir cambios

Si queremos borrar algo, nuestros compañeros ya van a tener problemas con el historial, ya que se lo estamos modificando y queda en divergencia, para hacerlo de una manera más limpia podemos utilizar un `revert`

`git revert "c546dsd66"`

_Esto nos hace un commit inverso a lo que teníamos antes (por ejemplo si metimos 10 lineas de codigo, sacaria estas 10 lineas de codigo)_

`git diff c546dsd66 master` (comparamos el revert que hicimos con lo que estaba en master) (ver ejemplo con readme para ver los cambios de texto)
