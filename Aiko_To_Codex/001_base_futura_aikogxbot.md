# Tarea futura para Codex - 001 Base inicial AikoGxBot

Estado: futura / no ejecutar todavia
Fecha: 2026-06-14
Repo: aikogxstudios/AikoGxBot

## Contexto

Este repo es para el futuro bot de Discord de AikoGx Studios.

Antes de programar, leer:

- README.md
- AGENTS.md
- docs/001_estudio_aikogxbot.md

## Objetivo futuro

Crear una primera base pequeña de AikoGxBot.

El bot debe ser un asistente amable de comunidad, no un bot generico.

## Filosofia

Fagner/Fak quiere un bot que ayude a la comunidad sin tener que repetir siempre lo mismo.

El bot debe:

- responder dudas frecuentes;
- explicar proyectos de AikoGx Studios;
- enlazar informacion oficial;
- recordar eventos y devlogs registrados;
- avisar si algo no esta confirmado;
- interactuar de forma cercana;
- ayudar a la comunidad a encontrar lo que busca.

## No hacer todavia

- No crear IA libre que invente respuestas.
- No publicar anuncios automaticos.
- No conectar redes externas todavia.
- No crear sistemas enormes en la primera version.
- No responder como si fuera Fagner/Fak.

## MVP recomendado

### 1. Estructura base

Crear una base simple con carpetas parecidas a:

```text
src/
knowledge/
Codex_Review/
```

### 2. Knowledge local

Crear archivos iniciales:

```text
knowledge/studio.md
knowledge/faq.md
knowledge/links.md
knowledge/events.md
knowledge/projects/caos_entre_reinos.md
```

### 3. Comandos iniciales

Comandos sugeridos:

- /aiko ayuda
- /aiko que-es-aikogx
- /aiko que-es-caos
- /aiko enlaces
- /aiko ultimo-devlog
- /aiko eventos
- /aiko faq

### 4. Respuestas

Las respuestas deben salir de archivos controlados, no de imaginacion.

Si no hay informacion, Aiko debe decir que no tiene esa informacion confirmada todavia.

## Preguntas pendientes para Fagner/Fak

Antes de implementar confirmar:

1. Nombre final del bot.
2. Idioma por defecto.
3. Canales donde puede responder.
4. Roles de equipo.
5. Enlaces oficiales definitivos.
6. Que lore es publico y que lore no.
7. Si debe responder solo por comandos o tambien por mencion.
8. Si debe tener mensajes de bienvenida.
9. Si debe recordar eventos comunitarios.
10. Si se quiere resumen semanal.

## Validacion futura

Cuando se implemente:

- probar arranque local;
- probar comandos basicos;
- comprobar que no inventa informacion;
- comprobar que las respuestas salen de knowledge;
- comprobar que los datos no confirmados se responden como no confirmados.

## Entrega de Codex

Crear resumen en:

Codex_Review/001_base_futura_aikogxbot_resumen.md
