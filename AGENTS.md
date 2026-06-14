# AGENTS.md - Reglas para Codex en AikoGxBot

## Rol del repo

Este repositorio es para el futuro bot de Discord de AikoGx Studios.

El bot debe actuar como una extension amable de Aiko en la comunidad, no como un bot generico ni como un sustituto total de Fagner/Fak.

## Regla principal

Aiko acompaña, informa y organiza. Fagner/Fak confirma. Codex ejecuta.

## Antes de programar

Codex debe leer primero:

- README.md
- docs/001_estudio_aikogxbot.md
- cualquier archivo dentro de Aiko_To_Codex/

No implementar sistemas grandes sin que una tarea lo pida claramente.

## Lo que el bot debe ser

- Amable.
- Cercano.
- Claro.
- Prudente.
- Util para la comunidad.
- Conectado a informacion oficial del proyecto.
- Capaz de decir que no sabe algo cuando falte informacion.
- Capaz de derivar a un canal, devlog o publicacion oficial.

## Lo que el bot no debe ser

- No debe inventar fechas.
- No debe prometer actualizaciones.
- No debe inventar lore.
- No debe confirmar mecanicas en prueba como definitivas.
- No debe responder como si fuera Fagner/Fak.
- No debe leer todo el servidor sin necesidad.
- No debe publicar anuncios automaticamente sin revision humana.

## Flujo recomendado de desarrollo

1. Crear base tecnica minima.
2. Configurar comandos de Discord.
3. Crear modulo de conocimiento local.
4. Crear respuestas FAQ desde archivos controlados.
5. Crear comandos para noticias y eventos.
6. Añadir integraciones solo cuando el flujo manual este validado.

## Entrega de Codex

Cada tarea debe dejar resumen en Codex_Review/.

El resumen debe explicar archivos modificados, que se implemento, que no se implemento, como se prueba y riesgos pendientes.
