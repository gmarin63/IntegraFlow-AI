# GA2-220501093-AA1-EV03

## Elaboración de historias de usuario del proyecto

**Proyecto:** Plataforma inteligente para la automatización de procesos administrativos, contables y de gestión empresarial mediante inteligencia artificial.

## Objetivo
Consolidar la especificación de requisitos del proyecto y describir las funcionalidades mediante historias de usuario priorizadas, criterios de aceptación y puntos estimados de esfuerzo.

## Especificación general
### Perspectiva del producto
Plataforma web modular para centralizar y automatizar procesos administrativos, contables, comerciales, documentales y de Recursos Humanos, incorporando inteligencia artificial como apoyo al procesamiento documental.

### Funciones del producto
- Autenticación, usuarios, roles y permisos.
- CRM y seguimiento de clientes.
- Gestión documental.
- Automatización contable.
- Gestión de candidatos y hojas de vida.
- Análisis y extracción documental mediante IA.
- Dashboard, reportes y trazabilidad.

### Usuarios
Administrador, asesor comercial, auxiliar contable, responsable de Recursos Humanos, gerente y usuarios autorizados según rol.

### Restricciones
La primera versión se plantea como aplicación web. El acceso depende de roles y permisos. Los resultados de IA deben poder ser revisados por usuarios autorizados. Integraciones productivas complejas con DIAN, bancos, nómina electrónica, correo y otros servicios quedan previstas para fases posteriores del MVP.

## Requisitos funcionales
Se mantienen RF-001 a RF-022 distribuidos en siete módulos.

## Requisitos no funcionales
- RNF-001 Rendimiento.
- RNF-002 Seguridad.
- RNF-003 Control de acceso.
- RNF-004 Disponibilidad.
- RNF-005 Usabilidad.
- RNF-006 Integridad.
- RNF-007 Trazabilidad.
- RNF-008 Escalabilidad.
- RNF-009 Compatibilidad.
- RNF-010 Respaldo y recuperación.

## Historias de usuario
Se documentaron HU-001 a HU-022 con número, prioridad, nombre, usuario, puntos de esfuerzo, descripción, observaciones y criterios de aceptación.

Los puntos de historia utilizan escala relativa Fibonacci: `1, 2, 3, 5, 8, 13`.

Historias de mayor esfuerzo inicial:
- HU-017 Analizar documento mediante IA — 8 SP.
- HU-018 Extraer información de documentos — 8 SP.

## Trazabilidad
La evidencia conserva la relación:

`RF-001..RF-022 -> HU-001..HU-022 -> CU-001..CU-022`

Esta nomenclatura se reutiliza en diagramas de actividades, modelo de dominio, pruebas y desarrollo.

## Estado
Versión 1.0 — evidencia desarrollada y documentada en el repositorio.