# Personal Git Cheatsheet

## Iniciar Repositorio
comando: git init  
uso: Inicializar un repositorio en el directorio actual  
sintaxis: `git init`

comando: git clone  
uso: Clonar un repositorio remoto  
sintaxis: `git clone <url>`

## Configuración Inicial
comando: git config  
uso: Configurar nombre y correo  
sintaxis:  
`git config --global user.name "<nombre>"`  
`git config --global user.email "<correo>"`

## Crear Rama Principal (main/master)
comando: git branch -M  
uso: Renombrar rama actual como principal  
sintaxis: `git branch -M main`  
`sintaxis (opcional): git branch -M master`

## Añadir y Gestionar Cambios
comando: git status  
uso: Ver estado de archivos  
sintaxis: `git status`

comando: git add  
uso: Añadir archivos al área de preparación  
sintaxis: `git add <archivo>`  
`sintaxis: git add .`

comando: git rm  
uso: Eliminar archivo del repositorio y sistema de archivos  
sintaxis: `git rm <archivo>`

comando: git mv  
uso: Mover o renombrar archivo  
sintaxis: `git mv <origen> <destino>`

## Guardar Cambios
comando: git commit  
uso: Guardar cambios con mensaje  
sintaxis: `git commit -m "<mensaje>"`

comando: git commit --amend  
uso: Modificar el último commit  
sintaxis: `git commit --amend -m "<nuevo mensaje>"`

## Conectar con GitHub
comando: git remote add  
uso: Añadir repositorio remoto  
sintaxis: `git remote add origin <url>`

comando: git remote -v  
uso: Ver remotos configurados  
sintaxis: `git remote -v`

comando: git push -u origin main  
uso: Subir rama principal al remoto  
sintaxis: `git push -u origin main`

comando: git push  
uso: Subir cambios al remoto  
sintaxis: `git push`

## Actualizar Cambios del Remoto
comando: git fetch  
uso: Descargar cambios del remoto sin fusionar  
sintaxis: `git fetch`

comando: git pull  
uso: Descargar y fusionar cambios del remoto  
sintaxis: `git pull`

## Ramas
comando: git branch  
uso: Listar ramas o crear nueva  
sintaxis: `git branch`  
`sintaxis: git branch <nombre>`

comando: git checkout  
uso: Cambiar de rama o restaurar archivos  
sintaxis: `git checkout <rama>`  
`sintaxis: git checkout -- <archivo>`

comando: git switch  
uso: Cambiar de rama (forma moderna)  
sintaxis: `git switch <rama>`  
`sintaxis: git switch -c <nueva_rama>`

comando: git merge  
uso: Fusionar ramas  
sintaxis: `git merge <rama>`

comando: git rebase  
uso: Reaplicar commits sobre otra base  
sintaxis: `git rebase <rama>`

## Deshacer Cambios
comando: git reset  
uso: Deshacer commits o cambios en staging  
sintaxis: `git reset <commit>`  
`sintaxis: git reset --hard <commit>`

comando: git revert  
uso: Crear commit inverso  
sintaxis: `git revert <commit>`

## Historial
comando: git log  
uso: Ver historial de commits  
sintaxis: `git log`

comando: git log --oneline --graph --decorate  
uso: Ver historial resumido  
sintaxis: `git log --oneline --graph --decorate`

## Stash
comando: git stash  
uso: Guardar cambios temporales  
sintaxis: `git stash`

comando: git stash pop  
uso: Restaurar cambios del stash  
sintaxis: `git stash pop`

## Etiquetas (Tags)
comando: git tag  
uso: Listar o crear etiquetas  
sintaxis: `git tag`  
`sintaxis: git tag <nombre>`

comando: git push origin --tags  
uso: Subir etiquetas al remoto  
sintaxis: `git push origin --tags`

## Otros
comando: git diff  
uso: Ver diferencias entre cambios  
sintaxis: `git diff`  
`sintaxis: git diff <archivo>`

comando: git clean  
uso: Eliminar archivos no rastreados  
sintaxis: `git clean -f`

comando: git ignore  
uso: Archivo para ignorar archivos/carpetas  
sintaxis: `.gitignore`

comando: git remote remove  
uso: Eliminar remoto  
sintaxis: `git remote remove <nombre>`
