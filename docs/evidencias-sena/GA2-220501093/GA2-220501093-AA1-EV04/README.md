# GA2-220501093-AA1-EV04

## Diagramas y documentación de actividades del proyecto

**Proyecto:** Plataforma inteligente para la automatización de procesos administrativos, contables y de gestión empresarial mediante inteligencia artificial.

## Objetivo
Modelar mediante UML las actividades y elementos conceptuales principales de la solución, manteniendo coherencia y trazabilidad con los requisitos, historias de usuario y casos de uso previamente especificados.

## Metodología
Se adopta un enfoque ágil e incremental tomando Scrum como marco de referencia. El trabajo se organiza mediante backlog de historias priorizadas, iteraciones, incrementos y refinamiento continuo. En el contexto formativo no se afirma la implementación completa de todos los roles y eventos de Scrum.

## Diagramas de actividades
Se definieron siete flujos principales:

- DA-01 Iniciar sesión — RF-001 / HU-001 / CU-001.
- DA-02 Registrar cliente — RF-004 / HU-004 / CU-004.
- DA-03 Cargar documento — RF-008 / HU-008 / CU-008.
- DA-04 Registrar y validar factura — RF-011 a RF-013 / HU-011 a HU-013 / CU-011 a CU-013.
- DA-05 Gestionar candidato — RF-014 a RF-016 / HU-014 a HU-016 / CU-014 a CU-016.
- DA-06 Analizar documento mediante IA — RF-017 a RF-019 / HU-017 a HU-019 / CU-017 a CU-019.
- DA-07 Consultar dashboard y reportes — RF-020 a RF-022 / HU-020 a HU-022 / CU-020 a CU-022.

## Diagrama de clases conceptual
Clases identificadas inicialmente:

`Usuario`, `Rol`, `Permiso`, `Cliente`, `Seguimiento`, `Proveedor`, `Documento`, `Factura`, `Candidato`, `HojaVida`, `ProcesamientoIA`, `ResultadoProcesamiento`, `Indicador`, `Reporte` e `HistorialOperacion`.

## Modelo de dominio preliminar
Relaciones conceptuales destacadas:
- Cliente tiene seguimientos.
- Proveedor emite facturas.
- Factura corresponde a un documento.
- Candidato posee hoja de vida.
- Documento puede ser procesado mediante IA.
- El procesamiento produce un resultado revisable.

## Modelo preliminar de datos
Entidades lógicas iniciales: usuarios, roles, permisos, usuarios_roles, clientes, seguimientos, proveedores, documentos, facturas, candidatos, hojas_vida, procesamientos_ia, resultados_procesamiento e historial_operaciones.

## Trazabilidad
La cadena utilizada en esta evidencia es:

`RF -> HU -> CU -> DA`

Ejemplo:

`RF-017 -> HU-017 -> CU-017 -> DA-06`

## Estado
Versión 1.0 — evidencia desarrollada y documentada en el repositorio. El modelo de dominio preliminar se refina en GA2-220501093-AA2-EV01.