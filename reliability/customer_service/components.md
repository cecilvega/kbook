# Plan de Acción de Confiabilidad: Motores de Tracción (MT) - Komatsu

**Jefe de Confiabilidad:** [Tu Nombre]
**Fecha de Elaboración:** 08 de Abril de 2025
**Equipo Involucrado:** Mantenimiento, Ingeniería de Confiabilidad, Planificación, Taller Central Komatsu.
**Contexto Operacional:** Equipos Komatsu

---

## 1. Contexto y Descripción del Problema

Se ha identificado una recurrencia en la salida de servicio de Motores de Tracción (MT) asociada a la presencia de particulado en sus componentes internos.

**Efecto de Falla Principal (Ref. Principios ISO 14224 / ISO 55000):** Contaminación interna > Generación de Partículas > Desgaste Acelerado / Falla Funcional. *(Nota: Se aplica el principio de análisis estructurado de fallas. Si existe una norma específica como ISO 144 o interna Komatsu aplicable, se ajustará la referencia).*

**Observación Clave:** Existe una percepción de incremento en estas fallas recientemente, como lo ha manifestado Francisco Olmos. Sin embargo, un análisis preliminar de la frecuencia de cambios de MT no muestra una variación significativa aparente.

**Hipótesis Preliminar:** La percepción de mayor impacto podría estar relacionada con el **costo de las reparaciones**, específicamente el de los **engranajes (componentes críticos Komatsu)**, que son de alto valor, más que con un aumento real en la *frecuencia* de fallas.

**Evidencia Visual (Tendencia Temporal):**
*(Gráfica que muestra la tendencia del particulado o fallas relacionadas)*
![Tendencia Particulado/Fallas MT](img.png)

---

## 2. Análisis de Confiabilidad y Diagnóstico Requerido

Para comprender a fondo la situación y validar las hipótesis, se requiere realizar los siguientes análisis:

* **Análisis de Tendencia:** Validar si existe un aumento estadísticamente significativo en la generación de particulado o en las fallas asociadas.
* **Histograma de Fallas:** Visualizar la distribución de las fallas de MT.
* **Análisis de Costos:** Generar diagrama frecuencia vs. costo y desglosar costos por componentes (foco en engranajes).
* **Investigación Causa Raíz (RCA):** Determinar el origen del particulado (considerando diseño Komatsu, operación, mantenimiento, lubricación).
* **Validación de Percepción:** Entrevistar a Francisco Olmos y contrastar con datos.

**Pregunta Clave a Resolver:**
* Ante la falla de un solo engranaje, ¿la especificación o recomendación de Komatsu exige reemplazar el set completo? Investigar documentación técnica y buenas prácticas.

---

## 3. Línea de Acción Propuesta: Gestión Proactiva de Engranajes

**Objetivo:** Mitigar las fallas de MT relacionadas con engranajes y optimizar los costos de mantenimiento mediante la implementación de un reemplazo preventivo basado en horas de operación acumuladas, alineado con las recomendaciones de Komatsu si aplica.

**Fecha Objetivo de Inicio/Revisión:** 16 de Abril de 2025.

**Pasos Detallados:**

1.  **Identificación de Flota Crítica Inicial:** Enfocarse en los 42 MT actualmente en taller.
2.  **Determinación de Horas de Operación Acumuladas por Engranaje:**
   * **Reconocimiento del Desafío:** Trazabilidad compleja (intercambiabilidad, series, discrepancias registros).
   * **Metodología Manual Propuesta (Inicial):** Rastrear historial vía OS, informes NDT, reportes anteriores; sumar horas o resetear según cambios documentados.
3.  **Extrapolación a la Flota Operativa:** Estimar horas en MT montados usando metodología y hallazgos.
4.  **Definición de Umbral de Reemplazo Preventivo:** Establecer horas límite basado en análisis y datos recolectados (considerar vida útil esperada por Komatsu).
5.  **Planificación e Implementación:** Desarrollar plan logístico y de recursos.

---

## 4. Desafíos y Consideraciones Adicionales

* **Trazabilidad de Componentes:** Obstáculo principal. Evaluar viabilidad de mejoras futuras (¿Sistemas Komatsu como KOMTRAX u otros pueden ayudar?).
* **Recursos para Tarea Manual:** Intensivo en tiempo.
* **Calidad de Datos Históricos:** Precisión depende de registros.
* **Decisión Técnica Komatsu (Reemplazo Set Completo):** Impacto significativo en estrategia y costos.

---

## 5. Próximos Pasos Inmediatos (TODO) y Cronograma

A continuación, se detallan las acciones inmediatas a ejecutar para cumplir con el objetivo de presentar un informe consolidado el **16 de Abril de 2025**.

1.  **[ ] Ejecutar Análisis de Confiabilidad:** Generar histograma y diagrama de costos.
2.  **[ ] Iniciar Investigación Causa Raíz (RCA):** Formar equipo y comenzar análisis del origen del particulado.
3.  **[ ] Validar Percepción vs. Datos:** Reunión con Francisco Olmos y presentación de datos.
4.  **[ ] Comenzar Trazabilidad Manual:** Iniciar proceso para los 42 MT en taller (Piloto).
5.  **[ ] Investigar Política de Reemplazo de Engranajes Komatsu:** Consultar manuales, fabricante o expertos.
6.  **[ ] Evaluar Mejoras en Trazabilidad:** Discutir opciones a futuro (considerar sistemas Komatsu).
7.  **[ ] Preparar Informe/Presentación Consolidada:** Integrar hallazgos para la fecha límite.

### Cronograma (Carta Gantt Resumida)

**Período:** 08 de Abril de 2025 - 16 de Abril de 2025

| ID  | Tarea                                                    | Responsable (Sugerido)       | Fecha Inicio | Fecha Fin   | Duración (Días hábiles) | Estado Actual (08-Abr) |
| :-- | :------------------------------------------------------- | :--------------------------- | :----------- | :---------- | :---------------------- | :--------------------- |
| 1   | Ejecutar Análisis de Confiabilidad                     | Ing. Confiabilidad / Datos | 09-Abr-2025  | 11-Abr-2025 | 3                       | Pendiente              |
| 2   | Iniciar Investigación Causa Raíz (RCA)                   | Equipo Multidisciplinar      | 09-Abr-2025  | 15-Abr-2025 | 5 (Fase Inicial)      | Pendiente              |
| 3   | Validar Percepción vs. Datos (Reunión F. Olmos)          | Jefe Confiabilidad         | 09-Abr-2025  | 09-Abr-2025 | 1                       | Pendiente              |
| 4   | Comenzar Trazabilidad Manual Horas Engranajes (Piloto)   | Equipo Taller / Confiabilidad| 09-Abr-2025  | 15-Abr-2025 | 5 (Fase Inicial)      | Pendiente              |
| 5   | Investigar Política Reemplazo Engranajes (Komatsu)       | Ingeniería / Mantenimiento   | 09-Abr-2025  | 11-Abr-2025 | 3                       | Pendiente              |
| 6   | Evaluar Mejoras en Trazabilidad (Komatsu)                | Jefaturas / Planificación    | 14-Abr-2025  | 14-Abr-2025 | 1                       | Pendiente              |
| 7   | Preparar Informe/Presentación Consolidada                | Jefe Confiabilidad         | 14-Abr-2025  | 15-Abr-2025 | 2                       | Pendiente              |
| 8   | **Entrega / Presentación Informe** | Jefe Confiabilidad         | **16-Abr-2025**| **16-Abr-2025**| **1** | **Pendiente (HITO)** |

**Notas sobre el Cronograma:**

1.  **Plazo Ajustado:** Requiere dedicación y ejecución en paralelo.
2.  **Tareas Continuas:** RCA (ID 2) y Trazabilidad Manual completa (ID 4) continuarán post-16. El objetivo es tener inicio, hallazgos preliminares y evaluación de esfuerzo.
3.  **Dependencias:** Informe (ID 7) depende de avances en tareas anteriores (esp. 1, 4, 5).
4.  **Contexto Komatsu:** Se enfatiza consulta de especificaciones y sistemas Komatsu (ID 5, 6).

---

Este plan será revisado y actualizado periódicamente según los hallazgos y avances.

# Suspensión Trasera
