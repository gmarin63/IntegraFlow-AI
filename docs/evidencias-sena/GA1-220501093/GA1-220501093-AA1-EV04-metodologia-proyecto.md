# GA1-220501093-AA1-EV04
## Documento sobre la metodología para el proyecto de desarrollo de software

**Proyecto:** IntegraFlow AI  
**Programa:** Análisis y Desarrollo de Software – ADSO  
**Aprendiz:** Gerardo Marín  
**Versión:** 1.0  
**Fecha:** Agosto de 2026

## Introducción

La selección de una metodología de desarrollo de software es una decisión importante porque determina la forma en que se organizarán los requisitos, las actividades, las entregas, la comunicación con los usuarios y la validación del producto. Para IntegraFlow AI se requiere un enfoque que permita avanzar de manera progresiva, incorporar cambios y mantener trazabilidad entre las necesidades detectadas y las funcionalidades desarrolladas.

IntegraFlow AI es una plataforma web orientada a la automatización e integración de procesos empresariales. Su arquitectura contempla módulos de CRM, Recursos Humanos, Contabilidad, Gestión Documental y Reportes, articulados mediante un Motor de Inteligencia Artificial y Automatización, con integraciones previstas con Gmail, DIAN API, WhatsApp y otras API.

Después de analizar las características del proyecto y aplicar filtros de selección como tamaño del proyecto, estabilidad de los requisitos, periodicidad de retroalimentación, estado de la tecnología, nivel de riesgo y necesidad de entregas incrementales, se selecciona **Scrum como marco de trabajo principal**, complementado con un tablero Kanban en GitHub Projects para visualizar el flujo de trabajo.

## 1. Contexto y características del proyecto

### 1.1 Nombre

**IntegraFlow AI**

### 1.2 Propósito

Centralizar procesos empresariales y automatizar tareas repetitivas con el fin de reducir errores manuales, duplicidad de información, tiempos operativos y dispersión de datos.

### 1.3 Módulos principales

- Usuarios y seguridad.
- CRM.
- Recursos Humanos.
- Contabilidad.
- Gestión documental.
- Dashboard y reportes.
- Motor IA + Automatización.
- Integraciones externas.

### 1.4 Estado actual

El proyecto se encuentra en una etapa de análisis, diseño y validación de requisitos. Ya se han definido historias de usuario, requisitos funcionales y no funcionales, prototipos y casos de prueba. La implementación técnica se realizará de forma progresiva.

## 2. Metodología seleccionada

Se selecciona **Scrum** como marco de trabajo ágil principal para IntegraFlow AI.

Scrum organiza el trabajo de manera iterativa e incremental mediante periodos llamados **Sprints**. Cada Sprint busca producir un incremento útil del producto y permite revisar resultados, recoger retroalimentación y adaptar el trabajo siguiente.

De acuerdo con la Scrum Guide, Scrum se basa en empirismo y pensamiento Lean y utiliza eventos, responsabilidades y artefactos definidos para facilitar la inspección y adaptación.

Para la gestión visual del flujo se utilizará además **GitHub Projects con una vista tipo Kanban**, sin reemplazar Scrum como marco principal. El tablero servirá para organizar estados como Backlog, Por hacer, En progreso, En pruebas y Completado.

## 3. Justificación de la selección

Scrum es adecuado para IntegraFlow AI porque el proyecto presenta requisitos que pueden evolucionar durante el desarrollo. Las funcionalidades de automatización, IA e integración con servicios externos pueden necesitar ajustes a medida que se construyan prototipos, se realicen pruebas y se obtenga retroalimentación.

Además, el proyecto puede dividirse en incrementos funcionales. Por ejemplo, se puede comenzar con autenticación y gestión de usuarios, continuar con CRM y gestión documental, y posteriormente incorporar automatizaciones, reportes e integraciones externas.

La filosofía ágil también es coherente con los valores del Manifiesto Ágil, especialmente con la colaboración, el software funcionando y la capacidad de responder al cambio.

## 4. Filtros utilizados para seleccionar la metodología

| Filtro | Situación en IntegraFlow AI | Implicación metodológica |
|---|---|---|
| Tamaño del proyecto | Proyecto de alcance medio, modular y escalable | Conviene dividir el trabajo en incrementos y Sprints |
| Tamaño del equipo | Puede desarrollarse inicialmente con un equipo pequeño | Scrum es aplicable a equipos reducidos y colaborativos |
| Estabilidad de requisitos | Los requisitos pueden evolucionar | Se necesita capacidad de adaptación |
| Retroalimentación con usuarios | Se requiere validación periódica | Scrum permite revisiones frecuentes al finalizar Sprints |
| Estado de la tecnología | IA, APIs e integraciones pueden requerir experimentación | Es preferible trabajar de manera iterativa |
| Riesgo técnico | Integraciones y automatizaciones presentan incertidumbre | Los incrementos reducen el impacto de decisiones equivocadas |
| Entregas | Es posible entregar módulos progresivamente | Scrum favorece incrementos funcionales |
| Priorización | Existen historias de usuario con diferentes prioridades | El Product Backlog facilita ordenar el trabajo |
| Documentación | Se requiere documentación SENA y técnica | Scrum permite documentar sin convertir la documentación en el objetivo principal |
| Control del trabajo | Se necesita trazabilidad del avance | GitHub Issues y Projects permiten visualizar y registrar el flujo |

## 5. Aplicación de Scrum al proyecto

### 5.1 Product Backlog

El Product Backlog estará compuesto inicialmente por las historias de usuario definidas para IntegraFlow AI:

- HU-01 – Inicio de sesión.
- HU-02 – Gestión de usuarios.
- HU-03 – Gestión de clientes.
- HU-04 – Gestión documental.
- HU-05 – Automatización de procesos.
- HU-06 – Dashboard de información.
- HU-07 – Generación de reportes.
- HU-08 – Asistencia mediante Inteligencia Artificial.

Estas historias podrán dividirse posteriormente en tareas técnicas y nuevos requisitos.

### 5.2 Priorización

Las historias se ordenarán según valor para el usuario, dependencia técnica, riesgo y esfuerzo estimado.

Las funcionalidades fundamentales de seguridad, usuarios, clientes, documentos y automatización tendrán mayor prioridad durante las primeras iteraciones.

### 5.3 Sprints

Se propone trabajar inicialmente con **Sprints de dos semanas**. Esta duración ofrece un equilibrio entre tiempo suficiente para desarrollar una funcionalidad y frecuencia adecuada de revisión.

Ejemplo de planificación inicial:

| Sprint | Objetivo propuesto |
|---|---|
| Sprint 1 | Inicio de sesión y estructura básica de usuarios |
| Sprint 2 | Gestión de usuarios |
| Sprint 3 | Gestión de clientes – CRM |
| Sprint 4 | Gestión documental |
| Sprint 5 | Automatización inicial de procesos |
| Sprint 6 | Dashboard y reportes |
| Sprint 7 | Asistencia mediante IA e integraciones iniciales |

La planificación puede modificarse según la velocidad real, dependencias y resultados de las revisiones.

### 5.4 Eventos de Scrum

**Sprint Planning:** se seleccionarán las historias o tareas que pueden abordarse durante el Sprint.

**Daily Scrum:** cuando exista un equipo de desarrollo, se utilizará como reunión breve de coordinación. En una etapa individual puede adaptarse como seguimiento personal diario del avance.

**Sprint Review:** se revisará el incremento obtenido y se recogerá retroalimentación.

**Sprint Retrospective:** se analizará qué funcionó, qué dificultades surgieron y qué puede mejorarse en el siguiente Sprint.

### 5.5 Artefactos

**Product Backlog:** historias, requisitos y necesidades priorizadas.

**Sprint Backlog:** trabajo seleccionado para cada Sprint.

**Incremento:** resultado funcional y verificable obtenido al finalizar la iteración.

## 6. Gestión mediante GitHub

GitHub será utilizado como plataforma de apoyo para la trazabilidad del proyecto.

- **GitHub Repository:** código fuente y documentación.
- **GitHub Issues:** historias de usuario, incidencias y tareas.
- **GitHub Projects:** tablero para visualizar el flujo de trabajo.
- **Commits:** registro de cambios.
- **Branches y Pull Requests:** se incorporarán cuando comience la implementación colaborativa.

El flujo visual propuesto es:

**Backlog → Por hacer → En progreso → En pruebas → Completado**

Este flujo corresponde a una visualización Kanban utilizada como herramienta complementaria a Scrum.

## 7. Periodicidad de retroalimentación

Se propone obtener retroalimentación al finalizar cada Sprint, es decir, aproximadamente cada dos semanas durante la etapa de implementación.

Esta periodicidad permitirá validar:

- Interfaz.
- Funcionalidad.
- Requisitos.
- Usabilidad.
- Comportamiento de automatizaciones.
- Calidad de los datos.
- Integraciones.

Cuando una funcionalidad presente mayor incertidumbre, podrán realizarse validaciones adicionales durante el Sprint mediante prototipos o pruebas técnicas.

## 8. Estado de la tecnología y gestión del riesgo

IntegraFlow AI contempla tecnologías que presentan diferentes niveles de incertidumbre. Los módulos tradicionales, como usuarios, CRM o gestión documental, son técnicamente conocidos. En cambio, el componente de Inteligencia Artificial, las automatizaciones y las conexiones con API externas pueden requerir pruebas de concepto.

Por esta razón, Scrum resulta conveniente porque permite validar tecnologías mediante incrementos pequeños antes de comprometer todo el diseño del sistema.

Las integraciones con Gmail, DIAN API y WhatsApp deben considerarse inicialmente como componentes previstos y estarán sujetas a disponibilidad técnica, permisos, seguridad, costos y condiciones de las respectivas plataformas.

## 9. Comparación frente a un enfoque tradicional

Un modelo secuencial como Cascada ofrecería una planificación clara y una documentación estructurada, pero sería menos conveniente para IntegraFlow AI debido a que exigiría mayor estabilidad de requisitos desde las primeras etapas.

El proyecto necesita incorporar aprendizajes derivados de prototipos, pruebas, automatizaciones e integraciones. Por ello, un enfoque iterativo permite corregir decisiones antes de que afecten a todo el sistema.

Scrum no elimina la planificación ni la documentación. En IntegraFlow AI estas actividades se mantienen, pero se desarrollan y actualizan progresivamente conforme avanza el producto.

## 10. Ventajas esperadas

- Mayor capacidad de adaptación a cambios.
- Priorización de las funcionalidades de mayor valor.
- Retroalimentación periódica.
- Identificación temprana de problemas.
- Desarrollo progresivo por módulos.
- Mejor trazabilidad mediante GitHub.
- Posibilidad de validar automatizaciones e IA antes de una implementación completa.
- Mejora continua del proceso de desarrollo.

## 11. Posibles limitaciones

La aplicación de Scrum también requiere disciplina. Si no existe una adecuada priorización del Product Backlog o no se realizan revisiones periódicas, el marco puede perder efectividad.

Asimismo, en un proyecto desarrollado inicialmente por una sola persona algunos roles y eventos deben adaptarse sin simular un equipo inexistente. A medida que el proyecto incorpore más participantes, será posible aplicar de forma más completa las responsabilidades de Scrum.

## 12. Conclusiones

Después de analizar el contexto y las características de IntegraFlow AI, se determina que Scrum es un marco adecuado para orientar su desarrollo. La decisión se fundamenta principalmente en la naturaleza modular del sistema, la posibilidad de cambios en los requisitos, la necesidad de retroalimentación periódica y la incertidumbre relacionada con automatización, Inteligencia Artificial e integraciones externas.

La utilización de Sprints permitirá construir el sistema progresivamente y validar las funcionalidades antes de continuar con etapas posteriores. A su vez, GitHub Projects proporcionará una vista Kanban del flujo de trabajo y GitHub Issues permitirá mantener trazabilidad de las historias de usuario.

En consecuencia, se propone utilizar **Scrum como marco de trabajo principal y Kanban como mecanismo visual complementario de gestión**, logrando una combinación adecuada entre planificación iterativa, seguimiento continuo y capacidad de adaptación.

## 13. Bibliografía

Agile Manifesto. (2001). *Manifesto for Agile Software Development*. https://agilemanifesto.org/

Kanban University. (s. f.). *The Official Guide to The Kanban Method*. https://kanban.university/kanban-guide/

Schwaber, K., & Sutherland, J. (2020). *The Scrum Guide: The Definitive Guide to Scrum: The Rules of the Game*. Scrum Guides. https://scrumguides.org/

Servicio Nacional de Aprendizaje – SENA. (s. f.). *Componente formativo: Metodologías de desarrollo de software*. SENA.
