# Tema 6 - Auditoría de un workflow

`despliegue.yml` es el workflow con el que un equipo ficticio despliega la API de tareas, y `.env`
es un archivo que ese equipo tiene en su repositorio. Los dos tienen problemas de configuración,
de manejo de secretos y de permisos.

**No se ejecuta.** El trabajo es leerlo como lo haría quien revisa el pull request que lo agrega.

## Qué registrar

Una tabla con una fila por problema encontrado:

| Línea | Problema | Riesgo concreto | Corrección propuesta |
|---|---|---|---|
| (número) | Qué está mal | Qué puede pasar, y a quién | Cómo se escribe bien |

Después, una versión corregida del workflow (`despliegue_seguro.yml`) que aplique las
correcciones de la tabla.

Herramienta opcional: `actionlint` (analizador de workflows de GitHub Actions) detecta algunos de
los problemas, no todos.
