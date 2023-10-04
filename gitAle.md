##  Comands

```
    git config --global -e : ver la confi global
    git status : ver las areas
    git reset : volver en el tiempo /soft/mixed/hard

    git add *.html
    git add js/*.js
    git add css/
    git status --short
    git commit --amend -m "msg" : cambiar name del último commit
    git reset --soft HEAD^ : mover a un commit especifico
    git pull : traer del repositorio archivos al local
    git reset --hard HASH : acción destructiva
    git reflog: mirar el historial incluso los eliminados
    git rm FILE : borrar pero dejando rastro
    git branch -d namebranch -f : borrar rama y forzarla a borrar
    git merge branch : unión de dos 2 ramas
    git branch -d "branchName"
```
## git stash
```
    git stash save "message"
    git stash list
    git stash clear : clean all stash

```
## git rebase
```
    git rebase master : unir los cambios a la rama, debes estar en la rama
    

```
## Alias ^^

```
    git config --global -e alias.s "status --short"
```