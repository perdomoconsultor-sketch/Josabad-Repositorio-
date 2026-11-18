# Reglas del Proyecto

## Flujo de Versionamiento y GitHub
- Cada vez que se termine una tarea, código o cambio en el proyecto, el agente debe preguntar al usuario:
  `¿Deseas que suba esta actualización a GitHub?`
- Si el usuario responde afirmativamente (por ejemplo "sí", "subelo", "dale", etc.), el agente debe ejecutar automáticamente:
  1. `git add .`
  2. `git commit -m "<descripción clara del cambio>"`
  3. `git push`
- El repositorio está configurado y vinculado a GitHub con autenticación por token en la rama `main`.
