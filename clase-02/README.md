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
