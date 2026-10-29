# Mesa de diagnóstico: ¿qué no se verificó? · Observación reflexiva (OR)

Guía para el docente. Unidad didáctica **Producción y publicación de piezas gráficas** · Mg. Mario Quiroz Martinez.

## Justificación DUA-Experiencial

La actividad continúa el expediente de la fase de Experiencia concreta y adopta el enfoque **DUA-Experiencial** en la fase de **Observación reflexiva (OR)**: el equipo contrasta lo vivido (piezas defectuosas) con los datos (reportes), separa observación, dato e inferencia, clasifica causas probables y formula hipótesis de verificación antes de buscar soluciones. Se trabaja en equipos de 3 a 4 integrantes durante 45 a 60 minutos.

| Estación | Fase | Mecánica | Puntaje |
| --- | --- | --- | --- |
| Registro y acuerdos | — | Datos del estudiante (nombre y correo) y del equipo · roles: moderador, secretario, cronometrista y vocero | — |
| Paso 1 · Inspección y reporte | OR | Inspección por puntos de las piezas · observación escrita con detector de «soluciones prematuras» | 20 |
| Estación 2 · Observación, dato o inferencia | OR · CA | Clasificador de 8 afirmaciones · definición de hipótesis de verificación | 26 |
| Paso 2 · Clasificación de causas | OR | Tablero A–D con 12 causas · marcado de evidencia (reporte / por verificar) · patrón | 42 |
| Paso 3 · Hipótesis de verificación | OR → CA | Redacción guiada con lista de cotejo automática (orientativa) | 24 |
| Estación 5 · Anagramas | CA | HIPÓTESIS · CALIBRACIÓN · VERIFICACIÓN | 30 |
| Matriz y plenaria | OR → EA | Matriz del equipo vs. referencia · preguntas de plenaria · constructor de lista de chequeo · coevaluación y ticket | 58 |
| **Total** | | | **200** |

- **Implicación:** trabajo en equipo con roles, temporizador por paso, insignias y error productivo (Pista · Dato clave · Contexto).
- **Representación:** piezas ilustradas con puntos de inspección, reportes objetivo vs. medido, tablero de categorías, matriz comparativa, mapa y glosario.
- **Acción y expresión:** tocar, clasificar, ubicar, marcar evidencia, redactar con andamiaje, construir una lista de chequeo y coevaluar.

## Fidelidad a la fuente

Los valores técnicos provienen de los reportes del caso:

- **DTF:** objetivo 160 °C / 20 s con presión neumática uniforme; medido 130 °C / 10 s; fusión del TPU entre 150 y 170 °C.
- **3D:** objetivo 210 °C; medido 175 °C.

**Artes finales del Paso 1:** la pieza A usa los dos artes finales reales del pedido, `078yp2qo.cdr` (águila ornamental) y `r7vm6967.cdr` (calavera «Youth Crew»), los mismos de la actividad EC. El equipo puede alternar el diseño de la prenda; los tres puntos de inspección caen sobre el contorno izquierdo, el centro agrietado y el borde inferior en ambos diseños.

Solo esos tres valores se consideran «respaldados por el reporte»; las demás causas del tablero son hipótesis plausibles por verificar.

La matriz de referencia reproduce la guía entregada con tres ajustes:

- «temperatura de transición vítrea/fusión» → **punto de fusión (150–170 °C)**: la transición vítrea es otro fenómeno y el reporte documenta el punto de fusión;
- «fibras del algodón» → **fibras del tejido**: la prenda es de algodón/poliéster;
- «tiempo de bajada» → **tiempo de prensado**.

## Lista de cotejo del Paso 3

Detecta por palabras clave si la hipótesis nombra un parámetro, usa los valores del reporte, explica el mecanismo y lo vincula con la falla. Exige al menos 3 de 4 criterios (12 puntos con 4, 9 con 3). Es orientativa: conviene revisar la redacción en el informe.

## Evidencia y datos

- Informe en **PDF y MD** por estudiante, con sus datos, los del equipo y todas las respuestas, intentos y puntos.
- Las respuestas se guardan en el navegador (`localStorage`, clave `expediente-qc-or-registro-v1`) y se pueden retomar.
- El PDF usa jsPDF 2.5.1 y jsPDF-AutoTable 3.8.2 incrustados: funciona sin conexión.
- Desde el servidor del curso carga `/envio-resultados.js` con `data-sub="or"`, separado de la actividad EC (`ec`).
