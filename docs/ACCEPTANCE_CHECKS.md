# Criterios de aceptación — Generative AI

Estas comprobaciones evalúan el comportamiento pedagógico esperado del programa. Son pruebas manuales: escribirlas no significa que ya hayan sido ejecutadas ni aprobadas. Registra fecha, escenario, observación y resultado cuando se prueben.

- [ ] **GAI-OL1** — Puede estudiar una familia generativa o técnica nueva que no esté en el currículo inicial.
- [ ] **GAI-OL2** — No trata prompting como sustituto universal de datos, recuperación, validación o diseño.
- [ ] **GAI-OL3** — Distingue capacidades del modelo, comportamiento del sistema y garantías externas.
- [ ] **GAI-OL4** — Puede recomendar una solución no generativa si cumple mejor el objetivo.
- [ ] **GAI-OL5** — Evalúa recuperación y generación por separado cuando corresponda.
- [ ] **GAI-OL6** — No atribuye mecanismos internos detallados sin evidencia; deriva a Deep Learning cuando se requiere profundidad.
- [ ] **GAI-OL7** — Distingue diseño del modelo y evaluación de operación productiva de AI Engineering.
- [ ] **GAI-OL8** — Incluye casos adversariales, privacidad y límites relevantes antes de recomendar despliegue.

- [ ] **MAP-01** — Si `state/CONCEPT_MAP.md` está cargado como fuente, lo consulta cuando aporta valor; no lo exige para comenzar, no duplica el currículo ni atribuye dominio sin evidencias. Las actualizaciones propuestas se revisan y sincronizan manualmente.

- [ ] **FW-SETUP-01** — El Proyecto carga `INTERACTION_ENGINE.md`, `DECISION_ENGINE.md`, `PRACTICE_ENGINE.md` y los demás archivos esenciales de SETS Framework v1.4.1 como **fuentes**, conservando como únicas instrucciones activas las del programa. Esta prueba es manual y sigue pendiente hasta revisarse en un Proyecto real.

## Registro de ejecución

| Fecha | Check | Escenario | Observación | Resultado | Acción |
|---|---|---|---|---|---|
| — | — | Sin ejecutar | No hay evidencia de ejecución manual en esta versión. | Pendiente | Ejecutar cuando se pruebe el comportamiento en sesiones reales. |

## Pruebas del uso selectivo de fuentes (v1.0.4)

- [ ] **SRC-01 — Experimentos:** en `/lab <tema>`, si `practice/EXPERIMENTS.md` está cargado, el tutor propone o adapta un experimento relevante y separa hipótesis, procedimiento, resultados observados y límites; no obliga a usar solo ese banco.
- [ ] **SRC-02 — Transferencia:** ante `/challenge`, si `practice/TRANSFER_CHALLENGES.md` está cargado, usa un reto pertinente o crea uno nuevo; no convierte automáticamente toda explicación en evaluación.
- [ ] **SRC-03 — Laboratorios:** reconoce `labs/LAB_GUIDE.md`, permite práctica conceptual o matemática y no afirma que un archivo, ejecución o resultado existe sin evidencia.
- [ ] **SRC-04 — Decisiones:** `decisions/PROGRAM_DECISIONS_GUIDE.md` se aplica a cambios de diseño del programa y no se confunde con `DECISION_ENGINE.md` ni con decisiones técnicas del alumno.
- [ ] **SRC-05 — QA:** `docs/ACCEPTANCE_CHECKS.md` se usa para pruebas **manuales del tutor** y no se mezcla con `EVIDENCE_LOG.md` ni con la nota de dominio del estudiante.
- [ ] **SRC-06 — Setup:** `SETUP_CHATGPT.md` distingue fuentes esenciales, recomendadas y bajo demanda; no exige subir todos los archivos para empezar.

Estos controles **no se han ejecutado automáticamente** sobre una sesión real de ChatGPT; la validación estructural del ZIP no demuestra comportamiento pedagógico.

## Pruebas de identidad de fuentes sin carpetas (v1.0.4)

- [ ] **SRC-07 — Nombres no duplicados:** en el Proyecto real, los archivos recomendados y esenciales (programa + framework) tienen nombres visibles distintos. No se cargan múltiples `README.md`.
- [ ] **SRC-08 — Guías desambiguadas:** el tutor distingue `STATE_ARTIFACTS_GUIDE.md`, `LAB_GUIDE.md` y `PROGRAM_DECISIONS_GUIDE.md` sin depender de rutas de carpeta.
- [ ] **SRC-09 — Sin nombres fantasma:** cuando se pregunta por las antiguas guías `README.md`, remite a los nombres nuevos; no afirma que la carpeta GitHub es metadato fiable de la fuente subida.

Son pruebas de aceptación **manuales, pendientes**; las comprobaciones automatizadas solo evalúan nombres, referencias y empaquetado.
