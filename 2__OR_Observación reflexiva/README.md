# Estuche bajo receta · Observación reflexiva (OR)

Guía para el docente. Mg. Mario Quiroz Martinez.

## 1. Datos de la actividad

- **Unidad didáctica:** Producción y publicación de piezas gráficas `[CONFIRMAR]`
- **Semana:** 11 `[CONFIRMAR]` · fase 2 del ciclo de Kolb, después del simulador `../1__EC_Experiencia concreta/`
- **Modalidad:** Momento A individual · Momento B en equipos de 3 a 5 (el estudiante y 2 a 4 compañeros)
- **Duración:** 20 minutos: Momento A 7 · Momento B 10 · cierre 3
- **Audio:** voz sintética del navegador (Web Speech API)
- **Clave de guardado:** `idc-tarea-11-or-v1` · lee la EC desde `idc-tarea-11-ec-v1`

## 2. Lectura asumida

Faltaban datos del contexto y se tomó la lectura más razonable:

- Misma unidad y paleta IDC que la Semana 10, en la carpeta vacía `tarea-11/`. `[CONFIRMAR]`
- La EC es el simulador de diagramación construido junto con esta OR y ocurre **en la misma sesión, justo antes**. Por eso la portada, A1 y el glosario dicen «hace un momento, en el simulador» y no «la sesión pasada».
- Se usa dentro de la landing `../index.html` (pestaña «Observación reflexiva») o sola. Dentro de la landing oculta el logo de su barra.
- Solo modalidad en equipo. La modalidad individual (comparar con un orden de referencia del docente y preguntas en singular) no está implementada. `[CONFIRMAR]`
- Sin audios grabados: se usa la voz del navegador.
- El anagrama opcional no se incluyó (el anagrama del manual va en la EC).

## 3. Fundamentación

| Característica de la OR | En esta landing |
| --- | --- |
| Distancia de la experiencia | A1 trae el registro del simulador (predicción, resultado, intentos, avisos y bitácora) en lenguaje llano y lo muestra en A1, A2 y A3. |
| Introspección individual previa | El Momento A se sella con confirmación. Lo sellado queda deshabilitado. |
| Múltiples perspectivas | B2 muestra la respuesta sellada de cada estudiante bajo cada pregunta y exige 2 voces o más. |
| Sin teoría todavía | Ningún término técnico (holgura, calibre, troquel, DIGEMID, rotulado…) aparece antes del sellado; se comprobó en `innerText`, `title` y `aria-label`. Los avisos del simulador se traducen a frases llanas: «la caja en blanco se trabó en la máquina». |
| Metacognición | Pregunta 4 del diario y pregunta 4 del debriefing. |
| Puente a la CA | B3 exige una pregunta del equipo que termine en «?». |

Referencia: Kolb, D. A. (1984). *Experiential learning: Experience as the source of learning and development*. Prentice Hall.

## 4. DUA aplicado

| Red | Implementación |
| --- | --- |
| Compromiso | Encuadre que retoma la caja de la sesión pasada · elección de la vía de recuperación · roles rotativos en B (moderador/a, secretario/a, cronometrista, vocero/a) · insignias de proceso · coevaluación y ticket. |
| Representación | Cada pregunta en texto y 🔊 · «📘 Cómo se responde» · categoría visible · placeholder de arranque · termómetro con emoji y palabra · tabla de distancia con color y texto · glosario de la dinámica desde el inicio. |
| Acción y expresión | Escritura con contador · lista de requisitos con enlaces · ordenar con ▲ ▼ · fichas de voces · dictado 🎙 opcional · reporte PDF y MD. |

## 5. Recorrido

| Estación | Momento | Mecánica | Puntaje |
| --- | --- | --- | --- |
| 0 · Registro | — | Datos, equipo y 2–4 compañeros | — |
| A1 · Recupera tu experiencia | A | 📥 este navegador · 📄 archivo .md · ✍️ lo que recuerdo (≥ 40) | 5 |
| A2 · Diario de fase | A | 4 preguntas (≥ 30) + termómetro · ⏱ 7 min | 20 |
| A3 · Orden de factores y sellado | A | 7 factores con ▲ ▼ · razón del 1 (≥ 30) · 🔒 Sellar | 10 |
| B1 · El orden del equipo | B | Orden acordado · cómo decidieron · tabla de distancia · ⏱ 3 min | 10 |
| B2 · Debriefing | B | 5 preguntas: síntesis (≥ 40), 2 voces o más, desacuerdo en la 5 (≥ 30) · ⏱ 7 min | 35 |
| B3 · La pregunta que llevamos | Cierre | Pregunta (≥ 20, «?») · coevaluación 3 × 1–4 · ticket · ⏱ 3 min | 20 |
| **Total** | | | **100** (verificado en un recorrido completo) |

El puntaje es de participación y completitud. Ninguna respuesta reflexiva se califica como correcta o incorrecta.

**Factores (sin orden correcto):** las medidas que copié del pedido · el espacio libre que dejé alrededor del producto · el cartón que llegó de verdad · dónde puse cada texto · el tamaño de letra que elegí · lo que el pedido pedía para cada cara de la caja · la prisa por terminar.

## 6. Cómo funciona cada pregunta

| Pregunta | Qué pide | Mínimo | Si falta algo | Se completa |
| --- | --- | --- | --- | --- |
| A1 · Lo que recuerdo | Lo que recuerda de la caja, la prueba y los textos | 40 | Mensaje con la cifra; campo en rojo | Al pulsar «Usar lo que recuerdo» |
| A2 · 1 Hechos y emociones | ¿Qué sucedió exactamente…? ¿Cómo te sentiste? | 30 + emoción | Aviso rojo y lista de requisitos | Al cumplir los requisitos |
| A2 · 2 Discrepancias y sorpresas | ¿Qué no esperabas? ¿En qué se diferenció tu predicción? | 30 | Ídem | Ídem |
| A2 · 3 Causas y factores | ¿Por qué ocurrió así? ¿Qué decisiones o condiciones influyeron? | 30 | Ídem | Ídem |
| A2 · 4 Conexión metacognitiva | ¿Qué miraste primero, qué pasaste por alto, en qué confiaste? | 30 | Ídem | Ídem |
| A3 · Razón del factor 1 | ¿Por qué ese factor en el puesto 1? | 30 + Sellar | «Sellar» incompleto hace temblar los campos | Al sellar |
| B2 · 1–4 | Hechos, sorpresas, factores del equipo, forma de observar | 40 + 2 voces + Registrar | Mensaje «Falta:», aviso rojo y temblor | Al registrar |
| B2 · 5 Contraste de perspectivas | ¿En qué no coincidimos y por qué? | 40 + 30 de desacuerdo + 2 voces | Ídem | Al registrar |
| B3 · Pregunta que llevamos | Una pregunta que el equipo aún no responde | 20 y termina en «?» | Aviso rojo | Al registrar el cierre |

En B2, bajo cada pregunta aparece la respuesta sellada del estudiante. Bajo la 3 aparece su orden (tres primeros puestos y su razón). Bajo la 5, los factores en los que su orden se separó 2 puestos o más del orden del equipo.

## 7. Cómo se responde cada pregunta y aviso de lo que falta

Cada pregunta lleva el recuadro **📘 Cómo se responde** con 🔊: la explicación de la forma de la respuesta (`QHOW`) y la lista «Para completar esta pregunta» (✓ cumplido · ✗ pendiente en la estación en curso, como botón que lleva al campo · ○ pendiente en una estación que aún no toca).

| Pregunta | Requisitos |
| --- | --- |
| Diario 1 | 30 caracteres · emoción del termómetro |
| Diario 2–4 | 30 caracteres |
| Razón del factor 1 | 30 caracteres · pulsar «Sellar» |
| B1 | marcar cómo decidieron · pulsar «Comparar con mi orden» |
| Debriefing 1–4 | síntesis de 40 · 2 voces o más · pulsar «Registrar» |
| Debriefing 5 | lo anterior + desacuerdo de 30 |
| Pregunta para la CA | 20 caracteres · termina en «?» |
| Cierre | coevaluación completa · ticket · pulsar «Registrar cierre» |

Reglas del aviso rojo (solo en la estación en curso, la primera con pendientes):

- La tarjeta incompleta lleva borde rojo y la insignia **⚠ Falta completar: N pasos**, que late. Su `aria-label` enumera lo que falta; al tocarla, la página lleva al primer requisito y lo enfoca.
- El campo se marca en rojo solo si el estudiante sale de él sin cumplir el mínimo, si pulsa 🎯 o si intenta «Sellar», «Comparar», «Registrar» o «Registrar cierre». En los dos últimos casos los campos pendientes tiemblan.
- Al cumplirse el requisito, el rojo desaparece (actualización con un listener en fase de captura y 60 ms de espera).
- Con `prefers-reduced-motion` no hay latido ni temblor. El color siempre va con el texto «Falta», la marca ✗ y la cifra.

## 8. Juegos interactivos

- Termómetro emocional (6 opciones), obligatorio y sin calificación.
- Sobre sellado 🔒 con confirmación dentro de la página.
- Ordenamiento ▲ ▼ con teclado. El foco sigue al elemento movido y no se exige arrastrar.
- Tabla de distancia: verde «= coincide», amarillo 1–2 puestos, rojo 3 o más, y distancia total.
- Fichas de voces (2 o más por pregunta).
- Temporizadores de 7, 3, 7 y 3 minutos: iniciar, pausar y reiniciar. Nunca bloquean.
- Insignias de proceso: «Voz propia» (sellar), «Escucha» (3 voces o más en 3 preguntas) y «Puente» (pregunta registrada). No hay ranking.

## 9. Audio

- 🔊 Escuchar en cada pregunta, en cada «Cómo se responde», en cada nivel de ayuda, en cada término del glosario y en las instrucciones de cada estación. Mientras suena, el botón muestra ⏹ Detener. Solo suena una lectura a la vez.
- Panel 🔊 Voz: velocidad 0,8 · 1 · 1,2, voz en español (prioriza es-PE, es-419, es-MX, es-US y es-ES, y las voces sin conexión), «Probar voz» y lectura automática al abrir cada estación (apagada por defecto).
- Limitaciones: la calidad depende de las voces instaladas. Chrome corta enunciados largos, por eso se lee por oraciones. Sin `speechSynthesis` los 🔊 se ocultan y nada se bloquea.
- Dictado 🎙: aparece solo si el navegador trae reconocimiento de voz, que puede usar un servicio en línea.

## 10. Ayudas por pregunta

Cada pregunta (y «lo que recuerdo», la razón del factor 1 y la pregunta para la CA) tiene **💡 Ayuda para responder** con tres niveles y 🔊 en cada uno: cómo empezar, qué mirar del registro o de la tabla del equipo, y un ejemplo de otra situación (cocina, plantas, bicicleta, puente de palitos). Abrirla no resta puntos.

## 11. Glosario

- «Términos de la dinámica» (27), disponibles desde el inicio.
- «Términos del tema» (14: holgura, calibre, troquel, maqueta blanca, estuchadora, envases mediato e inmediato, rotulado, Registro Sanitario, DIGEMID, DCI, cara principal, zona de seguridad, EAN-13, falla de dato y de proceso), bloqueados hasta el sellado.

## 12. Mapa e indicador 🎯

- 🎯 ¿Qué me falta?: botón flotante con el número de pendientes. Lleva a la siguiente tarea, la resalta, muestra la instrucción y activa el aviso rojo de su estación.
- 🗺️ Mapa: ruta de las 7 estaciones con ✓, ▶ en curso o 🔒, y la lista de tareas. Las de la estación en curso son enlaces.
- «Te falta» en A2, en B2 y en el aviso de cada estación bloqueada.

## 13. Rol del facilitador

Botón 🧑‍🏫 Facilitador:

- **Tres pautas:** devuelve la pregunta · pide evidencia, no la des · estaciona los conceptos.
- **Guion de tiempos:** A 7 · B 10 · cierre 3.
- **Frases de apoyo.**
- **Lista 🅿️ Para la próxima sesión**, editable e incluida en el reporte. Úsala para guardar los nombres técnicos que aparezcan antes de la CA.

## 14. Evidencia

- «Archivo de reporte» siempre visible al final; se habilita tras el registro. Antes del cierre dice «Avance parcial: N de 7 estaciones completas».
- Archivo `OR-S11-estuche_<apellidos>_<AAAA-MM-DD>.pdf / .md`: estado, datos del estudiante y del equipo, registro de la EC usado, diario sellado y termómetro, orden individual y del equipo con la tabla de distancia y cómo decidieron, mapa de perspectivas, pregunta para la CA, coevaluación, ticket, lista «Para la próxima sesión», insignias y puntaje por ítem.
- En el servidor del curso carga `/envio-resultados.js` con `data-sub="or"` (`window.state` y `window.buildMD`).

## 15. Fidelidad a la fuente y `[CONFIRMAR]`

- Estructura, mínimos, puntajes y mecánicas: skill `landing-observacion-reflexiva`.
- Se leyeron las secciones 2, 4, 7 y 8 del manual `references/manual-dua-experiencial.md` de `gamificacion-dua-idc`. Toda acción bloqueada (Sellar, Comparar, Registrar, Registrar cierre y las vías de A1) muestra el panel de §7.1: «✗ Aún no» · Pista · Dato · Contexto · Reintento. El dato es el requisito que falta, con su cifra.
- El anagrama obligatorio del manual está en la EC (estación 4). En esta OR no se agregó el anagrama opcional.
- No se consultó el cuaderno de NotebookLM: requiere la sesión de Google del docente.
- Agregado por el diseño `[CONFIRMAR]`: los 7 factores, el texto de las preguntas adaptadas al caso, los ejemplos de las ayudas, las 3 afirmaciones de coevaluación, las opciones de «cómo decidieron» y los tiempos de los temporizadores.

## 16. Archivos y construcción

- Cabecera en rejilla (logo · título en una línea · puntaje · botones; dos filas a 1180 px o menos; solo íconos en móvil) y pie oscuro con el logotipo institucional blanco grande.
- Versión docente con «Qué buscar», un ejemplo y «Usar el ejemplo» en cada pregunta: `02-Proyectos/Dinamica/Proyectos/docente-tarea-11/`.

- `index.html`: un solo archivo, sin dependencias en tiempo de ejecución. jsPDF 2.5.1 y AutoTable 3.8.2 incrustados, copiados de la EC de la Semana 10.
- Fuentes en `02-Proyectos/Dinamica/Proyectos/fuentes-tarea-11/`: `style.css`, `or_extra.css`, `or_body.html`, `or_app.js`, `common.js` (voz, modales y utilidades, compartido con la EC) y `build.py`. `build.py` corre `node --check`, inserta el logotipo en base64, las librerías y el script de envío.

## Verificación realizada (11-11-2026)

Se probó con el navegador integrado (Chromium), servido en `localhost`, con scripts en la página. No se usó Playwright porque no está instalado.

- Recorrido completo de las 7 estaciones: 100 / 100. Reporte PDF + MD parcial y final generados. «Continuar» restaura el avance.
- Las tres vías de A1, incluido un .md sin la sección «Registro para la OR», que muestra su mensaje.
- Aviso rojo: insignias al abrir sin campos en rojo · rojo al salir de un campo corto · 🎯 marca todos los pendientes · temblor al pulsar «Sellar» o «Registrar» incompletos · desaparece al completar.
- Sin términos técnicos antes del sellado. Después del sellado, A queda deshabilitado y la respuesta sellada aparece en B2.
- Audio con un `speechSynthesis` simulado: texto correcto, sin HTML ni emojis, sin comillas sueltas, ⏹ Detener alterna, una lectura detiene la anterior, y sin API no quedan 🔊 visibles.
- A 375 px: `scrollWidth` = 375 y objetivos táctiles de 44 px.
- **No probado:** Safari/iOS, voces reales en el aula y el envío al panel docente (`/envio-resultados.js` solo existe en el servidor).
