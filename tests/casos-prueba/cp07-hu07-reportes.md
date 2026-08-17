# CP-07 — HU-07 Generación de reportes

**Objetivo:** Verificar que un usuario autorizado pueda generar reportes con filtros.

**Historia asociada:** HU-07 – Generación de reportes

**Precondiciones:**
- Usuario autenticado.
- Permisos para generar reportes.
- Datos disponibles en el sistema.
- Módulo de reportes disponible.

| Paso | Acción | Resultado esperado |
|---|---|---|
| 1 | Acceder al módulo Reportes | Se muestra el generador de reportes. |
| 2 | Seleccionar tipo de reporte | El sistema carga plantillas disponibles. |
| 3 | Definir filtros (fecha, módulo, etc.) | El sistema registra los filtros. |
| 4 | Seleccionar formato (PDF, Excel, etc.) | El sistema acepta el formato. |
| 5 | Generar reporte | El sistema procesa y genera el archivo. |
| 6 | Descargar o visualizar | El reporte se entrega al usuario. |

**Resultado esperado final:** El usuario genera correctamente reportes con los filtros especificados.
