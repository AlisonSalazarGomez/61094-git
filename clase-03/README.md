# Clase 01
## Primer pas

```sh
git config --global user.name "Alison Salazar"
git config --global user.email "Email"
```
> Ejemplo
```sh
git conding --global user.name "Maximiliano Principe"
git confing --global user.email "mlapeducacionit@gmail.com"
```
## Por proyecto (Directorio o Carpeta)
### Repositorio Git
Crea ua carpeta ocukta . Llamada **.git**
```sh
git init
```

## AREAS de GIT
> Working Directory ()
> staging Area (EL area de confirmacion)
> local repo
>
## Estados de los archivos
> Untracked -> git no sabe que exist3e
> Modified: gt sabe que algo cambio del archivo
> Unmodified: git sabe que no se modifico algo
> Stage: el archivo esta en el staging area

```sh
git add . # con esto agrevo todo al staging area
git add clase-/README.md

```
## GIt DIFF
> para ver las diferencias entre el Working Directory y el local Repo

## GIT LOG
Para salir del comando git log, tengo que presionar la tecla "q"
```sh
git log #version larga de las historia del repo
git log --oneline #version resumida
```
