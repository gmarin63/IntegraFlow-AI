# GA2-220501093-AA1-EV02

## Elaboración de diagramas y plantillas para casos de uso del proyecto

**Proyecto:** Plataforma inteligente para la automatización de procesos administrativos, contables y de gestión empresarial mediante inteligencia artificial.

## Objetivo
Documentar los casos de uso, historias de usuario y trazabilidad derivados de los requisitos funcionales del proyecto, utilizando nomenclatura UML y una estructura uniforme de documentación.

## Alcance funcional
La evidencia toma como base 22 requisitos funcionales agrupados en siete módulos:

1. Usuarios y seguridad — RF-001 a RF-003.
2. CRM — RF-004 a RF-007.
3. Gestión documental — RF-008 a RF-010.
4. Automatización contable — RF-011 a RF-013.
5. Recursos Humanos — RF-014 a RF-016.
6. IA y automatización — RF-017 a RF-019.
7. Información gerencial — RF-020 a RF-022.

## Actores
- Administrador.
- Usuario del sistema / usuario autorizado.
- Asesor comercial.
- Auxiliar contable.
- Responsable de Recursos Humanos.
- Gerente.
- Servicio de inteligencia artificial, cuando corresponda.

## Casos de uso
Se definieron los casos CU-001 a CU-022 manteniendo correspondencia con los requisitos RF-001 a RF-022. Entre los principales se encuentran autenticar usuario, gestionar usuarios, gestionar roles y permisos, registrar/consultar/actualizar clientes, seguimiento comercial, cargar/consultar/clasificar documentos, registrar y validar facturas, detectar posible duplicidad, gestionar candidatos, analizar documentos mediante IA, extraer información, registrar resultados automáticos, consultar dashboard, generar reportes y consultar historial de operaciones.

## Historias de usuario
Se estableció una historia HU-001 a HU-022 para cada requisito funcional, conservando la cadena de trazabilidad:

`RF -> HU -> CU`

Ejemplo:

`RF-017 -> HU-017 -> CU-017: Analizar documento mediante IA`

## Artefactos UML
Los casos de uso se organizan por módulo para conservar legibilidad y evitar un único diagrama excesivamente cargado. Las plantillas documentan identificador, nombre, actores, objetivo, precondiciones, flujo principal, flujos alternos, postcondiciones y requisitos relacionados.

## Trazabilidad
Esta evidencia constituye la base para GA2-220501093-AA1-EV03 y GA2-220501093-AA1-EV04. Los identificadores RF, HU y CU no deben cambiar sin registrar el cambio y revisar los artefactos dependientes.

## Estado
Versión 1.0 — evidencia desarrollada y documentada en el repositorio.