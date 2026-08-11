# GA1-220501092-AA4-EV02 — Documento con especificación de requerimientos

## Proyecto: IntegraFlow AI

**Versión:** 1.0

### Introducción

Este documento consolida la especificación inicial de requisitos de IntegraFlow AI utilizando elementos del modelo IEEE 830 y la estructura de historias de usuario.

## 1. Alcance

IntegraFlow AI comprende una plataforma web orientada a la automatización e integración de procesos empresariales mediante IA, con módulos de CRM, RRHH, Contabilidad y Documentos y un motor de IA y automatización.

## 2. Perspectiva del producto

El sistema se plantea como una plataforma web centralizada que permitirá gestionar información empresarial y automatizar procesos. Se prevén integraciones con servicios externos como Gmail, DIAN API y WhatsApp.

## 3. Funciones del producto

- Autenticación y gestión de usuarios.
- Gestión de clientes.
- Gestión documental.
- Automatización de procesos.
- Dashboard de información.
- Generación de reportes.
- Asistencia mediante IA.
- Integración progresiva con servicios externos.

## 4. Características de los usuarios

Los usuarios objetivo pueden desempeñar funciones de administración, contabilidad, recursos humanos, área comercial, compras y gerencia. La interfaz debe ser comprensible para usuarios empresariales con diferentes niveles de experiencia tecnológica.

## 5. Restricciones

- El sistema debe desarrollarse como aplicación web.
- Las integraciones externas dependerán de las APIs y condiciones de los proveedores.
- Las funcionalidades de IA dependerán de los servicios y recursos tecnológicos seleccionados.
- Los requisitos podrán evolucionar durante las fases posteriores del proyecto.

## 6. Requisitos funcionales — formato de casos de uso

### CU-01 — Autenticación
**Actor:** Usuario.

**Precondición:** El usuario dispone de credenciales registradas.

**Flujo principal:** El usuario ingresa sus credenciales; el sistema valida la información y permite el acceso cuando es correcta.

**Resultado:** El usuario accede a las funcionalidades autorizadas.

### CU-02 — Gestión de usuarios
**Actor:** Administrador.

**Flujo principal:** El administrador registra, consulta, actualiza o desactiva usuarios y asigna roles.

### CU-03 — Gestión de clientes
**Actor:** Usuario autorizado.

**Flujo principal:** El usuario registra, consulta y actualiza información de clientes.

### CU-04 — Gestión documental
**Actor:** Usuario autorizado.

**Flujo principal:** El usuario carga, organiza, consulta y gestiona documentos.

### CU-05 — Automatización de procesos
**Actor:** Usuario autorizado.

**Flujo principal:** El usuario configura una regla o flujo; el motor de automatización ejecuta las acciones definidas.

### CU-06 — Dashboard
**Actor:** Usuario autorizado.

**Flujo principal:** El usuario consulta indicadores y datos consolidados.

### CU-07 — Reportes
**Actor:** Usuario autorizado.

**Flujo principal:** El usuario selecciona parámetros y genera un reporte.

### CU-08 — Asistencia IA
**Actor:** Usuario.

**Flujo principal:** El usuario realiza una consulta; el sistema procesa la solicitud y presenta una respuesta de asistencia.

## 7. Requisitos no funcionales

- Seguridad y control de acceso.
- Usabilidad.
- Rendimiento.
- Disponibilidad.
- Escalabilidad.
- Mantenibilidad.
- Compatibilidad con navegadores modernos.

## 8. Historias de usuario priorizadas

### HU-01 — Inicio de sesión
**Usuario:** Usuario del sistema. **Puntos:** 3. **Prioridad:** Alta.

**Historia:** Como usuario quiero iniciar sesión para acceder de forma segura a las funciones autorizadas.

**Criterios de aceptación:** credenciales válidas permiten acceso; credenciales inválidas muestran mensaje; el acceso se restringe según permisos.

### HU-02 — Gestión de usuarios
**Usuario:** Administrador. **Puntos:** 5. **Prioridad:** Alta.

**Historia:** Como administrador quiero gestionar usuarios y roles para controlar el acceso al sistema.

**Criterios de aceptación:** crear, consultar, actualizar y desactivar usuarios; asignar roles; aplicar permisos.

### HU-03 — Gestión de clientes
**Usuario:** Usuario autorizado. **Puntos:** 5. **Prioridad:** Alta.

**Historia:** Como usuario quiero gestionar clientes para mantener centralizada su información.

**Criterios de aceptación:** registrar, consultar y actualizar clientes.

### HU-04 — Gestión documental
**Usuario:** Usuario autorizado. **Puntos:** 5. **Prioridad:** Alta.

**Historia:** Como usuario quiero gestionar documentos para mantener organizada la información empresarial.

**Criterios de aceptación:** cargar, consultar y organizar documentos.

### HU-05 — Automatización de procesos
**Usuario:** Usuario autorizado. **Puntos:** 8. **Prioridad:** Alta.

**Historia:** Como usuario quiero automatizar tareas repetitivas para reducir errores y tiempos de operación.

**Criterios de aceptación:** configurar automatizaciones; ejecutar acciones; registrar resultado.

### HU-06 — Dashboard de información
**Usuario:** Usuario autorizado. **Puntos:** 5. **Prioridad:** Alta.

**Historia:** Como usuario quiero visualizar indicadores para apoyar la toma de decisiones.

**Criterios de aceptación:** mostrar información consolidada; actualizar datos; facilitar lectura de indicadores.

### HU-07 — Generación de reportes
**Usuario:** Usuario autorizado. **Puntos:** 5. **Prioridad:** Media.

**Historia:** Como usuario quiero generar reportes para analizar la información del sistema.

**Criterios de aceptación:** seleccionar parámetros; generar reporte; presentar resultados.

### HU-08 — Asistencia mediante IA
**Usuario:** Usuario. **Puntos:** 8. **Prioridad:** Alta.

**Historia:** Como usuario quiero recibir asistencia mediante IA para consultar información y apoyar tareas.

**Criterios de aceptación:** recibir consultas; procesar solicitudes; presentar respuesta de asistencia.
