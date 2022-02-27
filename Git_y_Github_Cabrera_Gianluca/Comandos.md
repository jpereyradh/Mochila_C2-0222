Iniciar Enlazar
Iniciar git en esta carpeta
Git init

Enlazar la carpeta del disco con un Repo externo
Git remote add origin (direccion del repo)

Quitar el enlace
Git remote remove origin

Operaciones entre ramas
Crear una rama
Git Branch (nombre de rama)

Borrar una rama local
Git Branch -d (nombre de rama) Git Branch -D (nombre de rama) *SI no esta fusionada completamente

Borra una rama remota
Git push origin –delete (nombre de la rama)

Listas ramas locales
Git Branch

Listar ramas remotas
Git branch -a

Cambiar de nombre a una rama actual
Git Branch -m (nuevo nombre)

Cambiar de rama
Git checkout (nombre de rama)

Volver a un commit anterior
Git checkout (commit-id) .
Git add .
Git commit -m “Revirtiendo cambios”
Git push
