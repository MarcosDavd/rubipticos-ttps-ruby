# Rubipticos 
## Trabajo integrador final de la TTPS opcion ruby
| # | Issue | Persona |
|---|---|---|
| 1 | Estructura de la base de datos y setup | Julian |
| 2 | Layout base y «Cómo se juega» | David |
| 3 | Jugador: cookie y nombre | David |
| 4 | Gestión de usuarios del backend (Admin y Editor de puntajes) | Joaquina |
| 5 | Catálogo de crípticos: validación y admin | Joaquina |
| 6 | Puntos de cada críptico y configuración | Julian |
| 7 | Sistema de puntaje y racha | Julian |
| 8 | Partida (con pistas y compartir resultado) | Adrian |
| 9 | Críptico del día | Adrian |
| 10 | Sincronización y seeds | Lauti |
| 11 | Tabla de posiciones | David |
| 12 | Admin de jugadores | David |
| 13 | Módulo de estadísticas | Lauti |
La issue de chatbot queda libre, queda asignada dependiendo de como vaya el proyecto
## Como levantar el proyecto
``` bash
cd rubipticos-ttps-ruby
```
``` bash
yarn install
```
``` bash
bin/setup
```
Instala las gemas de Ruby y las dependencias de JavaScript, prepara la base de datos y arranca la aplicación.
El proyecto queda en http://localhost:3000

## Comandos utiles de git
```bash
 - git branch nombre-rama //crea una nueva rama
 - git switch rama-destino //me cambio a rama-destino
 - git checkout -b nueva-rama // crea nueva-rama en base a la rama actual
 - git fetch // trae los ultimos cambios a la rama actual sin cambiar codigo
 - git pull //lo mismo que fetch pero si cambia el codigo
 - git add . //agrega todos los cambios al staging area, el  "." indica todo del directorio actual
 - git commit -m "un comentario" // agrega un comentario a lo que pusimos en el staging area
 - git push // sube todos los cambios al repo remoto
 - git merge nombre-rama // hace un merge trayendo todo lo de nombre-rama a la rama actual
```
## Convenciones de commit
```bash
 - git commit -m "feat: agrego POST de registro de usuario"
 - git commit -m "fix: arregle el controller"
 - git commit -m "docs: actualice el README"
 - git commit -m "style: cambie de estilo la pagina"
 - git commit -m "refactor: refactorice las peticiones htpp de usuarios"
 - git commit -m "chore: cree el .gitignore o actualice la version de un dependencia"
```