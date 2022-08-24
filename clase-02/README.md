## GIT REMOTE
Nos permite agregar al repositorio local un repositorio remoto

>Agregar un repositorio remoto al local
```sh
git remote add <alias> <url>
```
> Borra el repositorio remoto

```sh
git remote rename <alias-original> <alias-nuevo>
git remote rename origin pepito
```
## GIT CLONE
Nos srive para hacer una copia exacta del repositorio y su metadata (.git)
git clone <url> # Me va a clonar el repo dentro de una carpeta con el nombre del repo
git clone <url> . # Se clona en la carpeta actual, sin crear ninguna carpeta extra 
## GIT SWITCH
Me permite cambiar entre ramas 
>Cambiar de rama
```sh
git branch <nombre-tama-nueva>
git branch dev
``` 
>Para borrar una rama
```sh
git branch -d <nombre - rama-nueva>
git branch dev
```
>Para borrar una rama

## GIT MERGE (fusionar ramas)
Me permite unificar cambios de diferentes. Fusionar el contenido que tengan las ramas

**IMPORTANTE:** tengo que estar en la rama destino. O sea por ejemplo. SI quiero traerme los cambios que tengo en dev a master. Tengo que estar posicionado en la rama 
**MASTER**
```sh
git switch master
git merge dev
```

## SARASA, todo piola!

## pasar a rama principal
```sh 
git swtich master
git merge dev
```




