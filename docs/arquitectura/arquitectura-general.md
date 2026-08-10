# Arquitectura General — IntegraFlow AI

## Arquitectura conceptual

```text
USUARIOS
    │
    ▼
Plataforma Web IntegraFlow AI
    │
    ├──────────────┬──────────────┬──────────────┐
    ▼              ▼              ▼              ▼
   CRM            RRHH       Contabilidad   Documentos
    │              │              │              │
    └──────────────┴──────────────┴──────────────┘
                           │
                           ▼
                 Motor IA + Automatización
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
            Gmail        DIAN API     WhatsApp
```

## Componentes

### Plataforma Web

Es el punto de acceso para los usuarios autorizados y concentra la interacción con los módulos funcionales.

### CRM

Gestiona información de clientes y relaciones comerciales.

### RRHH

Contempla procesos relacionados con la gestión de recursos humanos. Su detalle funcional será especificado durante las siguientes fases de requisitos.

### Contabilidad

Contempla procesos contables y administrativos que puedan beneficiarse de centralización y automatización.

### Documentos

Permite centralizar la gestión documental y facilitar la consulta, organización y control de documentos.

### Motor IA + Automatización

Constituye el componente transversal destinado a ejecutar automatizaciones, apoyar tareas repetitivas y ofrecer asistencia inteligente.

### Integraciones

Se contemplan Gmail, DIAN API y WhatsApp como integraciones previstas. La implementación, credenciales, permisos y alcance de cada integración se definirán posteriormente.

## Relación con requisitos

La arquitectura conceptual se deriva del objetivo del proyecto y de las necesidades identificadas durante el levantamiento inicial de información. No representa todavía una arquitectura física o tecnológica definitiva.