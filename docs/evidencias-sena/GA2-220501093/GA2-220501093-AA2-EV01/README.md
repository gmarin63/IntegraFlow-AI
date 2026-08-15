# GA2-220501093-AA2-EV01

## Elaboración de los diagramas del modelo de dominio del proyecto

**Proyecto:** Plataforma inteligente para la automatización de procesos administrativos, contables y de gestión empresarial mediante inteligencia artificial.

## Objetivo
Elaborar el modelo de dominio del proyecto mediante diagramas UML de clases y paquetes, identificando conceptos, relaciones, cardinalidades, dependencias y herencias derivadas de los requisitos del software.

## Clases conceptuales
El modelo refina los conceptos identificados durante GA2-AA1-EV04. Entre las clases principales se encuentran:

- Usuario.
- Rol.
- Permiso.
- Cliente.
- Seguimiento.
- Proveedor.
- Documento.
- Factura.
- Candidato.
- HojaVida.
- ProcesamientoIA.
- ResultadoProcesamiento.
- Reporte.
- HistorialOperacion.

## Relaciones del dominio
Relaciones principales analizadas:

- Usuario se asocia con Rol.
- Rol agrupa Permisos.
- Cliente posee cero o muchos Seguimientos.
- Proveedor puede emitir múltiples Facturas.
- Documento funciona como concepto general para documentos empresariales.
- Factura especializa Documento.
- HojaVida especializa Documento.
- Candidato se relaciona con su HojaVida.
- Documento puede originar procesamientos mediante IA.
- ProcesamientoIA genera resultados de procesamiento.
- Usuario puede estar relacionado con operaciones auditables registradas en HistorialOperacion.

Las cardinalidades se establecen según las reglas del negocio y deberán refinarse cuando se diseñe el modelo lógico/físico de datos.

## Herencia
Se utiliza generalización/especialización para representar tipos documentales:

`Documento <- Factura`

`Documento <- HojaVida`

Esto permite compartir características comunes de los documentos sin duplicar conceptualmente sus propiedades generales.

## Paquetes
El dominio se segmenta en paquetes coherentes con los módulos funcionales:

1. Seguridad y usuarios.
2. CRM.
3. Gestión documental.
4. Contabilidad.
5. Recursos Humanos.
6. Inteligencia artificial y automatización.
7. Información gerencial y auditoría.

## Dependencias entre paquetes
Gestión documental sirve como núcleo transversal para contabilidad, Recursos Humanos e IA. Seguridad controla el acceso a los demás paquetes. Información gerencial consume información generada por los módulos operativos para reportes, indicadores y trazabilidad.

## Trazabilidad
El modelo se deriva de RF-001 a RF-022, HU-001 a HU-022, CU-001 a CU-022 y los diagramas de actividades definidos en GA2-AA1-EV04.

Cadena general:

`RF -> HU -> CU -> DA -> Clase/Paquete del dominio`

## Estado
Versión 1.0 — evidencia desarrollada y documentada en el repositorio.