# Ruta del estuche farmacéutico · landing de la Semana 11

Guía para el docente. Mg. Mario Quiroz Martinez. Unidad didáctica Producción y publicación de piezas gráficas

Los estudiantes abren `https://aplicativos-idc.<tu-red>.ts.net/tarea-11/`. La página reúne la sesión completa en tres partes.

| Parte | Dónde | Qué hace el estudiante |
| --- | --- | --- |
| 1 · Preámbulo | `index.html`, banda azul «Parte 1 · Preámbulo» | Recorre el diagrama de flujo con los códigos de falla; prueba la calculadora (pasos 1 a 7), que valida los datos y dibuja el **plano de la caja** con sus cotas, la zona de seguridad y el **sangrado del color de fondo** (3 mm fuera del corte, color elegible); revisa las plantillas SPD116 y SPD104, el checklist de rotulado (D-05) y las normas. |
| 2 · Simulador | pestaña «Simulador de la caja», incrustada desde `1__EC_Experiencia concreta/index.html` | Experiencia concreta: elige producto, predice, calcula, prueba la caja en blanco (P-01), diagrama 16 piezas sobre el troquel con fondo y sangrado, resuelve el anagrama y escribe la bitácora. |
| 3 · Observación reflexiva | pestaña «Observación reflexiva», incrustada desde `2__OR_Observación reflexiva/index.html` | Momento A individual y sellado; Momento B en equipo; pregunta para la próxima sesión. Lee el registro del simulador desde el mismo navegador. |

## Cómo funciona la parte incrustada

- Las dos actividades se cargan en marcos (iframes) del mismo servidor. Cada una sigue siendo una página independiente: también se abren solas con «↗ Abrir en otra pestaña».
- «⛶ Pantalla completa» muestra la actividad en toda la pantalla; «↻ Recargar» la vuelve a cargar sin perder el avance, que está guardado en el navegador.
- Las pestañas muestran el estado: «Sin empezar», «En curso · N / 100 pts» o «Completado». Al completar el simulador aparece «Seguir con la observación reflexiva →».
- Dentro de la landing, las actividades ocultan el logo de su barra (ya está en la cabecera). Fuera de ella lo muestran.
- El dictado 🎙 funciona en el marco porque se le da permiso de micrófono (`allow="microphone"`); el navegador lo pedirá la primera vez.

## Decisiones de diseño

- El preámbulo presenta el diagrama, la fórmula y las normas **antes** del simulador, como pidió el docente. La observación reflexiva mantiene su regla: ningún término técnico antes del sellado.
- El relato de la OR dice «hace un momento, en el simulador», porque las dos partes ocurren en la misma sesión.
- Cabecera: logo a la izquierda y las tres partes numeradas a la derecha; el cajetín del plano pasó a la portada. Pie oscuro con el logotipo institucional blanco grande.

## Versión docente

En `02-Proyectos/Dinamica/Proyectos/docente-tarea-11/`, **fuera** de la carpeta que publica el servidor. Tiene la misma landing y las mismas actividades con recuadros «🔑 Para el docente» y botones para cargar las respuestas. Ver su README.

## Archivos y construcción

- `index.html` (landing), `1__EC_Experiencia concreta/` y `2__OR_Observación reflexiva/`, cada uno con su README.
- Fuentes en `02-Proyectos/Dinamica/Proyectos/fuentes-tarea-11/`. `py -3.12 build.py` arma la versión de estudiante y la docente; `build.py estudiante` o `build.py docente` arman solo una.
- La landing carga sus tipografías desde Google Fonts. Sin conexión usa las del sistema y todo sigue funcionando.

## Verificación (11-11-2026)

Navegador integrado (Chromium), servido por HTTP en `localhost` (configuraciones `tarea-11` y `docente-tarea-11` de `.claude/launch.json`):

- La landing carga sin errores, el plano se redibuja con la calculadora y con el color de fondo, y no hay desborde horizontal.
- Recorrido completo dentro de la landing: simulador (95 / 100 con un atasco y una corrección) y OR (100 / 100) en sus pestañas. La OR leyó el registro del simulador, la landing actualizó los estados y se generaron los reportes PDF + MD desde los marcos.
- Cabecera de las actividades a 1280, 1000 y 375 px; pie con el logo de 76 px (60 px en móvil).
- **No probado:** Safari/iOS, el servidor real del curso y el envío al panel docente.
