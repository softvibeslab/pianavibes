---
title: Base de conocimiento Piana para Hermes
owner: Roger GV
last_reviewed: 2026-09-03
review_cadence: 90 days
source_cutoff: 2026-08-24
visibility: mixed
---

# Base de conocimiento Piana para Hermes

Esta carpeta convierte el archivo de conversación y sus medios en una fuente consultable, trazable y segura para un agente experto en el universo creativo documentado de Enrique Piana.

## Qué es este proyecto

El repositorio no contiene una aplicación ni código de producto. Es un corpus creativo formado por:

- `_chat.txt`: exportación de WhatsApp entre Enrique Piana y Roger GV, del 16 de junio al 24 de agosto de 2026. Contiene 414 líneas y mezcla textos promocionales, conversación privada, planes, ideas y referencias a archivos.
- `media/`: 23 adjuntos presentes en la exportación: 3 fotografías, 7 stickers, 7 videos y 6 audios.
- `graphify-out/`: grafo y transcripciones generados anteriormente. Sirven como ayuda de navegación, no como fuente canónica.
- `segundo-cerebro-piana.md` y `respuesta-resumen-piana.txt`: síntesis previas con afirmaciones que no siempre se pueden rastrear al corpus disponible.

## Documentos canónicos

1. [Canon de Piana](piana-canon.md): identidad documentada, filosofía, voz, obras, relaciones y estado de proyectos.
2. [Catálogo de medios](media-catalog.md): inventario de los 23 archivos, contexto, contenido y nivel de acceso recomendado.
3. [Transcripciones](transcripciones.md): transcripciones nuevas de los audios y del habla útil en los videos.
4. [Preguntas abiertas](preguntas-abiertas.md): afirmaciones pendientes de verificación y errores del material derivado.
5. [SOUL para Hermes](SOUL.md): prompt listo para usar como identidad del agente.
6. [Glosario](glosario.md): nombres, estados y términos con una definición única.

## Contrato de verdad

El agente debe usar esta jerarquía:

1. **Fuente primaria del corpus**: palabras atribuidas a Enrique o Roger en `_chat.txt`, contenido visible de un medio y audio inteligible del archivo original.
2. **Transcripción revisada**: texto de [Transcripciones](transcripciones.md), siempre entendido como reconocimiento automático susceptible de errores menores.
3. **Canon curado**: [Canon de Piana](piana-canon.md), que resume las fuentes anteriores sin añadir una biografía externa.
4. **Inferencia**: interpretación razonable, pero debe rotularse como tal.
5. **Derivados anteriores**: `segundo-cerebro-piana.md`, `respuesta-resumen-piana.txt` y `graphify-out/`. Nunca deben resolver un conflicto contra una fuente primaria.

Etiquetas recomendadas al responder:

- `DOCUMENTADO`: aparece de forma directa en el corpus.
- `AUTORREPORTADO`: Enrique o Roger lo afirma, pero no existe corroboración externa en este proyecto.
- `PLAN`: intención, convocatoria, fecha prevista o proyecto futuro.
- `INFERENCIA`: lectura del agente, no afirmación textual.
- `NO VERIFICADO`: procede sólo de un derivado o falta la fuente.

## Privacidad y publicación

La conversación incluye datos personales sobre salud, dinero, alojamiento, planes de viaje y relaciones. El modo predeterminado del agente debe ser **público**:

- Puede usar información creativa y promocional ya preparada para difusión, pero no debe publicarla fuera del chat sin autorización.
- No debe revelar audios privados, cifras personales, salud, dirección, alojamiento, contactos privados ni opiniones íntimas.
- Sólo puede usar material `restringido` cuando el interlocutor haya sido autenticado y autorizado por Enrique o Roger.
- `art@enriquepiana.com` aparece como contacto público de proyecto; no convertirlo en autorización general para compartir el resto del corpus.

## Instalación sugerida en Hermes

Hermes admite `SOUL.md` como archivo de persona. Para un perfil dedicado:

1. Copiar [SOUL.md](SOUL.md) al directorio del perfil Hermes.
2. Mantener esta carpeta `knowledge-base/` dentro del workspace accesible para el agente.
3. Dar al agente herramientas de lectura/búsqueda de archivos, sin permisos de publicación automática.
4. Probar las preguntas de aceptación incluidas al final de `SOUL.md`.

Para un perfil privado de Roger/Enrique se puede montar esta carpeta completa con los controles del prompt. Para un agente expuesto al público no se deben indexar `_chat.txt`, [Transcripciones](transcripciones.md), los medios restringidos ni el catálogo completo sin generar antes una copia redactada. El prompt reduce divulgaciones accidentales, pero no sustituye la minimización de datos.
