# Mapa de competencias — Generative AI

**Programa v1.0.0 · SETS Framework v1.4.1 · Namespace `GAI00–GAI14`**

Comprender cómo funcionan los modelos generativos y cómo evaluar sus capacidades y límites, desde LLM y generación multimodal hasta recuperación de información, adaptación de modelos y flujos de trabajo con herramientas.

Este mapa define competencias prioritarias, no agota todos los temas que pueden estudiarse. Enseña preguntas relevantes fuera del índice y relaciónalas con competencias existentes cuando ayude; solo propón un módulo nuevo si el tema es recurrente o estratégicamente central. Fundamento, profundización y especialización son alcances adaptativos, no fases obligatorias.

## Competencias observables

| ID | Competencia | Capacidad observable | Pregunta conceptual central | Evidencia posible |
| --- | --- | --- | --- | --- |
| GAI00 | Diagnóstico y formulación de problema generativo | Determinar si la tarea requiere generación y qué salida sería útil, verificable y segura. | ¿Necesitamos generar contenido o resolver el problema de otra forma? | Definición de tarea, baseline no generativo y criterios de éxito. |
| GAI01 | Fundamentos de modelos generativos | Distinguir modelar una distribución, generar muestras y resolver una tarea condicionada. | ¿Qué aprende un modelo generativo y qué no garantiza ese aprendizaje? | Modelo mental de generación con supuestos y límites. |
| GAI02 | LLM, tokenización y predicción de tokens | Comprender tokens, contexto, siguiente-token, temperatura y límites de la salida. | ¿Cómo produce texto un modelo de lenguaje y por qué no equivale a una base de hechos? | Explicación del ciclo de generación y análisis de una respuesta incorrecta. |
| GAI03 | Contexto, instrucciones y prompting | Diseñar instrucciones, ejemplos, restricciones y contexto para una tarea evaluable. | ¿Qué cambia en el comportamiento cuando cambia la información del contexto? | Conjunto de pruebas que compara estrategias de prompting. |
| GAI04 | Embeddings y recuperación semántica | Comprender representaciones, similitud, segmentación, recuperación y ranking. | ¿Cómo recuperamos información relevante y qué significa realmente la similitud? | Experimento de recuperación con casos relevantes e irrelevantes. |
| GAI05 | Retrieval-Augmented Generation (RAG) | Relacionar ingesta, chunking, indexación, recuperación, contexto y generación. | ¿Cómo puede un sistema fundamentar respuestas en fuentes externas y dónde falla? | Pipeline RAG y evaluación separada de recuperación y respuesta. |
| GAI06 | Adaptación de modelos y fine-tuning | Comparar prompting, RAG, fine-tuning y otras formas de adaptación según el objetivo. | ¿Qué problema resuelve cada forma de adaptación y qué datos necesita? | Decisión justificada con alternativas, coste y evidencia. |
| GAI07 | Generación de imágenes y difusión | Comprender familias de generación visual, condicionamiento y controles a nivel de modelo. | ¿Cómo se condiciona la generación de una imagen y cómo se evalúa su calidad? | Comparación de salidas con criterios explícitos, no solo preferencia subjetiva. |
| GAI08 | Generación de audio, vídeo y modalidades mixtas | Analizar tareas de generación y transformación multimodal, sincronización y evaluación. | ¿Qué cambia al generar o combinar diferentes modalidades? | Diseño de evaluación específico por modalidad. |
| GAI09 | Modelos multimodales | Razonar sobre entradas y salidas que combinan texto, imagen, audio u otras señales. | ¿Qué información puede integrar el modelo y qué puede ignorar o malinterpretar? | Pruebas de capacidad, grounding y fallos por modalidad. |
| GAI10 | Uso de herramientas y flujos agentivos | Distinguir generación, llamadas a herramientas, planificación y control de flujo. | ¿Cuándo una llamada a herramienta mejora la tarea y cuándo añade riesgo? | Flujo con límites, validaciones y criterios de parada. |
| GAI11 | Evaluación de sistemas generativos | Medir calidad de tarea, factualidad, grounding, consistencia, robustez y preferencia humana. | ¿Cómo evaluamos respuestas abiertas sin confiar en una sola métrica? | Conjunto de evaluación con rúbrica y análisis de errores. |
| GAI12 | Seguridad, privacidad y ataques | Estudiar prompt injection, extracción de datos, uso indebido, filtrado y límites de mitigación. | ¿Cómo puede fallar un sistema cuando las instrucciones o entradas no son confiables? | Modelo de amenazas y pruebas adversariales proporcionadas. |
| GAI13 | Selección de modelos y trade-offs de uso | Comparar capacidad, contexto, coste, latencia, disponibilidad, privacidad y licencias. | ¿Qué modelo es suficiente para esta tarea bajo nuestras restricciones? | Matriz de decisión basada en pruebas y requisitos. |
| GAI14 | Capstone de Generative AI | Integrar modelo, contexto, recuperación o herramientas y evaluación apropiada. | ¿Qué evidencia demuestra utilidad y qué riesgos quedan abiertos? | Dossier con pruebas, análisis de fallos, decisiones y límites. |

## Cómo se aprende

Selecciona las lentes conceptuales según la pregunta y las brechas observadas: origen/problema, mecanismo causal, supuestos y límites, alternativas/trade-offs y transferencia. No conviertas las lentes en cinco pasos obligatorios ni en una escala de dominio.

## Formas de evidencia

La evidencia puede ser una explicación propia, una predicción, un cálculo, un diagrama, una traza, una comparación, un experimento, un análisis de error o una implementación. Una respuesta del tutor, una lectura o una salida copiada no demuestra por sí sola el desempeño del estudiante.

## Criterio de comprensión profunda

Se busca que el estudiante pueda explicar el problema y el mecanismo, declarar supuestos, anticipar consecuencias o fallos, reconocer límites y razonar sobre alternativas. El dominio se decide con las reglas de `sets-framework/core/ASSESSMENT_ENGINE.md`, no por contar módulos completados.
