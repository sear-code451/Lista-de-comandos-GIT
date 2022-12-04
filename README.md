# LISTA DE COMANDOS GIT

#### 12 COMANDOS BÁSICOS

1. **git init** -> iniciar git.
2. **git add .** -> guuadar achivos en repositiorio local
3. **git reset .** -> este revierte lo que se guardó en (git add .).
4. **git checkout -- .**  -> Lo que hace es que si por ahí borramos algún archivo o lineas de codigo, para recuperar eso sería desde el último commit con este codigo lo restaura.
5. **git commit -m "nombre del commit"**
6. **git log** -> lista de todos los commit que se han hecho e incluido tambien las ramas.

7. **git commit --amend** -> para corregir el nombre del ultimo commit.
8. **git checkout -b (nombre de la rama)** -> Lo que hace es que con esto cremos directo una rama y esta en ella, tanto en lo visual y en el repositorio local.
9. **git checkout master-main** -> con esto nos manda al commit principal.
10. **git branch -d (nombre de la rama)** -> con esto borramos a una rama en específica.
11. **git push** -> con esto mandamos los cambios a nuestro repositorio remoto.
12. **git commit -am "nombre del commit"** -> es la combinación de add . y commit. Guarda en el repositorio local con add y agregamos un commit.



#### RESUMEN DE LA LISTA

1. **git init**
2. **git add .**
3. **git reset .**
4. **git checkout  -- .**
5. **git commit -m "nombre del commit"**
6. **git log**
7. **git commit --amend**
8. **git checkout -b (nombre de la rama)**
9. **git checkout (puede ser: master ó main)**
10. **git branch -d (nombre de la rama)**
11. **git push**
12. **git commit -am "nombre del commit"**