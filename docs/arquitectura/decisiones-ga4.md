# Decisiones de arquitectura — GA4

## Contexto

Durante GA4 se consolidó el diseño de **IntegraFlow AI** como plataforma web modular para integrar procesos empresariales de CRM, Recursos Humanos, Contabilidad y Gestión Documental.

## Estilo arquitectónico

Se adopta una arquitectura cliente-servidor desacoplada y organizada por capas, con servicios expuestos mediante API REST. La separación propuesta comprende:

1. **Presentación:** interfaz web para interacción con los usuarios.
2. **Aplicación y dominio:** reglas de negocio, casos de uso y coordinación de procesos.
3. **Persistencia:** acceso estructurado a la base de datos.
4. **Integraciones:** adaptadores para servicios externos.
5. **Automatización:** servicios para reglas, eventos, notificaciones y procesos repetitivos.

## Módulos funcionales

- **CRM:** clientes, contactos y oportunidades.
- **Recursos Humanos:** candidatos, empleados y procesos asociados.
- **Contabilidad:** facturas, pagos e información contable contemplada en el alcance.
- **Gestión Documental:** almacenamiento, clasificación y consulta de documentos.
- **Automatización:** ejecución de reglas y coordinación de eventos.
- **Integraciones:** comunicación controlada con servicios externos como Gmail, servicios habilitados por DIAN y canales autorizados de WhatsApp.

## Principios de diseño

- Bajo acoplamiento y alta cohesión.
- Separación de responsabilidades.
- Modularidad y mantenibilidad.
- Reutilización de servicios mediante API.
- Validación de entradas y manejo centralizado de errores.
- Autenticación y autorización para proteger recursos.
- Persistencia aislada mediante repositorios o componentes equivalentes.
- Integraciones externas desacopladas mediante adaptadores.

## Patrones considerados

- **MVC / separación por capas:** organización de responsabilidades.
- **Repository/DAO:** aislamiento de persistencia.
- **DTO:** transferencia controlada de información entre capas.
- **Adapter:** integración con proveedores externos.
- **Facade:** simplificación de operaciones complejas entre subsistemas.
- **Strategy:** variación de reglas o comportamientos intercambiables.
- **Observer / eventos:** notificaciones y automatizaciones desacopladas cuando resulte pertinente.

## Seguridad

La arquitectura prevé autenticación, autorización basada en roles o permisos, protección de credenciales, validación de datos, registro de eventos relevantes y manejo controlado de excepciones. La implementación concreta deberá ajustarse a los requisitos funcionales y no funcionales validados durante el desarrollo.

## Despliegue conceptual

La vista de despliegue contempla navegador del usuario, aplicación web/backend, base de datos PostgreSQL, almacenamiento documental y conectores hacia servicios externos. La infraestructura definitiva se decidirá en fases posteriores según requisitos de disponibilidad, seguridad, costos y escalabilidad.

## Relación con GA5

Esta línea base arquitectónica será utilizada para construir los prototipos de interfaz, reglas de usabilidad y accesibilidad, mapas de navegación, maquetación HTML y propuestas móviles de GA5.
