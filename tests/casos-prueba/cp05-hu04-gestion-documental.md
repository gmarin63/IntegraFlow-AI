# CP-05 — HU-04 Gestión documental

**Objetivo:** Verificar que un usuario autorizado pueda cargar, consultar y organizar documentos.

**Historia asociada:** HU-04 – Gestión documental

**Precondiciones:**
- Usuario autenticado.
- Permisos para acceder al módulo Documentos.
- Módulo de documentos disponible.
- Espacio de almacenamiento disponible.

| Paso | Acción | Resultado esperado |
|---|---|---|
| 1 | Acceder al módulo Documentos | Se muestra el listado de documentos. |
| 2 | Seleccionar "Cargar documento" | Se abre el diálogo de carga. |
| 3 | Seleccionar un archivo | El sistema acepta el archivo. |
| 4 | Ingresar metadatos (nombre, categoría) | El sistema valida la información. |
| 5 | Confirmar carga | El documento se almacena. |
| 6 | Consultar la lista | El nuevo documento aparece. |
| 7 | Aplicar filtro por categoría | El sistema filtra correctamente. |

**Resultado esperado final:** El usuario puede cargar, consultar y organizar documentos correctamente.
