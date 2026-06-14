# 001 - Estudio inicial AikoGxBot

Fecha: 2026-06-14
Repo: aikogxstudios/AikoGxBot
Estado: estudio / vision / preparacion futura

## 1. Vision del bot

AikoGxBot debe ser la presencia amable de Aiko dentro del Discord de AikoGx Studios.

No debe ser solo un bot de comandos. Debe sentirse como un asistente de comunidad:

- responde dudas basicas del proyecto;
- ayuda a nuevos miembros a entender que es AikoGx Studios;
- explica que es Caos Entre Reinos / Chaos Among Realms: Reborn;
- recuerda anuncios, eventos, devlogs y publicaciones importantes;
- ayuda a encontrar enlaces oficiales;
- propone donde mirar si alguien pregunta por algo concreto;
- acompaña con tono cercano y honesto;
- nunca inventa informacion que no este confirmada.

Frase guia:

**Aiko acompaña a la comunidad, no sustituye al equipo.**

## 2. Personalidad de Aiko dentro de Discord

Aiko debe sonar:

- amable;
- cercano;
- sencillo;
- un poco magico/estudio indie;
- honesto;
- organizado;
- con energia de AikoGx Studios;
- sin sonar corporativo;
- sin sonar como vendedor agresivo;
- sin parecer una IA fria.

Tono recomendado:

- Español principal, con posible soporte ingles mas adelante.
- Frases claras y cortas.
- Respuestas utiles antes que largas.
- Si algo no esta confirmado, decirlo.
- Si una pregunta necesita decision de Fagner/Fak, derivar con calma.

Ejemplo de tono:

> Todavia no hay fecha confirmada para eso. Cuando Fagner/Fak lo publique oficialmente, lo dejare marcado en el canal de novedades.

> Eso pertenece a Caos Entre Reinos: Reborn. Es un action RPG chibi de fantasia caotica donde las cartas ayudan a construir tu poder.

## 3. Que informacion debe conocer

### AikoGx Studios

- Nombre del estudio.
- Descripcion corta.
- Enlaces oficiales.
- Proyectos activos.
- Canales importantes del Discord.
- Normas basicas de comunidad.

### Caos Entre Reinos / Chaos Among Realms: Reborn

Debe conocer informacion publica y segura:

- genero general;
- tono del juego;
- estilo visual;
- estado de desarrollo;
- que es el Abismo;
- que es la Aguja del Caos;
- que es el Tomo del Viajero;
- que son las cartas;
- clases conocidas si son publicas;
- que contenido pertenece a demo/acceso anticipado;
- enlaces a itch.io, web, devlogs o videos si existen.

Debe evitar spoilers fuertes y no debe contar lore profundo salvo que este marcado como publico.

### Publicaciones y memoria publica

AikoGxBot deberia poder recordar:

- devlogs publicados;
- eventos comunitarios;
- anuncios importantes;
- trailers o videos nuevos;
- updates de itch.io;
- posts destacados;
- cambios de estado importantes del proyecto.

Esta memoria debe venir de fuentes controladas por el equipo, no de cualquier mensaje aleatorio.

## 4. Fuentes de informacion recomendadas

Para empezar, no conectar demasiadas cosas.

### Fuentes V1 simples

- Archivos Markdown dentro del repo.
- FAQ local.
- Lista manual de enlaces oficiales.
- Archivo de eventos/anuncios importantes.
- Archivo de proyectos.

Ejemplo de estructura futura:

```text
knowledge/
  studio.md
  projects/
    caos_entre_reinos.md
  faq.md
  links.md
  events.md
  announcements.md
```

### Fuentes V2 futuras

- Leer devlogs desde la web AikoGx.
- Leer updates de itch.io si se decide.
- Sincronizar anuncios manuales desde un archivo o panel.
- Conectar con Aiko Web News App para reutilizar material aprobado.

## 5. Funciones posibles del bot

### MVP recomendado

Comandos basicos:

- `/aiko ayuda`
- `/aiko proyecto`
- `/aiko caos`
- `/aiko enlaces`
- `/aiko devlog`
- `/aiko evento`
- `/aiko faq`

Funciones:

- responder FAQ;
- mostrar descripcion corta de proyectos;
- enlazar web, itch.io, YouTube, Discord o redes cuando existan;
- mostrar ultimo devlog/anuncio registrado manualmente;
- explicar si algo aun no esta confirmado.

### V2 comunidad

- resumen semanal manual o semiautomatico;
- recordatorio de eventos;
- comando para ver cartas/eventos comunitarios;
- comando para explicar como participar en ideas de cartas;
- respuestas con embeds bonitos;
- botones para enlaces oficiales;
- soporte ingles/español.

### V3 asistente mas inteligente

Solo despues de validar lo anterior:

- busqueda semantica en documentos del proyecto;
- memoria de anuncios publicados;
- integracion con Aiko Web News App;
- generacion de respuestas con IA controlada;
- panel para que Fagner apruebe respuestas largas;
- sistema de moderacion suave.

## 6. Comportamiento cuando alguien pregunta algo

Regla:

Aiko debe responder solo con informacion confirmada.

Si sabe la respuesta:

- responde corto;
- añade enlace si existe;
- sugiere canal adecuado si hace falta.

Si no sabe:

- dice que no tiene esa informacion confirmada;
- sugiere esperar anuncio oficial;
- puede avisar que Fagner/Fak deberia confirmarlo.

Si la pregunta pide spoiler:

- responder sin destripar;
- decir que ese tema se descubrira jugando o en futuros devlogs.

Si la pregunta es sobre fecha:

- nunca inventar fechas;
- responder con el estado oficial.

Si la pregunta es critica o negativa:

- responder con calma;
- no discutir;
- invitar a dar feedback en el canal correcto.

## 7. Ideas de comandos

### Informacion

- `/aiko que-es-aikogx`
- `/aiko que-es-caos`
- `/aiko estado-del-juego`
- `/aiko enlaces`
- `/aiko ultimo-devlog`
- `/aiko eventos`

### Comunidad

- `/aiko como-ayudar`
- `/aiko proponer-carta`
- `/aiko reportar-bug`
- `/aiko normas`
- `/aiko redes`

### Lore sin spoilers

- `/aiko lore-basico`
- `/aiko abismo`
- `/aiko aguja-del-caos`
- `/aiko tomo-del-viajero`

### Admin / equipo

- `/aiko publicar-anuncio`
- `/aiko registrar-evento`
- `/aiko registrar-devlog`
- `/aiko actualizar-enlace`
- `/aiko recargar-conocimiento`

Los comandos admin deben estar limitados a roles concretos.

## 8. Preguntas para Fagner/Fak antes de programar

### Identidad

1. El bot se llamara oficialmente `Aiko`, `AikoGxBot`, `AikoGx`, o algo mas bonito?
2. Debe hablar como Aiko actual del chat o mas como mascota del estudio?
3. Debe usar emojis? Si si, cuantos y cuales?
4. Debe responder en español por defecto o detectar idioma?

### Discord

5. Que canales oficiales existen o quieres crear?
6. En que canal puede responder el bot?
7. Debe responder solo con slash commands o tambien cuando lo mencionen?
8. Debe responder en canales publicos o mandar mensajes privados?
9. Que roles pueden usar comandos admin?

### Informacion

10. Que informacion del lore es publica y cual no?
11. Que links oficiales son definitivos?
12. Donde se guardaran eventos y devlogs aprobados?
13. Aiko puede hablar de fechas si estan en anuncios oficiales?
14. Debe recordar posts de X, itch.io, web y YouTube manualmente o automatico?

### Comunidad

15. Debe ayudar a nuevos miembros con bienvenida?
16. Debe recordar eventos comunitarios?
17. Debe sugerir canales para feedback, bugs o ideas?
18. Debe hacer resumen semanal?
19. Debe tener respuestas divertidas o solo informativas?

### Seguridad

20. Que cosas nunca debe responder?
21. Debe evitar spoilers de lore por defecto?
22. Debe negarse a hablar de builds internas no publicas?
23. Debe registrar preguntas frecuentes de la comunidad?
24. Quien aprueba anuncios largos?

## 9. Riesgos

### Riesgo 1: que invente informacion

Solucion:

- usar base de conocimiento controlada;
- respuestas cortas;
- decir no confirmado cuando falte informacion;
- no usar generacion libre sin fuentes.

### Riesgo 2: que sea demasiado grande desde el inicio

Solucion:

- MVP pequeño;
- comandos simples;
- FAQ local;
- nada de integraciones automaticas al principio.

### Riesgo 3: permisos de Discord demasiado amplios

Solucion:

- empezar con slash commands;
- evitar leer todos los mensajes si no hace falta;
- activar permisos solo cuando una funcion los necesite.

### Riesgo 4: confundir comunidad con respuestas antiguas

Solucion:

- cada dato importante debe tener fecha;
- marcar estado: confirmado, en prueba, antiguo, archivado;
- comando para ver ultima actualizacion de la informacion.

## 10. Recomendacion tecnica inicial

Para el MVP, lo mas seguro es:

- bot simple con slash commands;
- base de conocimiento Markdown local;
- respuestas por plantillas;
- comandos admin para registrar eventos manualmente;
- sin IA generativa al principio;
- sin leer todo el chat por defecto.

Motivo:

Discord recomienda usar Application Commands como forma nativa de interactuar con apps. Los comandos tipo slash son claros para usuarios y evitan depender de leer todo el contenido del chat. Ademas, leer contenido de mensajes puede requerir `MESSAGE_CONTENT`, que Discord trata como intent privilegiado. Por eso es mejor empezar con comandos y menciones controladas.

Referencias oficiales para revisar antes de implementar:

- Discord Application Commands: https://docs.discord.com/developers/interactions/application-commands
- Discord Gateway / Intents: https://docs.discord.com/developers/events/gateway

## 11. MVP propuesto

### Fase 1 - Base

- Crear proyecto tecnico del bot.
- Crear config de ejemplo.
- Crear estructura `knowledge/`.
- Crear slash commands basicos.
- Responder desde Markdown local.

### Fase 2 - Comunidad

- Embeds bonitos con estilo AikoGx.
- Comando de ultimo devlog.
- Comando de eventos.
- Comando de enlaces.
- Canal de bienvenida opcional.

### Fase 3 - Actualizaciones

- Registrar manualmente publicaciones importantes.
- Guardar historial de anuncios.
- Preparar resumen semanal.

### Fase 4 - Inteligencia controlada

- Buscar en documentos aprobados.
- Generar respuestas solo con fuentes.
- Si no hay fuente, preguntar o decir que no esta confirmado.

## 12. Decision recomendada por Aiko

No construir el bot completo todavia.

Primero crear una base pequeña:

1. Slash commands.
2. FAQ local.
3. Enlaces oficiales.
4. Ultimo devlog/evento manual.
5. Personalidad Aiko.

Despues conectar con herramientas mas grandes.

La version buena no es la que responde a todo. La version buena es la que responde bien, sin inventar, y ayuda a la comunidad a entender el proyecto.
