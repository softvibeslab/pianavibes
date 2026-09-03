# Graph Report - /Users/rogergv/Documents/SoftvibesLab/piana  (2026-08-24)

## Corpus Check
- 20 files · ~134,372 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 104 nodes · 140 edges · 10 communities
- Extraction: 61% EXTRACTED · 36% INFERRED · 3% AMBIGUOUS · INFERRED: 51 edges (avg confidence: 0.86)
- Token cost: 563,264 input · 18,000 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Biografía y Obra de Piana|Biografía y Obra de Piana]]
- [[_COMMUNITY_Stickers de Reacción del Chat|Stickers de Reacción del Chat]]
- [[_COMMUNITY_Rodaje Amor 7 Isola Bella|Rodaje Amor 7 Isola Bella]]
- [[_COMMUNITY_Personaje Pepito Sentinfante|Personaje Pepito Sentinfante]]
- [[_COMMUNITY_Ecosistema Hermes y Roger GV|Ecosistema Hermes y Roger GV]]
- [[_COMMUNITY_Cómic Nº 3 Pepito y Kike|Cómic Nº 3: Pepito y Kike]]
- [[_COMMUNITY_Lanzamiento Amor 7 Sicilia|Lanzamiento Amor 7 Sicilia]]
- [[_COMMUNITY_In Lak'ech y Cultura Maya|In Lak'ech y Cultura Maya]]
- [[_COMMUNITY_Aplausos y Celebración|Aplausos y Celebración]]
- [[_COMMUNITY_Humor Celebratorio|Humor Celebratorio]]

## God Nodes (most connected - your core abstractions)
1. `Enrique Piana` - 12 edges
2. `Pepito Sentinfante (comic character by Enrique Piana)` - 8 edges
3. `Amor 7 Isola Bella Sicilia (7/7, rodada julio 2026 con 17 participantes)` - 8 edges
4. `Portada Comic N.3 'Pepito Sentinfante y Kike, su creador' (Primera Edicion, Junio 2026, EUR 7,77 / ARG $7.777) - portada estilo vintage: el nino Pepito sentado en un banco dialoga con su creador anciano (Kike) que sostiene un cuaderno de bocetos en un estudio lleno de libros y dibujos` - 7 edges
5. `Sticker: toddler pulling a red rolling suitcase through a terminal corridor` - 7 edges
6. `Septemlogía Amor 7 (7 cortometrajes, 7 países, 7 años)` - 7 edges
7. `WhatsApp chat between Enrique Piana and Roger GV` - 6 edges
8. `Visión del Ecosistema Hermes: podcast de IA como puerta de entrada (contenido → comunidad → bootcamp → agentes → DAO)` - 6 edges
9. `Amor 7 launch poster - 'Hoy empieza AMOR 7' celebratory announcement image` - 5 edges
10. `Amor 7 (Septemlogía) - collaborative art project` - 5 edges

## Surprising Connections (you probably didn't know these)
- `Enrique Viana (director de zarzuela, homónimo de Enrique Piana)` --semantically_similar_to--> `Enrique Piana`  [AMBIGUOUS] [semantically similar]
  segundo-cerebro-piana.md → _chat.txt
- `Clip de video 15-08-2026 ('This is Sina Poesia', transcripción ruidosa)` --references--> `CINE POESÍA 7 (lenguaje cinematográfico: terapéutico, voluntarios no profesionales, toma única, sin fines de lucro, final en YouTube, movimientos grupales silenciosos, imagen+palabra)`  [AMBIGUOUS]
  graphify-out/transcripts/00000191-VIDEO-2026-08-15-16-41-07.txt → segundo-cerebro-piana.md
- `Visión del Ecosistema Hermes: podcast de IA como puerta de entrada (contenido → comunidad → bootcamp → agentes → DAO)` --semantically_similar_to--> `Agente 'Segundo Cerebro' de Enrique Piana (system prompt + base de conocimiento para la red Hermes)`  [INFERRED] [semantically similar]
  graphify-out/transcripts/00000202-AUDIO-2026-08-24-01-02-49.txt → segundo-cerebro-piana.md
- `Toddler child (small child seen from behind, curly hair)` --conceptually_related_to--> `WhatsApp chat between Enrique Piana and Roger GV`  [AMBIGUOUS]
  00000023-STICKER-2026-08-06-07-20-16.webp → 00000029-STICKER-2026-08-15-05-47-22.webp
- `Amor 7 Isola Bella Sicilia (7/7, rodada julio 2026 con 17 participantes)` --references--> `Max Martínez (cantautor salvadoreño)`  [INFERRED]
  _chat.txt → segundo-cerebro-piana.md

## Hyperedges (group relationships)
- **Amor 7 launch event: project starts at Isola Bella, Sicilia on 14 July 2026 with the full collaborative group** — amor7_project, amor7_isola_bella_sicilia, amor7_launch_date_14_julio_2026, amor7_grupo_colaborativo, amor7_enrique_piana [EXTRACTED 1.00]
- **Pepito Sentinfante sticker as branded creative asset: character, creator signature, and comics IP** — sticker_pepito_sentinfante_jumping, character_pepito_sentinfante, signature_piana, work_pepito_sentinfante_comics [INFERRED 0.85]
- **Pepito Sentinfante sticker as branded promotional artifact of Piana's comic universe** — sticker_pepito_jumping_joy, character_pepito_sentinfante, signature_piana, person_enrique_piana [INFERRED 0.85]
- **Applause sticker as celebratory reaction in the Piana-Roger chat** — sticker_applauding_crowd, concept_applause, concept_celebration_approval, conversation_piana_rogergv [INFERRED 0.75]
- **In Lak'ech greeting visualized as hand gesture with Mayan iconography** — piana_clasped_hands_photo, piana_interlocking_hand_grip, piana_mayan_glyphs, piana_in_lakech_ala_kin, piana_unity_brotherhood [INFERRED 0.85]
- **Escena central del comic N.3: la criatura Pepito interroga a su creador Kike en un dialogo metaficcional que estructura toda la portada** — personaje_pepito_sentinfante, personaje_kike_creador, concepto_dialogo_creador_criatura, comic_pepito_sentinfante_n3_portada [EXTRACTED 1.00]
- **Scene: toddler pulling a suitcase through a terminal, evoking a family trip or departure** — concept_toddler_child, concept_red_rolling_suitcase, concept_airport_terminal, concept_travel_departure [INFERRED 0.85]
- **Los cortometrajes conocidos de la Septemlogía Amor 7 (7 películas, 7 países, 7 años)** — segundo_cerebro_piana_amor_7_cabo_de_gata, segundo_cerebro_piana_amor_7_antigua_guatemala, chat_amor_7_bleu_chefchaouen, chat_amor_7_isola_bella_sicilia, segundo_cerebro_piana_septemlogia_amor_7 [EXTRACTED 1.00]
- **Ruta práctica del Ecosistema Hermes: podcast/contenido → comunidad → bootcamp → agentes tokenizados → DAO** — 00000202_audio_2026_08_24_01_02_49_vision_ecosistema_hermes, 00000202_audio_2026_08_24_01_02_49_bootcamp_ia, 00000202_audio_2026_08_24_01_02_49_agentes_tokenizados, 00000202_audio_2026_08_24_01_02_49_dao_hermes, segundo_cerebro_piana_red_hermes [EXTRACTED 1.00]
- **Universo narrativo de Pepito Sentinfante: personaje, villano Mundego, creador Kike y el Cómic Nº 3** — chat_pepito_sentinfante, segundo_cerebro_piana_mundego, segundo_cerebro_piana_kike, chat_comic_n_3 [EXTRACTED 1.00]

## Communities (10 total, 0 thin omitted)

### Community 0 - "Biografía y Obra de Piana"
Cohesion: 0.12
Nodes (22): Amor 7 – 7 Pueblitos con Alma (segunda etapa junto a Pepito Sentinfante), Amor 7 Bleu Chefchaouen Marruecos (6/7: 7 poemas + 7 fotografías), Chefchaouen, la Perla Azul de Marruecos (14 años de regresos), Cómic Nº 3: Pepito Sentinfante y Kike, su creador (diálogo terapéutico personaje-creador), Enrique Piana, Pepito Sentinfante (niño de 7 años que no lucha: transforma desde el amor), Romeo 1597 – Giulietta 2027 (película independiente, Verona a Asís, 14 días, equipo de 7, 3 inversores, Fiat 500), Amor 7 Cabo de Gata (Almería, España) (+14 more)

### Community 1 - "Stickers de Reacción del Chat"
Cohesion: 0.20
Nodes (15): WhatsApp chat between Enrique Piana and Roger GV, Airport or terminal corridor (tiled floor with yellow guide line), Approval / agreement gesture (thumbs up), Breaking-through motif (hand punching through surface, emphatic energy), Childlike independence and endearing determination (kid doing a grown-up task), Duck face / exaggerated pout expression, Family affection / sharing a tender personal moment, Playful affectionate humor (mock kiss / smug tenderness) (+7 more)

### Community 2 - "Rodaje Amor 7 Isola Bella"
Cohesion: 0.18
Nodes (12): Clip de video 15-08-2026 ('This is Sina Poesia', transcripción ruidosa), Amor 7 Isola Bella Sicilia (7/7, rodada julio 2026 con 17 participantes), Avant-première de Amor 7 Isola Bella (7 de diciembre de 2026, 19:00 h, Cabo de Gata-Níjar, Almería), Javi (intérprete de Maledetto), Lisa (iba a interpretar a la compañera de Maledetto), Maledetto (personaje de Amor 7 Isola Bella), Parque Natural Cabo de Gata-Níjar (Almería, España), Patrocinios simbólicos de 17 € y 77 € (nombre en créditos, destinados a la edición) (+4 more)

### Community 3 - "Personaje Pepito Sentinfante"
Cohesion: 0.29
Nodes (11): Pepito Sentinfante (comic character by Enrique Piana), Traditional folkloric costume (white blouse, vest, red faja sash, loose trousers, sandals), Joy / celebration (exuberant laughing jump, arms raised), Joy / exuberant celebration (character leaping mid-air, arms raised, laughing), Traditional folk costume (white shirt, dark vest, red waist sash, loose trousers, sandals), Enrique Piana (poet/filmmaker, creator of Pepito Sentinfante), Pepito Sentinfante comics (Enrique Piana's comic project), Piana signature (cursive handwritten branding on sticker) (+3 more)

### Community 4 - "Ecosistema Hermes y Roger GV"
Cohesion: 0.31
Nodes (10): Agentes tokenizados (agente como activo digital programable en blockchain: identidad, permisos, habilidades como módulos con regalías, conocimiento protegido), Bootcamp de IA patrocinado (puerta de entrada al ecosistema, no producto final), DAO de Hermes (etapa posterior: gobernanza, financiación de agentes y distribución de ingresos solo cuando exista economía real), Visión del Ecosistema Hermes: podcast de IA como puerta de entrada (contenido → comunidad → bootcamp → agentes → DAO), Película 'El cambio' (Wayne Dyer, recomendada por la mamá de Roger), In Lak'ech Ala K'in (saludo maya: 'yo soy otro tú / tú eres otro yo'), Roger GV, Agente 'Segundo Cerebro' de Enrique Piana (system prompt + base de conocimiento para la red Hermes) (+2 more)

### Community 5 - "Cómic Nº 3: Pepito y Kike"
Cohesion: 0.33
Nodes (9): Portada Comic N.3 'Pepito Sentinfante y Kike, su creador' (Primera Edicion, Junio 2026, EUR 7,77 / ARG $7.777) - portada estilo vintage: el nino Pepito sentado en un banco dialoga con su creador anciano (Kike) que sostiene un cuaderno de bocetos en un estudio lleno de libros y dibujos, Dialogo metaficcional creador-criatura: Pepito interroga a Kike ('Por que siempre me mostraste tan bueno?', 'Por que llevo un 7 en el pecho?', 'Antes de crearme... quien te creo a vos?') - 'Un dialogo profundo entre el nino que siente y el hombre que lo imagino', 'Nace un dialogo que cambia todo', Lema 'Sentir es el camino' - cartel visible en el estudio; eje tematico: 'Historias que nacen del corazon. Preguntas que transforman.', Motivo del numero 7: 7 en el pecho de Pepito, siete anos de edad, precio 7,77 / 7.777, serie de 7 comics, Amor 7 Septemlogia - obra poetica/cinematografica de Enrique Piana vinculada al universo del 7, Enrique Piana - poeta y cineasta, autor de la serie Pepito Sentinfante y de Amor 7 Septemlogia, Kike, su creador - anciano de barba blanca, gafas, sombrero panama blanco, bufanda azul y traje claro, dibujando en un cuaderno; el hombre que imagino a Pepito, Pepito Sentinfante - nino de pelo castano rojizo, ojos azules, camiseta azul con un 7 amarillo en el pecho, siete anos de edad; personaje que siente (+1 more)

### Community 6 - "Lanzamiento Amor 7 Sicilia"
Cohesion: 0.36
Nodes (8): Arte colaborativo - collaborative art as founding principle ('Bienvenido el arte colaborativo'), Enrique Piana - poet/filmmaker, central figure welcoming the group with open arms, El grupo - large collective of participants welcomed to the project ('Bienvenido todo el grupo'), Isola Bella, Sicilia - launch location depicted at sunset, 14 de julio del 2026 - start date of Amor 7, Amor 7 launch poster - 'Hoy empieza AMOR 7' celebratory announcement image, Amor 7 (Septemlogía) - collaborative art project, Siete años. Siete países. Una sola obra. - septology structure tagline (7 years, 7 countries, one single work)

### Community 7 - "In Lak'ech y Cultura Maya"
Cohesion: 0.48
Nodes (7): Clasped Hands with Mayan Glyph Overlay (photo), In Lak'ech Ala K'in (Mayan greeting), Indigenous Bracelets on Both Wrists, Interlocking Hand Grip Gesture, Mayan Culture, Mayan Glyphs and Solar Cross Symbol, Unity and Brotherhood Symbolism

### Community 8 - "Aplausos y Celebración"
Cohesion: 0.60
Nodes (5): Applause / ovation gesture, Celebration and enthusiastic approval (bravo message), TV show studio audience (crowd scene), WhatsApp conversation Enrique Piana - Roger GV, WhatsApp sticker: TV studio audience applauding and cheering

### Community 9 - "Humor Celebratorio"
Cohesion: 0.50
Nodes (5): WhatsApp chat between Enrique Piana and Roger GV, Animal-with-human-arms meme format (humor via absurd body swap), Celebratory humor / triumphant excitement expressed via sticker, Rock-on / devil horns hand gesture (celebration, enthusiasm), Sticker: white cockatoo with photoshopped human arms making rock-on devil horns gesture

## Ambiguous Edges - Review These
- `WhatsApp chat between Enrique Piana and Roger GV` → `Toddler child (small child seen from behind, curly hair)`  [AMBIGUOUS]
  00000023-STICKER-2026-08-06-07-20-16.webp · relation: conceptually_related_to
- `Indigenous Bracelets on Both Wrists` → `Mayan Culture`  [AMBIGUOUS]
  00000185-PHOTO-2026-08-15-06-47-26.jpg · relation: conceptually_related_to
- `Enrique Piana` → `Enrique Viana (director de zarzuela, homónimo de Enrique Piana)`  [AMBIGUOUS]
  segundo-cerebro-piana.md · relation: semantically_similar_to
- `CINE POESÍA 7 (lenguaje cinematográfico: terapéutico, voluntarios no profesionales, toma única, sin fines de lucro, final en YouTube, movimientos grupales silenciosos, imagen+palabra)` → `Clip de video 15-08-2026 ('This is Sina Poesia', transcripción ruidosa)`  [AMBIGUOUS]
  graphify-out/transcripts/00000191-VIDEO-2026-08-15-16-41-07.txt · relation: references

## Knowledge Gaps
- **20 isolated node(s):** `14 de julio del 2026 - start date of Amor 7`, `Siete años. Siete países. Una sola obra. - septology structure tagline (7 years, 7 countries, one single work)`, `Traditional folk costume (white shirt, dark vest, red waist sash, loose trousers, sandals)`, `Joy / celebration (exuberant laughing jump, arms raised)`, `Traditional folkloric costume (white blouse, vest, red faja sash, loose trousers, sandals)` (+15 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `WhatsApp chat between Enrique Piana and Roger GV` and `Toddler child (small child seen from behind, curly hair)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Indigenous Bracelets on Both Wrists` and `Mayan Culture`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Enrique Piana` and `Enrique Viana (director de zarzuela, homónimo de Enrique Piana)`?**
  _Edge tagged AMBIGUOUS (relation: semantically_similar_to) - confidence is low._
- **What is the exact relationship between `CINE POESÍA 7 (lenguaje cinematográfico: terapéutico, voluntarios no profesionales, toma única, sin fines de lucro, final en YouTube, movimientos grupales silenciosos, imagen+palabra)` and `Clip de video 15-08-2026 ('This is Sina Poesia', transcripción ruidosa)`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **Why does `Enrique Piana` connect `Biografía y Obra de Piana` to `Ecosistema Hermes y Roger GV`?**
  _High betweenness centrality (0.112) - this node is a cross-community bridge._
- **Why does `Septemlogía Amor 7 (7 cortometrajes, 7 países, 7 años)` connect `Biografía y Obra de Piana` to `Rodaje Amor 7 Isola Bella`?**
  _High betweenness centrality (0.072) - this node is a cross-community bridge._
- **Why does `Amor 7 Isola Bella Sicilia (7/7, rodada julio 2026 con 17 participantes)` connect `Rodaje Amor 7 Isola Bella` to `Biografía y Obra de Piana`?**
  _High betweenness centrality (0.055) - this node is a cross-community bridge._