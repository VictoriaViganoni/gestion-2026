# 🎲 Estimación de Esfuerzo — Proyecto OmniHear

> **Técnicas utilizadas:** Delphi (tareas no críticas) · PERT (tareas críticas/inciertas)
> **Estimadores:** [COMPLETAR: nombres del grupo]
> **Nota metodológica:** Para las tareas estimadas con Delphi se realizó un proceso de consenso grupal; se documenta únicamente el resultado final acordado. Para las tareas estimadas con PERT se registran los tres escenarios (optimista, probable, pesimista) y se calcula el tiempo esperado y el desvío estándar.

---

## 1. Estimaciones con PERT
### Tareas críticas o de alta incertidumbre

> **Fórmulas:**
> - Tiempo esperado: **Te = (O + 4·P + Pe) / 6**
> - Desvío estándar: **σ = (Pe − O) / 6**

| ID | Tarea | Optimista (hs) | Probable (hs) | Pesimista (hs) | **Te (hs)** | **σ** |
|----|-------|:--------------:|:-------------:|:--------------:|:-----------:|:-----:|
| 1.5 | Planificación e identificación inicial de riesgos | 20 | 35 | 60 | **37** | 7 |
| 2.3 | Relevamiento de normas y regulaciones | 15 | 25 | 50 | **28** | 6 |
| 2.5 | Diseño itinerario terapéutico | 35 | 55 | 90 | **58** | 9 |
| 3.1.2 | Diseño de arquitectura | 30 | 50 | 80 | **52** | 8 |
| 3.2.3 | Seguridad y acceso | 20 | 40 | 80 | **43** | 10 |
| 4.3.2 | Codificación módulo de calibración | 60 | 100 | 180 | **107** | 20 |
| 4.3.3 | Codificación módulo de sonidos | 40 | 70 | 120 | **73** | 13 |
| 4.3.4 | Codificación módulo discriminación fonemas | 80 | 130 | 250 | **142** | 28 |
| 4.3.5 | Codificación módulo reconocimiento palabras | 60 | 100 | 170 | **105** | 18 |
| 4.3.6 | Codificación módulo conversación | 100 | 160 | 300 | **173** | 33 |
| 4.6 | Depuración (bug fixing) | 20 | 50 | 120 | **57** | 17 |
| 4.7 | Integración entre módulos | 40 | 80 | 160 | **87** | 20 |
| 5.1.1 | Pruebas de integración entre módulos (caja negra) | 35 | 60 | 130 | **68** | 16 |
| 5.1.3 | Revalidación del sistema | 15 | 35 | 85 | **40** | 12 |
| 5.2.1 | Medición de niveles de audio | 15 | 25 | 60 | **29** | 8 |
| 5.2.2 | Verificación de frecuencia y dB | 15 | 30 | 60 | **33** | 8 |
| 5.2.3 | Verificación técnica de seguridad y protección de datos | 20 | 40 | 80 | **43** | 10 |
| 5.3.1 | Evaluación con especialistas | 30 | 50 | 120 | **58** | 15 |
| 5.3.2 | Revisión de eficacia terapéutica | 20 | 35 | 80 | **40** | 10 |
| 5.4.1 | Recopilación del dossier de diseño y fabricación | 40 | 80 | 150 | **85** | 18 |
| 5.4.2 | Consolidación de evidencia de validación | 30 | 60 | 120 | **65** | 15 |
| 5.4.3 | Solicitud de registro ANMAT | 20 | 40 | 100 | **47** | 13 |
| 5.4.4 | Presentación documental regulatoria | 30 | 70 | 330 | **107** | 50 |

---

## 2. Estimaciones con Delphi
### Tareas no críticas — resultado consensuado

> Las siguientes tareas fueron estimadas mediante consenso grupal (técnica Delphi). Se registra directamente la estimación final acordada tras la discusión entre los integrantes del equipo.

| ID | Tarea | Entregable | **Estimación final (hs)** |
|----|-------|------------|:------------------------:|
| 1.1 | Análisis de requerimientos inicial | Documento de requerimientos | **45** |
| 1.1.1 | Definición requerimientos funcionales | Documento de requerimientos | 25 |
| 1.1.2 | Definición requerimientos no funcionales | Documento de requerimientos | 20 |
| 1.2 | Generación de propuesta técnica | Propuesta del proyecto | **40** |
| 1.3 | Administración de la configuración | — | **20** |
| 1.4 | Generación de propuesta económica | Propuesta del proyecto | **30** |
| 1.4.1 | Estimación de costos y presupuesto preliminar | — | 18 |
| 1.6 | Validación de propuestas | Acta de constitución | **15** |
| 2.1 | Cronograma detallado (Gantt) | Plan de Gestión Integral | **25** |
| 2.2 | Definir entregables | Plan de Gestión Integral | **20** |
| 2.4 | Relevamiento legal | Dossier normativo | **20** |
| 2.6 | Actualización matriz de riesgos (I) | Matriz de riesgos actualizada | **10** |
| 2.7 | Reunión de Kickoff | Acta de reunión | **4** |
| 3.1.1 | Requisitos del software | Plan de diseño y pruebas | **35** |
| 3.1.3 | Diseño de casos de prueba | Plan de diseño y pruebas | **30** |
| 3.2.1 | Selección de entorno cloud | Especificación de infraestructura | **15** |
| 3.2.2 | Políticas de backup | Especificación de infraestructura | **10** |
| 3.2.4 | Escalabilidad y mantenimiento | Especificación de infraestructura | **12** |
| 3.3 | Revisión técnica y de diseño | Informe de revisión | **16** |
| 4.1.1 | Configuración del entorno cloud | Infraestructura implementada | **25** |
| 4.1.2 | Despliegue de base de datos | Infraestructura implementada | **20** |
| 4.1.3 | Configuración de servidores y almacenamiento | Infraestructura implementada | **15** |
| 4.2 | Codificación interfaz UX/UI | Prototipo de interfaz | **65** |
| 4.3.1 | Codificación módulo registro y perfil de usuario | Registro funcional | **35** |
| 4.3.7 | Actualización matriz de riesgos (II) | Matriz de riesgos actualizada | **12** |
| 4.4 | Creación de manuales | Manual del sistema | **50** |
| 4.5 | Pruebas internas de cada módulo | Bitácora de correcciones | **100** |
| 4.5.1 | Pruebas de desarrollo (caja blanca) | Bitácora de correcciones | 45 |
| 4.5.2 | Testing unitario | Bitácora de correcciones | 40 |
| 4.5.3 | Smoke testing (cada incremento) | Bitácora de correcciones | 15 |
| 5.1.2 | Registro y depuración de errores | Reporte de testing | **20** |
| 5.1.4 | Smoke testing final | Reporte de testing | **12** |
| 5.2.4 | Certificación de seguridad técnica | Informe de validación técnica | **20** |
| 5.3.3 | Ajustes finales | Informe de validación clínica | **45** |
| 5.3.4 | Certificación clínica | Informe de validación clínica | **20** |
| 6.1.1 | Análisis de mercado | Plan de marketing | **30** |
| 6.1.2 | Estrategia comercial | Plan de marketing | **25** |
| 6.1.3 | Campañas de difusión | Plan de marketing | **40** |
| 6.1.4 | Vinculación con obras sociales | Plan de marketing | **50** |
| 6.1.5 | Estrategia de implementación y adopción | Plan de marketing | **20** |
| 6.2.1 | Entrega del manual de usuario | Producto final | **10** |
| 6.2.2 | Entrega de documentación técnica | Producto final | **20** |
| 6.2.3 | Entrega de documentación normativa | Producto final | **15** |
| 6.2.4 | Entrega de documentación contractual | Producto final | **15** |
| 6.2.5 | Entrega formal del producto | Producto final | **10** |
| 7.1.1 | Cierre contractual | Acta de cierre | **15** |
| 7.1.2 | Validación de entregables finales | Acta de cierre | **12** |
| 7.1.3 | Aprobación formal del cierre | Acta de cierre | **4** |
| 7.2 | Reunión de cierre y lecciones aprendidas | — | **8** |

---

## 3. Resumen de esfuerzo por etapa

| Etapa | Horas | % del total |
|-------|------:|:-----------:|
| 1. Inicio | 205 | 7,72% |
| 2. Planificación | 164 | 6,18% |
| 3. Diseño | 213 | 8,03% |
| 4. Desarrollo | 1065 | 40,17% |
| 5. Verificación y validación | 731 | 27,57% |
| 6. Entrega de producto final | 235 | 8,86% |
| 7. Cierre | 39 | 1,47% |
| **TOTAL** | **2652** | **100%** |

---

## 4. Conversión a duración

> **Fórmula:** Duración (días) = Esfuerzo (hs) / (Recursos asignados × Dedicación × Hs laborales/día)
> 
> [COMPLETAR: definir cantidad de recursos por tarea, dedicación (%) y horas laborales diarias del equipo]

| ID | Tarea | Esfuerzo (hs) | Recursos asignados | Dedicación (%) | Hs/día | Duración (días) |
|----|-------|:-------------:|--------------------|:--------------:|:------:|:---------------:|
| [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR] | [COMPLETAR]% | [COMPLETAR] | [COMPLETAR] |

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
