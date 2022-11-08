#### git init -> Crear git en local

#### git status -> Estado de los archivos

#### git add . -> Alistar archivos

#### git reset ~ruta/nombre~ -> Remover el archivo

#### git commit -m "~mensaje~" -> Subir archivos alistados

#### git log --oneline -> mostrar versiones

#### git checkout -- . -> Volver al ultimo commit

#### git branch -> mirar en que rama estamos

#### git commit -am "~mensaje~" -> Subir archivos directamente

#### .gitkeep -> Agregar para carpetas vacias

#### git config --global alias.S "status --short" -> Aberviar comandos alias.~Abreviatura~ "~Metodo abreviado~"

#### git commit --amend -m "~mensaje~" -> Corregir texto del commit anterior

#### git reset --soft HEAD~3 -> Retroceder commits

#### git reset --soft ~codigo commit a45ca66~ -> Retroceder al commit seleccionado

#### git reset --mixed ~codigo commit a45ca66~ -> Retroceder al commit, saca todo del stage.

#### git reset --hard ~codigo commit a45ca66~ -> Retroceder al commit, borra todo lo que hay después del seleccionado

#### git reflog -> Muestra todo lo sucedido en orden cronologico

#### git mv ViejoNombre.md NuevoNombre.md -> Renombrar archivos sin perder historial

#### git rm ~ruta/nombre~ -> Remover un archivo, debe completarse con un commit

#### .gitignore -> Usado para agregar archivos a los que no se les da seguimiento 

