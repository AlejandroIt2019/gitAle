# Comando de Git.

##  Configuraciones y estados
```
    git config --global -e
    git status
    git reset
    git add *.html
    git add js/*.js
    git add css/
    git status --short
    git commit --amend -m "msg"
    git reset --soft HEAD^
```
## cambio de Alias
```
    git config --global -e alias.s "status --short"
```
 ## Volver al último commit agregar cosas especificas

 ```
<<<<<<< HEAD
    examples:
    git checkout -- . 
    git add *.html
    git add *.js
    git add css/
 ```
 ## Traer ramas y uniones desde el entorno remoto
 ```
    git pull, git fetch
 ```
 ## Creación de tags
 ```
    git tag -a v1.0.0 -m "tag de la version 1.0.0"
    git tag -a v0.1.0 HASH
    git push --tags
    git remote prune origin
 ```
 ## Git stash
 ```
    git stash
    git stash pop (une y elimina la primera posición)
    git stash save "message"
    git stash clear
    git stash apply stash@{x}
    git stash drop stash@{x}
 ```
## Rebase 
```
   git rebase master
   git rebase -i HEAD~x
   sacar del stage git checkout -- namefile
```
=======
 
 ```
>>>>>>> 680a772a13cdbc92d856eab9f0e298554ef7fc23
