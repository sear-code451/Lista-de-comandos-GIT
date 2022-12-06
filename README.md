# LISTA DE COMANDOS GIT

#### 12 COMANDOS BÁSICOS

1. **git init:** iniciar git.
2. **git add . :** guardar archivos en repositiorio local.
3. **git reset . :** este revierte lo que se guardó en (git add .).
4. **git checkout -- . :**  Lo que hace es que si por ahí borramos algún archivo o lineas de codigo, para recuperar eso sería desde el último commit con este codigo lo restaura.
5. **git commit -m "nombre del commit":**
6. **git log** lista de todos los commit que se han hecho e incluido tambien las ramas.

7. **git commit --amend:** para corregir el nombre del ultimo commit.
8. **git checkout -b (nombre de la rama):** Lo que hace es que con esto creamos directo una rama y esta en ella, tanto en lo visual y en el repositorio local.
9. **git checkout master-main:** con esto nos manda al commit principal.
10. **git branch -d (nombre de la rama):** con esto borramos a una rama en específica.
11. **git push:** con esto mandamos los cambios a nuestro repositorio remoto.
12. **git commit -am "nombre del commit":** es la combinación de add . y commit. Guarda en el repositorio local con add y agregamos un commit.
13. **git remote:** esto nos muestra en el repositorio remoto de como llama dicho archivo.
14. **git remote -v:** es lo mismo que el de arriba pero con la diferencia que nos da los detalles de la ubicación de cada repositorio remoto que tenemos algo así mas o menos buscar si no se entiende.

15. **NO ES PARTE DE GIT: pwd:** esto es un comando de la terminal y no de git que nos muestra el directorio de trabajo o la ubicación del archivo en el que estamos.


#### CONOCIMIENTOS GENERAL DE GIT:

## Cuando usar ( - ) y ( -- )

**ejemplo de cuando usar ( - )**
```bash
git add -a;  git branch -d;  git commit -am
```

Esto normalmente se usa con una letra despúes e incluso a veces 2.

**ejemplo de cuando usar ( -- )**
```bash
git log --oneline;  git commit --amend
```

Esto normalmente se usa en una palabra.


####
# RESUMEN DE LA LISTA

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
13. **git remote**
14. **git remote -v**
15. **pwd**