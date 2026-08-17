# Registro de cambios — IntegraFlow AI

Todos los cambios notables en este proyecto se documentarán en este archivo.

El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/).

## [Sin versión publicada] — 2026-08-17

### Añadido

- Documentación de requisitos iniciales.
- Historias de usuario (HU-01 a HU-08) con estimación en puntos.
- Casos de prueba para HU-01, HU-02, HU-03, HU-05.
- Casos de prueba adicionales para HU-04, HU-06, HU-07, HU-08.
- Prototipos SVG para 5 historias de usuario (HU-01 a HU-05).
- Arquitectura conceptual (SVG y documentación).
- Evidencias SENA organizadas.
- Guía de instalación (SETUP.md).
- Guía de contribución (CONTRIBUTING.md).

### Cambiado

- Reorganización de carpetas de documentación:
  - `docs/architecture/` → `docs/arquitectura/`
  - `docs/requirements/` → `docs/requisitos/`
  - `docs/diagrams/` → `docs/diagramas/`
- Consolidación de `casos-prueba/` en `tests/casos-prueba/`.
- Corrección de duplicados y caracteres dañados en el README principal.
- Ajuste de SETUP.md y CONTRIBUTING.md para no asumir un stack tecnológico aún no definido.

### Por hacer

- [ ] Definir stack tecnológico del backend.
- [ ] Definir stack tecnológico del frontend.
- [ ] Seleccionar el motor de base de datos.
- [ ] Implementar estructura base del backend.
- [ ] Implementar estructura base del frontend.
- [ ] Configurar CI/CD cuando exista una implementación.
- [ ] Implementar HU-01 (Inicio de sesión).
- [ ] Implementar HU-02 (Gestión de usuarios).
- [ ] Agregar pruebas automatizadas cuando corresponda.

---

Versionado según [Semantic Versioning](https://semver.org/lang/es/).
