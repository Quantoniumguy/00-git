# Apunte sobre git

## Comandos basicos


```bash
git init #Crea el repositorio
git add README.md #Añade el archivo para despues subirlo
git commit -m "mensaje del commit" #Agrega descripcion del commit
git commit -ammend #Permite cambiar la ultima descripcion del commit
git status #Permite ver el estado del repositorio
git log #Permite ver los commits anteriores
```                    


### .gitignore

Es una archivo que sirve para ignorar archivos
Ejemplo, dentro del archivo .gitignore:

```
passwords.txt
build/
*.JPG
```

## Ramas/branches

```bash
git checkout -b NOMBRE RAMA NUEVA
git checkout CON PINZAS(id) PARA VOLVER A UN COMMIT ANTERIOR
git checkout MOVERSE DE RAMA
merge JUNTA LAS RAMA DE OTRA RAMA
stash BORRA TEMPORALMENTE LAS MODIFICACIONES DE UN COMIT
push --set-upstream origin CREA Y SUBE UNA RAMA EN GITHUB
ls
diff VER DIFERENCIAS
difftool

PARA USAR DIFFTOOL HAY QUE INSTALAR MELD!
``` 