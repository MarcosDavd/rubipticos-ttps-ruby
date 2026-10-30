Cosas de git 
 - git branch nombre-rama //crea una nueva rama
 - git switch rama-destino //me cambio a rama-destino
 - git checkout -b nueva-rama // crea nueva-rama en base a la rama actual
 - git fetch // trae los ultimos cambios a la rama actual sin cambiar codigo
 - git pull //lo mismo que fetch pero si cambia el codigo
 - git add . //agrega todos los cambios al staging area, el  "." indica todo del directorio actual
 - git commit -m "un comentario" // agrega un comentario a lo que pusimos en el staging area
 - git push // sube todos los cambios al repo remoto
 - git merge nombre-rama // hace un merge trayendo todo lo de nombre-rama a la rama actual  
 
Convencion de commits con ejemplos
 - git commit -m "feat: agrego POST de registro de usuario"
 - git commit -m "fix: arregle el controller"
 - git commit -m "docs: actualice el README"
 - git commit -m "style: cambie de estilo la pagina"
 - git commit -m "refactor: refactorice las peticiones htpp de usuarios"
 - git commit -m "chore: cree el .gitignore o actualice la version de un dependencia"