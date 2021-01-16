# Comandos útiles de GiT

1. git init
2. git add . (lleva al stage)
3. git reset .  (revierte el add)
4. git commit -m "comentario" (tomamos foto de la version)
5. git checkout -- . (revierte los cambios hasta el anterior commit)
6. git log
7. git commit --amend (permite editar los commits, dentro del editor comandos de unix), (i para insertar, [esc] y luego :wq! para grabar y salir de una).
8. git checkout -b rama-heroes (creo y cambio de rama)
9. git branch (muestra la rama actual)
10. git checkout master (cambiar a una rama)
11. git merge rama-heroes (se trae todos los cambios de la rama en cuestion y los agrega a la rama master o desde la rama que se esta en ese momento)
12. git branch -d rama-heroes (borra la rama cuando ya no la requerimos)
13. para subir a un repo:
    a. creamos en repo en conetenedor de repos (github, gitlab, bitbuket)
    b. git remote add origin https://github.com/ferreiradeveloper/git-youtube.git (conect al repo)
    c. git branch -M main (rename the branch)
    d. git push -u origin main (subida al repo)
14. git push (cuando esta seteado el repo solo hacemos push pasa subir cambios)
15. git commit -am (hace los dos pasos de add + commit)