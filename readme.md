## Práctica del curso de git, gitHub y Sourcetree.
**1 - ¿Qué comando utilizaste en paso 11?**
```git reset HEAD ~1``` Para mover HEAD al commit anterior.
**2 - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
```git reflog``` Para ver el id el commit que habiamos hecho.
```git reset 1eeb1db``` Movemos HEAD a ese commit.
**3 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No ocurre ningún conflicto. Porque en este caso la rama que quieres absorber ya esta absobida.
**4 - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Si causa un conflicto porque se ha editado el archivo git-nuestro.md en dos ramas distintas.
**5 - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No ocurre conflicto porque no se han realizados cambios en el master.
**6 - ¿Qué comando o comandos utilizaste en el paso 25?**
```git log --graph```
**7 - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Si, porque las dos ramas forman una lista.
**8 - ¿Qué comando o comandos utilizaste en el paso 27?**
```git reflog``` Para ver el id del commit antes del merge.
```git reset 021ff70``` Movemo HEAD a ese commit.
**9 - ¿Qué comando o comandos utilizaste en el paso 28?**
```git restore git-nuestro.md```
**10 - ¿Qué comando o comandos utilizaste en el paso 29?**
```git branch -D title```
**11 - ¿Qué comando o comandos utilizaste en el paso 30?**
```git reset --hard df2bd17```
**12 - ¿Qué comando o comandos utilizaste en el paso 32?**
```git reset --hard 6dbe5a7```
**13 - ¿Qué comando o comandos utilizaste en el paso 33?**
```git reset --hard df2bd17```
