# CP-04 — HU-05 Automatización de procesos

**Objetivo:** Verificar que un usuario autorizado pueda configurar y ejecutar un flujo de automatización.

**Historia asociada:** HU-05 – Automatización de procesos

**Precondiciones:**
- Usuario autenticado.
- Permisos para administrar automatizaciones.
- Existe un proceso susceptible de automatización.

| Paso | Acción | Resultado esperado |
|---|---|---|
| 1 | Abrir Automatizaciones | Se muestra el listado de flujos. |
| 2 | Seleccionar “Crear flujo” | Se muestra el configurador. |
| 3 | Definir evento inicial | El sistema registra el disparador. |
| 4 | Definir acciones | El sistema permite configurar las acciones. |
| 5 | Guardar y activar | El flujo queda activo. |
| 6 | Ejecutar el evento | Se ejecutan las acciones configuradas. |

**Resultado esperado final:** El flujo de automatización se ejecuta correctamente.