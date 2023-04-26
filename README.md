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
ls
``` 