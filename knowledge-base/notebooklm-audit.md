---
title: Auditoría del export de NotebookLM sobre Piana
owner: Roger GV
last_reviewed: 2026-09-03
review_cadence: 90 days
visibility: internal
---

# Auditoría del export de NotebookLM

## Resultado

La carpeta `notebooklm/` contiene **14 artefactos generados**, no fuentes primarias nuevas. Los cinco audios y el video son resúmenes sintéticos con locución; los PDF, PNG, CSV y Markdown reorganizan o dramatizan información del mismo cuaderno. La repetición entre ellos no aumenta la confianza porque comparten el mismo conjunto de entrada.

El cuaderno remoto `Piana` estaba autenticado y mostraba 78 fuentes el 3 de septiembre de 2026. En su inventario aparecían chats, audios, videos, prensa, documentos generados y una fuente sobre **Enrique Viana**. La interfaz falló antes de permitir una extracción trazable de esas 78 fuentes; por ello esta base no atribuye a una fuente original lo que sólo aparece en el export.

## Inventario y decisión de uso

| Archivo | Tipo | Contenido observado | Uso permitido |
|---|---|---|---|
| `segundo-cerebro-piana (1).md` | Markdown | Biografía, filosofía, obras y prompt; llama a la síntesis “fuente de verdad absoluta”. Mezcla a Enrique Piana con Enrique Viana y convierte inferencias en hechos. | Sólo como ejemplo negativo y banco de hipótesis. |
| `Informe de Estado_ Proyecto Piana y Agente _Segundo Cerebro_ en la Red Hermes.pdf` | PDF, 3 págs. | Presenta el agente, tokenización y DAO como estrategia madura/aprobada; usa métricas del grafo contaminado. | No canónico; consultar únicamente para auditar riesgos. |
| `Kintsugi_Digital.pdf` | PDF, 12 diapositivas | Deck comercial visual sobre redención, Cine Poesía, Amor 7, Romeo y Hermes. Incluye afirmaciones legales, financieras y operativas no demostradas. | Inspiración visual; todos los datos requieren fuente. |
| `Amor 7 Antigua Guatemala_ Plan de Producción.pdf` | PDF, 2 págs. | Plan sintético con prompts, paletas, Dalí, códices, ritmos aztecas y mensajes ocultos en Cholq'ij. | Propuesta creativa, nunca canon cultural o histórico. |
| `Guía para Animaciones_ Cine Poesía 7 de Piana.pdf` | PDF, 1 pág. | Resume requisitos de animación y añade supuestas reglas de Cine Poesía. | Usar sólo requisitos que se reconfirmen en chat o fuente original. |
| `Fuentes Musicales y Colaboraciones para Proyectos Cinematográficos - Table 1.csv` | CSV, 43 registros además de cabecera | Mezcla personas, herramientas, estados y citas numéricas sin bibliografía visible. Incluye a Enrique Viana. | No usar estados como “aprobado”, “entregado”, “fallecido” o cesión de derechos sin fuente original. |
| `Enrique_Piana__Redención_Artística.png` | PNG, 2752×1536 | Infografía con arco biográfico, reglas, fechas, Hermes y métricas; contiene errores tipográficos y cronológicos. | Material visual de borrador. |
| `Enrique_Piana_y_Ecosistema_Hermes.png` | PNG, 2752×1536 | Infografía similar; mezcla biografía, proyecto artístico y propuesta tecnológica como una sola realidad. | Material visual de borrador. |
| `De_la_mafia_del_oro_al_algoritmo (1).m4a` | Audio, 28:38 | Conversación sintética que dramatiza biografía, arte y tecnología. | Derivado; no citar como voz de Enrique. |
| `Enrique_Piana_de_estafador_a_artista.m4a` | Audio, 24:07 | Variante narrativa de transformación y ecosistema Hermes. | Derivado; no citar como entrevista. |
| `La_IA_basada_en_el_exmafioso_Piana.m4a` | Audio, 24:59 | Propone entrenar un agente con la biografía y el grafo. | Derivado; no usar para decisiones técnicas o éticas sin validación. |
| `La_redención_con_IA_de_Enrique_Piana.m4a` | Audio, 25:09 | Convierte ideas de tokenización y legado automatizado en escenario operativo. | Derivado especulativo. |
| `La_redención_de_Enrique_Piana_con_IA (1).m4a` | Audio, 27:30 | Variante que conecta biografía, Pepito y una infraestructura Hermes. | Derivado especulativo. |
| `Enrique_Piana__Oro_a_Poesía.mp4` | Video, 7:14 | Video-resumen con cronología, “reglas”, dinero, agente y DAO. | Derivado visual; no confirma lo narrado. |

## Hallazgos de contaminación

1. **Homónimo:** Enrique Viana, director vinculado a zarzuela, es otra persona. Su obra, colaboradores y créditos no pertenecen a Enrique Piana.
2. **Propuesta convertida en decisión:** podcast, bootcamp, agentes tokenizados y DAO provienen del audio de Roger del 24 de agosto de 2026. El chat no contiene respuesta ni aprobación de Enrique.
3. **Biografía sensible sin fuente local:** nacimiento, familia, Casa Piana, fraude, arresto, cifras, procesos judiciales, prisiones, libro, Camino de Santiago, Tailandia y escultura en alambre aparecen repetidos, pero la carpeta no incluye la documentación original que permita verificarlos.
4. **Reglas inventadas o sobrerresueltas:** “Reglas Sentinel”, patente de Cine Poesía 7 y una lista formal de siete principios no están sustentadas por el corpus primario local.
5. **Estados absolutos:** expresiones como “fecha irrevocable”, “aprobado”, “derechos cedidos”, “fuente de verdad absoluta” o “gobernanza validada” exceden la evidencia.
6. **Errores visibles:** las infografías contienen ortografía corrupta, fechas inconsistentes y conteos de fuentes que no coinciden con las 78 fuentes observadas en el cuaderno.
7. **Riesgo cultural:** los prompts sobre cosmología maya/azteca, códices, Cholq'ij y salud espiritual son generación creativa. No deben presentarse como tradición auténtica sin especialista y fuente cultural.

## Qué sí se conserva

- La carpeta demuestra temas recurrentes útiles para búsqueda: transformación, oro/alambre, arte colaborativo, Cine Poesía, Amor 7, Pepito, memoria digital y Hermes.
- Sus composiciones visuales y estructuras pueden inspirar decks, guiones o piezas nuevas si se rotulan como `PROPUESTA_CREATIVA`.
- Las métricas `104 nodos / 140 relaciones` describen el archivo local `graphify-out/graph.json`, pero no calidad ni veracidad. El grafo heredó fuentes contaminadas.

## Política de ingestión para Hermes

- No indexar `notebooklm/` en el mismo nivel que el canon.
- Si se indexa para investigación, asignar a todos sus fragmentos `source_class=DERIVADO_NOTEBOOKLM`, `authority=low` y `publishable=false`.
- Nunca promover un dato por repetición entre los 14 artefactos.
- Exigir título de la fuente original, autor, fecha y pasaje verificable antes de promover una afirmación.
- Resolver conflictos en favor de fuentes primarias y registrar la contradicción.
- Mantener a Enrique Piana y Enrique Viana como entidades bloqueadas para fusión.

Volver al [índice](README.md), al [canon](piana-canon.md) o a [preguntas abiertas](preguntas-abiertas.md).
